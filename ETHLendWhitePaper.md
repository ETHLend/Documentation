# Documentation
ETHLend White Paper

Releasing soon

ETHLend
Democratizing Lending



 










Version 0.3
June 26, 2017
 

Table of Contents
Table of Contents	I
Executive Summary	III
1.	Background	1
1.1	About the White Paper	1
1.2	Lack of True Global Lending Market	1
1.3	Peer to Peer Lending and Cryptocurrency	2
1.4	Benefits of Decentralized Lending	3
1.4.1	Trustless	3
1.4.2	Transparency	3
1.4.3	Democracy and Access to Finance	4
1.4.4	Tokenization of Things	5
1.4.5	Current and Future Use-Cases for Decentralized Lending	6
2.	Why Ethereum Network?	7
2.1	Smart Contracts	7
2.2	Ether	8
2.3	Tokenization	9
2.4	Paradox of Value: Smart Contract Deployment	10
3.	Fully Decentralized On-Chain Solution for Lending Market	10
3.1	Secured Lending by Pledging Ethereum-Based Digital Tokens	11
3.1.1	New Loan Request	15
3.1.2	The Loan Contract	17
3.1.3	Sending Digital Tokens to the Smart Contract	18
3.1.4	Funding the Loan	21
3.1.5	Paying the Loan Back	23
3.1.6	Default Scenario	24
3.2	On-Demand Lending	26
3.3	Secured Lending by Pledging Ethereum Name Service Domains (ENS)	27
3.4	Unsecured Lending	29
3.4.1	uPort	30
3.4.2	Address Data	30
3.5	Introducing Credit Token (CRE) as the Reputation System	32
3.5.1	Rewarding Liquidity and Repayments	33
3.5.2	Credit Token as Reputation	34
3.5.3	Prevention of Misuse	35
3.6	User Experience on ETHLend	35
3.6.1	Accessibility	35
3.6.2	User Interface	35
3.6.3	Performance	35
3.6.4	Translations	36
3.7	Technical Roadmap	36
3.8	Map of ETHLend	37
4.	Legal Evaluation of the Loan agreement on ETHLend	37
4.1	Contractual Relationship	38
4.2	Collateral	39
4.3	Know Your Customer (KYC)	39
5.	ETHLend	40
5.1	The Team	41
5.2	Governance	41
5.3	Roadmap	41
6.	Token Sale	42
6.1	Token Distribution	43
6.2	Purchase Price	43
6.3	Burning Tokens	43
6.4	Vesting	44
6.5	Minting	44
6.6	Security	44
6.7	Funds Allocation	45
7.	Further Updates	45

 
Executive Summary
Text here
 
