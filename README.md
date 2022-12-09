# jonatascm Portfolio

## Describe in further detail why you feel that you are ready for a role promotion within Spearbit?

Since I left my job as a full-time developer to become a security researcher I have evolved a lot, I have been working as a junior security researcher for 6 months and during that time I have greatly improved my perception of how projects are developed and integrated and I have studied many past reports. I helped Speartbit to secure 3 projects and in all of them I was proactive and got the responsibility to write the reports, I also participate in Code4rena and Sherlock finding mediums and highs errors, focusing mainly on Defi. Besides bug hunt I participated in the Certora community using Certora Prover (formal verification) in Aave contracts. I improved a lot on how to describe the vulnerabilities found and how to make POCs.

I enjoy this area a lot, and I am very focused and committed to continuing to learn and stay up to date with recent blockchain security happenings. Currently, my biggest wish is to become an LSR and start going to in-person safety events.

I already have the knowledge and desire to take on greater responsibility and be promoted to Associate Security Researcher.

## Work Experience

### Web2
- FRM Sistemas
  - Junior Full-Stack Developer - Jun/2017 - Feb/2020
  - Co-founder and Full-Stack developer of Vehicle Tracker System, used technologies: Php, HTML, CSS, Javascript, Postgres, MySQL  
  - Full-Stack Developer of Membership Management System
  - Developed an automation service for beet harvest management

- Codehashi
  - Junior Full-Stack Developer - Feb/2020 - Dec/2020
  - Full-Stack: React, React-Native, NodeJS
  - Responsible for develop a meditation app and a building company site
  - Both projects deployed using AWS Services

- Codengage
  - Mid-Level Mobile Developer - Dec/2020 - April/2021
  - Mid-level React-Native developer responsible for develop HR app

- KiwiMe Inc
  - Mid-Level Mobile Developer 
  - April/2021 - Mar/2022
  - Mid-level Flutter Mobile Developer responsible for develop courier app

### Web3

- Starter Labs
  - Smart Contract Developer
  - April/2022 - Jul/2022
  - Develop smart contracts for IDO platform

- Part-time: Zelcore
  - Frontend Developer - Jan/2022 - Jun/2022
  - Helped to refactor zelcore wallet project

- Spearbit
  - Junior Security Researcher - June/2022 - today

### Security Works

Since I joined in Spearbit, I participated in some projects:

1. Auditing in Code4rena and Sherlock
2. Participating in Secureum Bootcamp:
    1. Trail of Bits - Echidna Workshop -  19 ~ 25 May 2022
    2. Certora Prover Tools - Aave Grant Program - July ~ September 2022
        1. Contracts: Aave Starknet Bridge and Aave Token V3
        2. Mentioned in report [Formal-Verification-Report-of-Aave-Starknet-Bridge-3.pdf](https://www.certora.com/wp-content/uploads/2022/10/Formal-Verification-Report-of-Aave-Starknet-Bridge-3.pdf)
3. Hats.finance CTF #2 - 26 September 2022

## Public Content

Post about ECDSA: https://twitter.com/jonataspvt/status/1593618077081640961

I'm trying to expose more myself in twitter.

## Audit experience

### Audits with spearbit

| Date	| 21th, June 2022 - 5th, July 2022 |
| --- | --- |
| Protocol |	OlympusDAO, DeFi, Staking and Bonding |
|Team members| <ul><li>Christoph Michel, Lead Security Researcher</li><li>Desmond Ho, Lead Security Researcher</li><li>Blackscale, Security Researcher</li><li>Jonatas Martins, Apprentice</li><li>Hagrid, Apprentice</li></ul> |
|Reflection |	It's my first audit I have made, there was found precision loss problem, state transition problems and other issues. The risks of the protocol was mitigated during the review weeks and the generated report was with high quality.</br></br>Findings: 3 Low Risk, 3 Informational,  4 Gas optimization |

| Date	| 18th, July 2022 - 1st, Aug 2022 |
| --- | --- |
| Protocol |	Exponent, DeFi, Token Equity and SEAL engagement |
|Team members| <ul><li>Rajeev @ Secureum, Lead Security Researcher</li><li>Desmond Ho, Lead Security Researcher</li><li>Jonatas Martins, Apprentice</li><li>Maxime Viard, Apprentice</li><li>Balazs Kocsis, Apprentice</li><li>Calvbore, Apprentice</li><li>Naps62, Apprentice</li><li>Hagrid, Apprentice</li><li>Tqts, Apprentice</li></ul> |
|Reflection |	This audit was really good for learning, we discussed a lot in threads during the audit and we were encourage to ask and think about some issues. There were problems related to dust amounts problem, precision loss problem and loss of user funds.</br></br>Findings:  2 Medium Risk,  1 Low Risk, 24 Informational, 4 Gas optimization |

| Date	| 17th, October 2022 - 4th, September 2022 |
| --- | --- |
| Protocol |	Maple Finance, DeFi, Borrowing and Lending |
|Team members| <ul><li>Christoph Michel, Lead Security Researcher</li><li>0xleastwood, Lead Security Researcher</li><li>Riley Holterhus, Security Researcher</li><li>Devtooligan, Junior Security Researcher</li><li>Jonatas Martins, Junior Security Researcher</li></ul> |
|Reflection |	In this audit, we needed to check a lending protocol and migration process (V1 to V2), 3 weeks of audit, was quite complex to understand every state change and the migration. There was pretty good finding on initial mount issue that could lead to significant loss of funds, found by cmichel and 0xleastwood, and others related to calculations: fees, accrued interest, initial cycle config. In second week there was a change of scope and was added some changes in the code. I was also responsible for creating the report and added another topic to report related to change of scope.</br></br>Findings:  1 Low risk, 4 Informational, 8 Gas optimization |

### External audits

None yet, just bug bounty.

## Bug Bounties

### Code4rena

|Date| 8th, May 2022 |	
|Protocol|	Cudos, Bridge Contracts |
|Link |	https://discord.com/channels/810916927919620096/810929015509483554/989164839253446726 |
|Reflection |	This one is my first bug bunty contests, tried before any audit in Spearbit |


|Date| 13th, May 2022 |	
|Protocol|	Cally, NFT Options |
|Link |	https://discord.com/channels/810916927919620096/810929015509483554/989289999914635344 |
|Reflection |	This also before Spearbit auditing, didn't know much about how to make an audit |


|Date| 31th, May 2022 |	
|Protocol| veToken, Forked version of the Convex Yield Protocol |
|Link |	https://discord.com/channels/810916927919620096/979086601323945984/1006238694413447271 |
|Reflection |	For this one I started to create a list on how to start look into a project, also find my first medium issue |

|Date| 8th, Jul 2022 |	
|Protocol|	Juicebox V2, Programmable Treasury |
|Link |	https://discord.com/channels/810916927919620096/992150836643893399/1010282250945962135 |
|Reflection |	After my first audit in Spearbit, high and medium findings, still difficult to understand the whole project |

|Date| 14th, Jul 2022 |	
|Protocol| Fractional V2, Shared ownership and governance of NFTs, Fractionalized NFTs |
|Link |	https://discord.com/channels/810916927919620096/994261516251562024/1017092105325256714 |
|Reflection |	Got more bugs related to logic, not just pattern issues like changing transfer to safeTransfer |

|Date| 15th, Jul 2022 |	
|Protocol| Swivel, Yield tokenization protocol, Lending  |
|Link |	https://discord.com/channels/810916927919620096/996465101697712188/1017217781202174013 |
|Reflection |	Find just one high issue, some low & gas |

|Date| 15th, Aug 2022 |	
|Protocol|FIAT DAO veFDT, Implementation of Curve's voting-escrow  |
|Link |	https://discord.com/channels/810916927919620096/1006962576049057963/1022139067820945450 |
|Reflection |	Got 5th place. One high, one medium issue, low & gas.  |

|Date| 15th, Aug 2022 |	
|Protocol| Foundation Drop, NFT MarketPlace	|
|Link |	https://discord.com/channels/810916927919620096/1006281012931739698/1022931587253424219 |
|Reflection |	Just found low issues |

|Date| 15th, Sep 2022 |	
|Protocol| Nouns Builder, Tool for deploying forks of Nouns DAO with custom NFT, auction, governance, and founder(s) settings	|
|Link |	https://discord.com/channels/810916927919620096/1014987087478526052/1030494715730219088 |
|Reflection |	1 medium, low & gas report |

|Date| 19th, Sep 2022 |	
|Protocol| Y2k Finance,  HEDGE & RISK Insurances |
|Link |	https://discord.com/channels/810916927919620096/1019329436736299090/1045049955825504327 |
|Reflection |	Got an invalid "high" issue but send some low & gas, at this time I was making more contests and studying less so I decided to change to study more to get my confidence back  |

### Sherlock

|Date| 19th, Sep 2022 |	
|Protocol| Sentiment, Undercollateralised	Lending & Borrowing|
|Link |	https://discord.com/channels/812037309376495636/1013896010793226300/1026557592291524659 |
|Reflection |	First audit of Sherlock, didn't have much time but found one medium issue |

|Date| 20th, Nov 2022 |	
|Protocol|	Buffer Finance, Short-term options trading platform |
|Link |	https://discord.com/channels/812037309376495636/1041727871414173776/1049440916517171240 |
|Reflection |	|

|Date| 30th, Nov 2022 |	
|Protocol| Opyn, Defi derivatives and options |
|Link |	https://discord.com/channels/812037309376495636/1044825791701209118/1050787547099435088 |
|Reflection | Found 2 medium issues but just one got considered |

|Date| 7th, Dec 2022 |	
|Protocol| Isomorph, Lending protocol	|
|Link | Waiting for result |
|Reflection |	Found just low issues and sent them |

|Date| 4th, Dec 2022 |	
|Protocol| NounsDAO, Streamer component allowing payer to create steam and fund	|
|Link |	https://discord.com/channels/812037309376495636/1047881174925721630/1050794800938487979 |
|Reflection | This project I start to measure my time of bug bounty found just one medium	|

## Tool familiarity

| Name of the tool |	Context (what did you use it for? what did you achieve?)
| :---: | :---: |
| Echidna | I learned how to use to make fuzz test, I made some tests in code4rena but currently I prefer foundry |
| Certora Prover | I learned though Certora - Aave Grant Program, I tested only in Aave Token V3 and Aave Starknet Bridge, really great tool helps a lot to check some invariants and to fuzz |
| Slither | This is the first that I learned how to use, but not found very useful because of a lot of false positives, helped to find low/gas optimizations but usualy I found also by manual review |
| Foundry | Very awesome tool, help a lot to create POC and to fuzzy some contracts, I used it most in bug hunt (C4) |