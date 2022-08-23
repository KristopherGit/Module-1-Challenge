# Unit 1 Homework Assignment: FinTech Case Study

## Overview and Origin

- Name of company:

  Kraken

- When was the company incorporated?:

  The company was incorporated July 28th, 2011.

- Who are the founders of the company?:

  The founders of the company included Jesse Powell and Thanh Luu.

- How did the idea for the company (or project) come about?:

  The inception and core development of Kraken arose while Powell was working as the operations lead of Mt.Gox. With the understanding that Mt.Gox was suffering from severe security issues and not immune to future failures - as was foreshadowed by the June 13, 2011 hack and bitcoin theft - Powell recognized a more robust trading & storage platform was required to service the growing interest in cryptographic currencies moving forward. Powell understood that site security, reliability and stability were core attributes inherently required in a successful trading platform.[1]

- How is the company funded? How much funding have they received?:

  Shortly after its initial public launch date of September 2013, Kraken received its first major backing from Munich based investment bank Fidor Group, which initially allowed Bitcoin, Litecoin and Dogecoin to be traded with traditional forex pairings.[2]

  Not soon afterwards, in March 2015 Kraken announced its first ever Series A funding from European based Hummingbird Ventures as well as Bitcoin Opportunity Fund (currently restructured as Digital Currency Group) of American origin. The combined venture capital investment from both firms yielded Kraken a $5M seed investment package.[3]

  Additional funding has come in the form of two Series B investment injections from Japan's based SBI Investments in February 2016 and Money Partners Group in April 2016. Both companies did not disclose the exact dollar figure of each funding injection, but were reportedly in the multi-million dollar range. Both firms are currently based in Japan.[4]

  Most recently as of last year, Kraken has been in talks to raise additional funding via investments from Fidelity, Tribe Capital and General Atlantic as of early 2021. As of recent, total funding since 2011 as approximated $125M in venture fundraising.[5]

## Business Activities:

- What specific financial problem is the company or project trying to solve?

  At a macro level view, Kraken's attempted mission is to provide the most secure network & ecosystem for institutional and retail investors in the cryptocurrency domain. It's core business revolves around generating margin fees from providing spot trading (with or without margin trading options), parachain auctioning, and token staking options for clients. It's trading platform can be accessed via a traditional desktop interface as well as an iOS based trading app. More recently, Kraken is also expanding into the non-fungible tokenized asset (NFT) sales realm.[6]

- Who is the company's intended customer? Is there any information about the market size of this set of customers?
  What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)

  Kraken's customer based is broad, but its core audience is focused on the emerging retail investor & trader.

  One specific feature that Kraken embodies and aims to set themselves apart from their competitors is their enabling of 'Proof of Reserves Auditing' mechanisms. Proof of Reserves Auditing enables existing Kraken customers to verify that their customers BTC & ETH holdings are accounted for and verified to be held in security via Kraken's cold wallet & air-gapped storage solutions. Kraken has utilized third party traditional banking accounting & auditing firm Armanini LLP to perform such audits. These audits conducted at semi-annual frequency, are performed to ensure transparency, verifiability & security for Kraken's customer base. Armanino LLP conducts such audits by using Kraken's user balances in an anonymous fashion in order to ensure balance values match, while at the same time shielding clients' sensitive user information.[7]

  Alongside Armanino's independent audit, results are then accessible on an individual customer basis to Kraken's clients. Subsequent to the finalized audit, customers are then able to access their individual audit results via a three-step verification process through Kraken's user setting's interface.

  As recently as 2021, various polling has placed ownership of some type of cryptocurrency - with regards to the customer base in the United States - between 16% and 21%. Comparatively, FDIC data analytics has reported that approximately 94.6% of American consumers have registered bank accounts in some form. Therefore, a wide gulf still exists between those invested and working within the traditional banking sector, and those who have still yet to hedge some of their portfolio in cryptocurrencies. Therefore, companies such as Kraken should be positioned strategically to take advantage of this expanding consumer investment base in the coming future.[8]&[9]

  Furthermore, with regards to its fees, relatively speaking, Kraken does offer a lower (maker/taker) fees than a significant amount of its competitors. Kraken currently offers 0.16% maker and 0.26% taker fees on each exchange transaction. This places Kraken slightly above the average trading fee range of all surveyed crypto spot trading exchanges with an industry global average of 0.16 maker and 0.213 taker fees, according to a study published in Cryptowisser.com, but still allowing them to be relatively competitive.[10]

  Amongst industry leaders, Coinbase for instance, imposes trading fees ranging from a flat $1.49-2.99/1.49% and 0.5-1.00% on spread trades. Moreover, Binance institutes a 0.1% maker and 0.1% taker fee, making it slightly more attractive than Kraken for basic spot trading purposes at the present time. Hence, although it offers roughly the industry average for trading fees, Kraken's advantage lies in its historical security reputation & remains less risky since it does not offer the liquidity risk issues of high margin trading that competitors such as Coinbase & Binance deal with.[11]

- Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)

  Up until 2018, Kraken's back-end API was developed utilizing PHP web server based architecture, with other elements of the platform written in a variety of other languages including C++ and Google's native language, Go. As of recent, however, Kraken has shifted its core exchange platform to Rust. Rust was chosen as the core underlying code base for Kraken's key exchange back-end API due to its better security and performance features than PHP.

  The process to migrating all of Kraken's back-end API & other services from PHP to Rust is a compartmentalized process, whereby functionality segments of the service are upgraded in stages and stored on their private Github repositories.

  In addition to the main back-end exchange services being transitioned to the Rust language, Kraken has also built its developing Kraken Future's Exchange platform, Kraken Bank as well as their underlying cryptocurrency cold storage wallets using the Rust language.[12]

  Additional software used for their business analytics side of the company includes implementation of Microsoft's Power BI. And for Kraken's software infrastructure implementation management side, Kraken employs Hashicorp's Terraform software in order to aid in deploying specific applications onto the underlying cloud-based infrastructure.[13]

## Landscape:

- What domain of the financial industry is the company in?

  As mentioned previously, Kraken's domain of expertise is in the cryptocurrency trading and banking space. The fintech space has unofficially been categorized as sub-divided into four main categories, colloquially referred to as the 'ABCDs' of fintech. Those four categories are cloud computing, AI, blockchain and big data. Subjectively, one could say the technology behind Kraken's trading & crypto banking framework borrow from each of the four. However, the focal point of Kraken's business lies in the field of blockchain.[14]&[15]

