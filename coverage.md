# Directory coverage

Independent sample: 1,095 Wikidata companies resolved, 133 on a system the directory tracks, 0 on another system, 353 with a careers page we can't read.

## Universe: how much of each hiring system we hold

**Sample coverage** is the target figure: Wikidata companies resolved from their own websites, and the share of their live boards our URL sources already had (a sample under 30 is too small to trust). **Estimate** is a lower bound on all boards, from how often our URL sources agree.

| Hiring system | Ours (live + dormant) | Estimate | Ours / estimate | Sample boards | Already had | Sample coverage | Listed only by restricted sources |
|---|---|---|---|---|---|---|---|
| greenhouse | 8,971 | 9,478 | 95% | 7 | 7 | 100% | 225 |
| lever | 2,829 | 2,838 | 100% | 3 | 3 | 100% | 63 |
| ashby | 4,391 | 4,491 | 98% | 1 | 1 | 100% | 189 |
| smartrecruiters | 3,738 | 7,551 | 50% | 1 | 1 | 100% | 0 |
| workday | 5,423 | 5,539 | 98% | 41 | 39 | 95% | 8,317 |
| workable | 3,630 | 3,690 | 98% | 2 | 2 | 100% | 0 |
| recruitee | 879 | 129,067 | 1% | 2 | 2 | 100% | 0 |
| personio | 802 | 161,002 | 0% | 1 | 0 | 0% | 0 |
| bamboohr | 5,546 | 32,154 | 17% | 4 | 1 | 25% | 0 |
| breezy | 2,309 | 2,475 | 93% | 1 | 1 | 100% | 0 |
| successfactors | 18 | 18 | 100% | 18 | 0 | 0% | 0 |
| teamtailor | 940 | 1,004 | 94% | 3 | 2 | 67% | 0 |
| comeet | 124 | 3,876 | 3% | 1 | 0 | 0% | 0 |
| oracle | 885 | 1,402 | 63% | 14 | 12 | 86% | 0 |
| icims | 1,527 | 582,552 | 0% | 4 | 2 | 50% | 0 |
| taleo | 220 | 220 | 100% | 0 | 0 | – | 0 |
| jobvite | 740 | 800 | 93% | 1 | 0 | 0% | 0 |
| pinpoint | 924 | 5,426 | 17% | 2 | 1 | 50% | 0 |
| rippling | 1,114 | 1,743 | 64% | 1 | 0 | 0% | 0 |
| jazzhr | 1,254 | 1,847 | 68% | 0 | 0 | – | 0 |
| zoho | 881 | 194,701 | 0% | 0 | 0 | – | 0 |
| hibob | 207 | 10,868 | 2% | 0 | 0 | – | 0 |
| freshteam | 380 | 3,201 | 12% | 0 | 0 | – | 0 |
| **All** | 47,732 | 1,165,943 | 4% | 107 | 74 | 69% | 8,794 |

### Which URL source carries its weight (live + dormant boards)

| Source family | Boards | Only this source |
|---|---|---|
| latmay | 35,184 | 11,430 |
| commoncrawl | 28,024 | 5,025 |
| wayback | 20,174 | 3,249 |
| kalil | 15,937 | 564 |
| openjobsdata | 364 | 9 |
| cryptojobs | 294 | 4 |
| openroles | 10,570 | 1 |
| jobseek | 3,371 | 0 |
| lastround | 9,236 | 0 |
| outscal | 829 | 0 |

# Coverage of must-have companies

Seed list: 315 companies (scripts/catalog/seeds/industries.json). Resolved 2026-10-11.

**Trackable** = on a hiring system we scan today. **Not scannable** = board found on a system we don't scan yet. **Custom site** = careers page with no board we can read (hint: which system its pages mention).

## By industry