1.	Background
We are not professionals. We are people who want to develop something important and to break unworkable and unfair lending market. We want make lending available on global scale. Instead of relying on local banks and lenders, we believe that borrower should have the possibility to obtain a loan from anywhere in the loan. We believe that Canadian borrower could obtain a loan from Sweden, China, Brazil, Japan or Germany and vice versa. 
Why global lending market is important? When lending market is not bound by the borders and jurisdictions, there is true competition and liquidity available for the lending market. This means that same amount of liquidity is available for example in China as in Europe. The effect is revolutionary. Interest rate differences between countries and regions will disappear since there is more liquidity and competition.
Less control for the banks. Banks lend money that is deposited by the account holders. This liquidity is lend to the market. Practically it means that banks charge 5-12% interest on loans and compensate you 0-1% for holding your assets at the bank. Since the rise of crypto-currency, you can become your own banking institution. With ETHLend, you become your own lending institution. You decide whom you lend to, on which interest rate securely or insecurely. This all is available with blockchain technology, on which ETHLend relies on.
1.1	About the White Paper
This white paper is an overview on ETHLend, a decentralized lending application (DAPP) running on Ethereum Network. Besides the DAPP, this white paper covers the ideology of ETHLend, the team behind the innovation and the upcoming token sale for contributing to ETHLend.
Readability on focus. Since the popular adaption on Ethereum-based applications and interest on blockchain economy, we aimed to write this white paper to be understandable without wide knowledge or experience on technology associated with Ethereum. We tried to present the functions of the DAPP in much as possible in textual form and pictures. Moreover, when we present code, we explain it sufficiently enough to understand the function behind the code.
This white paper was compiled together with persistent effort. ETHLend team wanted to produce a coherent, understandable and plausible concept out to the public. We want to make sure that anyone associated or is contributing to ETHLend does understand our vision, who we are, how the DAPP works and how the token sale takes place. We hope that our white paper inspires you for new ideas and innovations on blockchain technology.
1.2	Lack of True Global Lending Market
There is no access to true global lending market. This is about to change. Today lending market is controlled by governmental monetary policies, which affect the competition on lending market. Moreover, politics casts a dark shadow on the lending market. Therefore, banks are controlled on how they loan and on what price.
Blockchain provides global access to transactions. Blockchain makes it possible to send transactions uninterrupted and uncompromised globally. By using the Ethereum blockchain technology, anyone can send to anywhere a transaction of value, Ether (ETH). ETH is the native token of Ethereum, which is used as compensation for sending transaction on the Ethereum network. Ethereum also provides the possibility to use Smart Contracts for the need of sophisticated and complex transactions.
Repairing the lending market. Today the inflation-adjusted interest rate in different countries varies based on the available liquidity. In high liquidity market, Europe, interest rates are between 0.5-5 percent, in Russia 12-15 percent, in India 12 percent and in Brazil 32 percent. This means that there is inequality in the lending market based on where liquidity is located. We believe that this inequality between the borrowers from different regions should be democratized.
Somekind of before (left side) and after (right side). Pictures with world map. On left world map different sizes of interest rate (can be arbitrary, no need to be precise) on diagram followed by percent (%) sign. On the right side these different sizes of diagrams are all in the same level (flattened) to indicate global competition on interest rates (should be lower than average on left side).
Inequality has many reasons. Indeed higher interest rates on some countries are a product of high risk on default. However, we believe that if there would be more liquidity on these high interest rate markets, there would be more pressure on the interest rates. Moreover, using collaterals such as we are presenting on this white paper would provide the ratio to lend to these markets.
The crypto-currency economy provides the environment to democratize the lending market. First, crypto-currency is not effected by FIAT-based currency inflation. Therefore, borrowers are treated equally positions since they are all borrowing ETH. This means that no government monetary policy or economic change in FIAT-based country affects directly to crypto-currency lending. Secondly, the lending market is open for all lenders and borrowers. This means that lending is not restricted by borders, jurisdictions or even by the access to banking system.
Risk derived from different regions and lending markets. Since the borrowers are pledging Ethereum-based ERC-20 compatible digital tokens (ERC-20 Tokens) or Ethereum Name Service domains (ENS domains), the loans are secured and could be equally treated. Therefore, we do not need to set the borrowers in unequal position by conducting subjective assessment on the borrower. Instead, we can objectively assess the risk level on the collateral that the borrower has provided even the need to know any backgrounds of the borrower. The borrower can use self-assessment of the collateral before placing the loan request by picking the price of the ERC-20 token from exchange.
After the borrower has a price at hand, the volatility is calculated to make sure that the collateral is sufficient by end of the loan period. Volatility is calculated typically in 3-month-period, 6-month-period or 12-month-period. Therefore, even though the borrower is located in high interest rate region, decentralized lending can bring new liquidity to that regional lending market. For example, a Chinese borrower might be restricted by the capital provided by Chinese lenders and banks. With decentralized lending and the Ethereum Blockchain Network, the Chinese borrower could attract lenders from other parts of the world. Since the collateral is ERC-20 token or ENS domain, the lender has less risk of losing the loan capital.
Tokenization of assets opens the door for true global liquidity. Asset tokenisation provides that an ERC-20 token represent real assets such as gold, company shares or property. Tokenization would result that a borrower in Canada could place a property that the borrower is about to purchase in to an ERC-20 token. Then, the borrower could pledge the token on ETHLend and request funding not solely from Canadian lenders, but globally from any lender from any part of the world. This is a game changer in the financial industry.
1.3	Peer to Peer Lending and Cryptocurrency
Risk of default as a barrier in decentralised crypto-currency lending. There are no obstacles on lending crypto-currency as such. Any crypto-currency could be lend to anyone anywhere, and it would be a simple transaction. Then again, how do we know that the borrower will repay the loan? In FIAT economy, if you do not pay a loan back, your credit score or rating declines. This means that you might not get another loan from the market. However, in decentralized blockchain environment, securing the repayment of the loan needs more creativity in working solely on-chain.
Securing the repayment of decentralised loans. As transactions in Ethereum network are conducted by address-to-address traffic, so is the lending. Therefore, it would be impossible to know whether the borrower that the lender has sent Ether would pay the loan back in a situation where the lender and the borrower do not know each other. Since we are working in a fully decentralized environment, the solution should be on-chain as well.
Represented value as a collateral for borrowing. Contrary to what might occur, Ethereum-based ERC-20 tokens are perfect for the use of as a collateral. First, all popular Ethereum-based ERC-20 tokens are traded on exchange. Therefore, we do not have to roll the dices to form a price on most common ERC-20 tokens. Secondly, since we have a price, we usually have the price history as well. This means that we can calculate the volatility of the ERC-20 token and take the volatility in to account when we are pledging the tokens to attract lenders.
Graphics: Box of Ethereum Based tokens (at least 8 different) and exchange rate arrow behind going up and down or something similar
Moreover, Ethereum-based ERC-20 tokens are easily transferrable between Ethereum Wallets and Smart Contracts. Lastly, digital tokens are flexible. You can tokenize anything that has value. Due to this flexibility, real assets such as real property, company shares and commodities can be placed on a token and pledged for a loan. The aforementioned function could revolutionize lending and trading on all assets. Even assets or value that was previously hard to value and trade, would be now be available for liquidity.
Example, we want to launch a rocket into the moon and we need to finance this venture. We could tokenize the rocket, all parts, rocket launcher, the company behind the venture to be represented as ERC-20 token called ROCK. Next, to finance the project we can pledge the tokens on decentralized lending platform such as ETHLend. Now anyone can participate in the funding of the rocket venture. The same is applicable on todays infrastructure projects such as nuclear power plants, solar power plants or privately held factories.
1.4	Benefits of Decentralized Lending
Decentralization provides more security and trust by design. Decentralization is a method to organise anything in a way that does not require trust on third parties. The trust is eliminated by executing code that does not require central government, management or central servers.
Decentralization changes dramatically the architecture of lending. By decentralizing lending, we do not require banks or any other intermediaries for conducting a loan transaction. Decentralization means also that borrowers and lenders do not need to trust even ETHLend once the Smart Contract is deployed to the Ethereum network. These Smart Contracts provide a trustless and transparent lending environment, which is not available on todays FIAT lending market. Trustless means that no one can interfiere, stop or manipulate the loan once deployed. Transparent means that anyone can see the deployed transaction on blockchain ledger by using a blockexplorer. There is no equivalent power on found on centralized environment.
1.4.1	Trustless
There is no need to trust the counterparty. When the borrower places the loan request on ETHLend, the counterparty, ETHLend or any other party cannot manipulate, stop and prevent the loan request once the loan is depoyed. Instead of the need to trust the counterparty, decentralization removes the necessity to trust your provider and your counterparty. 
Removing the counterparty or third party risk is vital to avoid any unfair and unwanted behaviour. By using trustless environment, we are able to avoid risk that are associated with third parties. For example, we do not have to take into account if the peer to peer lending service provider is under cyberattack, incurs fraud or the service provider would end up into insolvency proceedings.
For example, who bears the risk if the peer to peer lending platform would get hacked and all your deposited assets are stolen? The service providers usually shift the risk on the users in the hard-to-read-and-understand terms and conditions. However, such policies are not necessary in decentralized lending since the assets are locked and controlled by Smart Contracts that are broadcasted on blockchain. Therefore, a hacker must hack all the thousands of servers to make any difference and spend great deal of ETH doing that.
1.4.2	Transparency
Transparency is subject to trustless environment. Ethereum network provides a ledger, which is open for inspection from transaction to transaction. This means that every transaction is recorded. Any transaction that is deployed on Ethereum blockchain could be explored though blockexplorers. Transparent ledger removes the trust that normally one would need to have when making a transaction between two banking institutions. In banking system, the sender has to trust the receiver and vice versa. Practically one needs a receipt of payment to confirm payment. However, such receipt is not protected by forgery.
Transparency brings more power to finance industry. Today when you make any sort of a transaction through the banking system, you do not have an access to the ledger. Therefore, you cannot check whether your counterparty has received the transaction. The current method of transactions creates friction and uncertainty.
When it comes to lending, timing is vital. Loan capital must move between borrowers and lenders as fast as possible in a global scale. Today, current banking system does not provide such tools for the lending market. Crypto-currency and blockchain technology fulfils this need.
Moreover, ETHLend provides decentralized lending possible in the crypto-world without being exposed to loss of loan capital. The transparency that blockchain ledger provides is vital for a lending system that works complete out of the banking system since public ledger makes trustless lending possible. The lender is always able to check whether the borrower received the loan and vice versa. No trust needed.
1.4.3	Democracy and Access to Finance
Democracy to lending market. Blockchain-based lending removes barriers between segregated lending markets. By using ETH and the Ethereum network, lenders and borrowers can arrange loan transactions from anywhere to anyone, address-to-address. The effect is that there is more liquidity available at markets that have been previously restricted or segregated. Moreover, by using this structure lenders and borrowers do not need banks to transfer the loan capital back and forth. Therefore, fractioned and divided global lending market becomes more democratic and accessible.
Global liquid pool on supply and demand. When the lending market becomes a whole instead of fractioned, there is more access to competition. Access to capital ensures that borrowers have more choices and the interest rate is lower due to increase in competition. For the lenders this means that there are more options to fund and to choose the risk from instead of relying on local lending market offerings.
Access to finance. Crypto-currencies do provide basic banking needs for the unbankable. We should always reminded ourselves that there is 2.5 billion people that do not have a decent access to the banking system. Since banks are the general source of finance, the unbankable do not have sufficient access to finance either.
This has yield high number of microfinance ventures. The issue with microfinance is that it does not represent what lending market should be. Instead of individuals providing liquidity for lenders of developing countries (intermediaries), ETHLend provides the full access to loan market globally without these intermediaries. It does not matter where the borrower or lender is located, all loans are secured by a collateral and fired up within few minutes.
Inequality shadows the global lending market. Today, central banks impose lending rates on interbank loans or on lending to the end consumer or the businesses. Different risk level and FIAT currency inflation creates loan markets that are not equal in comparison. For example, a real estate backed loan in Brazil might have an interest rate of 32 percent (inflation adjusted). On the other hand, similar loan in Europe might have an interest rate between 0.5-5 percent. This inequality is removed with decentralized lending.
1.4.4	Tokenization of Things
Tokenization unleashes the power of decentralization. Tokenization means that anything that represents value can be issued and represented on Ethereum-based ERC-20 compatible token. This means that instead of dealing the value itself, we can use the ERC-20 token that represent the value for our transaction. Tokens can theoretically represent any value such as company shares, real property, intellectual property, art or commodities. One of the first common example of tokenization is gold. DigixDAO issued tokens where one DigixDAO token represents 1 gram of gold. Therefore, when the token holder owns DigixDAO token, the token holders owns factually 1 gram of gold, which is located and audited somewhere in the world.
How do we know that the property is real? In case of DigixDAO for example, an audit takes place, which confirms that the gold reserve is true. Audit is just one example. There are other examples such as oracles or any sort of outsourced trust. In terms of adoption of tokenization, it does not require much that in near future all forms of assets could be represented as ERC-20 compatible tokens.
Graphics: House, Car, Shares, Commodities, Nuclear power plant, Wind Energy mill and picture of trade or something that would indicate chain…
Tokenization provides more opportunities on lending. When property is tokenized, the tokens could be traded or pledged against a loan. This means that there would be tokens at the loan market that have less volatility and are more suitable as a collateral.  In near future, we do not see any obstacles on having Apple or Facebook shares tokenized and pledged against a loan on ETHLend. Even further, one could tokenize his house that is under construction and pledge it to receive a loan from lenders all parts of the world. The global competition on lending market would provide the most competitive interest rate for the borrower.
1.4.5	Current and Future Use-Cases for Decentralized Lending
Decentralized crypto-currency lending is the new kid on the block. Lending address-to-address does have demand in today’s blockchain world. Theoretically, crypto-currency lending could be used for similar purposes as lending in the centralized economy. However, since address-to-address lending requires the need to secure the repayment of the loan, decentralised lending is in the stage of development.
First, there is no need for decentralization for lending ETH. Decentralization is needed when the parties do not know or trust each other for the repayment of the loan. In these situations, ETHLend provides a solution for securing loans by providing a Smart Contract which requires a collateral from the borrower. There are other means to provide trust between the parties such as reputation. However, requiring a collateral is sufficient here to establish neutral and equal lending market that is available globally for all.
Lending crypto-currencies is developing rapidly on the blockchain environment. However, the rapid development is because the field is modestly new. Moreover, decentralized lending is completely fresh area since the technology, innovation and market has not reached beyond the level that decentralized lending would have valid solution to provide decentralized lending without the risk of loss of capital. However, now we propose a solution that makes address-to-address lending possible without the fear of default.
Curiosity and trading crypto-currencies. Until this day, most of the borrowers do borrow for the sake of curiosity on decentralized lending market. The users want to know how the decentralized lending functions. Another current use-case is crypto-trading. Particular borrowers use decentralized lending to get hold on ETH. Once ETH is received, they trade the ETH for other crypto-currencies or ERC-20 tokens, which are increasing in value faster than ETH. When the increase bypasses the ETH value on borrow including the premium added with profit, the borrower exchanges the bought crypto-currency or ERC-20 token back to ETH and pays the loan back. In this scenario, the borrower used his rare token that he did not want to sell and gained more ETH by using his scarce ERC-20 token to get access to leveraged trading (loan based trading).
Current finance market consist of barriers. In FIAT environment, there might not be a lender that would accept ERC-20 tokens or ENS domains as a collateral for the loan. Secondly, even if the crypto-trader would obtain FIAT-based loan, he would need to wait to get the loan into his bank account and after receiving it, exchange it to ETH and reverse the action when repaying the loan back. Therefore, the borrower would pay interest on days that the borrower factually is not using the loan capital for the borrower’s needs. Moreover, the circumstances might occur today that if the bank is not welcoming crypto-traders, the traders might not factually have even access to finance for his crypto-lending ventures.
2.	Why Ethereum Network?
Ethereum Network provides decentralized ecosystem. Decentralized lending requires value that could be send and received, Smart Contracts to perform more complex transactions and additionally Ethereum is well known. Ethereum is the first widely known blockchain network that allows Smart Contracts. Ether (ETH), the native token of Ethereum has gained much popularity in the last couple of years. For users to adopt decentralized crypto-currency lending there should be a crypto-currency that is widely used. Secondly, the blockchain ledger should deal with more complex transactions than merely sending and receiving value. There should be the possibility to add, store data and perform complex requests and calls.
Moreover, the possibility to use and create digital tokens ensures that Ethereum network is the right landscape for ETHLend. However, Ethereum is not perfect. We will cover the issues ETHLend might occur on Ethereum network, yet it does have the fullest potential where ETHLend might grow for wider use.
2.1	Smart Contracts
Lending requires more than sending Ether. Decentralized lending requires a blockchain ledger that is able to run more complex transactions than the fundamental sending and receiving value. The core power of Ethereum is the adoption of Smart Contracts. This function provides the ability to use blockchain ledger extensively. Smart Contracts in general definition provides a solution to deploy commands on the blockchain network, which affect the way on how data is stored, represented or handled in the Ethereum blockchain network. This means that we can deploy code that executes but cannot be modified once deployed.
Graphics: Loan smart contract (creative)
Loan agreement as a Smart Contract. The basic function of a loan agreement is the storage of data. This data includes the information on the loan capital, premium (interest charged), days to loan and the parties of the loan agreement. By using the aforementioned information, we can perform a loan transaction between trusted persons. However, when we want to enable workable solution for lending between borrowers and lenders that do not know each other, we need more than the above data.
Collateral enables secured lending. Lending to a person that we do not trust or know beforehand, we would require something that would either: (i) indicate from the past record or the present reputation that the borrower shall repay the loan or (ii) we secure the loan with a pledged collateral. To secure a loan with a collateral, our Smart Contract should store the collateral until the borrower has repaid the loan and the premium. The solution represents the basic pawnshop functionality. Ethereum Smart Contracts are flexible enough to handle storing collaterals such as ERC-20 compatible tokens or ENS domains.
Since the collaterals and the crypto-currency used for lending is within the ecosystem of Ethereum, it was convienient for us to choose Ethereum for the ledger. Alternative ledger would have to communicate with Ethereum network, which would create more complex engineering, which would not benefit the users.
Track record for lending. Another important function that ETHLend needed was a way to handle reputation-based lending. If the borrower would need always ERC-20 tokens to place a loan request, lending would be limited to users that have “token wealth”. Therefore, we introduce that on each repaid loan, the borrower and the lender are rewarded by our native ERC-20 Token called, Credit Token or CRE. By creating a Smart Contract for Credit Token, the reputation system is painless. Moreover, by using the Ethereum-based ERC-20 compatible token we are still working within the decentralized ecosystem, instead of resorting to off-chain credit ratings and the old tarnished banking and credit system.
2.2	Ether
Popular crypto-currency. Ether (ETH), the Ethereum native token (consider also as crypto-currency), was another decisive factor when choosing the ledger. Ether is widely used for dapps, trading and is growing for merchant payments. We believe that Ethereum with the use of Smart Contract is growing popularity not just developers but amongst users of Bitcoin and other Altcoins.
To establish a decentralised lending application we needed a popular crypto-currency. Of course, Bitcoin was the one with largest market capitalization. Ether comes second. Since Ethereum has the power of Smart Contracts and we were working within the Ethereum ecosystem, it became clear that Ether would be our choice for the lending currency. Moreover, Ether is faster in transactions than Bitcoin. Using any other altcoin would have created the need for the discussion between blockchains, which might not be an ideal at the moment.
2.3	Tokenization
Tokenization of value is what fuels ETHLend. ERC-20 compatible tokens are used as a collateral to secure loans on ETHLend. When a token has value, the token can be pledged to secure the repayment of the loan. This practically means that the borrower promises to give up of the pledged token for the lender if the borrower does not pay the loan back. Pledging is quite common in the finance industry. Most commonly used collaterals are real property for mortgage or pledging shares of a listed stock company.
Tokenization is growing. Today there are few dozens of ERC20 tokens that have significant value and are traded in crypto-currency exchanges. Each week new token crowdsales are launched and there will be even more tokens that are open for trade. This effects that there would be more tokens that one could pledge for a loan at ETHLend.
Future of tokenization and lending. Today the tokens have many different representations. One of the interesting one is tokenization of commodities such as gold. At some point, it can be convenient to place a house or a new solar power plant as a token and trade the token or pledge the token to receive finance. Actually, tokenization is quite reachable today and the barriers lies within the formal requirements such as real property deed registrations and such. Therefore, even now one could issue ERC-20 compatible tokens that represents the shares of a company and agree on the shareholders agreement that the shares are represented on Ethereum-based ERC-20 compatible digital tokens. From that point, the share could be used as collateral for Ether loan for funding the company’s ventures or the shareholders’ needs.
Once the tokenization is widely adopted, the uses cases are beyond imagination. Borrower from Brazil could agree with the home seller that the borrower can place the house on ERC-20 token and pledge the house to obtain a loan to finance the purchase. Instead of resorting to Brazilian banks for mortgage, the borrower has full access to the global lending market. 
Moreover, infrastructure projects are another example. Contractors could first issue a crowdsale of ERC-20 compatible tokens and after the crowdsale, the contractors could have even more access to liquidity by pledging the tokens that are left from the crowdsale and get more funding for the project. The opportunities and the use-cases are only limited by imagination.
2.4	Paradox of Value: Smart Contract Deployment
Ethereum is not seamless. Ethereum has all the ingredients for developing decentralized Smart Contracts on-chain. However, deploying Smart Contract on Ethereum blockchain does not come without costs. Each time the borrower creates a loan agreement there will be exhaustion of small amount of gas. Besides the gas consumption, the deployment of the loan agreement would costs some small amount of ETH. Even though the consumed amount of ETH is currently small, the situation might change. When ETH price continues to surge, it will be more expensive to deploy the contract if the borrower is using funds that were shortly before the deployment converted from FIAT into ETH.
On the other hand, this is not a problem if the borrower lives in the crypto-currency economy. This might be the case for many within the next five years. It would mean that the user would get his income in ETH (or any other crypto-currency). In this case, the borrower do not need to bear the cost of rising ETH price. However, if there would be high amount of users from the FIAT economy, this would eventually mean that it would make more sense to borrow bigger amounts that resorting to microlending. This could raise the bar for access to finance, which worries us the most.
3.	Fully Decentralized On-Chain Solution for Lending Market
Decentralized lending. Ethereum provides the ecosystem for lending that is conducted on-chain. By decentralized lending we refer that all transactions are made on blockchain and all data that is associated with the loans are stored and running on the blockchain network. The solution provides safety, trust and transparency between the borrowers and the lenders.
Smart Contracts. Ethereum-based Smart Contracts provide the ecosystem for creating trustless functions between parties. By trustless we refer that we can eliminate the need to rely on third party services. All transactions are performed with the use of Smart Contracts. This means that when deployed, the loan agreement (the code) cannot be manipulated or compromised, even by ETHLend since the code is running on the blockchain, copying itself from hard-drive to hard-drive.
Smart Contracts for decentralized lending. Smart Contract are suitable for lending that does not happen on local or centralized services. In decentralized environment, there is need to secure or provide reputation based trust between the borrower and lender since we must trust that the loan is repaid back. Smart Contracts can handle complex transactions such as future payments, sending tokens, sending ENS domains and conducting all sorts of calculations. Moreover, Smart Contracts are capable to store and group data on blockchain which is important for the loan agreements since we need to store information on-chain regarding to the loan amount, premium, days to loan, collateral, the parties of the loan agreement.
Smart contracts are perfect for secured lending. In secured lending, we use a collateral such as an Ethereum-based ERC20 Token or ENS domain. Basic secured lending works in the following way:
Borrower creates a Smart Contract by creating a New Loan Request
 
