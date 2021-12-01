# Why a bug bounty?
Bug bounties are a common way of guaranteeing and improving the security of a protocol. If anyone discovers a bug or a loophole in our protocol, he can report it to our team and claim the associated bounty instead of abusing it. 
By offering this option, we allow developers and hackers who find an exploit to be rewarded for it without causing any damage to the protocol or to the funds of our users. 
Even with our protocol being audited by three different audit firms, we believe that we need to set an example in the Solana ecosystem and always aim for more security. This bug bounty is another way of raising our security level and a step towards this commitment.

# Rewards by threat level

Bounties will be distributed according to the impact of the vulnerability. In order to assess the vulnerabilities, we will use the Immunefi Vulnerability Severity Classification System. This is a simplified 5-level scale, with separate scales for websites/apps and smart contracts/blockchains, encompassing everything from consequence of exploitation to privilege required to likelihood of a successful exploit.

## Smart Contracts and Blockchain bounties

Critical: Up to USD 250,000
High:  USD 15,000

Critical vulnerabilities are further **capped at 10% of economic damage**, with the main consideration being the funds affected in addition to PR and brand considerations, at the discretion of the team.
However, there is a **minimum payout of USD 50,000 for Critical bug reports**.

Payouts are handled by the Marinade Finance team directly and are denominated in USD. However, payouts are done in mSOL and MNDE.

# Scope of the bounty program
## Assets in Scope

The smart contracts of Marinade Finance in scope for this bounty can be found here.

## Impacts in Scope

Only the following impacts are accepted within this bug bounty program. All other impacts are not considered as in-scope, even if they affect something in the assets in scope table.

- Loss of user funds staked (principal) by freezing or theft 
- Loss of governance funds
- Theft of unclaimed yieldFreezing of unclaimed yield
- Temporary freezing of funds for at least 6 days (2 epochs)
- Unable to call smart contract

## Prioritized vulnerabilities

We are especially interested in receiving and rewarding vulnerabilities of the following types:

- Re-entrancy
- Logic errors (including authentification errors)
- Trusting trust/dependency vulnerabilities (including composability vulnerabilities)
- Oracle failure/manipulation
- Novel governance attacks
- Economic/financial attacks (including flash loan attacks)
- Congestion and scalability (including running out of gas, block stuffing and susceptibility to frontrunning)
- Consensus failures
- Cryptography problems (including signature malleability, susceptibility to replay attacks, weak randomness, weak encryption)
- Susceptibility to block timestamp manipulation
- Missing access controls / unprotected internal or debugging interfaces

## Out of Scope & Rules

The following vulnerabilities are **excluded** from the rewards for this bug bounty program:

- Attacks that the reporter has already exploited themselves, leading to damage
- Attacks requiring access to leaked keys/credentials
- Attacks requiring access to privileged addresses (governance, strategist)
- Incorrect data supplied by third party oracles (not to exclude oracle manipulation/flash loan attacks)
- Basic economic governance attacks (e.g. 51% attack)
- Lack of liquidity
- Best practice critiques
- Sybil attacks
- 
The following activities are **prohibited** by this bug bounty program:

- Any testing with mainnet or public testnet contracts; all testing should be done on private testnets
- Any testing with pricing oracles or third party smart contracts
- Attempting phishing or other social engineering attacks against our employees and/or customers
- Any testing with third party systems and applications (e.g. browser extensions) as well as websites (e.g. SSO providers, advertising networks)
- Any denial of service attacksAutomated testing of services that generates significant amounts of traffic
- Public disclosure of an unpatched vulnerability in an embargoed bounty


# How to claim a bounty? 

If you want to claim a bounty, follow the following steps: 

- Join our Discord. 
- Reach out to LMT-luciotato#1019 and provide him your Proof-of-Concept. 
- Your submission will be analyzed and confirmed or not. If your submission is confirmed, our team will reach out to you to confirm the amount of the bounty to claim. 
