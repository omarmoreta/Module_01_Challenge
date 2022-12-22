# Module 1 Challenge
### Unit 1 Homework Assignment: FinTech Case Study

# Name of company
* Robinhood Markets, Inc. (subsidiaries - Robinhood Financial LLC., Robinhood Securities, LLC., and Robinhood Crypto, LLC.)

# When was the company incorporated?
* Incorporated in the State of Delaware on November 22, 2013.

# Who are the founders of the company?
* Vladimir Tenev and Baiju Bhatt.

# How did the idea for the company come about?
* Robinhood’s story begins almost a decade ago at Stanford, where Baiju and Vlad met as roommates and classmates. After graduation they packed their bags for New York and built two finance companies, selling trading software to hedge funds. With their newfound experience in the world of finance, they realized that big Wall Street firms pay effectively nothing to trade stocks, while most Americans were charged commission for every trade. They soon decided it was more important to build products that would provide everyone with access to the financial markets, not just the wealthy. Two years after heading to New York, they moved back to California and built Robinhood — a company that leverages technology to encourage everyone to participate in our financial system.

# How is the company funded? How much funding have they received?
### Funding
* Rebates from market makers and trading venues - this algorithm, known as the smart order router, prioritizes sending customer orders to a market maker that’s likely to give customers the best execution, based on historical performance. As of May 13, 2022, for every $100 of notional crypto order volume executed, Robinhood received $0.35 in rebates from its trading venues. Rebates account for 70% of their revenue.
* Robinhood Gold subscription - gives access to Morningstar research reports, NASDAQ Level II Market Data, bigger instant deposits, and margin investing at a discounted rate.
* Margin interest - If eligible for Gold subscription, customers pay a $5/monthly subscription fee plus 7% yearly interest on the settled margin amount above $1,000. 
* Stock loan - Robinhood Securities earns income from lending securities to counterparties.
* Income generated from cash - Robinhood Securities generates income on uninvested brokerage cash that isn't swept to the brokerage cash sweep network of program banks, primarily by depositing this cash in interest-bearing bank accounts.
* Cash Management - Sutton Bank, which issues the Robinhood debit card, receives an interchange fee that is passed to Robinhood Financial.
* Other - smaller revenue streams, including proxy service revenue and fees.

### Funding Received
* Robinhood has raised a total of $6.2B in funding over 28 rounds. Their latest funding was raised on May 13, 2022 from a Post-IPO Secondary round. Robinhood is funded by 81 investors. Robinhood generated $1.81 billion revenue in 2021.

## Business Activities:

# What specific financial problem is the company or project trying to solve?
* The company's mission is to "democratize finance for all". They were one of the first to pioneer commission-free trading in 2013, and at that time everyone, especially well-establish stockbrokerages, thought it was a big joke. But now, zero-commission trading has gone mainstream and there are fewer companies requiring minimums to open accounts or charging large fees to trade stocks, ETFs, and options. On the company's website it states that: "we believe that everyone should have access to the financial markets, so we’ve built Robinhood from the ground up to make investing friendly, approachable, and understandable for newcomers and experts alike." The company has essentially broken the barrier of entry for many investors.

# Who is the company's intended customer? Is there any information about the market size of this set of customers? 
* Robinhood targets anyone who is 18 years of age or older, lives in the U.S. - as a citizen, permanent resident, or has a valid U.S. visa, and has internet access to interact with the mobile app or website. There also is no minumum to open accounts which taps into the microinvestor market. Robinhood had 15.9 million active users in 2022 and 22.5 million in 2021. The average user is 31 years old, and the largest age group is people in their late 20's.

# What solution does this company offer that their competitors do not or cannot offer?
* At first, Robinhood was the only company offering commision-free trading but then other competitors joined in on the same offer after they had success. Now Robinhood offers crypto trading, IRA accounts with a 1% match, fractional shares investing, cash management - 4% interest on unbrokeraged balances, and a cash card. I think the advantage is mostly tied into the appeal to younger investors as 50% of users are investing for the first time and 80% are organic or referred new customers.

# Which technologies are they currently using, and how are they implementing them?
* Robinhood uses 29 technology products and services including HTML5, Google Analytics, and Google Fonts, according to G2 Stack. Robinhood is actively using 77 technologies for its website, according to BuiltWith. These include Viewport Meta, IPhone / Mobile Compatible, and LetsEncrypt. When Robinhood was first getting started, they were a Python/Django shop, however they’ve been shifting towards Go. They’ve also been microservices oriented, and most of their APIs are written in Python and Go. There is some Java and Rust in their codebase however. Robinhood is built on AWS, so they use Amazon RDS (Relational Database Service) for their data store. They use Postgres as the database engine for RDS.

* In December 2019, Robinhood’s system received 100k requests per second at peak time. In June 2020, Robinhood’s system received 750k requests per second, a 7x load increase to the system in a 6 month period. To respond to this, Robinhood set out to make their brokerage infastructure horizontally scalable. They accomplished this by implementing sharding into their system at the application layer (not just the database). Sharding is where you split up a large dataset into smaller partitions (shards). Robinhood created multiple shards where each shard held a subset of their users and every shard had its own application servers, database and deployment pipeline.

## Landscape:

# What domain of the financial industry is the company in?
* Stockbroker and Cryptocurrencies