Borrower places data on the Smart Contract, such as the loan amount, premium, which token is used for collateral, amount of tokens and the collateral token address
 Borrower sends the tokens to the Smart Contract
 Lender funds the loan by sending loan amount to the Smart Contract
a) Borrower repays the loan by sending loan amount back and the premium to the Smart Contract. Lender receives the loan amount and premium and borrower receives the tokens back from pledge; or
b) Borrower does not repay the loan on time, the tokens are transferred to the lender (who can sell the tokens on exchange)
Let us now review the full code of the Smart Contract
Smart Contracts provide the solution for the borrower and the lender to perform a secured loan without relying on third parties. Since Smart Contracts can store ERC-20 compatible tokens and ENS domains, the collateral is easily moved to in any direction. This might not be the case in real life. Moreover, since ERC-20 tokens can represent any value from centralized world, Smart Contracts would provide the possibility to control this value on blockchain. Theoretically, anything can be used as a collateral once tokenized, even a dog.
Grapchis here: Borrower creates smart contract, send token (for example 10 DigixDAO). Lock picture on the Smart Contract, lender send money.
Repayment picture: borrower pays the loan back and interest to the smart contract, lender receives these from the smart contract and the token collateral is unlocked and send back to the borrower.
Default scenario picture: Borrower does not pay, the tokens are transferred from the smart contract to lender. Lender goes to exchange and sells the tokens
3.1	Secured Lending by Pledging Ethereum-Based Digital Tokens
In this section, we will demonstrate how ETHLend DAPP works from the user experience perspective. We will go step-by-step walk-through on how to request a loan and to fund a loan. You will need to have Google Chrome and the MetaMask plugin installed. MetaMask is Google Chrome plugin to allow decentralized application, such as, ETHLend, to be run in the browser without downloading the full Ethereum node.
To download Google Chrome, please visit:
https://www.google.com/chrome
To download MetaMask, please visit:
https://metamask.io/
 