- What have been the major trends and innovations of this domain over the last 5-10 years?

  To summarize the complexities, potential & realized social changes forged since the Bitcoin White Paper was published in 2008 is a daunting task unto itself. However, this abridged account of blockchain's relatively short reign will attempt to highlight the keystone events & developments in the space, thus far.

  Bitcoin (BTC/XBT), emerged as a concept & soon to be dominant form of decentralized electronic ledger who's transaction verification utilized a complex mixture of SHA-256 cryptographic verification and proof-of-work (PoW). Proof-of-work is the underlying core concept toward block creation & bitcoin creation via the block mining concept whereby a computer network of mining CPU's compete to solve complex mathematical problem whereby the 'winner' of the then presently solved block of transactions is awarded or paid with newly generated bitcoin.

  After the publication of Satoshi Nakamoto's Bitcoin White Paper, the following year saw the mining of the first bitcoin genesis block. Mining and trading of bitcoins was now underway. Individuals in the tech & financial speculation space saw bitcoin tokens as an alternative hedge against government issued fiat and perhaps the first ever trustless secured P2P global digital currency network. As value was sought in the finite nature of the ledger's available tokens, trading soon began underway amongst hardcore enthusiasts and emerging market exchanges. The first so called proto-exchanges involved P2P forums such as Bitcointalk, 'bitcoin faucet' distribution systems & finally Bitcoin Market. Bitcoin Market was fundamental in establishing a spot market bitcoin pricing index and acted as a temporary third party custodian for transactions between buyers & sellers. Payments on Bitcoin Market where settled via PayPal's services.

  Between 2010-2011, several more spot exchanges began to make their way onto the scene including VirWox, Tradehill and perhaps one of the most infamous exchange, Mt. Gox - originally a website used to trade digital Magic the Gathering Cards, prior to 2010.
  Mt.Gox, however, was plagued with many of the same trust & security issues other exchanges faced in an an emerging new global digital currency environment. Although by 2013 Mt. Gox was handling approximately 70% of all bitcoin transactions at the time, their lingering security vulnerabilities culminated in a number of hacks & theft that inevitably led to the downturn of the company in 2014. Other exchanges continued to face hacks over the years since Mt.Gox's attack including Bitfinex, Binance, Bitstamp, and Bithumb, to name a few.[15b]

  The optics for bitcoin's reputation as a safe-haven were saddled by the fact that the exchanges required to obtain bitcoin were notorious for being unsecure and unregulated as the years went by. However, this in part became a driving force toward a push for more regulation in the industry. Also, customers were driven towards taking accountability & responsibility for their own bitcoin as the push toward cold wallet storage emerged. With cold wallet & off-exchange private security wallets, customers would then be required to keep the private keys of their own corresponding public keys in their personal possession.

  Since this time, the industry leading - or at least, industry surviving - exchanges leaned toward a better focus on security, compliance and regulation after a furious spree of ongoing security breaches. All of these have been tedious and slow to develop over the years, however.

  Since the introduction of major exchanges & as the bitcoin network effect took hold, numerous technologies branched off from this main decentralized blockchain network. Since 2011, thousands of colloquially defined 'altcoins' emerged on the scene. The most infamous was Ethereum (ETH) being a competing form of currency that utilizes a philosophically and functional alternative to the PoW theorem and instead is merging toward a proof-of-stake (PoS) based algorithm. Ethereum also differs in that it is an altcoin that embodies smart-contract capabilities within its algorithm and tokenization properties. Smart-contracts have created the realized and unrealized possibility of transactions that not only settle a value amount, but also have a pseudo-legal contractual/ownership obligations between both parties of the transaction. This has opened a pandora's box of new digital financial products including the tokenization of digital property, goods & services in the form of NFTs. Other altcoins have emerged in an exponential growth phase since Ethereum's ERC-20 tokens arrived on the scene. Some of these altcoins found utility in the realm of decentralized energy usage tokenization, shared CPU/GPU decentralized work tokenization, and a variety of other digital utilities.

  Only within the last few years have traditional financial institutions arrived into the space. However, the trend toward institutional investment is only expected to continue as government based institutions grapple with balancing free-market innovation & required government regulation in the space. Institutional hurdles are being tamed as the industry has witnessed some of the first corporate bought & individually held bitcoin (i.e. through Microstrategy, Blackrock, Tesla, etc.), the creation and deployment of spot & future's ETFs, and government's recognition of Bitcoin and other altcoins as either legitimate currency or securities.[16]

- What are the other major companies in this domain?

  Within the direct spot cryptocurrency exchange trading & banking space, the industry's top revenue earners include Binance, Coinbase, Deepcoin, FTX, KuCoin, Crypto.com, among others. Coinmarketcap currently lists approximately 290 currently operating spot exchanges in the cryptocurrency spot market trading sphere in which Kraken competes within. [17]

## Results

- What has been the business impact of this company so far?

  Kraken's impact within the cryptocurrency realm of fintech has been significant, albeit at a relatively consistent growth pace relative to the top revenue earners in the industry.

  More importantly, however, is Kraken's ability to maintain sustained growth while nurturing a trading exchange ecosystem that has earned a reputation for high security for its customers. Since 2011, there have been no reported large scale major hacks or compromises reported within Kraken's infrastructure. There have been reports of some customers losing funds or reported to have been hacked, but to date those appear to be either isolated incidents, unconfirmed reports, hearsay or compromises resulting from accidentally leaked private information from the user's end.

  In the approximate $125M raised in venture capital, Kraken's marketcap has an estimated low-end valuation of $10B, according from sources at Bloomberg & Sacra. This roughly puts its P/S (price-to-sales ratio) multiple in the range of 22.0x, in mid-2021. At the same time, this gives it a much higher estimated P/S ratio relative to its top peers - Coinbase and Binance. Coinbase was reported to have a P/S ratio of approximately 5.5X, and Binance had an estimated P/S ratio of approximately 15X. Thus, Kraken could be considered to have over-evaluation relative to its peers.

  Since its inception, Kraken has been able to maintain a high level of security while at the same time develop a substantial customer following. On average, Kraken ranks between 27th and 42nd worldwide in terms of spot exchange volume. However, when factoring qualitative measurements including customer service, cybersecurity ratings, reliability & trustworthiness it ranks approximately between 4th & 8th according to exchange data analytics/tracking websites Coinmarketcap & CoinGecko.[18],[19] & [20]