# What have been the major trends and innovations of this domain over the last 5-10 years?
* Electronic trading has dramatically increased the trading volume and liquidity, which has reduced the dominance of brokers. Being a complete tech-driven platform, they can operate with substantially less overheads seeing a significant reduction in fees. The move to more digital platforms has opened up new avenues to robo-advisors, AI trading algorithms, and predictive stock ratings.

# What are the other major companies in this domain?
* Gradual reduction of commission due to ongoing competition has finally given birth to discount brokers like Robinhood, TradeStation Global and Firstrade. Almost every discount brokers have a similar pricing structure hence to differentiate everyone is focusing on technology. Leading players have been seen to advancing both their backend and frontend with the latest technologies such as EKYC, biometric authentication, order management systems, advanced charting, algo-trading & analytical solutions for technical and fundamental analysis etc. Discount brokers are investing heavily in technology to offer innovative solutions to investors. AI and ML has become the most frequently used technology structure in wealth management solutions. 

## Results:

# What has been the business impact of this company so far?
* Since 2010, the S&P 500 has produced an average annual return of approximately 13%. That has coincided with a substantial increase in participation among retail investors seeking to improve their financial health. Retail investing now comprises roughly 20% of U.S. equity trading volume, doubling in the decade from 2010 to 2020. Robinhood has had some positive, and profound, implications for the market. The company has removed barriers to trading by making investing commission-free and mobile-first. It has simplified investing, and made it more accessible and personal. Robinhood says its tools are reaching a more diverse group of investors. Citing data from a survey it conducted in December among over 98,000 Americans, it says 16% of its customers come from the Hispanic community, compared with 7% at incumbent brokerages including Schwab, E-Trade, Fidelity, TD Ameritrade and Vanguard; and 9% are African American, compared with 3% at other brokers. And it is bringing in younger investors. The company says Gen Y and Gen Z comprise 70% of its users.

# What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?
* Some of the core metrics for Robinhood and other companies in this domain are active users, monthly app downloads, and trading volume. For Robinhood, total trading volumes in July were down slightly from June 2022. Equities were $49 Billion (down 3%), Option contracts were 67 Million (down 2%), and Cryptocurrencies were $6 Billion (down 1%). Robinhood had 15.9 million active users in 2022 and 334,939 monthly app downloads in the last 30 days on its "Robinhood: Investing for All" app, according to Apptopia, down 7.83% from previous month. Based on these metrics the company is still sufering some growing pains. It lost millions of users from a high of 22.5 million in 2021 to 15.9 million this year. App downloads are also decreasing as well as trading volume month over month.

# How is your company performing relative to competitors in the same domain?
* Compare to similar companies, based on crunchbase data, like Bitfinex - 1.4 million monthly visits, Bitwise - 61K monthly visits, and Bitpanda - 2.2 million monthly visits, Robinhood has millions of more active users with 16.3 million monthly visits, hundreds of thousands more app dowloads monthly, and far more trading volume. Bitwise and Bitpanda are still growing and have positive monthly visits growth, 109.72% and 15.9% respectively. But Bitfinex lost 27.95% monthly visits in the last 30 days. 

## Recommendations:

# If you were to advise the company, what products or services would you suggest they offer?
* I would suggest the company to explore other options other than their payment-for-order-flow model, since it is banned in other parts of the world and it does not truly "democratize finance for all". Opening up in other countries can increase users and revenue streams for the company. Since they have cancelled prospects of expanding outside of the U.S. it is only democraticing finance for U.S. users. I think also expanding to maybe crypto options and futures would be a good idea to attract more users from other exchanges, especially since the fall of FTX which offered crypto options trading.

# Why do you think that offering this product or service would benefit the company?
* Their current model is flawed and forces the company to be at the mercy of the market makers, and it was very apparent when Robinhood froze trading on stocks, GameStop and BlackBerry, for a few days - which was thought to be caused by retail investors trying to "force a short squeeze" on the hedge funds. This move was seen as Robinhood trying to play the middle man and siding with Wall Street instead of allowing the market to playout without intervention. "It added $3.4 billion to its balance sheet during the GameStop stock squeeze, after suspending trades for a week" - TechCrunch. Expanding across the world and to more crypto products can help increase the user and app downloads they have lost in their recent controversies.

# What technologies would this additional product or service utilize?
* In order to expand to other countries, Robinhood might have to engage in some sort of foreign exchange products in order to convert deposits from new users from around the world. Also a new derivatives platform would need to be implemented in order for swaps, options, and futures to be transacted.

# Why are these technologies appropriate for your solution?
* These technologies seem appropriate to me for this solution because it is similar to what FTX was doing before it collapsed. It seemed to be working for the three years that FTX was operating but there maybe more research and testing to be done before it is rolled out to consumers. Possibly tighter regulations and accounting measures may need to be taken so another FTX doesn't happen again.

## Sources: 
* https://www.sec.gov/Archives/edgar/data/1783879/000162828021013318/robinhoods-1.htm
* https://robinhood.com/us/en/support/articles/how-robinhood-makes-money/
* https://www.crunchbase.com/organization/robinhood/company_financials
* https://www.businessofapps.com/data/robinhood-statistics/
* https://www.statista.com/statistics/822176/number-of-users-robinhood/
* https://blog.quastor.org/p/robinhoods-tech-stack
* https://stackshare.io/robinhood/robinhood
* https://pirimidtech.com/how-technology-is-transforming-the-brokerage-industry/
