<!-- ## How to: Add KOY Network to Anchor Wallet -->

The KOY Network will employ user-friendly interfaces that do not impose the challenges of key management on users. However, for those users already versed in the Antelope protocol system, the popular Anchor Wallet by Greymass can be easily set up to interact with the KOY mainnet and testnets. Just make sure you’ve installed the latest version of Anchor Wallet for desktop or iPhone (the Android version does not yet allow adding new chains so KOY Networks will need to be added in a coming release). 

You can get help in the **[Official KOY Network Telegram Group](https://t.me/koyblockchain)**.

## Step by Step

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

### Step 1

Open Anchor Wallet. At the top left corner of the interface, just to the right of the Anchor logo, is the name of the chain that you are currently signed into. Click the drop-down arrow beside it to open the Select Blockchain drop menu. Click on the Manage Blockchains button at the top of the list.

<!-- ![step 1](/img/S1.PNG)<FigureText>Fig 1. Anchor Wallet Chain Selector</FigureText> -->
<img
    src="/img/S1.PNG"
    alt="step 1"
    style={{
      width: '400px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  />
  <FigureText>Fig 1. Anchor Wallet Chain Selector</FigureText>

### Step 2

The Manage Available Blockchains screen will open. Scroll to the bottom of it and click on the tile for Add/Remove.

<img
    src="/img/S2.PNG"
    alt="step 1"
    style={{
      width: '400px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 2. Add/Remove Chain</FigureText>

### Step 3

You will see a list of all the blockchains that Anchor Wallet already knows about. However, KOY Network is not yet on this list so click the Custom Blockchain button at the top right of the screen.

<img
    src="/img/S3.PNG"
    alt="step 1"
    style={{
      width: '250px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 3. Custom Blockchain button</FigureText>

### Step 4

You will see the add a custom blockchain screen. For the KOY Mainnet fill in the fields as follows:
Chain ID: 8a34ec7df1b8cd06ff4a8abbaa7cc50300823350cadc59ab296cb00d104d2b8f
Name of Blockchain: KOY Mainnet
Default node: https://mainnet.koy.network
You do not need to use the Advance Configuration dropdown, but if you choose to, use
Public Key Prefix: EOS
Default Token Symbol: SYS
Features and Contracts available: (leave blank)
This blockchain is a test network: (do not check)
Click the Save button.

<img
    src="/img/S4.PNG"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 4. New Blockchain Properties page</FigureText>

### Step 5

You will have returned to the list of networks that Anchor knows about. Find the KOY network(s) and make sure their checkboxes are checked. Click the button at the top left that reads “Enable # blockchains”.

<img
    src="/img/S5.PNG"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 5. Enable/Disable Blockchains</FigureText><br/>

<img
    src="/img/S7.PNG"
    alt="step 1"
    style={{
      width: '330px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 6. Enable button</FigureText>

### Step 6

Returning to the Manage Available Blockchains screen, you can click on the KOY network you choose to open it. You can also click the pin icon for KOY to ensure it appears in the blockchain dropdown screen. Once you’ve selected the KOY networks, you can import accounts just as with any other network.

<img
    src="/img/S8.PNG"
    alt="step 1"
    style={{
      width: '450px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 7. Manage Available Blockchains screen</FigureText>

### Step 7

To add the KOY Testnet, follow the same process but in step 4, use these parameters:
Chain ID: 2081223fcffc96ce2d22ab63df414d1d6bf2f64f2e2922d500808decacd8b8b,
Blockchain name: KOY Testnet, and Default node: https://testnet.koy.network. Also click the checkbox at
the bottom to indicate the network is a testnet. And Click the Save button

<img
    src="/img/S9.PNG"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 8. Add KOY Network Testnet Parameters</FigureText>

## Add the KOYN token to Anchor Wallet

### Step 8

While connected to the KOYN Mainnet, Click Tools on the left-side menu. Then Click Manage Tracked Tokens.

<img
    src="/img/S10.PNG"
    alt="step 1"
    style={{
      width: '430px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 9. Anchor Wallet “Manage Tracked Tokens” Tool</FigureText>

### Step 9

Click the + Add Custom Token button.

<img
    src="/img/S11.PNG"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 10. Anchor Wallet with no tokens tracked</FigureText>

### Step 10

In the Contract Account Name and Contract Asset Symbol, enter eosio.token, and KOYN, respectively. Click the Add Custom Token button.

<img
    src="/img/S12.PNG"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 11. Parameters for adding KOYN token</FigureText>

### Step 11

 Click the Confirm Token Addition button

<img
    src="/img/S13.PNG"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 12. Add Custom Token Verification Screen</FigureText>

### Step 12

You’ll now see KOYN as a manually tracked balance. Your balance is likely to be zero because Anchor Wallet does not show your staked balances. You can find these on the **[KOY Network Block Explorer](https://explorer.koynetwork.io/)**.


<img
    src="/img/S14.PNG"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 13. KOYN Token added</FigureText>

### Step 13

Go to your Anchor Wallet Home screen at the top of the left-hand menu. Click the Tokens tab to see your KOYN balance. You may need to push the Load All Balances button at the bottom of the page to refresh your balances.

<img
    src="/img/S15.PNG"
    alt="step 1"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 14. KOYN Token is tracked on KOY Network Mainnet</FigureText>

## Good to Go!

Congratulations, you’re ready to run on the KOY Network!
**[Download Anchor Wallet](https://www.greymass.com/anchor)**.

<!-- ![Anchor](/img/S16.PNG) -->