---
sidebar_position: 3
---

This document outlines the technical requirements for running various types of nodes on KOY, with a focus on optimizing performance and reliability within the KOY Network.

## General Recommendations

### CPU Speeds for API Nodes

It is recommended not to exceed CPU speeds of 5 GHz for API nodes. Higher speeds may cause discrepancies in subjective billing, potentially leading to situations where transactions are initially accepted but ultimately rejected by nodes with slower CPUs.

### Use of tmpfs File System

All nodes are advised to utilize the tmpfs file system for their node state folder. This approach requires the mounting of the node state folder onto a tmpfs partition, necessitating a large swap partition and at least 32GB of RAM. The tmpfs system operates entirely in virtual memory, ensuring fast access to data but also meaning that data is not persistently stored on disk and will be lost if the tmpfs instance is unmounted.

### Storage for State History Nodes

For nodes handling significant State History requests, it's recommended to use SSD or NVMe drives to accommodate the high throughput and storage access speed required.

## Node Configuration Requirements

### API Node without Blocks Log

CPU: 2 cores, each >= 3.7 GHz  
RAM: 16 GB, with an additional 16 GB swap (32GB recommended)  
Storage: 1024 GB HDD  
Internet Connection: 100 Mb/s  

### API Node with Blocks Log

CPU: 4 cores, each >= 3.8 GHz  
RAM: 32 GB  
Storage: 1024 GB HDD  
Internet Connection: 100 Mb/s or higher  

### State History Node with Blocks Log

CPU: 4 cores, each >= 3.8 GHz  
RAM: 32 GB  
Storage: 2048 GB HDD  
Internet Connection: 100 Mb/s or higher  