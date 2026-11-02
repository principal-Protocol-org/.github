<div align="center">
  <a href="https://principalmarket.fi">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/principal-Protocol-org/.github/main/profile/logo-dark.svg" />
      <img src="https://raw.githubusercontent.com/principal-Protocol-org/.github/main/profile/logo-light.svg" alt="Principal" width="380" />
    </picture>
  </a>

# Yield tokenization for Stellar real-world assets.

[**Website**](https://principalmarket.fi) · [**Testnet app**](https://testnet.principalmarket.fi/app) · [Documentation](https://principalmarket.fi/docs)

</div>

Principal takes a real-world asset on Stellar that earns a variable yield, such as a tokenized
US Treasury note, and splits it into two tokens you can hold or trade separately:

1. **Principal Token (PT)**: a fixed return at maturity. Buy it below one dollar's worth of the
   asset and you lock in your yield.
2. **Yield Token (YT)**: the asset's variable yield until maturity, claimable as it accrues.

Each market has one pool where PT trades against SY, the standardized wrapper of the asset, and
YT trades through the same pool. Every SY, PT, YT and liquidity position checks the issuer's own
authorization of the account, live: compliance comes from the asset. If you know Pendle, this is
the same PT/YT model, built on Soroban for Stellar's regulated assets.

Principal runs on **Stellar Testnet** with a test asset. The contracts have not had an
independent security review yet.

## Repositories

| Repo                                                                 | What it is                                                       |
| -------------------------------------------------------------------- | ---------------------------------------------------------------- |
| [**principal**](https://github.com/principal-Protocol-org/principal) | The protocol: Soroban smart contracts in Rust                    |
| [**dapp**](https://github.com/principal-Protocol-org/dapp)           | The website and the app (Next.js)                                |
| [**docs**](https://github.com/principal-Protocol-org/docs)           | The documentation site, [principalmarket.fi/docs](https://principalmarket.fi/docs) |

## Learn more

- [What is Principal](https://principalmarket.fi/docs/guide/): the problem, PT and YT, compliance
- [How it works](https://principalmarket.fi/docs/how-it-works/): tokenization, pricing, maturity, fees, oracle
- [For developers](https://principalmarket.fi/docs/technical/developers): contract source, build and test, integration