| Industry | Seeds | trackable | not scannable | custom site | not found | unreachable | Trackable % |
|---|---|---|---|---|---|---|---|
| Crypto & Web3 | 202 | 139 | 10 | 26 | 20 | 7 | 69% |
| Brokerage, CFD & FX | 43 | 17 | 10 | 11 | 2 | 3 | 40% |
| Fintech (general) | 29 | 27 | 1 | 0 | 0 | 1 | 93% |
| Crypto exchange | 21 | 10 | 2 | 3 | 5 | 1 | 48% |
| Payments | 19 | 9 | 3 | 1 | 4 | 2 | 47% |
| Wealth & asset management | 17 | 6 | 3 | 5 | 3 | 0 | 35% |
| Trading technology | 10 | 3 | 1 | 6 | 0 | 0 | 30% |
| Banking | 8 | 2 | 2 | 2 | 0 | 2 | 25% |
| Digital assets & custody | 8 | 3 | 2 | 3 | 0 | 0 | 38% |
| Tokenization & RWA | 7 | 4 | 0 | 2 | 0 | 1 | 57% |
| Digital bank / neobank | 6 | 1 | 1 | 2 | 1 | 1 | 17% |
| Market making & prop trading | 4 | 3 | 0 | 1 | 0 | 0 | 75% |
| Regtech & financial crime | 2 | 0 | 1 | 0 | 0 | 1 | 0% |
| Lending & BNPL | 2 | 1 | 1 | 0 | 0 | 0 | 50% |
| **All** | 315 | 202 | 25 | 45 | 27 | 16 | 64% |

## Next connectors (by seed companies they would unlock)

| Hiring system | Seed boards found | Seed sites mentioning it | Directory companies on it | Seed companies |
|---|---|---|---|---|
| workable | 7 | 0 | 3,630 | Admirals, Distributedcrafts, Hex Trust, Io-Global, Pepperstone, Walletconnect, Zodia Custody |
| workday | 3 | 0 | 5,423 | Circle, OANDA, Saxo Bank |
| comeet | 3 | 0 | 126 | eToro, Leverate, Rapyd |
| bamboohr | 2 | 0 | 5,546 | IC Markets, Tickmill |
| rippling | 2 | 0 | 1,114 | O1labs, Webull |
| oracle | 2 | 0 | 885 | ADGM, Emirates NBD |
| recruitee | 2 | 0 | 880 | Bitfinex, Deribit |
| pinpoint | 1 | 0 | 924 | Tabby |
| personio | 1 | 0 | 802 | Safe.Global |
| taleo | 1 | 0 | 221 | Mashreq |
| successfactors | 1 | 0 | 19 | Equiti |

## Not trackable yet

