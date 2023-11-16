# privy-stackup-example
A simple login app with Privy and Stackup to create smart wallets

This is a template forked to integrate [**Privy Auth**](https://www.privy.io/) into a [NextJS](https://nextjs.org/) project.

## Setup

1. Clone this repository and open it in your terminal. 
```sh
git clone https://github.com/ivanmmurciaua/privy-stackup-example.git
```

2. Install the necessary dependencies (including [Privy Auth](https://www.npmjs.com/package/@privy-io/react-auth)) with `npm`.
```sh
npm i 
```

3. Initialize your environment variables by copying the `.env.example` file to an `.env.local` file. Then, in `.env.local`, [paste your Privy App ID from the console](https://docs.privy.io/guide/console/api-keys) and your StackUp Node and Paymaster URLs.
```sh
# In your terminal, create .env.local from .env.example
cp .env.example .env.local

# Add your Privy App ID to .env.local
NEXT_PUBLIC_PRIVY_APP_ID=<your-privy-app-id>
NEXT_PUBLIC_STACKUP_RPC_URL=<your-stackup-node-url>
NEXT_PUBLIC_STACKUP_PAYMASTER_URL=<your-stackup-paymaster-url>
```

## Building locally

In your project directory, run `npm run dev`. You can now visit http://localhost:3000 to see your app and login with Privy!