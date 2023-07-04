# BBEARSAirbnb


Binance Smart Chain

Getting Started
Install the latest version of the SDK:

npm install @thirdweb-dev/sdk ethers@5
Initialize the SDK and contract on your project:

import { ThirdwebSDK } from "@thirdweb-dev/sdk/evm";

const sdk = new ThirdwebSDK("binance");
const contract = await sdk.getContract("0x340870b7A9714BF2fb866E96B678f64Ea0aEB2b4");
