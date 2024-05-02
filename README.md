# BOS + Aave

This repository is an example of how to implement Aave technology in a BOS component to query the supply and borrow available on the ETH network.

<img src="https://drive.google.com/uc?id=1U10_dhSXLOo_0PY1kFuEEwhGiMKuYv8R" width="35%">

## How to implement the Aave technology in BOS?

To implement the Aave technology and get the supply and borrow available from our BOS component we will have to make some configurations and calls to an API.

The first thing to do is to initialize each of the corresponding ABI and network configurations, in this case ETH.

```jsx

```



## How to test the Component?

To run this project in BOS you must run the widget (BOS-Aave.jsx) on an available BOS gateway, for example: [near.social ](https://near.social/edit)

Once the code for the widget has been added we can render it by clicking on the preview button to render the component.

<img src="https://drive.google.com/uc?id=1Q6TgIz26ZMsliTlR1M9glGx4YQWM2U2A" width="50%">

For this example you will also need to have installed and configured [metamask](https://metamask.io/) and [ETH](https://revoke.cash/es/learn/wallets/add-network/ethereum) network.

Once this is done, you can click **Connect Wallet** to run metamask and connect the component to your account.

<img src="https://drive.google.com/uc?id=1pOoc5njKVM9EpXubbH8HB3Gy55dLGQWT" width="50%">

Once metamask is connected we will be able to start interacting with the UI.

Once connected to our metamask account, the component will automatically make the necessary queries to the corresponding API to obtain the supply and borrow available in the ETH network, this information can be displayed in the available tabs.

<img src="https://drive.google.com/uc?id=1vuOoLd7mX6zHraoRSBkXHY1YsxE16Sue" width="50%">

## BOS Widget

Aave: https://near.social/owa-is-bos.near/widget/BOS-Aave
