# Radical

*Rooting the noise, to square the signals.*

# Abstract

Radical is a thesis-driven private investment fund. Radical was set up by Him Gajria to operate as a pooled investment vehicle taking advantage of the "crypto" paradigm. With a focus on digital assets, the fund makes investments using a variety of strategies, from long-short positions, to liquidity mining.

# Resources

- For **Phase Reports**, go to the [Reports Folder](https://github.com/rdclxyz/Radical/tree/master/Reports) in the Radical repository.

- For **NAV** updates, go to the [NAV File](https://github.com/rdclxyz/Radical/blob/master/NAV.md) in the Radical repository.

- For **Portfolio**, go to the [Portfolio File](https://github.com/rdclxyz/Radical/blob/master/Portfolio.md)

- For **Insights**, go to the Radical [Medium Publication]().

- To **Contact**, email `him@vrbl.xyz`.

# Current Thesis

Title: `Investing in a Paradigm Shift`

With the introduction of the paper titled “Bitcoin: a peer-to-peer cash system”, a pseudonymous entity going by the name Satoshi Nakamoto, solved a problem that computer scientists and economists have been trying to solve for decades. A problem titled the “Byzantine Generals Problem”, which analogises Trust. This problem has entailed all of human cooperation, which is why applications on the internet were limited. Even within this limitation, the internet flourished, encompassing the entire planet with applications solving trillion dollar problems. Now for the first time ever, previous impossibilities have opened up in relation to every application and use-case entailing trust. This leads us into a new paradigm, which most layman are blind to or pessimistic about due to the current perception of the industry.
As speculation in digital assets peaked with all the hype created around blockchain technoology in 2017, scams became prominent, taking advantage of the newly borne gold rush. Since most assets within the industry were overpriced, due to a lack of any intrinsic value created in that same period resulted in the negative perception of cryptocurrencies and blockchain in general. This was a result of most headlines linking the technology to one scam or another. This does not come as a surprise to those who have witnessed paradigm shifts, as in their early days any paradigm attracts its own set of scammers due to the inflow of new capital.

All this attention led to a boom in interest from developers, scientists and researchers, with hordes of talent coming into the space to build problem solving products. These developments are dis-intermediating or completely replacing functions performed, products offered, and services rendered by existing companies and industries, let alone build new products that would not have been possible without the technology. Every time an innovation enables the disintermediation of existing industries and traditional ways of doing things, it’s considered a paradigm shift. A few notable paradigm shifts were Electrification, the Telephone, the Personal Computer, the Internet, the Smartphone, and now the Blockchain. And managing to catch a paradigm shift while it’s happening has historically proven to be extremely profitable. Entire funds have been built on the shifting of paradigms: Sequoia Capital and Accel Partners for Personal Computers, Andreeson Horowitz for the Internet, and Pantera Capital for Digital Assets.

Read entire thesis: [Investing in a Paradigm Shift](https://medium.com/@himgajria/crypto-thesis-2cf346eb8c5e).

# Structure

```
Unit: RDCL.
Unit holder limit: NA.
Inception Unit Value: $1 USD/Unit.
Minimum Investment: NA.
Current Management: Him Gajria.
Deposits: Perpetual.
Withdrawals: Perpetual.
```

## Addresses

Fund (Primary): `0x21B70Ef84e18B03D5e289cc0db416AAE1DdFB22B`

Fund (Secondary): `0x002885a1dD0Bd4dDd7b9D4d47811A28a689f7258`

Deposit: `0xFCFB33c0F77F4413af501dF32f4AE1dFd923069A`

Withdraw: `0xFCFB33c0F77F4413af501dF32f4AE1dFd923069A`

Fee: `0xA839d9115011B572BC34AC8be648f6C2A51104A3`

Custodian/s: `0x056E9027aff448b6E1D373c39EA73FD8b833f6C4`

Organisation: `0xe17b95eBbF5F06E215EF275A91ed0A11D159b293` *OR* `radical.aragonid.eth`

Organisation Agent: `0x6167ca14874a3ff32d6c0a91e633977aa0e6b322`


# NAV

Capital moves in and out of Radical as deposits and redemptions. Each investor gets a specified number of units or shares in proportion to their invested amount, and they are free to sell (redeem the value of) their fund units at a later date and collect the principle with a profit/loss, if any. Since constant buying and selling (investment and redemption) of fund units occur, a mechanism is required to price the units of the fund. This pricing mechanism is based on NAV; ergo, when Radical's NAVPS updates, so does its redeemable value.

The Net Asset Value (NAV) of the fund represents the book value of the fund at a specific time. The Net Asset Value Per Share (NAVPS)  represents the redeemable value of the funds units (RDCL). It can be equated as follows:

```
NAVPS = Assets Under Management / Total Outstanding Units
```

## Deposits

- Deposits are made in the form of a *stablecoin* (currently, only `USDT` and `USDC` are supported).
- Deposits can only be made to the following address:
```
0xFCFB33c0F77F4413af501dF32f4AE1dFd923069A
```

*Note: cross-check the address multiple times before making a deposit, as sending it to a wrong address will result in a permanent loss of funds.*

- Only use an ERC20 compliant wallet to transfer funds.
- There is no prescribed *minimum investment*.
- Deposits can either be made in batches or as a whole.
- Fund units to be minted and issued are ascertained on the last day of the phase, using NAVPS.

## Withdrawals

- Redemptions can only be made by transferring fund units to the following address:
```
0xFCFB33c0F77F4413af501dF32f4AE1dFd923069A
```

*Note: cross-check the address multiple times before making a redemption transfer, as sending it to a wrong address will result in a permanent loss of funds.*

- There is no prescribed *minimum redemption*.
- Redemption/s can either be made in batches or as a whole.
- Capital to be withdrawn are ascertained on the last day of the phase, using NAVPS.
- Redeemers in a phase will receive their capital within the first 5 days of the next phase.

## Custodial Functions (Beginning 1st-5th of every month)

- Ascertain and Update Portfolio.md
- Ascertain Capital Appreciation
  - Ascertain AUM before fees.
  - Ascertain AUM of the previous phase.
  - `Capital appreciation = AUM before fees - AUM of the previous Phase`.
- Ascertain/Divide fees
  - `Management fees = 0.16% of total assets of the phase`
  - `Performance fees = 20% of appreciation in AUM for the phase`
  - Transfer Fees to Fee address.
- Ascertain Assets Under Management (AUM)
  - `AUM = AUM before fees - Fees`.
- Ascertain NAVPS
  - `NAVPS = AUM / (Outstanding Units - Custodian/s Units)`.
- Update NAV repository
- Issue phase report
- Ascertain deposits
  - Ascertain total deposits.
  - `Fund Units to be minted = Capital deposited / NAVPS`.
  - Ascertain (a) addresses, (b) capital and (c) fund units to mint.
  - Transfer minted tokens to Deposit/Withdrawal address from Organisation.
  - Transfer tokens from Deposit/Withdrawal address to depositors.
  - Transfer capital to Proxy address.
-	Ascertain redemptions
  - `Redemptions = Fund Units received * NAVPS`.
  - Ascertain (a) addresses, (b) capital and (c) fund units to burn.
  - Transfer redeemed capital from Fund/Proxy address to Deposit/Withdrawal address.
  - Transfer capital from Deposit/Withdrawal address to withdrawers.
  - Transfer fund units from withdrawal address to Burn address.
  - Transfer equivalent fund units from Custodian/s address to Burn address.

# Disclosure

The “fund” described in this document is not subject to the same regulatory requirements as traditional investment vehicles as it uses unregulated means/mediums/structures/technologies to conduct activity. Although, there are substantial risks in investing in a fund. Persons interested in investing in any fund should carefully note the following:
  - A fund represents a speculative investment and involves a high degree of risk. An investor could lose all or a substantial portion of his/her investment. Investors must have the financial ability, sophistication/experience and willingness to bear the risks of an investment in a fund.
  - An investment in a fund should be discretionary capital set aside strictly for speculative purposes.
  - An investment in a fund is not suitable or desirable for all investors. Only certain persons meeting certain additional eligibility criteria may invest in a fund.
  - A fund may employ leverage and other investment techniques, and such leverage and other investment techniques may result in increased volatility of the fund’s performance and increased risk of loss.
  - A fund may trade in a single asset class or an assortment of asset classes to form a “portfolio” of assets. Some assets may increase the risk of loss of the fund.
  - Fund investments are illiquid and there are generally significant restrictions on transferring interests in a fund.
  - There will likely be no secondary market for the interests of a fund.
  - A fund may have limited or no operating history.
  - The investment manager of a fund may have certain discretionary authority over the fund’s assets.
  - A fund may invest in a limited number of securities or instruments, which could result in a limited degree of diversification and higher risk.
  - A fund generally involves a complex tax structure, which should be reviewed carefully.
  - The management fees of a fund’s investment manager may be substantial regardless of whether the fund has a positive return, and will offset the fund’s profits.
  - There are likely to be a number of conflicts of interest or potential conflicts of interest in connection with an investment manager’s management of fund assets.

The above summary is not a complete list of the risks and other important disclosures involved in investing in funds. Before making any investment in a fund, investors are advised to thoroughly and carefully review offerings with their financial, legal and tax advisors to determine whether an investment is suitable, and permitted in their respective jurisdiction.