- What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?

  Core metrics in the spot crypto trading exchange can, at times, often be manipulated and not totally reliable. However, when referencing so called self-regulated or reported data within the crypto spot exchange realm, standard yearly revenue as well as average 24hr volume, as well as daily/weekly user visitation numbers can be a useful - if not always reliable - gauge for measuring the relative size & weight of a crypto exchange company.

  Presently within Coinmarketcap's database of 290 currently operating exchanges with reportable 24hr volume, site visits, and liquidity quality ratings, Kraken ranks 42nd with an average trading volume $603M (dated 08/16/22).[21]

  Additionally, Kraken has demonstrated positive growth the past year by building up a team of over 637 current employees and growing their workforce by 25% as of last year.[22]

- How is your company performing relative to competitors in the same domain?

  Relative to Kraken, Coinbase is currently the leading American crypto trading firm with reported 10-K annual revenue for the 2021 calendar year at $7,354,753.[23]

  Binance, on the other hand, is reported to have generated approximately $20,000,000,000 in the same year. Being a privately traded company, these stats may not be entirely accurate, but at least gives a range to work with in comparison to Coinbase. Furthermore, estimates on Kraken's net income for the 2021 calendar year fall somewhere between $200,000,000 and $450,000,000. Again, not being a publicly listed company, accurate financial details otherwise derived from a standard 10-K are difficult to precisely obtain.[24]&[25]

  Furthermore, it is reported that although daily trading volumes reportedly fluctuate between 27th and 42nd (on average as of 08/16/22), Kraken does hold the spot for the 4th largest cryptocurrency centralized trading exchange in the world, with a market share claimed ownership of 3.2% as of 2021.[26]

  Growth of the workforce, as reported earlier has been steady with positive 25% growth in its workforce over the 2021 calendar year, however, this was dwarfed by rising crypto giants Binance and Coinbase who reportedly have an employee base of 10623 employees at a 395% growth rate, and 6222 employees at a 133% growth rate, respectively.[27]

## Recommendations

- If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

_Note: In the recommendations section, each sub-section is broken up into lower-case Roman numerals that are carried forth through each individual sub-section question. (I.e. i.) & i.) are a single recommendation carried through)._

i.) <u>Taker/Maker Fees:</u> As an advisor to this company, the first recommendation I would suggest is a way to lower taker/maker fees to be inline with Binance - the industry marketcap leader - in a bid to attract new customers. This would involve lowering the current maker/taker percent rate fees from 0.16% & 0.26% to 0.1% and 0.1%, respectively.

ii.) <u>Advertising & Higher Risk Leverage:</u> Secondly, another option to look into in order to potentially increase revenue and/or grow Kraken at a more significant rate, say in order to keep up with the industry leaders in the space, it may be worth considering expanding marketing in step with increasing the number of cryptocurrencies offered on the exchange with more options in terms of leveraged positions.

iii.) <u>Release a Native Cold-Storage Wallet></u> Finally, I would like to see Kraken get into the business of designing & manufacturing their own proprietary hardware wallet. According to their blog archive, they have a natural affinity to reverse engineering & finding flaws in pre-existing cold storage hardware wallets (i.e. finding vulnerabilities in Trezor's and Ledger's prior firmware upgrades). I suspect they have the talent & expertise to at least conceptually design and/or manufacture and lend their name to their own branded wallet.

- Why do you think that offering this product or service would benefit the company?

i.) <u>Taker/Maker Fees:</u> Again, with respect to maker/taker fees, onboarding new customers is always a difficult task and bringing them inline with the industry leader would be a step in the right direction on a global scale. Although, this amounts to an upfront & immediate reduction in revenue, with strategic implementation this initial revenue hit would optimistically be offset with a volume gain in net customer growth. Afterwards, once a larger growth rate is established and net customer account numbers have risen, a re-adjustment in positive rate increases could then be reconsidered.