Click ‘GET CHROME PLUGIN’
 
Click Add to Chrome
 
Click Add extension
 
In the top right corner, you will see the icon of MetaMask
 
Click accept after reading and accepting the privacy policy
 
You will then create your MetaMask account here
 
After creating the account, you will be provided 12 words, which will be used to recover your account
 
You can see the details of your account and you can request a loan or fund a loan of ETH using ETHLend now
3.1.1	New Loan Request
In the upcoming sections, we are going to demonstrate two scenarios:
1.	Borrower repaying the loan and lender receiving his original principal plus interest
2.	Borrower not repaying the loan and lender receiving the tokens which borrower pledged as collateral
Before dive into that, we will introduce a few useful resources here:
Ether Scan: https://etherscan.io/ - You can check the details of your Ethereum account, such as balance of ETH and ERC-20 tokens
Token Factory: https://tokenfactory.surge.sh/ - Transfer token to another Ethereum account 
Coin Market Cap: https://coinmarketcap.com/ - Live prices of ETH and ERC-20 tokens. Useful for calculating the amount of collateral, tokens, needed to make an attractive borrowing request
Ether Delta: https://etherdelta.github.io/ - Exchange for trading tokens. For lenders to sell ERC-20 tokens and purchase ETH if they wish when the loan is defaulted
We will have three accounts - lender, borrower1 and borrower2.
 
We are going to use Basic Attention Token (BAT) as collateral. For more information about BAT, please visit https://basicattentiontoken.org/
 
To create a loan, first click New Loan Request
 
MetaMask should pop up, and after reviewing you would need to click accept to continue
 
The message ‘Done!’ will be displayed after the transaction goes through
 
If you go back to All Loan Requests and shuffle the loans, you will see that a new loan is created. The red dot indicates that it is your address.
3.1.2	The Loan Contract
 
After that you clicking into the contract just created, please enter the details of the contract
 
Then click Set Data and MetaMask will pop up again for you to confirm
 
The message ‘Done!’ will be displayed when the transaction is completed.
3.1.3	Sending Digital Tokens to the Smart Contract
 
We will see the status of the contract is changed to ‘waiting for tokens’
 
You will need to transfer the amount token set in the contract to the address given
 
You can visit Token Factory to transfer tokens to the address, first click ‘interact with token contract’ (Alternatively, you can go to your Ethereum wallet and sent the tokens to the loan Smart Contract).
 
You will be asked for the token address
 
You can find out the contract address information on Etherscan
 
You can also check your balance here to ensure you have sufficient amount of tokens
 
You can transfer the token to the address given in ETHLend here
 
Once transfer is completed, you can go to ETHLend to check on the status and you will be asked to confirm on MetaMask
 
After that is competed, you will see the status of your loan has changed to waiting for lender
3.1.4	Funding the Loan
 
This is an example we are going to switch to a lender account. In practice, the following steps will be conducted by a lender
 
After selecting the loan, lender can click fund this loan request
 
Confirm via MetaMask
 
Borrower has successfully received his loan
3.1.5	Paying the Loan Back
 
As the borrower, you can choose the loan you would like to repay
 
Click return token and confirm via MetaMask
 
You can see in the balance borrower has returned to lender the loan amount plus ineterst
 
 
Borrower has received back his token pledged earlier for collateral
3.1.6	Default Scenario
 
We are going to demonstrate a default scenario next
 
We follow identical steps except for the number of days we are putting 0 day to simulate the loan defaulting
 
After the loan is defaulted, lender can see the message has changed to get token
 
