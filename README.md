# Troca - Freedom of Exchange via Crypto Swap s/CLI/TUI/g

> Troca helps you seamlessly swap between crypto pairs leveraging multiple Decentralized Exchanges.

<sub>([feminine] /'tɾɔka/ - to exchange/swap)</sub>


## Features

- Multi-DEX support for best rates
- Cross-chain swaps
- Privacy-focused
- Command-line interface
- SSH and Web interfaces (WIP: coming soon)

## Demo

<a href="https://troca.dev/asset/demo.mp4">
  <img src="asset/demo.gif" alt="Demo GIF" />
</a>

_Click the image above to view the video_

## Installation

### Bash one-liner

```bash
curl -sSL https://get.troca.dev | bash
```

### Go install

```bash
go install github.com/lfaoro/troca/cmd/troca@latest
```

### MacOS (brew)

```bash
brew install lfaoro/tap/troca
```

### Nix (soon)

```bash
nix-env -iA troca
```

## Storage

- `~/.config/troca/config.ini`
- `~/.config/troca/transactions.log`

## Remote Access

- SSH: ```ssh troca@ssh.troca.dev``` (WIP: coming soon)
- Web: https://app.troca.dev (WIP: coming soon)

## Build it yourself

> requires [Go](https://go.dev/doc/install)

```bash
git clone https://github.com/lfaoro/troca.git && cd troca
make build
bin/troca
```

## Contributing

I love pull requests, don't hesitate.

## Support

- [issues](https://github.com/lfaoro/troca/issues)
- [telegram](https://t.me/trocaswap)

## Help Troca grow

> With your help, we can make Troca better.

- Star the repo
- Tell your friends
- XMR **9XCyahmZiQgcVwjrSZTcJepPqCxZgMqwbABvzPKVpzC7gi8URDme8H6UThpCqX69y5i1aA81AKq57Wynjovy7g4K9MeY5c**
- BTC **bc1qzaqeqwklaq86uz8h2lww87qwfpnyh9fveyh3hs**
- [FIAT Donation](https://checkout.revolut.com/pay/7c8fae59-f65b-44de-9875-39dc014dc817)
- [Sponsor](https://github.com/sponsors/lfaoro)

## Disclaimer

I, Leonardo Faoro, provide a service (hereinafter referred to as "the Platform") that facilitates the swapping of crypto tokens by integrating third-party services. Please be aware of the following:

- **No Ownership or Custody**: I do not own, hold in custody, or control any of the crypto tokens that are exchanged. All transactions occur directly between users through external services.

- **Third-Party Services**: The Platform merely serves as an interface to external services for token transfers. I am not responsible for the execution, security, or performance of these third-party services.

- **Compliance**: While I strive to maintain compliance with EU regulations, users are personally responsible for adhering to local laws, including tax obligations, anti-money laundering (AML) regulations, and know your customer (KYC) requirements where applicable.

- **Risks Inherent in Crypto Transactions**: Cryptocurrency investments and transactions involve significant risks, such as price volatility, security breaches, and regulatory changes. Users should conduct thorough research and understand these risks before engaging with the Platform.

- **No Financial Advice**: The Platform does not provide financial, legal, or tax advice. Users should consult with professionals for such guidance.

- **Liability Limitation**: I disclaim any liability for any losses, damages, or costs arising from the use or inability to use the Platform, including but not limited to loss of profits, goodwill, or any other intangible losses, to the maximum extent permitted by law.

- **Commission**: A commission is charged on each transaction facilitated through the Platform, solely for the use of the interface. This does not imply involvement in the actual transfer of tokens.

- **Regulatory Changes**: The regulatory environment for cryptocurrencies is rapidly evolving, particularly with the implementation of the EU's MiCA regulation. I will attempt to adapt to these changes, but cannot guarantee uninterrupted service or that all aspects of the service will remain compliant under new regulations.

- **Indemnification**: By using this Platform, you agree to indemnify, defend, and hold harmless Leonardo Faoro from and against any claims, liabilities, damages, losses, and expenses, including legal fees, arising from your use of the services or your violation of this disclaimer.

- **Use at Your Own Risk**: All users engage with the Platform at their own risk.

**By using this service, you acknowledge that you have read, understood, and agreed to this disclaimer and the associated risks.**