| Company | Industries | Outcome | Detail |
|---|---|---|---|
| Aragon | crypto | custom site | https://www.aragon.org/careers |
| Avara | crypto | custom site | https://aave.com/careers |
| B2Broker | trading-tech, brokerage, crypto | custom site | https://b2broker.com/careers/ |
| Baraka | brokerage, wealth | custom site | https://getbaraka.com/careers |
| Biconomy | crypto | custom site | https://www.biconomy.io/careers |
| Bitcoindepot | crypto | custom site | https://bitcoindepot.com/careers |
| BitcoinSuisse | crypto | custom site | https://bitcoinsuisse.com/careers |
| Bitstamp | crypto, crypto-exchange | custom site | https://www.bitstamp.net/careers |
| Bitwise | crypto | custom site | https://bitwiseinvestments.com/careers |
| Blox-Route | crypto | custom site | https://bloxroute.com/careers/ |
| Clearmatics | crypto | custom site | https://clearmatics.com/careers/ |
| Cow-Dao | crypto | custom site | https://cow.fi/careers |
| Darwinex | brokerage | custom site | https://jobs.darwinex.com/jobs |
| Deriv | brokerage | custom site | https://careers.deriv.com/?from=uae |
| Dfinity | crypto | custom site | https://dfinity.org/careers |
| Dubai Islamic Bank | banking | custom site | https://dib.ae/about-us/news/2026/09/28/dib-opens-new-career-pathways-for-emirati-talent-at-ruya-careers-uae-2026?type=news |
| Eiger | crypto | custom site | https://careers.eiger.co/ |
| Ethenalabs | crypto | custom site (teamtailor) | https://careers.ethena.fi/ (mentions teamtailor) |
| Exodus54 | crypto | custom site | https://www.exodus.com/careers |
| Finalto | brokerage, trading-tech | custom site | https://finalto.com/careers |
| Flashbots | crypto | custom site | https://www.flashbots.net/jobs |
| Flowdesk | market-making | custom site | https://www.flowdesk.co/careers |
| Fuze | crypto | custom site | https://fuze.finance/careers |
| Goldsky | crypto | custom site | https://goldsky.com/careers |
| Hub71 | crypto | custom site | https://jobs.hub71.com/companies |
| Interactive Brokers | brokerage, wealth | custom site | https://www.interactivebrokers.com/en/general/about/careers-splash.php?menu=B |
| Komainu | crypto, digital-assets | custom site | https://komainu.com/careers/ |
| KuCoin | crypto, crypto-exchange | custom site | https://www.kucoin.com/careers |
| Laser Digital | crypto, digital-assets | custom site | https://www.laserdigital.com/careers |
| LMAX Group | trading-tech, crypto-exchange, crypto | custom site | https://careers.lmax.com/ |
| Match-Trade Technologies | trading-tech, brokerage | custom site | https://match-trade.com/career/ |
| Matrixport | crypto, digital-assets | custom site | https://www.bit.com/careers |
| MetaQuotes | trading-tech, brokerage | custom site | https://www.metaquotes.net/en/company/vacancies |
| Mubadala | wealth | custom site | https://www.mubadala.com/en/careers |
| NymCard | payments | custom site | https://www.nymcard.com/ae/company/careers |
| Plus500 | brokerage | custom site (comeet) | https://careers.plus500.com/ (mentions comeet) |
| Prypco | tokenization | custom site | https://prypco.com/careers |
| Ripple | crypto | custom site | https://ripple.com/careers/ |
| Sarwa | wealth, brokerage | custom site (teamtailor) | https://careers.sarwa.co/ (mentions teamtailor) |
| Spotware | trading-tech, brokerage | custom site | https://careers.spotware.com/ |
| StashAway | wealth | custom site | https://www.stashaway.ae/careers |
| Swanbitcoin | crypto | custom site | https://bitcoinerjobs.com/company/swan-bitcoin |
| Tokeny | tokenization | custom site | https://tokeny.com/why-join-us/ |
| Wio Bank | digital-bank, banking | custom site | https://wio.io/careers |
| Zand | digital-bank | custom site | https://www.zand.ae/careers |
| ADQ | wealth | not found | no careers page found |
| Almanak | crypto | not found | no careers page found |
| Aztec | crypto | not found | no careers page found |
| Bitget | crypto, crypto-exchange | not found | no careers page found |
| Caldera | crypto | not found | no careers page found |
| Coinlist | crypto | not found | no careers page found |
| CoinMENA | crypto, crypto-exchange | not found | no careers page found |
| Decentraland | crypto | not found | no careers page found |
| Futu (Moomoo) | brokerage, wealth | not found | no careers page found |
| HTX | crypto, crypto-exchange | not found | no careers page found |
| Linera.Io | crypto | not found | no careers page found |
| M2 | crypto, crypto-exchange | not found | no careers page found |
| Mara | crypto | not found | no careers page found |
| MEXC | crypto, crypto-exchange | not found | no careers page found |
| Network International | payments | not found | no careers page found |
| Oasisnetwork | crypto | not found | no careers page found |
| Obol-Tech | crypto | not found | no careers page found |
| Pyth | crypto | not found | no careers page found |
| Pyypl | payments | not found | no careers page found |
| Scroll | crypto | not found | no careers page found |
| Shardeum | crypto | not found | no careers page found |
| Ssv.Network | crypto | not found | no careers page found |
| Telr | payments | not found | no careers page found |
| Tiger Brokers | brokerage, wealth | not found | no careers page found |
| Wyndlabs | crypto | not found | no careers page found |
| YAP | digital-bank, payments | not found | no careers page found |
| Zora | crypto | not found | no careers page found |
| ADGM | regtech | not scannable (oracle) | oracle:fa-eukk-saasfaprod1 |
| Admirals | brokerage | not scannable (workable) | workable:admirals |
| Bitfinex | crypto, crypto-exchange | not scannable (recruitee) | recruitee:bitfinex |
| Circle | payments | not scannable (workday) | workday:circle/wd1/circle |
| Deribit | crypto, crypto-exchange | not scannable (recruitee) | recruitee:deribit |
| Distributedcrafts | crypto | not scannable (workable) | workable:distributedcrafts |
| Emirates NBD | banking | not scannable (oracle) | oracle:fa-evlo-saasfaprod1 |
| Equiti | brokerage | not scannable (successfactors) | successfactors:egmmarketip2 |
| eToro | brokerage, wealth, crypto | not scannable (comeet) | comeet:41.009 |
| Hex Trust | crypto, digital-assets | not scannable (workable) | workable:hextrust |
| IC Markets | brokerage | not scannable (bamboohr) | bamboohr:icmarketsglobal |
| Io-Global | crypto | not scannable (workable) | workable:io-global |
| Leverate | trading-tech, brokerage | not scannable (comeet) | comeet:02.004 |
| Mashreq | banking, digital-bank | not scannable (taleo) | taleo:mashreqbank |
| O1labs | crypto | not scannable (rippling) | rippling:o1-labs-operating-corporation |
| OANDA | brokerage | not scannable (workday) | workday:oanda/wd10/external |
| Pepperstone | brokerage | not scannable (workable) | workable:pepperstone |
| Rapyd | payments | not scannable (comeet) | comeet:73.00e |
| Safe.Global | crypto | not scannable (personio) | personio:safe-labs |
| Saxo Bank | brokerage, wealth | not scannable (workday) | workday:saxobank/wd3/careeratsaxobank |
| Tabby | lending, payments, fintech | not scannable (pinpoint) | pinpoint:tabby |
| Tickmill | brokerage | not scannable (bamboohr) | bamboohr:tickmill |
| Walletconnect | crypto | not scannable (workable) | workable:walletconnect |
| Webull | brokerage, wealth | not scannable (rippling) | rippling:webull |
| Zodia Custody | crypto, digital-assets | not scannable (workable) | workable:zodia-custody |
| ADCB | banking | unreachable | HTTP 403 (https://adcb.com/company/careers) |
| AvaTrade | brokerage | unreachable | HTTP 403 (https://avatrade.com/company/careers) |
| BitOasis | crypto, crypto-exchange | unreachable | HTTP 403 (https://bitoasis.net/company/careers) |
| Cointracker | crypto | unreachable | HTTP 403 (https://cointracker.io/company/careers) |
| DIFC | regtech | unreachable | HTTP 429 (https://difc.ae/company/careers) |
| Emirates Digital Wallet | fintech | unreachable | fetch failed (https://edw.ae/company/careers) |
| Exness | brokerage | unreachable | HTTP 404 (https://exness.com/company/careers) |
| Foundrydigital | crypto | unreachable | HTTP 403 (https://foundrydigital.com/company/careers) |
| FXCM | brokerage | unreachable | HTTP 403 (https://fxcm.com/company/careers) |
| Messari | crypto | unreachable | HTTP 429 (https://messari.io/company/careers) |
| Polymesh | tokenization | unreachable | HTTP 404 (https://polymesh.network/company/careers) |
| Revolut | digital-bank, payments | unreachable | HTTP 403 (https://revolut.com/company/careers) |
| Sygnum | crypto | unreachable | HTTP 403 (https://sygnum.com/company/careers) |
| Tarabut | banking, payments | unreachable | HTTP 404 (https://tarabut.com/company/careers) |
| Theblock | crypto | unreachable | HTTP 403 (https://theblock.co/company/careers) |
| Trojan-Trading | crypto | unreachable | HTTP 403 (https://trojan.com/company/careers) |
