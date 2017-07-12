# ETHLend.io White Paper - Democratizing Lending

26 June 2017

<p>Abstract: ETHLend.io introduces decentralized lending on Ethereum network by using ERC-20 compatible tokens or Ethereum Name Service (ENS) domains as a collateral. ETHLend solves the problem on reducing the loss of loan capital on default. On healthy loan relationships the loan is paid back. However, the pseudo-anonymous nature of Ethereum blockchain network opens the possibility to avoid repayment of the loan since the lender might not have all the necessary details of the borrower to enforce the debt in the borrower's jurisdiction. Moreover, enforcement in a decentralized environment, where the parties can be from any part of the world, might not be efficient. ETHLend provides decentralized solutions to avoid loss of capital and to make one true global lending market available.</p>

<p>Copyright 2017 ETHLend.io</p>

<p>Without explicit permission, anyone has the right to use, reproduce or distribute any material in this white paper for non-commercial purposes and educational use, provided that the original source and the applicable copyright notice are cited.</p>

DISCLAIMER: This White Paper is inteded for distribution solely on information purposes. ETHLend.io does not guarantee the accuracy of the conclusions and statements reached in this white paper. Moreover, this white paper is provided "as is" with no representations and warranties, express or implied, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, title or noninfringement; (ii) that the contents of this white paper are free from error or suitable for any purpose; and (iii) that such contents will not infringe third-party rights. All warranties are expressly disclaimed. ETHLend.io and its affiliates expressly disclaim all liability for and damages of any kind (direct or indirect, including loss of profit) arising out of the use, reference to, or reliance on any information contained in this white paper, even if advised of the possibility of such damages. Under no circumstances ETHLend or its affiliates will be liable to any person, entity, partners, partner’s customer or end-users for any consequential, incidental, direct, indirect, special or punitive damages, including without limitation damages for lost profits, revenues, lost business or loss of use of products whether or not ETHLend advised in this white paper or any of the content contained herein, that such damages will or may occur, and whether such damages are claimed based on breach of contract, negligence, strict liability in tort or any other legal or equitable theory. No action regardless of form, arising out of this white paper may be brought against ETHLend.</p>
 
**Table of Contents**