Lender can claim the token and we can confirm on token factory
3.2	On-Demand Lending
Learning curve for the borrower. Currently the ETHLend’s decentralized application provides solely that the borrower can create the loan request. This means that the borrower must have a basic understanding on lending. The borrower must place such data as the premium, amount of tokens for pledge and the token Smart Contract address. It might be difficult for a first time borrower to evaluate the value of the ERC-20 token (even if the token is traded on the exchange) and the amount of premium which borrower is willing to accept to pay. If the borrower sets too low premium or overvalues the collateral, the loan might not be attractive for the lenders. This would mean that the loan would not be funded.
Liquidity provided by the lender. Alternative for the borrower’s loan request, ETHLend shall adopt a Smart Contract where the lender may place the loan offer for the borrowers. The lender creates a Loan Smart Contract. The lender inserts data on how much liquidity the lender in total is willing to lend, on what premium, and which tokens the lender is willing to accept for collateral. After the lenders Loan Smart Contract is deployed, anyone may lend from lender simply by sending ERC-20 tokens to the Smart Contract.
Graphics: Different borrowers sending tokens and arrows pointing (to send) to the smart contract.Lender sends ETH to different borrowers
On-demand lending. The lender provides as above state liquidity for any borrower with the pre-set conditions. This means that instead of participating in multiple loan requests, the lender can handle all loans form one Smart Contract. When a borrower returns the loan the, the token is released and sent back to the borrower and the lender Loan Smart Contract has more liquidity for lending. Factually, we have here an on-going lending institution that the lender has created. The lender may at any point close his loan offer. This would mean that no new loans are granted and the borrowed capital will close on due.
Flexibility and less learning curve for the borrower. On-demand lending provides flexibility for the lender. The lender does not need to fund single small loans, instead the lender can place the terms for the loan capital and anyone can borrow merely by sending the accepted ERC-20 token to the loan agreement. For the borrower, on-demand lending means less necessary knowledge on lending. The learning curve is transferred from borrower to the lender, which means that the borrower does not have to evaluate the value of the collateral or evaluate the attractiveness of the premium. Of course, if the borrower is not satisfied of the price of the liquidity that the lenders are providing, the borrower may always place a loan request with its own terms.
3.3	Secured Lending by Pledging Ethereum Name Service Domains (ENS)
New name service created a gold rush. Ethereum Name Service Domains (ENS) are domains that are used in the Ethereum ecosystem. ENS domains provides a way to use a name for the long Ethereum address. For example if one would like to send ETH to Jim, the person would need to write long Ethereum address. By using ENS domain one could just sent the ETH to an ENS domain such as jim.eth (which is owned by Jim) and the ETH will be transferred to Jim’s Ethereum address.
ENS domains are auctioned against ETH. ENS domains are not actually bought but the ownerships is guaranteed by willingness to lock ETH for at least a year. When the auction is ended, the new owner of the domain is able to create subdomains, lease, loan or sell the domain. This means that the domain can be sold further to a third party or pledged for a loan. Today, as of 22 June 2017, there are over 75 000 registered domain names. If ENS domains would be ICANN gTLD domain, it would be the 48th largest between .solutions and .news.
ENS domains have significant value. ENS domains bear at least two forms of value. The first form of value is the ETH that is locked in the domain. For every single .eth domain there is an auction. Today there are 341 643 auctions started. The winning bid of the auction means that the second highest bid ETH amount is locked down on the ENS domain Smart Contract. There are currently 148 312 ETH locked down on ENS domains which results in 50 361 713 USD. Moreover, there are currently almost a billion dollars’ worth of ETH deposited in bids. This means that there are plenty of interest in ENS domains.
Unlocking the benefits of ENS domains. Since ENS domains hold ETH that cannot be used, pledging domains might be perfect option for those that would want to use some of the Locked ETH. The reason practically lies in the fact that unused funds could be placed for use to attract more funds or other use. The highest locked down amount on ENS domain is darkmarket.eth (20 103.10 ETH, equivalent to 6 826 329 USD) and followed by openmarket.eth (10 054.76 ETH, equivalent to 3 414 255 USD). Locking the funds means that these funds could not be used or moved. However, the locked down funds could be used for other purposes such as bidding on other ENS domains or using the funds on other investments instead of letting the funds lie in the ENS domain Smart Contract.
Even though it might not seem idealistic, when .eth domain that holds 0.01 Ether value would be up to pledge. However, ENS domains do have other value than the locked up Ether. Domain names are scarce. This means that even though an ENS Domain might hold as low as 0.01 Ether locked, it might have other value as well. For example, flourist.eth (which is not taken yet) might go for 0.01 Ether. However, the ENS domain might have future value or value for the industry or topic that the domain is related to.
For example, one might create a sophisticated Smart Contract on Ethereum that would track the source of flowers, thus giving an edge to florists’ who adopts the chain. In this sphere, flourist.eth might become quite popular even though the locked value is 0.01 ETH. This would mean that low bid domains is usable for pledge when valued carefully.
ENS domains as a collateral. Domains are great for collateral for two reasons. First, the amount of collateral is the same. When pledging ERC-20 tokens, on can pledge more than one token. When pledging ENS domains, you will have a single value because you cannot pledge more than one domain for the same loan (at this point). This makes things easier. 
Secondly, ENS domains can be pledged against the lockdown value to cover the loan amount and the premium. This means that the amount of ETH does not change during the pledge. Therefore, unlike pledging Ethereum-based digital tokens, the borrower could create a loan request that is guaranteed 100% by the ENS domain lockdown without the risk of volatility that ERC-20 tokens might bear.
On the other hand, one must notion that the locked down ETH is released when the domain period ends, usually within a year. However, this does not stop the lender to sell the domain on an auction just as a digital token or hold the domain itself if it is scarce and wait the ecosystem to develop further.
ENS domain collateral Smart Contract. The ENS domain by design is transferrable. Transferability provides that the ENS domains are capable for collateral.  When a borrower on ETHLend pledges an ENS domain for a loan, the borrower needs to send the ENS domain to the Smart Contract. The Smart Contract will hold the ENS domain in case the borrower does not repay the loan back. In case of default, the lender is able to claim and transfer the ENS domain to his address for further realization.
Consequently, the ENS domain pledge follows the same roadmap as the tokens pledge. The main distinction is that on token pledge token smart contract address is used for interaction and data. On the other hand, in ENS domain pledge we are using the hash key provided by the ENS registry for transferring the ENS domain to the Smart Contract. The use of Smart Contract additionally guarantees that the address where the received funds are allocated does not change during the pledge, providing security and transparency for the borrower.
Graphics: Arrow, Borrower Sending ENS domain (news.eth) to Smart Contract and a picture of a lock. Second arrow lending sending ETH to borrower
The rapid growth of ENS domains will lock down vast amount of ETH in to the ENS Smart Contracts. This means that at some point there shall be ETH locked that could be worth of billions of USD. Therefore, ENS domain pledge provides a convenient way to “unlock” these funds for use by obtaining funding and pledging the ENS domain. Eventually ENS domains could end up being even more suitable alternative for a collateral for a loan. ENS domains do not have the volatility that some of the ERC-20 tokens might have. Of course, the volatility with the tokens might disappear eventually and would follow such volatility that is seen on stock market or currency exchange. However, since tokens do differ this not the case for all tokens.
3.4	Unsecured Lending
Unsecured loan brings wider use for borrowers. Secured loans which requires a collateral such as ERC-20 tokens or ENS domains do raise the bar for access to finance. However, secured loans provides the starting point for decentralized lending. Without using collateral, it would be challenging for borrowers and lenders who do not know each other to trust. Therefore, secured loans is truly a trustless solution for decentralized lending. Although, eventually to achieve a burst in crypto-lending, unsecured lending should be adopted. However, current crypto-lending options do not live in the decentralized environment. Moreover, an option that would implement real-wold credit scores would not be in our mind a sufficient solution, merely an escape route back to the centralized environment.
Decentralized solutions for unsecured lending. When the borrower repays the loans, the borrower (and lender) will receive 10 CRE (against 1 ETH loan). This CRE is used as any other ERC-20 token collateral. By using CRE, the borrower can spare other ERC-20 Tokens and eventually by volume would use solely CRE for securing loans on ETHLend. In one way, CRE would provide a way to avoid placing a collateral. However, using CRE based on reputation, requires repayment of loans. This means that we would still need a solution for first time borrowers. Of course, unsecured lending would add more risk of default, but this risk is compensated with higher interest rate (provided by the market) to satisfy lenders who are willing to bare the risk of unsecured lending.
Next we will introduce couple of functions that could be added to ETHLend to cover unsecured lending. These solutions presented are not yet implemented to the decentralized application. On a general basis, we believe that unsecured lending shall be part of ETHLend accordingly with the development roadmap. However, the technical solution that we shall implement the functions is yet to be determined due to vast phase of evolvement of the Ethereum ecosystems. Following solutions would be added to ETHLend to provide unsecured loans.
3.4.1	uPort
Self-sovereignty as reputation. uPort provides a self-sovereign identity system. uPort identity system provides the possibility to create identity based lending. User could register credentials through uPort. This would mean that if the loan is not repaid, the address or the identity would be banned from ETHLend and the data would be transferred to uPort. The default of the loan would eventually mean that the sovereignty of the uPort user would be affected in other Ethereum-based applications as well. This would be a risk and loss for the user that has built his reputation on uPort.
On the other hand, uPort would not eliminate the risk of default completely. It reduces the risk same way as ETHLend’s native Credit Tokens are reducing. The distinctive here is that uPort would provide reputation from other applications. However, nothing stops using Credit Tokens on other Ethereum-based applications. In fact, Credit Token represents the repayments of loan, therefore the most vital trust that is known in the financial economy.
3.4.2	Address Data
Ethereum addresses provide much useful data. Addresses that are used as a base for transactions of ETH are all open to exploration on blockexplorers. Since these addresses are open for review, they do hold interesting information that could have lot of valuable use-cases. One of the use case could be connected with unsecured lending.
Valuable data for lending. Ethereum addresses provide data that could be used to assess the risk level of the loan request. To analyse the risk of the loan we would need some background information from the borrower. Just as a bank might evaluate the transaction or income history of the borrower, a similar approach can be done by exploring the Ethereum blockchain. The data that would be important to decide whether the borrower has a stable address is:
•	Age of the address (time from the first transaction)
•	Total number of transaction
•	To how many addresses ETH is sent
•	From how many addresses received ETH
•	What is the average monthly ETH balance
•	Does the address hold tokens
•	Does the address create or interact with Smart Contracts
•	Is the address name registered at blockexplorer services or any such
Picture of address on Etherscan
Stability and indication of willingness to pay. The idea behind the address data is to capture information that would indicate that the borrower uses the address regularly. For example, an address that does not have any of the above stated data, would be more risky to lend 1 ETH to a borrower compared to lending to an address that had its first transaction two years ago, has over 2 000 transactions from the first one, has sent to over 100 different addresses and received from over 100 different addresses with a monthly balance of 1 ETH and has previously held tokens.
Ways to control malicious use. Unsecured loans provides that if the borrower would default, the loan capital would be lost. The fact that there is “nothing to loose” except the Ethereum address reputation sounds tempting for misuses. The common tools for discouraging such behaviour would be banning the defaulted address or even harsher solution would be locking the address down (taking control) by using private keys (encrypted) when an unsecured loan takes place.
However, we should mind that these two solutions would ban the address but not the user. Therefore, using address data is a good way to widen the use of unsecured loans from Credit Token System and uPort, but it does not guarantee always the full repayment of the loan. Moreover, address data might be a good starting point for new borrowers to gain reputation with small loans on ETHLend for gaining Credit Tokens. When the borrower has enough CRE, the borrower could start securing the loans with CRE. Thus, moving from unsecured to secured lending market.
Rewarding rehabilitation on default. One innovation that the ETHLend team had in mind was using Credit Tokens as a reward for successful rehabilitation. Let us assume that the borrower did not pay the loan and defaulted. The borrower is added to the blacklist and his address is confiscated. If the borrower would at some point repay the full amount including the premium, the borrower would be rewarded with motivational amount of CRE. This would provide that the lender would receive the loan capital and premium, and the borrower can continue to borrow.
Factually, the solution would mean that there would be slightly more CRE minted on the market. Eventually, the solution would still benefit the token holders, the borrowers and the lenders since the default risk would be shared. Instead of letting the lender bear the default risk, the default risk would be shared amongst all. Therefore, it would not be in borrowers or anyone else’s interest to create bad debt.
Time will provide the end-solution for unsecured decentralized loans. Even though we provided few examples on unsecured decentralized lending without the affiliation and resorting to traditional banking system or credit rating systems, the developing ecosystem of Ethereum and blockchain technology will provide means to solve the issue. Now the most representing way to borrow for a first time borrower (without a collateral)s would be with the use of uPort and slightly moving towards secured lending with CRE. Consequently, using any centralized solution such as identification verification, credit score would merely stall the fascinating findings of Ethereum and blockchain technology itself.
3.5	Introducing Credit Token (CRE) as the Reputation System
Native token to boost and create trust on value. By its function Token crowdsale in its purest form is based on believe and trust that the venture behind the token sale will provide future value on the token that is sold. Tokenization itself has many potential uses in decentralized environment such as the Ethereum blockchain and our decentralized application, ETHLend. The use of tokens in decentralized lending needs to benefit the borrower, the lender and the token holders. Actually, these three parties need each other to create more value for the minted token.
Revealing Credit Token. ETHLend introduces Credit Token, simply as CRE. The token holds and represents value of the decentralized lending market. First, the value of lending market depends on successful and repaid loans, which indicates the health of the lending market. On the other hand, lending market with increasing default rate would otherwise indicate of unworkable lending market. The value would eventually affect the demand and supply of loans. This representation of value is now placed on ERC-20 token, just as any other value such as gold or attention can be placed. Credit tokens has two important functions. First, it derives supply and demand on ETHLend by rewarding repayments of the loan and lending itself. Secondly, CRE functions as reputation on past performance on ETHLend. This reputation is transferrable to third party Ethereum applications.
3.5.1	Rewarding Liquidity and Repayments
Borrower and lender are rewarded. The main idea of CRE is to reward successful and healthy lending. Successful lending means that loans are repaid and the lender gets the loan capital and the premium taking the risk to lend. There are two reason why users should be rewarded. First, rewarding the borrower for repayment incentivises repayment and reduces the default rate even if the collateral is sufficient to cover the loan capital and the premium. Secondly, rewarding the lenders is equally important since the lenders are providing liquidity to the market.
Picture of CRE symbol
On a successful repayment, the borrower receives 10 CRE and the lenders receives 10 CRE for a loan amount that equals to 1 ETH. This means that in case the loan amount is 10 ETH, the both parties equally receive 100 CRE. On the other hand, if the loan amount is 0.1 ETH, the parties receive 1 CRE. Even though, borrower and lender have different roles, it is important to reward the parties equally since without one, the loan does not take place.
Rewarding CRE would not affect severely the token holders position. On Token Sale, there will be 1 000 000 000 (one billion) CRE available for purchase. Approximately 1 ETH would amount to 5 000 CRE depending on the purchase time and amount. There shall be 300 000 000 CRE reserved for the development team.
Eventually since 1 ETH repayments of the loan mints 20 CRE, it has a minor effect on the total supply of 1 300 000 000 CRE. However, the added value by the repayments and eventually trust on lending market, is more beneficial compared to the fact that more CRE is added to the total supply. When loans are repaid, there is more trust on the market. As there is more trust, there is more value since trust is the base of CRE. Therefore, repayments and liquidity on ETHLend should indicate as value added and overcomes the minting effect on total supply. Consequently, small minting with value added considered as a factor that drives vast speculation away and provides less volatility for the token for further development of the market value of CRE.
3.5.2	Credit Token as Reputation
Reputation on CRE. As CRE is granted on repayments of loans, CRE is an easy way to establish reputation management on ETHLend. Reputation system is a convenient way to establish trust between the borrowers and the lenders. Trust means that the lender is willing to provide loan eve if the loan is not secured. CRE is a solution to (i) secure a loan and (ii) to get access to unsecured loans.
Securing a loan with CRE. Since CRE is ERC-20 compatible token, it can be used to secure a loan on ETHLend. Practically it would mean that on each repaid loan the borrower receives CRE, which could be pledged as a collateral for the loan. Therefore, the borrower can spare other ERC-20 tokens and use CRE instead as eventually the borrower will have sufficient amount of CRE. Let us review a case-example:
	The borrower has repaid the following loans on ETHLend:
1.	0.1 ETH Loan with BAT Collateral = Receives 1 CRE
2.	0.5 ETH Loan with GOLEM Collateral = Receives 5 CRE
3.	1 ETH Loan with REP Collateral = Receives 10 CRE
4.	5 ETH Loan with DigixDAO Collateral = Receives 50 CRE
5.	10 ETH Loan with Status.im Collateral = Receives 100 CRE
After these loans, the borrower has 166 CRE that can be used as a collateral instead of BAT, GOLEM, REP, DigixDAO and Status.im ERC-20 tokens. The question on how much the borrower could receive ETH for loan would naturally depend on the CRE value at the moment of the loan request.
By using CRE instead of other ERC-20 tokens, the borrower is factually using his reputation on past performance to secure the loans on ETHLend.
CRE for unsecured loans. When borrower repays a loan and receives CRE, this CRE balance is also indicated on the next loan request in the field of Borrower’s Reputation. The idea behind the reputation is to indicate that the borrower has successful past performance and the past performance was credited on ETHLend.
3.5.3	Prevention of Misuse
Repayments back and forth. Since repayments of the loan creates new CRE for the lender and the borrower, it might become tempting for misusing ETHLLend for creating CRE. One might create false borrower’s and lender’s account and loan back and forth for the purpose of creating more CRE. First, creating a Loan Smart Contract exhaust small amount of gas and a mining fee, which reduces the motivation on such behaviour. Secondly, such behaviour would be reduced by ip-address recording on the Ethereum blockchain and placing time limits and using other tools to prevent such behaviour. The focus should be on value. Unwanted behaviour should be much more labour intense compared to the motivation of misuse.
3.6	User Experience on ETHLend
3.6.1	Accessibility
Providing wide usage. Currently ETHLend DAPP is accessed with Google Chrome or Mozilla Firefox browser together with MetaMask plugin. To provide full coverage, the ETHLend DAPP shall be developed further for implementing mobile usage, parity and MyEtherWallet. The ETHLend team considers that the DAPP should be easily available with less learning curve as possible.
3.6.2	User Interface
Focus on user experience. ETHLend team considers that the user interface is the game breaker for adopting Ethereum-based applications for a wider audience. Eventually, our goal is to eliminate the learning curve as much as possible on blockchain applications. Moreover, we are bound to follow any innovations and improvements when it comes to user experience on decentralized applications. It is surely true that decentralization and blockchain-based Smart Contracts do create challenges for user experience and might require prior knowledge on blockchain and Ethereum basics. However, we believe that these challenges could be overcome merely by pushing hard development on the user experience.
3.6.3	Performance
Choices between on-chain and off-chain. Today ETHLend is a fully decentralized application running on Ethereum blockchain network. This means that all functionalities and data are on blockchain (on-chain). Once a wise man said that one should not force everything on the chain. This saying means now more than ever since the Ethereum blockchain network is growing on data to such the extend that it takes few days to load the full chain. Even though some functions could be left off-chain, we are trying to avoid these functions. ETHLend team’s aim is to create decentralized solutions by pushing innovation further instead of falling back to centralized solutions. However, we should not be always naive and we should not live in a vacuum, instead ETHLend should follow the directions that the mainstream blockchain development.
In regards of performance of the DAPP, we are aiming to provide ways to get as much as possible unnecessary functions from Smart Contract to develop the best technical experience that can be achieved on Ethereum network.
3.6.4	Translations
Languages are part of access. Translations provides wider accessibility to use ETHLend. Moreover, since we have a lending market at hand, accessibility would mean here access to finance as well, the very core and fundamental principle of funding, that not everyone is granted in today’s world.
Since the development of ETHLend, the team has recruited language skilled individuals who are part of the Ethereum community or starting with the community that were willing to assist the ETHLend project. We received lot of interest and eventually were able to receive translations of the ETHLend site and the DAPP, totalling into multiple languages. The languages that were included in the translations were Spanish, French, Chinese, Korean, Japanese, German, Russian, Portuguese, Dutch, Italian, Turkish, Norwegian, Danish, Finnish, Malay, Arabic, Filipino and Lithuanian. There translations are implemented during our upcoming user experience upgrade.
3.7	Technical Roadmap
We consider ETHLend as a long term project. However, to make most of us, concrete deadlines are necessary. Therefore, we shall introduce the following roadmap for technical implementations:
1.	Implementing ENS Domain Collateral  26.6.2017
2.	Implementing CRE for Repayments 26.6.217
3.	Token Crowdsale  Late August / Early September 2017
4.	User Experience Upgrade  September 2017
5.	On-Demand Lending  October 2017
6.	uPort Integration  October 2017
7.	Second User Experience Upgrade  January 2018
8.	Lending Bitcoin and Litecoin  March 2018
9.	KYC on-board implementation  May 2018
10.	Lending Other Altcoins  August 2018

