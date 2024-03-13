---
sidebar_position: 2
---

## Why Adding Accounts to Anchor is Essential

Adding accounts to Anchor enhances your experience by allowing seamless interaction with the KOY Network. It enables secure transactions, smart contract execution, and easy management of digital assets. Integrating your accounts ensures you fully leverage the blockchain's capabilities, ensuring a smoother, more efficient workflow.

## Prerequisites

Before you embark on the steps below, ensure you have already integrated KOY Network as a Blockchain with Anchor, following the initial setup instructions.

## Adding Accounts: Step-by-step

export const FigureText = ({children, color}) => (
  <span
    style={{
      color: '#ce1c61',
      display: 'block', // Ensure the span takes the full width
      textAlign: 'center', // Center the text
      fontStyle: 'italic' // Make the text italic
    }}>
    {children}
  </span>
);

### Step 1: Navigate to your Blockchains

Begin by accessing the `Manage Available Blockchains` page. Choose the KOY Network or the KOY Testnet Network option to be directed to the `Setup a wallet to use on the KOY Network Blockchain` page.

<img
    src="/img/steps/add_accounts_to_network/step_1.png"
    alt="step 1"
    style={{
      width: '600px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto', // Center the image horizontally
    }}
  />
  <FigureText>Fig 1. Available Blockchains</FigureText>

### Step 2: Begin the Account Import Process

Proceed by clicking on the `Import an existing Account` button, and then select `Import Private Key`.

<img
    src="/img/steps/add_accounts_to_network/step_2.png"
    alt="step 1"
    style={{
      width: '600px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  />
  <FigureText>Fig 2. Anchor Wallet Chain Selector</FigureText>

<img
    src="/img/steps/add_accounts_to_network/step_2.1.png"
    alt="step 1"
    style={{
      width: '600px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto',
      marginTop: '20px'
    }}
  />
  <FigureText>Fig 2.1. Link Account selection</FigureText>

### Step 3: Import Your Private Key

Upon selecting `Import Private Key`, you'll be prompted with an input field. Paste your private key here. The account associated with this key will then be displayed. Confirm the account by selecting it and then click on `Import Account` to move forward.

<img
    src="/img/steps/add_accounts_to_network/step_3.png"
    alt="step 1"
    style={{
      width: '600px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  />
  <FigureText>Fig 3. Import a Private Key</FigureText>

### Step 4: Authorize the Addition of a new account

You will be asked for your Anchor password in a popup dialogue. Enter this password and click on the `Authorize` button to approve the addition of your account to the blockchain.

<img
    src="/img/steps/add_accounts_to_network/step_4.png"
    alt="step 1"
    style={{
      width: '400px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  />
  <FigureText>Fig 4. Authorization Dialog</FigureText>

## Completion

Once you have followed these steps, you will be taken to the "Account(s) Overview" page, where your newly added accounts are displayed. This marks a significant step towards enhancing your blockchain operations within Anchor.

<img
    src="/img/steps/add_accounts_to_network/completion.png"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  />
  <FigureText>Fig 5. Account Overview</FigureText>