ii.) <u>Advertising & Higher Risk Leverage:</u> This recommendation would be considered the most debatable of all included in this list. With increasing higher margin trading you introduce new potential risks inherent to the companies held currency reserves and risks associated with operating in specific countries/jurisdictions that might ultimately affect Kraken's macro business environment, nonetheless they are worth exploring in at least some detail. For instance, Binance and FTX both offer leveraged trading options as high as 20x, whereby Kraken only operates up until 5x (depending on the currency pairing utilized). Although not every customer would ultimately take advantage or want to risk as high as 20x, advertising this as an option becomes an attractive & enticing option outside the realm of traditional marketing strategies.

iii.) <u>Release a Native Cold-Storage Wallet> </u>With their own proprietary air-gapped cold storage hardware wallet, they would first of all create a new revenue stream. Secondly, there could be some interesting innovations they could develop in the future through the interface of their existing trading platform & an semi-limited/controlled interaction with their hardware wallet.

- What technologies would this additional product or service utilize?

i.) <u>Taker/Maker Fees:</u> As for maker/taker fee adjustments to attract new customers, currently no new technologies would have to be implemented, therefore, resulting in no upfront reinvestment and/or write down of capital expenditures.

ii.) <u>Advertising & Higher Risk Leverage:</u> Again, no new technologies would again have to be employed if these trading leveraged margins were expanded. There would, however, have to be adjustments made at in the account/reserve balances of Kraken's core holdings and possibly the addition or changes to risk analytic models that its team uses to evaluate the overall dynamic risk the company is involved in at any one time.

iii.) <u>Release a Native Cold-Storage Wallet></u> This would utilize a physical hardware device that Kraken would develop in house & have complete autonomy over. This may involve the purchase of a pre-existing hard-ware wallet startup company or investing in their own R&D/manufacturing facility.

- Why are these technologies appropriate for your solution?

i.) <u>Taker/Maker Fees:</u> N/A

ii.) <u>Advertising & Highr Risk Leverage:</u> N/A

iii.) <u>Release a Native Cold-Storage Wallet></u> A hardware wallet would be an appropriate solution because they could already leverage their in house security teams & pre-existing hardware hacker/vulnerabilities testing teams to further solidify themselves as a company with a reputation & genuine concern for customer cryptocurrency security. Again, there could be interesting innovations & tech developed in the future between their existing high security trading exchange & interfacing with a native cold wallet they have oversight on. For instance, by having a cold wallet linked in an air-gapped way to a customer's account they could open new & safe opportunities in staking rewards issuance going forward.

&nbsp;
&nbsp;
&nbsp;
&nbsp;

<u> References: </u>

1.) Alpeyev, Pavel. (2014, August 17). <i>Mt. Gox Insider’s Kraken Bitcoin Exchange to Open in Japan</i>
https://www.bloomberg.com/news/articles/2014-08-17/mt-gox-insider-s-kraken-exchange-to-open-in-japan-next-month

2.) https://www.coindesk.com/markets/2013/10/09/kraken-partners-with-fidor-bank-to-offer-bitcoin-trading-services-in-the-eu/

3.) Kerr, Dara. (2014, March 25). <i>Bitcoin exchange Kraken raises millions of dollars</i> https://www.cnet.com/tech/services-and-software/bitcoin-exchange-kraken-raises-millions-of-dollars/

4.) Dotson, Kyt. (2016, April 12). <i>Money Partners Group fuels Bitcoin exchange Kraken with Series B Investment</i> https://siliconangle.com/2016/04/12/money-partners-group-fuels-bitcoin-exchange-kraken-for-series-b-investment/

5.) Sinclair, Sebastian (2021, February 26). <i>Kraken Negotiating New Capital Raise At Least A $10B Valuation Report</i> https://www.coindesk.com/markets/2021/02/26/kraken-negotiating-new-capital-raise-at-least-a-10b-valuation-report

6., 7.) Rapoport, Alex. (2022, February 03). <i>Kraken Launches Proof of Reserves Audits Allowing Clients to Verify Crypto Balances</i> https://financialpost.com/pmn/press-releases-pmn/business-wire-news-releases-pmn/kraken-launches-proof-of-reserves-audits-allowing-clients-to-verify-crypto-balances

