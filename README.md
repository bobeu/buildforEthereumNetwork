# buildforEthereumNetwork

Introduction
The aim of this project is directed at walking the students through the beginner phase to advance level where they will be able to write a good solidity program and deploy it - creating a production-ready smart contract. It was selected to feature every solidity-required topics and subtopics under solidity programming language including but not limited to other development tools that are necessary for the course. This will be used to assign tasks and grade them. 

Project Name:               Tax Incentive Smart Contract


Contract feature/requirement
Lagos State for instance generates most of her revenue from tax. Taxation should be easier  to collect. It is a contribution to the society as regard the law of the land and paying should be in accordance with all attributes of taxation. But many citizens do not pay tax while others declare less profit so they would have to pay less tax. Government came up with an idea to incentivize taxation by rewarding honest tax payers thereby encouraging tax compliance. 
Implementation requires incentives via tokenized model plus a tax relief structure. Corporations, firms and individuals who consistently declare profits, pay tax regularly and comply with tax regulations will be rewarded duly by sending a token to them.
  
Our Smart Contract is require the following functionalities and or features:

Contract definition.
Assumption that contract is owned by a body i.e Government.
Token contract creation.
Minting token
Tax structures and calculation
Categories of payer
Registration of payer
Payers account section
Tax Identification Number generation
Fund access control
Contract duration (if any)
Contract Upgrade pattern

The contract expected to:

List of different categories of payers
Each category should have a specified rate of taxation
Provision for Individual/small businesses willing to comply but unable to take proper account to determine profit for tax deduction
Specified reward pattern/amount on instant tax remittance to payer’s wallet or based or accumulated compliance report.
Compliance report(internal function private to the contract on which token reward is based)
Special reward for faithful/top citizens. Ie payers who have been consistent over a long period of time (2 years plus).
Determinant of faithful citizens.
Tax relief and determinant(s).
Ability to query value with key - “TxID”
Events.

Additional information
Contract inheritance.
For accessibility control, our contract may have to inherit the Ownable.sol library of OpenZeppelin. 
Contract will use additions and subtractions in several functions, hence, we will import the SafeMath library of OpenZeppelin. 
Other functions require OZ Lib would be applied.