3.8	Map of ETHLend
Below is provided the ecosphere of decentralized lending on ETHLend:
Mind map of Collaterals (heading: Secured Lending) (ERC20 Tokens, CRE, ENS domains) + (heading: Unsecured Lending) grey uPort
Mind map of Currencies (heading: Currencies) (ETH) + (heading: Upcoming Currencies) grey Bitcoin, Litecoin, Other Altcoins
4.	Legal Evaluation of the Loan agreement on ETHLend
Crypto-lending without borders. Traditionally lending is provided locally due to the fact that lending involves due diligence on the borrower. This process requires the access to local credit score or rating system. Moreover, the legislation on lending depends by jurisdiction to jurisdiction and there are distinctions between the common law and civil law jurisprudence. Even though lending has been local, there has been always international finance that has not been restricted by jurisdictions. Mainly the question is about complying legislation to ensure the loans on ETHLend are binding.
Crypto-currency is defined differently through jurisdiction to jurisdiction. Since crypto-currency is relatively new to governments, they have not been too keen on regulating or defining the legal status on crypto-currencies. Moreover, we must acknowledge that the definition given in other fields of law such as tax law does not finally settle or give analogy to use the definition in other fields of law. What we can certainly define is what crypto-currency is not. Crypto-currencies are not currencies in the form that governments’ of different jurisdictions define, since crypto-currencies are not issued by state authority. Therefore, in most sensible definition crypto-currencies are left out to contractual agreements (when not regulated).
4.1	Contractual Relationship
Something for something. Where crypto-currencies are not regulated, they are contractual agreements between the parties. This would mean that the agreement between the borrower and the lender for borrowing ETH would be conducted on the basis on contract law. The next questions is which contract law would apply since there are distinctions between common law contract law and civil law contract law, not to mention the jurisdictional differences.
Freedom to contract. The basic principle in any contract law despite the jurisdictional differences is the freedom to contract. This means that anyone can agree to lend to anyone. Since the principle is the main rule, there are some exceptions such as lending to minors, which we need to take into account. Decentralized environment grants access to anyone since that is the point of decentralization. However, decentralization does not mean that we would have to act irresponsibly.
Terms and conditions. A loan transaction would be in place when there is a consent to repay the loan between the sender of ETH and the receiver of ETH. This would represent the simplest loan contract in the decentralized environment that is based on the agreement between the borrower and the lender. However, to make the loan transaction a good agreement between the borrower and the lender, this simple form of contracting is not sufficient.
Even thought, the loan is on Smart Contract and on a trustless environment, the users are living under governed jurisdictions. This means that the lending agreement should be valid, even though one might not have the ability to enforce it (if the counterparty is not known). To provide a sufficient loan agreement, ETHLend shall implement all legal functions of the loan to simple terms and conditions. These terms includes the loan period, premium, the collateral, the lender, the borrower, governing law and dispute resolution. Therefore, the parties do not have to deal with the juridical questions to participate in the lending market.
4.2	Collateral
New form of collaterals. In most jurisdiction collaterals or known as pledge are governed to establish the legal standing of a pledge against third parties. This has been important through time since enforcing a collateral is seen as an exception on the right to ownership. Moreover, most of the rules on collateral from jurisdiction to jurisdiction apply on real property, thus pledging non real property such as a phone or jewellery has soften regulation, if any. There is not much jurisprudential literacy on pledging ERC-20 tokens and ENS domains. In fact, ETHLend is the first who uses ERC-20 tokens and ENS domains for securing loans.
Acknowledgement and transfer of collateral. Non real property collateral do need to comply certain actions to establish valid collateral and thus enable the transfer of ownership in case of default. These rules do apply in most jurisdictions and the jurisdiction where ETHLend would be governed (see. governance). First, to be a valid collateral, the collateral must be transferred to the lender. The same principle is seen in pawnshops where the borrowers leave items to the pawnshop. The possession is important to acknowledge third parties that the item is held as a collateral.
The property could be held by a third party as well. However, Smart Contracts are interesting since by using Smart Contract, ETHLend does not hold the collateral. Instead, the collateral is running on the blockchain which is controlled by the Smart Contract. The aim behind the possession is to inform third parties (extra partes) that the item is pledged. This aim is by design complied on Ethereum blockchain. All transactions can be inspected by the blockexplorer. Therefore, when ERC20 token or ENS domain is pledged on ETHLend, the collateral is moved to the Smart Contract and locked until the loan is repaid. This information is accessible to anyone, anywhere with an internet connection.
4.3	Know Your Customer (KYC)
ETHLend does not lend or hold assets. ETHLend is a decentralized application running on Ethereum blockchain network. This means that ETHLend does not store any data on centralized servers. All data is running on Ethereum blockchain, peer-to-peer. ETHLend does not control any assets between the lenders and the borrowers. First, ERC-20 tokens and ENS domains are not defined as asset in the traditional meaning. ERC-20 tokens and ENS domains are representation of value. Secondly, all transactions are conducted on Smart Contracts. This means that when the borrower places a loan request, the borrower creates the Smart Contract.
Therefore, the borrower creates the environment for the specific loan. When the Smart Contract is created, the data is broadcasted to Ethereum network and is not stored on any servers locally. ETHLend could be seen as a tool set loans and browse loan on Ethereum network.
KYC regulation applies on money lending between borrowers and lenders. When FIAT money is lend, the lender must conduct known your customer compliance on certain thresholds by verifying the customer, the origins of the funds and other verifications. The thresholds do vary from jurisdiction to jurisdiction but remain similar in principles. However, uncertainty lies within lending ETH since ETH is not a currency by goverments’ definition. Therefore, whether lending ETH is subject to KYC is an unsettled question.
KYC on-boarding. Whether or not lending ETH is subject to KYC, ETHLend endorses the KYC policies between ETH loans due to the fact that regulation might follow sooner or later since decentralized environment does not occur in a vacuum. For this reason according to our roadmap, ETHLend will implement integrations for assisting the parties to comply with KYC regulations. The aim is to provide KYC when deemed to be needed and provide it as easy as possible.
Currently, KYC can be solved through messaging and interaction between the lender and borrower. However, current solutions would be off-chain. The ETHLend team is working on to provide a KYC solution that would not spill over to off-chain. The easiest way to provide KYC without the need to spill the application to off-chain would require the borrower to insert a link to the material that would comply with KYC. This material would include identification, proof of address and origin of funds. Even decentralized storage could be used to achieve the storage of KYC data.
5.	ETHLend
Decentralized governance. Since lending on ETHLend is decentralized, it would be in line to add decentralization as much as possible to the governance of the DAPP and the project itself. When we created the ETHLend DAPP, we wanted to provide more democracy for lending market by decentralized lending. Democracy can be provided to the ETHLend development and governance as well to provide more value for the token holders and people who are willing to contribute on ETHLend development.
5.1	The Team
Introducing our team:
Stani Kulechov, Founder of ETHLend. stani@ETHLend.io
Jordan Lazaro Gustave, Head of Management. jordan@ETHLend.io
Martin Wichmann, Head of Token Sale, martin@ETHLend.io
Sergej Stein, Financial Advisor, sergej@ETHLend.io
Scott Malsbury, Head of Communications, scott@ETHLend.io
Jin Park, Head of Marketing, jin@ETHLend.io
Slack Wizard
Vlogger
Rowan, Graphics & Visualization
5.2	Governance
ETHLend follows decentralized governance. ETHLend introduces 3-tier governance for decentralized lending application. The decentralized application (DAPP) shall be governed by decentralized governance model similar to DAO. Each token holder can propose changes in provided procedure for the DAPP. Each proposition is voted within the CRE token holders. Regular changes would require majority of voters present and core changes would require 2/3 of the voters present. The aim is to create a democratic system to control on what direction the DAPP development will take place.
The third tier shall be the layer that owns the DAPP. This layer shall be Swiss Foundation or Swiss LLC, which would provide the surroundings for ETHLend and connects the decentralized environment to centralized world. Such connection might not be ideal when we are aiming for complete decentralization. However, such a layer is vital for protecting our users for any liabilities that might occur for the liabilities in respect to different jurisdictions. Swiss Foundation or Swiss LLC would offer limited liability on risk of liabilities. This veil is vital since the regulation on decentralized applications, crypto-currencies and token crowdsale is still living under uncertainty due to lack of regulation.
Roadmap to consensus. The 3-tier governance needs a roadmap for implementation. Theoretically, the 3-tier governance could be used from the beginning. However, since the DAPP needs much development that requires flexibility and agile performance, implementing decentralized democracy would stall the development on ETHLend in the most vital stage. Therefore, we are implementing the 3-tier democracy within 2 years from the token sale. By this time, we would have a DAPP that has been driven through the test period.
5.3	Roadmap
Road to decentralization. ETHLend introduces the following roadmap adopting changes, improvements and governance to ETHLend:
1.	ETHLend DAPP v. 1.0  May 2017
2.	White Paper on ETHLend  June 2017
3.	Token Sale Smart Contract Testing  July 2017
4.	Token Sale  August-September 2017
5.	Swiss Foundation or Swiss LLC  October 2017
6.	CRE Trading on Exchanges  November 2017
7.	Relocation to Zug, Switzerland  January 2018
8.	New Recruits on the ETHLend Team  February 2018
9.	Opening Proposition Forum for Token Holders  May 2018
10.	Creating and Testing Democracy DAO  November 2018
11.	Voting on Proposition Deployed  May 2019
12.	Vesting for CRE Ends  August-September 2019