- [ETHLend.io White Paper - Democratizing Lending](#)
- [1.	Background](#)
	- [1.1	About the White Paper](#)
	- [1.2	Lack of True Global Lending Market](#)
	- [1.3	Peer to Peer Lending and Cryptocurrency](#)
	- [1.4	Benefits of Decentralized Lending](#)
		- [1.4.1	Trustless](#trustless)
		- [1.4.2	Transparency](#)
		- [1.4.3	Democracy and Access to Finance](#)
		- [1.4.4	Tokenization of Things](#)
		- [1.4.5	Current and Future Use-Cases for Decentralized Lending](#)
- [2.	Why Ethereum Network?](#)
	- [2.1	Smart Contracts](#)
	- [2.2	Ether](#)
	- [2.3	Tokenization](#)
	- [2.4	Paradox of Value: Smart Contract Deployment](#)
- [3.	Fully Decentralized On-Chain Solution for Lending Market](#)
	- [3.1	Secured Lending by Pledging Ethereum-Based Digital Tokens](#)
		- [3.1.1	New Loan Request](#)
		- [3.1.2	The Loan Contract](#)
		- [3.1.3	Sending Digital Tokens to the Smart Contract](#)
		- [3.1.4	Funding the Loan](#)
		- [3.1.5	Paying the Loan Back](#)
		- [3.1.6	Default Scenario](#)
	- [3.2	On-Demand Lending](#)
	- [3.3	Secured Lending by Pledging Ethereum Name Service Domains (ENS)](#)
	- [3.4.1	Unsecured Lending](#)
		- [3.4.1	Decentralized Credit Rating with Credit Token (CRE)](#)
		- [3.4.2	Self-sovereignty](#)
	- [3.5	User Experience on ETHLend](#)
		- [3.5.1	Accessibility](#)
		- [3.5.2	User Interface](#)
		- [3.5.3	Performance](#)
		- [3.5.4	Translations](#)
		- [3.6	Technical Roadmap](#)
	- [3.7	Map of ETHLend](#)
- [4.	Legal Evaluation of the Loan agreement on ETHLend](#)
	- [4.1	Contractual Relationship](#)
	- [4.2	Collateral](#)
	- [4.3	Know Your Customer (KYC)](#)
- [5.	ETHLend](#)
	- [5.1	The Team](#)
	- [5.2	Governance](#)
	- [5.3	Roadmap](#)
- [6.	Introducing LEND Token and the Token Sale](#)
	- [6.1	Profit Sharing](#)
	- [6.2	Excemption on Borrower's Fees](#)
	- [6.3	Token Distribution](#)
	- [6.4	Purchase Price](#)
	- [6.5	Burning Tokens](#)
	- [6.6	Vesting](#)
	- [6.7	Security](#)
	- [6.7	Funds Allocation](#)
- [7.	Further Updates](#)
 
 <h1>1.	Background</h1>

<p>Pioneers in the fintech industry. We want to develop something important and to break the process-heavy and unfair lending market we all know. We want to make lending available on global scale. Instead of relying on local banks and lenders, we believe that borrower should have the possibility to obtain a loan from anywhere in the world. We believe that Canadian borrower could obtain a loan from Sweden, China, Brazil, Japan or Germany and vice versa.</p>

<p>Why global lending market is important? When the lending market is not bound by borders and jurisdictions, true competition can happen and more liquidity become available for the lending market. This means that the same amount of liquidity is available, for example, in China as in any country in Europe or Africa. The effect is revolutionary. Interest rate differences between countries and regions will disappear since there is more liquidity and competition.</p>

<p>Less control for the banks. Banks lend money that is deposited by account holders when banks need liquidity. This liquidity is lent to the market. Practically it means that banks charge 5-12% interest on loans and compensate you 0-1% for holding your assets at the bank. Since the rise of crypto-currency, you can become your own banking institution. With ETHLend, you become your own lending institution. You decide whom you lend to, on which interest rate securely or insecurely. All of this is available thanks to blockchain technology, on which ETHLend relies on.</p>

<h2>1.1	About the White Paper</h2>

<p>This white paper is an overview on ETHLend, a decentralized lending application (DAPP) running on Ethereum Network. Besides the DAPP, this white paper covers the ideology of ETHLend, the team behind the innovation and the upcoming token sale for contributing to ETHLend.

<p>Readability on focus. Since the popular adaption on Ethereum-based applications and interest on blockchain economy, we aimed to write this white paper to be understandable without wide knowledge or experience on technology associated with Ethereum. We tried to present the functions of the DAPP as much as possible in textual form and pictures. Moreover, when we present code, we explain it sufficiently enough to understand the function behind the code.

<p>This white paper was compiled together with persistent effort. ETHLend team wanted to produce a coherent, understandable and plausible concept out to the public. We want to make sure that anyone associated with or contributing to ETHLend does understand our vision, who we are, how the DAPP works and how the token sale takes place. We hope that our white paper inspires you for new ideas and innovations on blockchain technology.

<h2>1.2	Lack of True Global Lending Market</h2>

<p>There is no access to true global lending market. This is about to change. Currently lending market is controlled by governmental monetary policies, which affect the competition on lending market. Moreover, politics casts a dark shadow on the lending market. Therefore, banks are controlled on how they loan and on what price.</p>

<p>Blockchain provides global access to transactions. Blockchain makes it possible to send transactions uninterrupted and uncompromised globally. By using the Ethereum blockchain technology, anyone can send to anywhere a transaction of value, Ether (ETH). ETH is the native token of Ethereum, which is used as compensation for sending transaction on the Ethereum network. Thanks to Ethereum Smart Contracts complexe and sophisticated transaction can take place in a secure way</p>

<p>Fixing the lending market. Today the inflation-adjusted interest rate in different countries varies based on the available liquidity. In high liquidity market, Europe, interest rates are between 0.5-5 percent, in Russia 12-15 percent, in India 12 percent and in Brazil 32 percent. This shows a clear inequality in the way acces to the lending market is distributed. We believe that this inequality between the borrowers should be flattened.</p>

<p>Before (left side) After (right side). Pictures with world map. On left world map different sizes of interest rate on diagram followed by percent (%) sign. On the right side these different sizes of diagrams are all in the same level (flattened) to indicate global competition on interest rates (should be lower than average on left side).</p>

<p>Inequality has many reasons. Indeed higher interest rates on some countries are a product of high risk on default. However, we believe that if there would be more liquidity on these high interest rate markets, there would be more pressure on the interest rates. Moreover, using collaterals such as we are presenting on this white paper would provide the ratio to lend to these markets.</p>

<p>The crypto-currency economy provides the environment to democratize the lending market. First, crypto-currency is not effected by FIAT-based currency inflation. Therefore, borrowers are treated equally in positions since they are all borrowing ETH. This means that no government monetary policy or economic change in FIAT-based country affects directly to crypto-currency lending. Secondly, the lending market is open for all lenders and borrowers. It results in lending, that is not restricted by borders, jurisdictions or even by the access to banking system.</p>

<p>Risk derived from different regions and lending markets. Since the borrowers are pledging Ethereum-based ERC-20 compatible digital tokens (ERC-20 Tokens) or Ethereum Name Service domains (ENS domains), the loans are secured and could be equally treated. Therefore, we do not need to set the borrowers in unequal position by conducting subjective assessment on the borrower. Instead, we can objectively assess the risk level on the collateral that the borrower has provided even the need to know any backgrounds of the borrower. The borrower can use self-assessment of the collateral before placing the loan request by picking the price of the ERC-20 token from exchange.</p>

<p>After the borrower has a price at hand, the volatility is calculated to make sure that the collateral is sufficient by end of the loan period. Volatility is calculated typically in 3-month-period, 6-month-period or 12-month-period. Therefore, even though the borrower is located in high interest rate region, decentralized lending can bring new liquidity to that regional lending market. For example, a Chinese borrower might be restricted by the capital provided by Chinese lenders and banks. With decentralized lending and the Ethereum Blockchain Network, the Chinese borrower could attract lenders from other parts of the world. Since the collateral is ERC-20 token or ENS domain, the lender has less risk of losing the loan capital.</p>

<p>Tokenization of assets opens the door for true global liquidity. Asset tokenisation means that an ERC-20 token can represent assets such as gold, company shares or property. Tokenization would result that a borrower in Canada could place a property that the borrower is about to purchase in to an ERC-20 token. Then, the borrower could pledge the token on ETHLend and request funding not solely from Canadian lenders, but globally from any lender from any part of the world. This is a game changer in the financial industry.</p>

<h2>1.3	Peer to Peer Lending and Cryptocurrency</h2>

<p>Risk of default as a barrier in decentralised crypto-currency lending. There are no obstacles on lending crypto-currency as such. Any crypto-currency could be lend to anyone anywhere, and it would be a simple transaction. Then again, how do we know that the borrower will repay the loan? In FIAT economy, if you do not pay a loan back, your credit score or rating declines and legal consequenses may follow. This means that you might not get another loan from the market. However, in decentralized blockchain environment, securing the repayment of the loan needs more creativity in working solely on-chain.</p>

<p>Securing the repayment of decentralised loans. As transactions in Ethereum network are conducted by address-to-address traffic, so is the lending. Therefore, it would be impossible to know whether the borrower that the lender has sent Ether would pay the loan back in a situation where the lender and the borrower do not know each other. Since we are working in a fully decentralized environment, the solution should be on-chain as well.</p>

<p>Represented value as a collateral for borrowing. Contrary to what might occur, Ethereum-based ERC-20 tokens are perfect to use as a collateral. First, all popular Ethereum-based ERC-20 tokens are traded on exchange. Therefore, we do not have to roll the dices to form a price on most common ERC-20 tokens. Secondly, since we have a price, we usually have the price history as well. This means that we can calculate the volatility of the ERC-20 token and take the volatility into account when we are pledging the tokens to attract lenders.</p>

<p>Moreover, Ethereum-based ERC-20 tokens are easily transferrable between Ethereum Wallets and Smart Contracts. Smart Contracts iself can represent legally binding agreement (an offer and acceptance of offer), and the contractual statute can be agreed upon on the terms and conditions. Lastly, digital tokens are flexible. You can tokenize anything that has value. Due to this flexibility, assets such as real property, company shares and commodities can be placed on a token and pledged for a loan. The aforementioned function could revolutionize lending and trading on all assets. Even assets or value that was previously hard to value and trade, would be now be available for liquidity.</p>

<p>Example, we want to launch a rocket into the moon and we need to finance this venture. We could tokenize the rocket, all parts, rocket launcher, the company behind the venture to be represented as ERC-20 token called ROCK. Next, to finance the project we can pledge the tokens on decentralized lending platform such as ETHLend. Now anyone can participate in the funding of the rocket venture. The same is applicable on existing infrastructure projects such as nuclear power plants, solar power plants or privately held factories.</p>

<h2>1.4	Benefits of Decentralized Lending</h2>

<p>Decentralization provides more security and trust by design. Decentralization is a method to organise anything in a way that does not require trust on third parties. The trust is eliminated by executing code that does not require central government, management or central servers.</p>

<p>Decentralization changes dramatically the architecture of lending. By decentralizing lending, we do not require banks or any other intermediaries for conducting a loan transaction. Decentralization means also that borrowers and lenders do not need to trust even ETHLend once the Smart Contract is deployed to the Ethereum network. These Smart Contracts provide a trustless and transparent lending environment, which is not available on todays FIAT lending market. Trustless means that no one can interfiere, stop or manipulate the loan once deployed. Transparent means that anyone can see the deployed transaction on blockchain ledger by using a blockexplorer. There is no equivalent power on found on centralized environment.</p>

<h3>### 1.4.1 Trustless</h3>

<p>There is no need to trust the counterparty. When the borrower places the loan request on ETHLend, the counterparty, ETHLend or any other party cannot manipulate, stop and prevent the loan request once the loan is depoyed. Instead of the need to trust the counterparty, decentralization removes the necessity to trust your provider and your counterparty.</p>

<p>Removing the counterparty or third party risk is vital to avoid any unfair and unwanted behaviour. By using trustless environment, we are able to avoid risk that are associated with third parties. For example, we do not have to take into account if the peer to peer lending service provider is under cyberattack, incurs fraud or the service provider would end up into insolvency proceedings.</p>

<p>For example, who bears the risk if the peer to peer lending platform would get hacked and all your deposited assets are stolen? The service providers usually shift the risk on the users in the hard-to-read-and-understand terms and conditions. However, such policies are not necessary in decentralized lending since the assets are locked and controlled by Smart Contracts that are broadcasted on blockchain. Therefore, a hacker must hack all the thousands of servers to make any difference and spend great deal of ETH doing that.</p>

<h3>1.4.2	Transparency</h3>

<p>Transparency is subject to trustless environment. Ethereum network provides a ledger, which is open for inspection from transaction to transaction. This means that every transaction is recorded. Any transaction that is deployed on Ethereum blockchain could be explored though blockexplorers. Transparent ledger removes the trust that normally one would need to have when making a transaction between two banking institutions. In banking system, the sender has to trust the receiver and vice versa. Practically one needs a receipt of payment to confirm payment. However, such receipt is not protected against forgery.</p>

<p>Transparency brings more power to finance industry. Today when you make any sort of a transaction through the banking system, you do not have an access to the ledger. Therefore, you cannot check whether your counterparty has received the transaction. The current method of transactions creates friction and uncertainty.</p>

<p>When it comes to lending, timing is vital. Loan capital must move between borrowers and lenders as fast as possible in a global scale. Today, current banking system does not provide such tools for the lending market. Crypto-currency and blockchain technology fulfil this need.</p>

<p>Moreover, ETHLend provides decentralized lending possible in the crypto-world without being exposed to loss of loan capital. The transparency that blockchain ledger provides is vital for a lending system that works complete out of the banking system since public ledger makes trustless lending possible. The lender is always able to check whether the borrower received the loan and vice versa. No trust needed.</p>

<h3>1.4.3	Democracy and Access to Finance</h3>

<p>Democracy to lending market. Blockchain-based lending removes barriers between segregated lending markets. By using ETH and the Ethereum network, lenders and borrowers can arrange loan transactions from anywhere to anyone, address-to-address. The effect is that there is more liquidity available at markets that have been previously restricted or segregated. Moreover, by using this structure lenders and borrowers do not need banks to transfer the loan capital back and forth. Therefore, fractioned and divided global lending market becomes more democratic and accessible.</p>

<p>Global liquid pool on supply and demand. When the lending market becomes a whole instead of fractioned, there is more access to competition. Access to capital ensures that borrowers have more choices and the interest rate is lower due to increase in competition. For the lenders it results that there are more options to fund and to choose the risk from instead of relying on local lending market offerings.</p>

<p>Access to finance. Crypto-currencies do provide basic banking needs for the unbanked. We should always reminded ourselves that there is 2.5 billion people that do not have a decent access to the banking system. Since banks are the general source of finance, the unbanked do not have sufficient access to finance either.</p>

<p>This has yield high number of microfinance ventures. The issue with microfinance is that it does not represent what lending market should be. Instead of individuals providing liquidity for lenders of developing countries (intermediaries), ETHLend provides the full access to loan market globally without these intermediaries. It does not matter where the borrower or lender is located, all loans are secured by a collateral and fired up within few minutes.</p>

<p>Inequality shadows the global lending market. Today, central banks impose lending rates on interbank loans or on lending to the end consumer or the businesses. Different risk level and FIAT currency inflation creates loan markets that are not equal in comparison. For example, a real estate backed loan in Brazil might have an interest rate of 32 percent (inflation adjusted). On the other hand, similar loan in Europe might have an interest rate between 0.5-5 percent. This inequality is removed with decentralized lending.</p>

<h3>1.4.4	Tokenization of Things</h3>

<p>Tokenization unleashes the power of decentralization. Tokenization means that anything that represents value can be issued and represented on Ethereum-based ERC-20 compatible token. This means that instead of dealing the value itself, we can use the ERC-20 token that represent the value for our transaction. Tokens can theoretically represent any value such as company shares, real property, intellectual property, art or commodities. One of the first common example of tokenization is gold. DigixDAO issued tokens where one DigixDAO token represents 1 gram of gold. Therefore, when the token holder owns DigixDAO token, the token holders owns factually 1 gram of gold, which is located and audited somewhere in the world.</p>

<p>How do we know that the property is real? In case of DigixDAO for example, an audit takes place, which confirms that the gold reserve is true. Audit is just one example. There are other examples such as oracles or any sort of outsourced trust. In terms of adoption of tokenization, it does not require much that in near future all forms of assets could be represented as ERC-20 compatible tokens.</p>

<p>Tokenization provides more opportunities on lending. When property is tokenized, the tokens could be traded or pledged against a loan. This means that there would be tokens at the loan market that have less volatility and are more suitable as a collateral.  In near future, we do not see any obstacles on having Apple or Facebook shares tokenized and pledged against a loan on ETHLend. Even further, one could tokenize his house that is under construction and pledge it to receive a loan from lenders all parts of the world. The global competition on lending market would provide the most competitive interest rate for the borrower.</p>

<h3>1.4.5	Current and Future Use-Cases for Decentralized Lending</h3>

<p>Decentralized crypto-currency lending is the new kid on the block. Lending address-to-address does have demand in today’s blockchain world. Theoretically, crypto-currency lending could be used for similar purposes as lending in the centralized economy. However, since address-to-address lending requires the need to secure the repayment of the loan, decentralised lending is in the stage of development.</p>

<p>First, there is no need for decentralization for lending ETH. Decentralization is needed when the parties do not know or trust each other for the repayment of the loan. In these situations, ETHLend provides a solution for securing loans by providing a Smart Contract which requires a collateral from the borrower. There are other means to provide trust between the parties such as reputation. However, requiring a collateral is sufficient here to establish neutral and equal lending market that is available globally for all.</p>

<p>Lending crypto-currencies is developing rapidly on the blockchain environment. However, the rapid development is ongoing because the field is relatively new. Moreover, decentralized lending is completely fresh area since the technology, innovation and the market have not reached beyond the level that decentralized lending would have valid solution to provide decentralized lending without the risk of loss of capital. However, now we propose a solution that makes address-to-address lending possible without the fear of default.</p>

<p>Curiosity and trading crypto-currencies. Until this day, most of the borrowers do borrow for the sake of curiosity on decentralized lending market. The users want to know how the decentralized lending functions. Another current use-case is crypto-trading. Particular borrowers use decentralized lending to get hold on ETH. Once ETH is received, they trade the ETH for other crypto-currencies or ERC-20 tokens, which are increasing in value faster than ETH. When the increase bypasses the ETH value on borrow including the premium added with profit, the borrower exchanges the bought crypto-currency or ERC-20 token back to ETH and pays the loan back. In this scenario, the borrower used his rare token that he did not want to sell and gained more ETH by using his scarce ERC-20 token to get access to leveraged trading (loan based trading).</p>

<p>Current finance market consist of barriers. In FIAT environment, there might not be a lender that would accept ERC-20 tokens or ENS domains as a collateral for the loan. Secondly, even if the crypto-trader would obtain FIAT-based loan, he would need to wait to get the loan into his bank account and after receiving it, exchange it to ETH and reverse the action when repaying the loan back. Therefore, the borrower would pay interest on days that the borrower factually is not using the loan capital for the borrower’s needs. Moreover, the circumstances might occur today that if the bank is not welcoming crypto-traders, the traders might not factually have even access to finance for his crypto-lending ventures.</p>

<h1>2.	Why Ethereum Network?</h1>

<p>Ethereum Network provides decentralized ecosystem. Decentralized lending requires value that could be send and received, Smart Contracts to perform more complex transactions and additionally Ethereum is well known. Ethereum is the first widely known blockchain network that allows Smart Contracts. Ether (ETH), the native token of Ethereum has gained much popularity in the last couple of years. For users to adopt decentralized crypto-currency lending there should be a crypto-currency that is widely used. Secondly, the blockchain ledger should deal with more complex transactions than merely sending and receiving value. There should be the possibility to add, store data and perform complex requests and calls.</p>

<p>Moreover, the possibility to use and create digital tokens ensures that Ethereum network is the right landscape for ETHLend. However, Ethereum is not perfect. We will cover the issues ETHLend might occur on Ethereum network, yet it does have the fullest potential where ETHLend might grow for wider use.</p>

<h2>2.1	Smart Contracts</h2>

<p>Lending requires more than sending Ether. Decentralized lending requires a blockchain ledger that is able to run more complex transactions than the fundamental sending and receiving value. The core power of Ethereum is the adoption of Smart Contracts. This function provides the ability to use blockchain ledger extensively. Smart Contracts in general definition provides a solution to deploy commands on the blockchain network, which affect the way on how data is stored, represented or handled in the Ethereum blockchain network. This means that we can deploy code that executes but cannot be modified once deployed.</p>

<p>Loan agreement as a Smart Contract. The basic function of a loan agreement is the storage of data. This data includes the information on the loan capital, premium (interest charged), days to loan and the parties of the loan agreement. By using the aforementioned information, we can perform a loan transaction between trusted persons. However, when we want to enable workable solution for lending between borrowers and lenders that do not know each other, we need more than the data above.</p>

<p>Collateral enables secured lending. Lending to a person that we do not trust or know beforehand, we would require something that would either: (i) indicate from the past record or the present reputation that the borrower shall repay the loan or (ii) we secure the loan with a pledged collateral. To secure a loan with a collateral, our Smart Contract should store the collateral until the borrower has repaid the loan and the premium. The solution represents the basic pawnshop functionality. Ethereum Smart Contracts are flexible enough to handle storing collaterals such as ERC-20 compatible tokens or ENS domains.</p>

<p>Since the collaterals and the crypto-currency used for lending is within the ecosystem of Ethereum, it was convenient for us to choose Ethereum for the ledger. Alternative ledger would have to communicate with Ethereum network, which would create more complex engineering, which would not benefit the users.</p>

<p>Track record for lending. Another important function that ETHLend needed was a way to handle reputation-based lending. If the borrower would need always ERC-20 tokens to place a loan request, lending would be limited to users that have “token wealth”. Therefore, we introduce that on each repaid loan, the borrower is rewarded by our native ERC-20 Token called, Credit Token or CRE. By creating a Smart Contract for Credit Token, the reputation system is painless. Moreover, by using the Ethereum-based ERC-20 compatible token we are still working within the decentralized ecosystem, instead of resorting to off-chain credit ratings and the old tarnished banking and credit system. Therefore, by using ERC-20 token we factually create a decentralized credit rating system.</p>

<h2>2.2	Ether</h2>

<p>Popular crypto-currency. Ether (ETH), the Ethereum native token (consider also as crypto-currency), was another decisive factor when choosing the ledger. Ether is widely used for dapps, trading and is growing for merchant payments. We believe that Ethereum with the use of Smart Contract is growing popularity not just developers but amongst users of Bitcoin and other Altcoins.</p>

<p>To establish a decentralised lending application we needed a popular crypto-currency. Of course, Bitcoin was the one with largest market capitalization. Ether comes second. Since Ethereum has the power of Smart Contracts and we were working within the Ethereum ecosystem, it became clear that Ether would be our choice for the lending currency. Moreover, Ether is faster in transactions than Bitcoin. Using any other altcoin would have created the need for the discussion between blockchains, which might not be an ideal at the moment.</p>

<h2>2.3	Tokenization</h2>

<p>Tokenization of value is what fuels ETHLend. ERC-20 compatible tokens are used as a collateral to secure loans on ETHLend. When a token has value, the token can be pledged to secure the repayment of the loan. This practically means that the borrower promises to give up of the pledged token for the lender if the borrower does not pay the loan back. Pledging is quite common in the finance industry. Most commonly used collaterals are real property for mortgage or pledging shares of a listed stock company.</p>

<p>Tokenization is growing. Today there are few dozens of ERC20 tokens that have significant value and are traded in crypto-currency exchanges. Each week new token crowdsales are launched and there will be even more tokens that are open for trade. This effects that there would be more tokens that one could pledge for a loan at ETHLend.</p>

<p>Future of tokenization and lending. Today the tokens have many different representations. One of the interesting one is tokenization of commodities such as gold. At some point, it can be convenient to place a house or a new solar power plant as a token and trade the token or pledge the token to receive finance. Actually, tokenization is quite reachable today and the barriers lies within the formal requirements such as real property deed registrations and such. Therefore, even now one could issue ERC-20 compatible tokens that represents the shares of a company and agree on the shareholders agreement that the shares are represented on Ethereum-based ERC-20 compatible digital tokens. From that point, the share could be used as collateral for Ether loan for funding the company’s ventures or the shareholders’ needs.</p>

<p>Once the tokenization is widely adopted, the uses cases are beyond imagination. Borrower from Brazil could agree with the home seller that the borrower can place the house on ERC-20 token and pledge the house to obtain a loan to finance the purchase. Instead of resorting to Brazilian banks for mortgage, the borrower has full access to the global lending market.</p>

<p>Moreover, infrastructure projects are another example. Contractors could first issue a crowdsale of ERC-20 compatible tokens and after the crowdsale, the contractors could have even more access to liquidity by pledging the tokens that are left from the crowdsale and get more funding for the project. The opportunities and the use-cases are only limited by imagination.</p>

<h2>2.4	Paradox of Value: Smart Contract Deployment</h2>

<p>Ethereum is not seamless. Ethereum has all the ingredients for developing decentralized Smart Contracts on-chain. However, deploying Smart Contract on Ethereum blockchain does not come without costs. Each time the borrower creates a loan agreement there will be exhaustion of small amount of gas. Besides the gas consumption, the deployment of the loan agreement would costs some small amount of ETH. Even though the consumed amount of ETH is currently small, the situation might change. When ETH price continues to surge, it will be more expensive to deploy the contract if the borrower is using funds that were shortly before the deployment converted from FIAT into ETH.</p>

<p>On the other hand, this is not a problem if the borrower lives in the crypto-currency economy. This might be the case for many within the next five years. It would mean that the user would get his income in ETH (or any other crypto-currency). In this case, the borrower do not need to bear the cost of rising ETH price. However, if there would be high amount of users from the FIAT economy, this would eventually mean that it would make more sense to borrow bigger amounts that resorting to microlending. This could raise the bar for access to finance, which worries us the most.</p>

<h1>3.	Fully Decentralized On-Chain Solution for Lending Market</h1>

<p>Decentralized lending. Ethereum provides the ecosystem for lending that is conducted on-chain. By decentralized lending we refer that all transactions are made on blockchain and all data that is associated with the loans are stored and running on the blockchain network. The solution provides safety, trust and transparency between the borrowers and the lenders.</p>

<p>Smart Contracts. Ethereum-based Smart Contracts provide the ecosystem for creating trustless functions between parties. By trustless we refer that we can eliminate the need to rely on third party services. All transactions are performed with the use of Smart Contracts. This means that when deployed, the loan agreement (the code) cannot be manipulated or compromised, even by ETHLend since the code is running on the blockchain, copying itself from hard-drive to hard-drive.</p>

<p>Smart Contracts for decentralized lending. Smart Contract are suitable for lending that does not happen on local or centralized services. In decentralized environment, there is need to secure or provide reputation based trust between the borrower and lender since we must trust that the loan is repaid back. Smart Contracts can handle complex transactions such as future payments, sending tokens, sending ENS domains and conducting all sorts of calculations. Moreover, Smart Contracts are capable to store and group data on blockchain which is important for the loan agreements since we need to store information on-chain regarding to the loan amount, premium, days to loan, collateral, the parties of the loan agreement.</p>

<p>Smart contracts are perfect for secured lending. In secured lending, we use a collateral such as an Ethereum-based ERC20 Token or ENS domain. Basic secured lending Smart Contract works in the following way:</p>

<p>Borrower creates a Smart Contract by creating a New Loan Request. </p>

     function createNewLendingRequest()payable byAnyone returns(address out){

          // 2 - create new LR
          // will be in state 'WaitingForData'
          out = new LendingRequest(mainAddress,msg.sender,whereToSendFee);

          // 3 - add to list
          uint currentCount = lrsCountPerUser[msg.sender];
          lrsPerUser[msg.sender][currentCount] = out;
          lrsCountPerUser[msg.sender]++;

          lrs[totalLrCount] = out;
          totalLrCount++;
     }

<p>Borrower places data on the Smart Contract, such as the loan amount, premium, which token is used for collateral, amount of tokens and the collateral token address</p>

     State public currentState = State.WaitingForData;

     // This must be set by borrower:
     address public borrower = 0x0;
     uint public wanted_wei = 0;
     uint public token_amount = 0;
     uint public premium_wei = 0;
     string public token_name = "";
     string public token_infolink = "";
     address public token_smartcontract_address = 0x0;
     uint public days_to_lend = 0;

<p>Borrower sends the tokens to the Smart Contract</p>

     function checkTokens()byLedgerMainOrBorrower onlyInState(State.WaitingForTokens){
          ERC20Token token = ERC20Token(token_smartcontract_address);

          uint tokenBalance = token.balanceOf(this);
          if(tokenBalance >= token_amount){
               // we are ready to search someone 
               // to fund the loan
               currentState = State.WaitingForLender;
          }
     }

<p>Lender funds the loan by sending loan amount to the Smart Contract</p>

     function waitingForLender()payable onlyInState(State.WaitingForLender){
          if(msg.value<safeAdd(wanted_wei,lenderFeeAmount)){
               throw;
          }

          // send platform fee first
          if(!whereToSendFee.call.gas(200000).value(lenderFeeAmount)()){
               throw;
          }

          // if you sent this -> you are the lender
          lender = msg.sender;     

          // ETH is sent to borrower in full
          // Tokens are kept inside of this contract
          if(!borrower.call.gas(200000).value(wanted_wei)()){
               throw;
          }
          currentState = State.WaitingForPayback;

          start = now;
     }

<p>a) Borrower repays the loan by sending loan amount back and the premium to the Smart Contract. Lender receives the loan amount and premium and borrower receives the tokens back from pledge; or</p>

     // if time hasn't passed yet - Borrower can return loan back
     // and get his tokens back
     // 
     // anyone can call this (not only the borrower)
     function waitingForPayback()payable onlyInState(State.WaitingForPayback){
          if(msg.value<safeAdd(wanted_wei,premium_wei)){
               throw;
          }

          // ETH is sent back to lender in full
          // with premium
          if(!lender.call.gas(200000).value(msg.value)()){
               throw;
          }

          // tokens are released back to borrower
          ERC20Token token = ERC20Token(token_smartcontract_address);
          uint tokenBalance = token.balanceOf(this);
          token.transfer(borrower,tokenBalance);

          // finished
          currentState = State.Finished;
     }

     // How much should lender send
     function getNeededSumByLender()constant returns(uint out){
          uint total = safeAdd(wanted_wei,lenderFeeAmount);
          out = total;
          return;
     }

<p>b) Borrower does not repay the loan on time, the tokens are transferred to the lender (who can sell the tokens on exchange)</p>

     // After time has passed but lender hasn't returned the loan ->
     // move tokens to lender
     // 
     // anyone can call this (not only the lender)
     function requestDefault()onlyInState(State.WaitingForPayback){
          if(now < (start + days_to_lend * 1 days)){
               throw;
          }

          // tokens are released to the lender 
          ERC20Token token = ERC20Token(token_smartcontract_address);
          uint tokenBalance = token.balanceOf(this);
          token.transfer(lender,tokenBalance);

          currentState = State.Default; 
     }
	 
<p>Above was excerpts of the solidity-based Smart Contract on secured lending. The above demonstrates how a simple loan transaction where the collateral is stored on the contract and all transactions are handled within the Smart Contract that the borrower creates.</p>

<p>Smart Contracts provide the solution for the borrower and the lender to perform a secured loan without relying on third parties. Since Smart Contracts can store ERC-20 compatible tokens and ENS domains, the collateral is easily moved to in any direction. This might not be the case in real life. Moreover, since ERC-20 tokens can represent any value from centralized world, Smart Contracts would provide the possibility to control this value on blockchain. Theoretically, anything can be used as a collateral once tokenized, even a dog.</p>

<h2>3.1	Secured Lending by Pledging Ethereum-Based Digital Tokens</h2>

<p>In this section, we will demonstrate how ETHLend DAPP works from the user experience perspective. We will go step-by-step walk-through on how to request a loan and to fund a loan. You will need to have Google Chrome and the MetaMask plugin installed. MetaMask is Google Chrome plugin to allow decentralized application, such as, ETHLend, to be run in the browser without downloading the full Ethereum node.</p>

<p>To download Google Chrome, please visit:</p>

<p>https://www.google.com/chrome</p>

<p>To download MetaMask, please visit:</p>

<p>https://metamask.io/</p>
 
<p>Click ‘GET CHROME PLUGIN’</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img1.jpg)
 
<p>Click Add to Chrome</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img2.jpg)
 
<p>Click Add extension</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img3.jpg)
 
<p>In the top right corner, you will see the icon of MetaMask</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img4.jpg)
 
<p>Click accept after reading and accepting the privacy policy</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img5.jpg)
 
<p>You will then create your MetaMask account here</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img6.jpg)
 
<p>After creating the account, you will be provided 12 words, which will be used to recover your account</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img7.jpg)
 
<p>You can see the details of your account and you can request a loan or fund a loan of ETH using ETHLend now</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img8.jpg)

<h3>3.1.1	New Loan Request</h3>

<p>In the upcoming sections, we are going to demonstrate two scenarios:</p>

<p>1.	Borrower repaying the loan and lender receiving his original principal plus interest</p>

<p>2.	Borrower not repaying the loan and lender receiving the tokens which borrower pledged as collateral</p>

<p>Before dive into that, we will introduce a few useful resources here:</p>

<p>Ether Scan: https://etherscan.io/ - You can check the details of your Ethereum account, such as balance of ETH and ERC-20 tokens</p>

<p>Token Factory: https://tokenfactory.surge.sh/ - Transfer token to another Ethereum account</p>

<p>Coin Market Cap: https://coinmarketcap.com/ - Live prices of ETH and ERC-20 tokens. Useful for calculating the amount of collateral, tokens, needed to make an attractive borrowing request</p>

<p>Ether Delta: https://etherdelta.github.io/ - Exchange for trading tokens. For lenders to sell ERC-20 tokens and purchase ETH if they wish when the loan is defaulted</p>

<p>We will have three accounts - lender, borrower1 and borrower2.</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img9.jpg)
 
<p>We are going to use Basic Attention Token (BAT) as collateral. For more information about BAT, please visit https://basicattentiontoken.org/</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img10.jpg)
 
<p>To create a loan, first click New Loan Request</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img11.jpg)
 
<p>MetaMask should pop up, and after reviewing you would need to click accept to continue</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img12.jpg)
 
<p>The message ‘Done!’ will be displayed after the transaction goes through</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img13.jpg)
 
<p>If you go back to All Loan Requests and shuffle the loans, you will see that a new loan is created. The red dot indicates that it is your address.</p>

<h3>3.1.2	The Loan Contract</h3>
 
<p>After that you clicked into the contract you just created, enter the details of the contract</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img14.jpg)
 
<p>Then click Set Data and MetaMask will pop up again for you to confirm</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img15.jpg)
 
<p>The message ‘Done!’ will be displayed when the transaction is completed.</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img16.jpg)

<h3>3.1.3	Sending Digital Tokens to the Smart Contract</h3>
 
<p>We will see the status of the contract is changed to ‘waiting for tokens’</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img17.jpg)
 
<p>You will need to transfer the amount token set in the contract to the address given</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img18.jpg)
 
<p>You can visit Token Factory to transfer tokens to the address, first click ‘interact with token contract’ (Alternatively, you can go to your Ethereum wallet and sent the tokens to the loan Smart Contract).</p>
 
![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img19.jpg)
 
<p>You will be asked for the token address</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img20.jpg)
 
<p>You can find out the contract address information on Etherscan</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img21.jpg)
 
<p>You can also check your balance here to ensure you have sufficient amount of tokens</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img22.jpg)
 
<p>You can transfer the token to the address given in ETHLend here</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img23.jpg)
 
<p>Once transfer is completed, you can go to ETHLend to check on the status and you will be asked to confirm on MetaMask</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img24.jpg)
 
<p>After that is competed, you will see the status of your loan has changed to waiting for lender</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img25.jpg)

<h3>3.1.4	Funding the Loan</h3>
 
<p>This is an example we are going to switch to a lender account. In practice, the following steps will be conducted by a lender</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img26.jpg)
 
<p>After selecting the loan, lender can click fund this loan request</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img27.jpg)
 
<p>Confirm via MetaMask</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img28.jpg)
 
<p>Borrower has successfully received his loan</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img29.jpg)

<h3>3.1.5	Paying the Loan Back</h3>
 
<p>As the borrower, you can choose the loan you would like to repay</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img30.jpg)
 
<p>Click return token and confirm via MetaMask</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img31.jpg)

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img32.jpg)
 
<p>You can see in the balance borrower has returned to lender the loan amount plus interest</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img33.jpg)
 
<p>Borrower has received back his token pledged earlier for collateral</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img34.jpg)

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img35.jpg)

<h3>3.1.6	Default Scenario</h3>
 
<p>We are going to demonstrate a default scenario next</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img36.jpg)
 
<p>We follow identical steps except for the number of days we are putting 0 day to simulate the loan defaulting</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img37.jpg)
 
<p>After the loan is defaulted, lender can see the message has changed to get token</p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/img38.jpg)
 
<p>Lender can claim the token and we can confirm on token factory</p>

<h2>3.2	On-Demand Lending</h2>

<p>Learning curve for the borrower. Currently the ETHLend’s decentralized application provides solely that the borrower can create the loan request. This means that the borrower must have a basic understanding on lending. The borrower must place such data as the premium, amount of tokens for pledge and the token Smart Contract address. It might be difficult for a first time borrower to evaluate the value of the ERC-20 token (even if the token is traded on the exchange) and the amount of premium which borrower is willing to accept to pay. If the borrower sets too low premium or overvalues the collateral, the loan might not be attractive for the lenders. This would mean that the loan would not be funded.</p>

<p>Liquidity provided by the lender. Alternative for the borrower’s loan request, ETHLend shall adopt a Smart Contract where the lender may place the loan offer for the borrowers. The lender creates a Loan Smart Contract. The lender inserts data on how much liquidity the lender in total is willing to lend, on what premium, and which tokens the lender is willing to accept for collateral. After the lenders Loan Smart Contract is deployed, anyone may lend from lender simply by sending ERC-20 tokens to the Smart Contract.</p>

<p>On-demand lending. The lender provides as above state liquidity for any borrower with the pre-set conditions. This means that instead of participating in multiple loan requests, the lender can handle all loans form one Smart Contract. When a borrower returns the loan the, the token is released and sent back to the borrower and the lender Loan Smart Contract has more liquidity for lending. Factually, we have here an on-going lending institution that the lender has created. The lender may at any point close his loan offer. This would mean that no new loans are granted and the borrowed capital will close on due.</p>

<p>Flexibility and shorter learning curve for the borrower. On-demand lending provides flexibility for the lender. The lender does not need to fund single small loans, instead the lender can place the terms for the loan capital and anyone can borrow merely by sending the accepted ERC-20 token to the loan agreement. For the borrower, on-demand lending means less necessary knowledge on lending. The learning curve is transferred from borrower to the lender, which means that the borrower does not have to evaluate the value of the collateral or evaluate the attractiveness of the premium. Of course, if the borrower is not satisfied of the price of the liquidity that the lenders are providing, the borrower may always place a loan request with its own terms.</p>

<h2>3.3	Secured Lending by Pledging Ethereum Name Service Domains (ENS)</h2>

<p>New name service created a gold rush. Ethereum Name Service Domains (ENS) are domains that are used in the Ethereum ecosystem. ENS domains provides a way to use a name for the long Ethereum address. For example if one would like to send ETH to Jim, the person would need to write long Ethereum address. By using ENS domain one could just sent the ETH to an ENS domain such as jim.eth (which is owned by Jim) and the ETH will be transferred to Jim’s Ethereum address.</p>

<p>ENS domains are auctioned against ETH. ENS domains are not actually bought but the ownerships is guaranteed by willingness to lock ETH for at least a year. When the auction is ended, the new owner of the domain is able to create subdomains, lease, loan or sell the domain. This means that the domain can be sold further to a third party or pledged for a loan. Today, as of 22 June 2017, there are over 75 000 registered domain names. If ENS domains would be ICANN gTLD domain, it would be the 48th largest between .solutions and .news.</p>

<p>ENS domains have significant value. ENS domains bear at least two forms of value. The first form of value is the ETH that is locked in the domain. For every single .eth domain there is an auction. Today there are 341 643 auctions started. The winning bid of the auction means that the second highest bid ETH amount is locked down on the ENS domain Smart Contract. There are currently 148 312 ETH locked down on ENS domains which results in 50 361 713 USD. Moreover, there are currently almost a billion dollars’ worth of ETH deposited in bids. This means that there are plenty of interest in ENS domains.</p>

<p>Unlocking the benefits of ENS domains. Since ENS domains hold ETH that cannot be used, pledging domains might be perfect option for those that would want to use some of the Locked ETH. The reason practically lies in the fact that unused funds could be placed for use to attract more funds or other use. The highest locked down amount on ENS domain is darkmarket.eth (20 103.10 ETH, equivalent to 6 826 329 USD) and followed by openmarket.eth (10 054.76 ETH, equivalent to 3 414 255 USD). Locking the funds means that these funds could not be used or moved. However, the locked down funds could be used for other purposes such as bidding on other ENS domains or using the funds on other investments instead of letting the funds lie in the ENS domain Smart Contract.</p>

<p>Even though it might not seem idealistic, when .eth domain that holds 0.01 Ether value would be up to pledge. However, ENS domains do have other value than the locked up Ether. Domain names are scarce. This means that even though an ENS Domain might hold as low as 0.01 Ether locked, it might have other value as well. For example, flourist.eth (which is not taken yet) might go for 0.01 Ether. However, the ENS domain might have future value or value for the industry or topic that the domain is related to.</p>

<p>For example, one might create a sophisticated Smart Contract on Ethereum that would track the source of flowers, thus giving an edge to florists’ who adopts the chain. In this sphere, flourist.eth might become quite popular even though the locked value is 0.01 ETH. This would mean that low bid domains is usable for pledge when valued carefully.</p>

<p>ENS domains as a collateral. Domains are great for collateral for two reasons. First, the amount of collateral is the same. When pledging ERC-20 tokens, on can pledge more than one token. When pledging ENS domains, you will have a single value because you cannot pledge more than one domain for the same loan (at this point). This makes things easier.</p>

<p>Secondly, ENS domains can be pledged against the lockdown value to cover the loan amount and the premium. This means that the amount of ETH does not change during the pledge. Therefore, unlike pledging Ethereum-based digital tokens, the borrower could create a loan request that is guaranteed 100% by the ENS domain lockdown without the risk of volatility that ERC-20 tokens might bear.</p>

<p>On the other hand, one must notion that the locked down ETH is released when the domain period ends, usually within a year. However, this does not stop the lender to sell the domain on an auction just as a digital token or hold the domain itself if it is scarce and wait the ecosystem to develop further.</p>

<p>ENS domain collateral Smart Contract. The ENS domain by design is transferrable. Transferability provides that the ENS domains are capable for collateral.  When a borrower on ETHLend pledges an ENS domain for a loan, the borrower needs to send the ENS domain to the Smart Contract. The Smart Contract will hold the ENS domain in case the borrower does not repay the loan back. In case of default, the lender is able to claim and transfer the ENS domain to his address for further realization.</p>

<p>Consequently, the ENS domain pledge follows the same roadmap as the tokens pledge. The main distinction is that on token pledge token smart contract address is used for interaction and data. On the other hand, in ENS domain pledge we are using the hash key provided by the ENS registry for transferring the ENS domain to the Smart Contract. The use of Smart Contract additionally guarantees that the address where the received funds are allocated does not change during the pledge, providing security and transparency for the borrower.</p>

<p>The rapid growth of ENS domains will lock down vast amount of ETH in to the ENS Smart Contracts. This means that at some point there shall be ETH locked that could be worth of billions of USD. Therefore, ENS domain pledge provides a convenient way to “unlock” these funds for use by obtaining funding and pledging the ENS domain. Eventually ENS domains could end up being even more suitable alternative for a collateral for a loan. ENS domains do not have the volatility that some of the ERC-20 tokens might have. Of course, the volatility with the tokens might disappear eventually and would follow such volatility that is seen on stock market or currency exchange. However, since tokens do differ this not the case for all tokens.</p>

<h2>3.4.1	Unsecured Lending</h2>

<p>Unsecured loan brings wider use for borrowers. Secured loans which require a collateral such as ERC-20 tokens or ENS domains do raise the bar for access to finance. However, secured loans provides the starting point for decentralized lending. Without using collateral, it would be challenging for borrowers and lenders who do not know each other to trust. Therefore, secured loans are truly a trustless solution for decentralized lending. Although, eventually to achieve a burst in crypto-lending, unsecured lending should be adopted. However, current crypto-lending options do not live in the decentralized environment. Moreover, an option that would implement real-wold credit scores would not be in our mind a sufficient solution, merely an escape route back to the centralized environment.</p>

<p>Decentralized solutions for unsecured lending. When the borrower repays the loans, the borrower (and lender) will receive 10 CRE (against 1 ETH loan). This CRE is used as any other ERC-20 token collateral. By using CRE, the borrower can spare other ERC-20 Tokens and eventually by volume would use solely CRE for securing loans on ETHLend. In one way, CRE would provide a way to avoid placing a collateral. However, using CRE based on reputation, requires repayment of loans. This means that we would still need a solution for first time borrowers. Of course, unsecured lending would add more risk of default, but this risk is compensated with higher interest rate (provided by the market) to satisfy lenders who are willing to bare the risk of unsecured lending.</p>

<p>Next we will introduce couple of functions that could be added to ETHLend to cover unsecured lending. These solutions presented are not yet implemented to the decentralized application. On a general basis, we believe that unsecured lending shall be part of ETHLend accordingly with the development roadmap. However, the technical solution that we shall implement the functions is yet to be determined due to vast phase of evolvement of the Ethereum ecosystems. Following solutions would be added to ETHLend to provide unsecured loans.</p>

<h3>3.4.1	Decentralized Credit Rating with Credit Token (CRE)</h3>

<p>Reputation is gained. Reputation system is a convenient way to establish trust between the borrowers and the lenders. Trust means that the lender is willing to provide a loan even if the loan is not secured. Unsecured decentralized lending is mostly based on previous repayments of secured loans. This means that the borrower needs to present previous behaviour of repayments. Due to the pseudo-anonymous nature of cryptocurrencies and Ethereum addresses, willingness of repayment is difficult to achieve without an indication of past compliance. By using reputation, we can lower the risk of default on unsecured loans. The outcome is that unsecured decentralized lending is more attractive when risk level is lower compared to lending for the first time borrower without any reputation.</p>

<p>ETHLend manages reputation with Credit Token. Credit Token (CRE) is an ERC-20 compatible token that is used within the ETHLend. Credit Token cannot be traded or even transferred to another address. The sole function of CRE is to represent the borrower’s reputation on ETHLend. Each repayment of the loan mints CRE (1 ETH loan mints 0.1 CRE). This CRE is used in two different ways. First, on secured lending, high amount of CRE indicates reputation and attracts the lenders even if the interest rate solely would not compensate the risk. Secondly, the important aspect of CRE is that it provides access to unsecure lending, which will be adopted on ETHLend.</p>

<p>Access to unsecured lending. On each loan repayment, CRE is minted. This means that if the borrower repays 10 different loans, each of 1 ETH (10 ETH on total), 1 CRE is minted and transferred to the borrower. The borrower now can use the 1 CRE to access unsecured lending. This means that the borrower does not have to use a collateral for the maximum of 1 ETH. If the borrower does not repay secured or unsecured loan, all borrower’s CRE is burned. The idea here is to raise the threshold on defaults. The borrower might not be eager to default a loan for the sake of losing all his CRE balance.</p>

<p>Risks of unsecured lending. Unsecured lending does not come without risks. Unsecured lending means that if the borrower does not repay the loan, there is no collateral, which would compensate the lender for even part of the losses. However, CRE provides a higher threshold for defaults since CRE represents decentralized credit rating, which accumulates on repayments. CRE can be compared to centralized credit score or rating systems. For example, if you default by not paying your electricity bill, you might not get a bank loan or even an insurance in most countries. The distinctive difference between centralized credit rating system and the decentralized is that in most countries centralized systems start with the default of person being creditworthy. On the other hand, in decentralized credit rating the creditworthiness must be accredited due to the pseudo-anonymous nature.</p>

<p>Even though, a reputation system is not a new invention, using an ERC-20 token for reputation management is a fascinating method to create the system in decentralized environment. Other means would be merely by broadcasting reputation value on the blockchain. However, digital tokens provide more transparency and trust, since the ERC-20 token is created with its own smart contract. Moreover, the data is easily removed from defaulted borrower since digital tokens can be burned on default.</p>

<h3>3.4.2	Self-sovereignty</h3>

<p>Self-sovereignty as reputation. uPort provides a self-sovereign identity system. uPort identity system provides the possibility to create identity based lending. User could register credentials through uPort. This would mean that if the loan is not repaid, the address or the identity would be banned from ETHLend and the data would be transferred to uPort. The loan default would eventually mean that the sovereignty of the uPort user would be affected in other Ethereum-based applications as well. This would be a risk and loss for the user that has built his reputation on uPort.</p>

<p>Gateway for first time borrowers. uPort could be a solution for borrowers that do not own ERC-20 tokens or ENS domains to use as a collateral for the loan. Since the borrower needs to repay secured loans to receive Credit Tokens to access unsecured lending, uPort would be a solution to access unsecured lending without the need to participate to secured loans in the first place. Since using self-sovereignty as a reputation, the high risk of default can be limited by the amount of ETH that the borrower can loan. For example, uPort loans can be limited to 0.1 ETH and only to a one loan per sovereign user. Therefore, by active lending the borrower can gain Credit Token, which eventually replaces the need for uPort on unsecured loans and provides access to higher and less restricted loan amounts.</p>

<p>uPort would not eliminate the risk of default completely. It reduces the risk in similar manner as the ETHLend’s native Credit Token is reducing. The distinctive here is that uPort would provide reputation from outside ETHLend, from other applications. However, nothing stops using Credit Tokens on other Ethereum-based applications (at some future point). In fact, Credit Token represents the repayments of loan, therefore the most vital trust that is known in the financial economy.</p>

<h2>3.5	User Experience on ETHLend</h2>

<h3>3.5.1	Accessibility</h3>

<p>Providing wide usage. Currently ETHLend DAPP is accessed with Google Chrome or Mozilla Firefox browser together with MetaMask plugin. To provide full coverage, the ETHLend DAPP shall be developed further for implementing mobile usage, parity and MyEtherWallet. The ETHLend team considers that the DAPP should be easily available with less learning curve as possible.</p>

<h3>3.5.2	User Interface</h3>

<p>Focus on user experience. ETHLend team considers that the user interface is the game breaker for adopting Ethereum-based applications for a wider audience. Eventually, our goal is to eliminate the learning curve as much as possible on blockchain applications. Moreover, we are bound to follow any innovations and improvements when it comes to user experience on decentralized applications. It is surely true that decentralization and blockchain-based Smart Contracts do create challenges for user experience and might require prior knowledge on blockchain and Ethereum basics. However, we believe that these challenges could be overcome merely by pushing hard development on the user experience.</p>

<h3>3.5.3	Performance</h3>

<p>Choices between on-chain and off-chain. Today ETHLend is a fully decentralized application running on Ethereum blockchain network. This means that all functionalities and data are on blockchain (on-chain). Once a wise man said that one should not force everything on the chain. This saying means now more than ever since the Ethereum blockchain network is growing on data to such the extend that it takes few days to load the full chain. Even though some functions could be left off-chain, we are trying to avoid these functions. ETHLend team’s aim is to create decentralized solutions by pushing innovation further instead of falling back to centralized solutions. However, we should not be always naive and we should not live in a vacuum, instead ETHLend should follow the directions that the mainstream blockchain development.</p>

<p>In regards of performance of the DAPP, we are aiming to provide ways to get as much as possible unnecessary functions from Smart Contract to develop the best technical experience that can be achieved on Ethereum network.</p>

<h3>3.5.4	Translations</h3>

<p>Languages are part of access. Translations provides wider accessibility to use ETHLend. Moreover, since we have a lending market at hand, accessibility would mean here access to finance as well, the very core and fundamental principle of funding, that not everyone is granted in today’s world.</p>

<p>Since the development of ETHLend, the team has recruited language skilled individuals who are part of the Ethereum community or starting with the community that were willing to assist the ETHLend project. We received lot of interest and eventually were able to receive translations of the ETHLend site and the DAPP, totalling into multiple languages. The languages that were included in the translations were Spanish, French, Chinese, Korean, Japanese, German, Russian, Portuguese, Dutch, Italian, Turkish, Norwegian, Danish, Finnish, Malay, Arabic, Filipino and Lithuanian. There translations are implemented during our upcoming user experience upgrade.</p>

<h3>3.6	Technical Roadmap</h3>

<p>We consider ETHLend as a long term project. However, to make most of us, concrete deadlines are necessary. Therefore, we shall introduce the following roadmap for technical implementations:</p>

1.	Implementing ENS Domain Collateral on June 2017
2.	Implementing CRE for Repayments on June 2017
3.	LEND Token Crowdsale on September 2017
4.	User Experience Upgrade during October 2017
5.	Unsecured Lending with CRE on October 2017
6.	uPort Integration on November 2017
7.	On-Demand Lending on January 2018
8.	Second User Experience Upgrade on February 2018
9.	Lending Bitcoin and Litecoin on April 2018
10.	KYC on-board implementation on May 2018
11.	Lending Other Altcoins on August 2018

<h2>3.7	Map of ETHLend</h2>

<p>Below is provided the ecosphere of decentralized lending on ETHLend:<p>

<p>Secured lending: ERC-20 Tokens, ENS domains + Unsecured Lending: CRE, uPort (to be implemented)</p>

<p>Currencies: ETH + Upcoming Currencies: Bitcoin, Litecoin, Other Altcoins</p>

<h1>4.	Legal Evaluation of the Loan agreement on ETHLend</h1>

<p>Crypto-lending without borders. Traditionally lending is provided locally due to the fact that lending involves due diligence on the borrower. This process requires the access to local credit score or rating system. Moreover, the legislation on lending depends by jurisdiction to jurisdiction and there are distinctions between the common law and civil law jurisprudence. Even though lending has been local, there has been always international finance that has not been restricted by jurisdictions. Mainly the question is about complying legislation to ensure the loans on ETHLend are binding.<p>

<p>Crypto-currency is defined differently through jurisdiction to jurisdiction. Since crypto-currency is relatively new to governments, they have not been too keen on regulating or defining the legal status on crypto-currencies. Moreover, we must acknowledge that the definition given in other fields of law such as tax law does not finally settle or give analogy to use the definition in other fields of law. What we can certainly define is what crypto-currency is not. Crypto-currencies are not currencies in the form that governments’ of different jurisdictions define, since crypto-currencies are not issued by state authority. Therefore, in most sensible definition crypto-currencies are left out to contractual agreements (when not regulated).<p>

<h2>4.1	Contractual Relationship</h2>

<p>Something for something. Where crypto-currencies are not regulated, they are contractual agreements between the parties. This would mean that the agreement between the borrower and the lender for borrowing ETH would be conducted on the basis on contract law. The next questions is which contract law would apply since there are distinctions between common law contract law and civil law contract law, not to mention the jurisdictional differences.<p>

<p>Freedom to contract. The basic principle in any contract law despite the jurisdictional differences is the freedom to contract. This means that anyone can agree to lend to anyone. Since the principle is the main rule, there are some exceptions such as lending to minors, which we need to take into account. Decentralized environment grants access to anyone since that is the point of decentralization. However, decentralization does not mean that we would have to act irresponsibly.<p>

<p>Terms and conditions. A loan transaction would be in place when there is a consent to repay the loan between the sender of ETH and the receiver of ETH. This would represent the simplest loan contract in the decentralized environment that is based on the agreement between the borrower and the lender. However, to make the loan transaction a good agreement between the borrower and the lender, this simple form of contracting is not sufficient.<p>

<p>Even thought, the loan is on Smart Contract and on a trustless environment, the users are living under governed jurisdictions. This means that the lending agreement should be valid, even though one might not have the ability to enforce it (if the counterparty is not known). To provide a sufficient loan agreement, ETHLend shall implement all legal functions of the loan to simple terms and conditions. These terms includes the loan period, premium, the collateral, the lender, the borrower, governing law and dispute resolution. Therefore, the parties do not have to deal with the juridical questions to participate in the lending market.<p>

<h2>4.2	Collateral</h2>

<p>New form of collaterals. In most jurisdiction collaterals or known as pledge are governed to establish the legal standing of a pledge against third parties. This has been important through time since enforcing a collateral is seen as an exception on the right to ownership. Moreover, most of the rules on collateral from jurisdiction to jurisdiction apply on real property, thus pledging non real property such as a phone or jewellery has soften regulation, if any. There is not much jurisprudential literacy on pledging ERC-20 tokens and ENS domains. In fact, ETHLend is the first who uses ERC-20 tokens and ENS domains for securing loans.<p>

<p>Acknowledgement and transfer of collateral. Non real property collateral do need to comply certain actions to establish valid collateral and thus enable the transfer of ownership in case of default. These rules do apply in most jurisdictions and the jurisdiction where ETHLend would be governed (see. governance). First, to be a valid collateral, the collateral must be transferred to the lender. The same principle is seen in pawnshops where the borrowers leave items to the pawnshop. The possession is important to acknowledge third parties that the item is held as a collateral.<p>

<p>The property could be held by a third party as well. However, Smart Contracts are interesting since by using Smart Contract, ETHLend does not hold the collateral. Instead, the collateral is running on the blockchain which is controlled by the Smart Contract. The aim behind the possession is to inform third parties (extra partes) that the item is pledged. This aim is by design complied on Ethereum blockchain. All transactions can be inspected by the blockexplorer. Therefore, when ERC20 token or ENS domain is pledged on ETHLend, the collateral is moved to the Smart Contract and locked until the loan is repaid. This information is accessible to anyone, anywhere with an internet connection.<p>

<h2>4.3	Know Your Customer (KYC)</h2>

<p>ETHLend does not lend or hold assets. ETHLend is a decentralized application running on Ethereum blockchain network. This means that ETHLend does not store any data on centralized servers. All data is running on Ethereum blockchain, peer-to-peer. ETHLend does not control any assets between the lenders and the borrowers. First, ERC-20 tokens and ENS domains are not defined as asset in the traditional meaning. ERC-20 tokens and ENS domains are representation of value. Secondly, all transactions are conducted on Smart Contracts. This means that when the borrower places a loan request, the borrower creates the Smart Contract.<p>

<p>Therefore, the borrower creates the environment for the specific loan. When the Smart Contract is created, the data is broadcasted to Ethereum network and is not stored on any servers locally. ETHLend could be seen as a tool set loans and browse loan on Ethereum network.<p>

<p>KYC regulation applies on money lending between borrowers and lenders. When FIAT money is lend, the lender must conduct known your customer compliance on certain thresholds by verifying the customer, the origins of the funds and other verifications. The thresholds do vary from jurisdiction to jurisdiction but remain similar in principles. However, uncertainty lies within lending ETH since ETH is not a currency by goverments’ definition. Therefore, whether lending ETH is subject to KYC is an unsettled question.<p>

<p>KYC on-boarding. Whether or not lending ETH is subject to KYC, ETHLend endorses the KYC policies between ETH loans due to the fact that regulation might follow sooner or later since decentralized environment does not occur in a vacuum. For this reason according to our roadmap, ETHLend will implement integrations for assisting the parties to comply with KYC regulations. The aim is to provide KYC when deemed to be needed and provide it as easy as possible.<p>

<p>Currently, KYC can be solved through messaging and interaction between the lender and borrower. However, current solutions would be off-chain. The ETHLend team is working on to provide a KYC solution that would not spill over to off-chain. The easiest way to provide KYC without the need to spill the application to off-chain would require the borrower to insert a link to the material that would comply with KYC. This material would include identification, proof of address and origin of funds. Even decentralized storage could be used to achieve the storage of KYC data.<p>

<h1>5.	ETHLend</h1>

<p>Decentralized governance. Since lending on ETHLend is decentralized, it would be in line to add decentralization as much as possible to the governance of the DAPP and the project itself. When we created the ETHLend DAPP, we wanted to provide more democracy for lending market by decentralized lending. Democracy can be provided to the ETHLend development and governance as well to provide more value for the token holders and people who are willing to contribute on ETHLend development.<p>

<h2>5.1	The Team</h2>

<p>Introducing our team:</p>

<p>Stani Kulechov, Founder of ETHLend & Development, stani@ETHLend.io</p>

<p>Jordan Lazaro Gustave, Head of Management, jordan@ETHLend.io</p>

<p>Martin Wichmann, Head of Token Sale, martin@ETHLend.io</p>

<p>Adnan Javed, Legal Advisor, adnan@ETHLend.io</p>

<p>Sergej Stein, Financial Advisor & Blog, sergej@ETHLend.io</p>

<p>Scott Malsbury, Head of Communications, scott@ETHLend.io</p>

<p>Jin Park, Head of Marketing, jin@ETHLend.io</p>

<p>Rowan vab Ginkel, Graphics & Visualization</p>

<p>Edmund To, Lead Junior Developer<p>

<p>Anastasija Plotnikova, Translations</p>

<p>Andreas Haraldsvik, Slack Wizard</p>

<p>Nolvia Serrano, Vlog</p>

<p>Kelly Pope, Social Media</p>

<p>Andreas Haraldsvik, Slack Wizard</p>

<p>Stephen You, Korean Desk</p>

<h2>5.2	Governance</h2>

<p>ETHLend follows decentralized governance. ETHLend introduces 3-tier governance for decentralized lending application. The decentralized application (DAPP) shall be governed by decentralized governance model similar to DAO. Each token holder can propose changes in provided procedure for the DAPP. Each proposition is voted within the LEND token holders. Regular changes would require majority of voters present and core changes would require 2/3 of the voters present. The aim is to create a democratic system to control on what direction the DAPP development will take place.</p>

<p>The third tier shall be the layer that owns the DAPP. This layer shall be Swiss Foundation or Swiss LLC, which would provide the surroundings for ETHLend and connects the decentralized environment to centralized world. Such connection might not be ideal when we are aiming for complete decentralization. However, such a layer is vital for protecting our users for any liabilities that might occur for the liabilities in respect to different jurisdictions. Swiss Foundation or Swiss LLC would offer limited liability on risk of liabilities. This veil is vital since the regulation on decentralized applications, crypto-currencies and token crowdsale is still living under uncertainty due to lack of regulation.</p>

<p>Roadmap to consensus. The 3-tier governance needs a roadmap for implementation. Theoretically, the 3-tier governance could be used from the beginning. However, since the DAPP needs much development that requires flexibility and agile performance, implementing decentralized democracy would stall the development on ETHLend in the most vital stage. Therefore, we are implementing the 3-tier democracy within 2 years from the token sale. By this time, we would have a DAPP that has been driven through the test period.</p>

<h2>5.3	Roadmap</h2>

<p>Road to decentralization. ETHLend introduces the following roadmap adopting changes, improvements and governance to ETHLend:</p>

1.	ETHLend DAPP v. 1.0 on May 2017
2.	White Paper on ETHLend on June 2017
3.	Token Sale Smart Contract Testing on July 2017
4.	Token Sale on September 2017
5.	Swiss Foundation or Swiss LLC on October 2017
6.	LEND Trading on Exchanges on November 2017
7.	Excemption for borrower's fees (LEND) starts from January 2018
8.	Profit Sharing for LEND tokens holders starts from January 2018
9.	Opening Proposition Forum for Token Holders on May 2018
10.	Creating and Testing Democracy DAO on November 2018
11.	Voting on Proposition Deployed on May 2019
12.	Vesting for LEND Ends on September 2019

<h1>6.	Introducing LEND Token and the Token Sale</h1>

<p>Raising funds for developing global peer-to-peer lending market. ETHLend issues ERC-20 compatible Ethereum-based LEND token for crowdsale. The aim for issuing the token sale is to finance the development and management of ETHLend. Currently, we are a team that is developing a global scale decentralized lending market. To provide a functional lending market to such extent, liquidity is required. Our aim is to attract early adopters and investors and reward the contribution with value such as the profit sharing and fee reductions.</p>

<p>Principles of the tokens sale. ETHLend aims to provide a token sale that is democratic, decentralized, secure and fair. This also applies to the vesting model and to the future governance on ETHLend. To comply with democracy, anyone can buy LEND on Token Sale period. The Token Sale shall be provided in a decentralized manner by using an Ethereum-based Smart Contract, which would provide more security due to the decentralized nature. Moreover, all the token purchases will be verified manually before distribution to avoid any misuse.</p>

<h2>6.1	Profit Sharing</h2>

<p>Token holders are entitled to profit derived from loan Smart Contract that are deployed on ETHLend. The goal of the token sale is to raise funds. Token sale contributors are the early adopters and investors of ETLend decentralized lending. To compensate the contribution on most crucial stage of the development, ETHLend will share profit with the token holders. This means that part of the profit is paid to the token holders address once claimed, on a monthly or quarterly basis.</p>

<p>Profit from deploying Smart Contract. ETHLend derives cash-flow when loan requests are deployed or funded. These fees are in place to fund the development of decentralized lending. However, since token holders are contributing by token sale, ETHLend is able to share the revenue with the token holders and keep the fees low.</p>

<p>Value increasing profit share. Currently, the fees for deploying a loan request is set to 0.01 ETH, which the borrower pays (unless LEND token is used for collateral). Similarly, the lender pays 0.01 ETH for funding the loan. ETHLend will distribute flat 5% of these fees to the token holders. Moreover, additional 1 to 5% is distributed on top of the flat 5% fee depending on the volume growth in ETLend (compared to previous year’s volume). Therefore, ETHLend can distribute as much as 10% as profit share. The profit sharing scheme starts on January 2018. Here is a demonstration of the profit share:</p>

1.	First year (during 2018) = 5%
2.	5% + additional 1% when fee revenue is 20% higher than in previous year
3.	5% + additional 2% when fee revenue is 40% higher than in previous year
4.	5% + additional 3% when fee revenue is 60% higher than in previous year
5.	5% + additional 4% when fee revenue is 80% higher than in previous year
6.	5% + additional 5% when fee revenue is 100% higher than in previous year

<p>Rewarding token sale contributors. The profit sharing model aim to compensate those token holders that participated in the token sale or are early token holders. Since decentralized lending is forming it shape and growing, up to 10% could be achieved for few years. After the market gets more stable, the profit share might balance itself to 5-6%. This gives an edge to the tokens holders that are participating early on. Secondary aim for LEND token is to provide a token that has concrete value to hold and cash-flow. This makes LEND sought after token.</p>

<h2>6.2	Excemption on Borrower's Fees</h2>

<p>Pledging LEND exempts from the borrower’s fees. LEND tokens is primarily targeted to our contributors. Since most contributors are or will at some point use ETHLend, there are also benefits from holding LEND tokens. When the borrower uses LEND as a collateral, the borrower is exempted from the loan request fee. Using a LEND as a collateral gives the LEND token holders an edge compared to other token holders, which should be soon as an value holding factor for the LEND token.</p>

<h2>6.3	Token Distribution</h2>

<p>Total of 1 000 000 000 (one billion) LEND is released for sale. Additionally, 300 000 000 LEND is held for development fund to incentivise the development team and to recruit more talent for ETHLend. There will be no follow-up sale on LEND. The tokens are available for purchase for the period of 30 days from the token sale launch. The date for the token sale is to be announced.</p>

<h2>6.4	Purchase Price</h2>

<p>Endorsing early purchase. The price on LEND is determined in different tiers based on timing and quantity of the purchase. We want to endorse token buyers that are amongst the first by reducing the token sale price for the first purchases.</p>

<p>Multitier token sale. The purchase price for LEND is subject to time and quantity. ETHLend proposes the following tiers for the token sale:</p>

1.	First 1 000 000 priced at 7 000 LEND per 1 ETH
2.	1 000 001 to 10 000 000 LEND priced at 6 000 LEND per 1 ETH
3.	10 000 001 to 500 000 000 LEND priced at 5 000 LEND per 1 ETH
4.	500 000 001 to 750 000 000 LEND priced at  4 000 LEND per 1 ETH
5.	750 000 001 to 1 000 000 000 LEND priced at 3 000 LEND per 1 ETH

<h2>6.5	Burning Tokens</h2>

<p>All tokens that are not sold during the token sale are burned. This means that these tokens cannot be used and the total supply of the tokens is reduced and the value of sold tokens increases. The maximum amount of tokens for sale is one billion. This limit cannot be exceeded and there will be no minting or a follow up sale for LEND.</p>

<h2>6.6	Vesting</h2>

<p>Ensuring commitment. All tokens distributed to the core team are subject to vesting. Vesting model ensures more value and security for the token contributors. Vesting provides more loyalty from the core team towards the project and ensures that LEND is not subject to market manipulation and provides stable market development for the LEND token. Eventually vesting is a way for the ETHLend team to show the commitment and loyalty for the ETHLend project.</p>

<p>ETHLend introduces the following Vesting model for the core team:</p>

1.	80% of LEND is locked once Token Sale distribution has ended
2.	60% of LEND is locked after 6 months from Token Sale distribution
3.	40% of LEND is locked after 12 months from Token Sale distribution
4.	20% of LEND is locked after 18 months from Token Sale distribution
5.	0% of LEND is locked after 24 months from Token Sale distribution

<p>The vesting model is active for 24 months in total. All tokens that are distributed to new team members from the development fund after the LEND token sale follows the vesting model on a pro-rata basis (will join the vesting model from the next mark).</p>

<h2>6.7	Security</h2>

<p>Security on focus. LEND token sale is performed on decentralized Ethereum Smart Contract. The token sale contract shall be tested on Kovan testnet and performed on Ethereum mainnet. There will be a manual due diligence of each token sale transaction that has taken place to make sure there is no misuse of the token sale.</p>

<p>Storing the funds. All raised funds are stored in divided multi-signature Ethereum wallets. Therefore, the access to funds would require multiple people to sign. Diversification of wallets provides extra-safety in case private key would be compromised. A spending account with less than 5% of the funds can be held on a single-signature account.</p>

<h2>6.7	Funds Allocation</h2>

<p>Most of the funds are allocated to further development of the DAPP, either on core development or on user experience development. ETHLend provides the following funds allocation based on needs for application that ETHLend is developing:</p>

*	35% on core development
*	20% on user experience development
*	20% on management of ETHLend Foundation or LLC (including legal and management costs)
*	15% on promotions
*	10% on unexpected costs

<p>Funds allocation is subject to change for providing flexibility. ETHLend will use best practices on funds allocation and its own discretion.</p>

<h1>7.	Further Updates</h1> </p>

<p>Further updates on LEND Token Sale and DAPP updates are published on http://about.ETHLend.io and in our mailing list. The Token Sale launch will be announced on our mailing list and published on http://about.ETHLend.io/blog </p>

<p>For questions, join our slack:</p>

<p>https://join.slack.com/ETHLend/shared_invite/MjAzMTM0MzEyNzA3LTE0OTg0MDk0NDItOGY0MTlkMTlmZA </p>

<p>Reddit:</p>

<p>https://www.reddit.com/r/ETHLend/ </p>

![Image](http://about.ethlend.io/wp-content/uploads/2017/06/logo_300DPI-05-1.png)
