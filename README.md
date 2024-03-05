# DeviceVerifier

DeviceVerifier extends Web3Things to provide authentication and verification for IoT device actions through blockchain.

## Features

- Authenticate IoT device actions.
- Record verified actions on the Ethereum blockchain.
- Leverage Web3Things for secure IoT-blockchain interaction.

## Installation

```bash
npm install deviceverifier


```

## Usage

```bash
const DeviceVerifier = require('deviceverifier');
const verifier = new DeviceVerifier('https://mainnet.infura.io/v3/YOUR_PROJECT_ID', 'mqtt://broker.hivemq.com');

verifier.verifyDeviceAction('deviceId123', 'turnOn');
verifier.recordDeviceActionOnBlockchain('deviceId123', 'turnOn');


```
DeviceVerifier ensures that every action taken by your IoT devices is authenticated and recorded, offering unparalleled security and transparency.