6.	Token Sale
Providing value and finance. To provide a workable Reputation system on ETHLend that holds value, ETHLend is commencing its own native Credit Token (CRE) crowdsale. By commencing the token sale, there are more participants on ETHLend that provide additional value for CRE. Theoretically, CRE will hold the value on lending market since small amount of additional CRE is minted on successful loans. Therefore, the value of CRE is affected by the current value of lending market, the default rate to be precise.
Principles of the tokens sale. ETHLend aims to provide a token sale that is democratic, decentralized, secure and fair. This also applies to the vesting model and to the future governance on ETHLend. To comply with democracy, anyone can buy CRE on Token Sale period. The Token Sale shall be provided in a decentralized manner by using an Ethereum-based Smart Contract which would provide more security due to the decentralized nature. Moreover, all the token purchases will be gone through manually before distribution to avoid any unwanted behaviour.
Endorsing early purchase. The price on CRE is determined in different tiers based on timing and quantity of the purchase. We want to endorse token buyers that are amongst the first by reducing the token sale price. However, to retain democracy on token sale, the reduced price is restricted to certain amount of tokens. This would avoid the situation where few persons would buy within a certain time limit all the available tokens, and on discount. Next, we will introduce our preliminary structure on Token Sale. The structure is subject to change and final terms and conditions are released early before the Token Sale launch.
6.1	Token Distribution
Small development fund, large circulation. Total of 1 000 000 000 (one billion) CRE is released on sale. Additionally, 300 000 000 CRE is held for development fund to incentivise the development team and to recruit more talent to ETHLend. There will be no follow-up sale on CRE. The token are available for purchase for the period of 30 days from the token sale launch.
6.2	Purchase Price
Multitier token sale. The purchase price for CRE is subject to time and quantity. ETHLend proposes the following tiers for the token sale:
1.	First 1 000 000 CRE priced at 15 000 CRE per 1 ETH
2.	1 000 000 CRE to 10 000 000 CRE priced at 12 500 CRE per 1 ETH
3.	10 000 000 CRE to 50 000 000 CRE priced at 10 000 CRE per 1 ETH
4.	50 000 000 CRE to 100 000 000 CRE priced at  7 500 CRE per 1 ETH
5.	100 000 000 CRE to 1 000 000 000 CRE priced at 5 000 CRE per 1 ETH
6.3	Burning Tokens
All tokens that are not sold during the token sale, shall be burned. This means that these tokens cannot be used and the total supply of the tokens is reduced and the value of sold tokens increases. The maximum amount of tokens for sale is one billion. This limit cannot be exceeded.
6.4	Vesting
Ensuring continuation. All tokens distributed to the core team are subject to vesting. Vesting model ensures more value and security for the token contributors. Vesting provides more loyalty form the core team towards the project and ensures that CRE is not subject to market manipulation and provides stable market development for the CRE token.
ETHLend introduces the following Vesting model for the core team:
1.	80% of CRE is locked once Token Sale distribution has ended
2.	60% of CRE is locked after 6 months from Token Sale distribution
3.	40% of CRE is locked after 12 months from Token Sale distribution
4.	20% of CRE is locked after 18 months from Token Sale distribution
5.	0% of CRE is locked after 24 months from Token Sale distribution
The vesting model is active for 24 months in total. All tokens that are distributed to new team members from the development fund after the CRE token sale follows the vesting model on a pro-rata basis (will join the vesting model from the next mark).
6.5	Minting
Value minting. ETHLend will not mine any CRE to finance or to enlarge the total supply of CRE. Instead, the only time when new CRE is produced is the repayments of the loans on ETHLend. The repayment of the loans indicates the value of the lending market. Therefore, any new CRE that is minted will actually provide more value for the CRE. Each loan repayment that equals to 1 ETH would produce 10 CRE to the borrower and 10 CRE to the lender. Rewarding the borrower and the lender would incentivise lending on ETHLend.
6.6	Security
Security on focus. CRE token sale is performed on decentralized Ethereum Smart Contract. The token sale contract shall be tested on Kovan testnet and the Ethereum mainnet. There will be a manual due diligence of each token sale transaction that has taken place to make sure there is no misuse of the token sale.
Storing the funds. All raised funds are stored in divided multi-signature Ethereum wallets. Therefore, the access to funds would require multiple people to sign. Diversification of wallets provides extra-safety in case private key would be compromised. A spending account with less than 5% of the funds can be held on a single-signature account.
6.7	Funds Allocation
Most of the funds are allocated to further development of the DAPP. ETHLend provides the following funds allocation based on needs for application that ETHLend is developing:
Pie chart
•	35% on core development
•	20% on user experience development
•	20% on management of ETHLend Foundation or LLC
•	15% on promotions
•	10% on unexpected costs
Funds allocation is subject to change for providing flexibility. ETHLend will use best practices on funds allocation and its own discretion.
7.	Further Updates
Further updates on CRE Token Sale and DAPP updates are published on http://about.ETHLend.io and in our mailing list. The Token Sale launch will be announced on our mailing list and published on http://about.ETHLend.io/blog
For questions, join our slack:
https://join.slack.com/ETHLend/shared_invite/MjAzMTM0MzEyNzA3LTE0OTg0MDk0NDItOGY0MTlkMTlmZA

