---
sidebar_position: 2
---

<!-- ## How to: Add KOY Network to Anchor Wallet -->

The KOY Network is designed with user-friendly interfaces, simplifying the experience by removing the complexities of key management. For users familiar with the Antelope protocol, the renowned Anchor Wallet by Greymass offers an effortless way to engage with both the KOY mainnet and testnets. Ensure you have the latest version of the Anchor Wallet installed on your desktop or iPhone. Please note, the Android version currently doesn't support adding new chains, but this feature for KOY Networks will be included in an upcoming update.

You can get help in the **[Official KOY Network Telegram Group](https://t.me/KOYJumuiya)**.

Download **[Anchor Wallet ](https://www.greymass.com/anchor#download)**.

## Add a Blockchain: Step-by-Step

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

### Step 1: Open Anchor

First, open the Anchor Wallet app. At the top left corner of the interface, right next to the Anchor logo, you'll notice the logo of the currently active blockchain. Click on the drop-down arrow beside this name to reveal a drop-down menu with a list of blockchains. From here, you'll want to click on the `Manage Blockchains` button, which is prominently displayed at the top of the list.

<!-- ![step 1](/img/S1.PNG)<FigureText>Fig 1. Anchor Wallet Chain Selector</FigureText> -->
<img
    src="/img/steps/step_1.png"
    alt="step 1"
    style={{
      width: '400px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  />
  <FigureText>Fig 1. Anchor Wallet Chain Selector</FigureText>

### Step 2: Manage Available Blockchains

After clicking `Manage Blockchains`, you'll be taken to the `Manage Available Blockchains` screen. Scroll down to the bottom of this page until you find the `Add/Remove` tile; click on it to proceed.

<img
    src="/img/steps/step_2.png"
    alt="step 2"
    style={{
      height: '400px',
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 2. Add/Remove Chain</FigureText>

### Step 3: Add Custom Blockchain

You will now see a list showcasing all the blockchains that Anchor Wallet currently recognizes. However, since the KOY Network might not be listed, you'll need to select the `Custom Blockchain` button located at the upper right corner of the screen.

<img
    src="/img/steps/step_3.png"
    alt="step 3"
    style={{
      width: '250px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 3. Custom Blockchain button</FigureText>

### Step 4: Configure KOY Network

At this stage, you're ready to input the details for either the KOY Mainnet or the Testnet, depending on your needs:

For the **KOY Mainnet**, you will need to provide:

- Chain ID: `Mainnet ID still to be provided`
- Name of Blockchain: `KOY Network Mainnet`
- Default node: `Mainnet node still to be provided`

For the **KOY Testnet**, you will need to provide:

- Chain ID: `181e289803751d4e0fc257fd186edaa6df8169e28631f1bf63fc9287a80cfb5f`
- Name of Blockchain: `KOY Network Testnet`
- Default node: `http://api.testnet.koynetwork.io/`

**Advanced Configuration (Optional)**: While not required, should you wish to customize further, here are the recommended details:

- Public Key Prefix: `EOS`
- Default Token Symbol: `KOYN`
- Features and Contracts Available: Leave blank

Make sure `This blockchain is a test network` remains unchecked for the mainnet.

Click `Save` once you've filled in the necessary fields.

<img
    src="/img/steps/step_4.png"
    alt="step 4"
    style={{
      width: '800px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 4. New Blockchain Properties page</FigureText>

### Step 5: Enable KOY Blockchains

Once saved, you'll return to the list of networks known to Anchor. Locate the KOY network or networks you've just added and ensure their corresponding checkboxes are selected. Then, click the `Enable # blockchains` button located at the top left corner.

<img
    src="/img/steps/step_5.png"
    alt="step 5"
    style={{
      width: '700px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 5. Enable/Disable Blockchains</FigureText><br/>

<img
    src="/img/steps/step_5.1.png"
    alt="step 5.1"
    style={{
      width: '400px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 6. Enable button</FigureText>

### Step 6: Manage KOY Networks

Finally, back on the `Manage Available Blockchains` screen, choose the KOY network you wish to use. Optionally, click the pin icon next to KOY to make it readily available in the blockchain dropdown menu for future access. Just like with any other network on Anchor Wallet, you can now import accounts into the KOY networks you've enabled.

<img
    src="/img/steps/step_6.png"
    alt="step 6"
    style={{
      width: '500px', // Set the desired width in pixels
      display: 'block', // Ensure the image takes the full width
      margin: '0 auto' // Center the image horizontally
    }}
  /><FigureText>Fig 7. Manage Available Blockchains screen</FigureText>

## Add the KOYN token to Anchor Wallet

### Step 7: Manage Tracked Tokens

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

### Step 8: Add Custom Token

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

### Step 9: Confirm Token Addition

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

### Step 10: Confirm Token Addition

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

### Step 11: View Tracked Balance

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

### Step 12: Finalize Setup

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