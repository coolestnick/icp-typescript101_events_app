# EVENTS APP

This repository is a submission for the [TypeScript Smart Contract 101](https://dacade.org/communities/icp/challenges/256f0a1c-5f4f-495f-a1b3-90559ab3c51f) challenge by the Internet Computer community on [Dacade](https://dacade.org/).

## Getting started

Follow the steps below to set up and run the project locally.

### Prerequisites

- Node.js (v18 or later)
- DFX (v0.18.1 or later)

### Installation

1. Clone this repository:

```bash
git clonehttps://github.com/perisKim001/icp-typescript101_events_app
```

2. Navigate to the project directory:

```bash
cd icp-typescript101_events_app
```

3. `dfx` is the tool you will use to interact with the IC locally and on mainnet. If you don't already have it installed:

```bash
npm run dfx_install
```

### Quickstart

Install dependencies, create identities, start a replica, and deploy a canister:

```bash
npm run canister_setup
```

### Interacting With Canister

The `package.json` file contains several commands starting with `canister_call` that can be used to interact with the canister.

### Tear Down

Uninstall the canister, stop the replica, remove identities, and remove dependencies:

```bash
npm run clean_state
```

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to suggest improvements or add new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
