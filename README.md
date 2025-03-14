# WaveSend: "Money moves offline, with just a text."
<img src="https://github.com/dannilobr/WS/blob/main/wave%20send%20app.jpg?raw=true">

## Overview

Wave send (Contract WaveSend.sol) is a revolutionary digital wallet that enables blockchain transactions via SMS, making it ideal for areas with unreliable infrastructure, crisis situations, and disasters. Our solution ensures financial access even when the internet is unavailable. Developed on the Scroll network, the project offers a transparent, efficient, and automated platform for those who need to perform offline transactions.

## Main Features

### For Consumers
- *Keep Connection*: Consumers in regions with intermittent or no internet can still send and receive money using basic mobile phones.
- *Beyond Disasters*: In natural disasters or crises, when data networks fail, users maintain access to financial services via SMS, ensuring they can manage funds in critical times.
- *General Inclusion*: Reaches 1.7 billion people with limited internet access but basic phone ownership, offering them a gateway to financial services.
- *Low tech Acessibility*: No need for smartphones or stable data—just a simple phone with SMS capability, making it affordable and widely usable.
- *High Efficiency*: The compact base188 encoding reduces SMS size and cost, making transactions affordable even in low-income regions.
- *Transparency*: Receiving transaction IDs and nonces via SMS provides clear confirmation, giving users confidence in the process.

### Payment services
- *Global Impact*: Expands the reach of digital payments to underserved areas, leveraging the 98% global SMS availability.
- *Whole Enhancement*: Enhances the resilience of the payment ecosystem by functioning independently of internet connectivity.
- *Financial Inclusion*: Promotes financial inclusion, broadening the user base without requiring advanced technology.
- *Barriedless*: Reduces dependency on expensive hardware or data plans, lowering barriers to entry for digital transactions.
- *Overall Security*: Optimizes transaction processing, keeping operational costs low while maintaining blockchain security.
- *Trustfull System*: Builds trust in the system by ensuring users can verify completed transactions easily.


## Technologies Used

- *Solidity*: Programming language for smart contracts.
- *Base188 Encoding*: A custom, optimized encoding system that compresses transaction data into a compact format suitable for SMS transmission (typically limited to 160 characters).
- *Rede Scroll*: It offers scalability, low cost, and high transaction speed.

## Smart Contract Features

### Transaction Process 
- initiateTransaction: Verifies the signature and queues the transaction for processing via SMS relay.
- processTransaction: Decodes the data, validates it, and updates the blockchain state (e.g., transferring funds).

### Security Verification
- verifySignature: Ensures the transaction’s authenticity before execution, using standard Ethereum signature verification (e.g., ecrecover).

### Funds Management
- withdrawFunds: Transfers the specified amount to the caller after validation.

### Transaction Details
- getTransactionStatus: Queries the blockchain for transaction details, such as whether it’s pending, completed, or failed.

### Security Enhancement
- setRelayAddress: Restricts transaction processing to an authorized relay, enhancing security.

## Advantages of the Scroll Network

- **Ethereum Compatibility**: Simplifies connection with the Ethereum network.
- **High Speed**: Quick transaction validations.
- **Scalability**: Handles a high number of transactions.
- **Low Cost**: Lowered transaction expenses.

## Roadmap de Desenvolvimento

### Phase 1: Deploy
- Full deployment on Scroll Sepolia
- Support for ERC-20 tokens

### Phase 2: Expasion
- Expansion to additional blockchain networks
- Support for NFTs

### Phase 3: Partneship
- Partnerships with humanitarian organizations for implementation in crisis areas.

### Phase 4: LoRa Integration
- Implementation of LoRa technology for long-range communication
- Development of LoRa-compatible hardware for areas without cellular coverage
- Hybrid SMS/LoRa communication protocols for maximum resilience
- Field testing in remote regions with limited infrastructure
  
## How to Contribute

1. Fork the repository
2. Create a branch for your feature. (git checkout -b feature/NewFunction)
3. Commit your changes (git commit -m 'Add New Function')
4. Push to the branch (git push origin feature/NewFunction)
5. Open a Pull Request

## Contato

Link do Projeto: [https://github.com/juancolchete/waveSend](https://github.com/juancolchete/waveSend)

## Licence

This project is licensed under the MIT License.