8.) Perrin, Andrew. (2021, November 11). <i>16% of Americans say they have ever invested in, traded or used cryptocurrency</i> https://www.pewresearch.org/fact-tank/2021/11/11/16-of-americans-say-they-have-ever-invested-in-traded-or-used-cryptocurrency/

9.) Franck, Thomas. (2022, March 31st). <i> One in five adults has invested in, traded or used cryptocurrency, NBC News poll shows </i> https://www.cnbc.com/2022/03/31/cryptocurrency-news-21percent-of-adults-have-traded-or-used-crypto-nbc-poll-shows.html

10.) Ramberg, Richard. (October 30th, 2021). <i> EMPIRICAL STUDY: Average Crypto Trading Fees, 31 October 2020 </i> https://www.cryptowisser.com/news/average-crypto-trading-fees-october-2020

11.) Lodha, Chandan. (July 22nd, 2022). <i> 2022 Crypto-Exchange Fee Comparison </i> https://www.cointracker.io/blog/2019-crypto-exchange-fee-comparison

12.) Chemouil, Simon. (February 19th, 2021). <i> Oxidizing Kraken: Improving Kraken Infrastructure Using Rust </i> https://blog.kraken.com/post/7964/oxidizing-kraken-improving-kraken-infrastructure-using-rust/

13.) Zoominfo. (August, 22nd, 2022). <i> Kraken Overview </i> https://www.zoominfo.com/c/kraken/398664952

14.) Lai, Tze L.†, Liao, Shih-Wei., Wong, Samuel P. S., and Xu, Huanzhong. (June 23rd, 2020). <i> Statistical models and stochastic optimization in
financial technology and investment science </i> https://tzelai.ckirby.su.domains/pubs/2020_AMSA_05_02_A05.pdf

15.) Khan, Faisal. (July 18th, 2018). <i> The ABCDs of Fintech </i> https://www.datadriveninvestor.com/2018/07/18/the-abcds-of-fintech/

15b.) Sheldon, Robert. (August 9th, 2021). <i> A timeline and history of blockchain technology </i> https://www.techtarget.com/whatis/feature/A-timeline-and-history-of-blockchain-technology

16.) Cryptopedia Staff contributions. (March 17th, 2022). <i> The Early Days of Crypto Exchanges - More Bitcoin Exchanges Hit the Scene </i> https://www.gemini.com/cryptopedia/crypto-exchanges-early-mt-gox-hack#section-more-bitcoin-exchanges-hit-the-scene

17.) CoinGecko - Exchanges. (August 16th, 2022). https://www.coingecko.com/en/exchanges

18.) CoinmarketCap - Exchange Rankings. (August, 16th, 2022). https://coinmarketcap.com/rankings/exchanges/

19.) Sacra. (August 16th, 2022). Kraken Overview https://sacra.com/c/kraken/

20.) CoinGecko - Exchanges. (August 16th, 2022). https://www.coingecko.com/en/exchanges

21.) CoinmarketCap - Exchange Rankings. (August, 16th, 2022). https://coinmarketcap.com/rankings/exchanges/

22.) Growjo - Kraken Digital Asset Exchange Revenue and Competitors. (August 16th, 2022). https://growjo.com/company/Kraken_Digital_Asset_Exchange

23.) Coinbase Global Inc. (2021, December 31). <i>Form 10-K</i>. Retrieved from Investor Coinbase - Financials - SEC Filings. https://d18rn0p25nwr6d.cloudfront.net/CIK-0001679788/8e5e0508-da75-434d-9505-cba99fa00147.pdf

24.) Curry, David. (May 4th, 2022). <i> Binance Revenue and Usage Statistics (2022) </i> https://www.businessofapps.com/data/binance-statistics/

25.) Sacra. (August 16th, 2022). Kraken Overview https://sacra.com/c/kraken/

26.) Sacra. (August 16th, 2022). Kraken Overview https://sacra.com/c/kraken/

27.) Growjo - Kraken Digital Asset Exchange Funding. (August 16th, 2022).https://growjo.com/company/Kraken_Digital_Asset_Exchange#funding-rounds
