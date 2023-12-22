# Audits

# CodeHawks <img src="https://github.com/We3abs/Audits/assets/123958271/b4062916-8172-4700-8a3e-46c57d230ab8" width="50" height="50">



| Contest        | High risk | Medium risk | Low Risk     | Language    |Security Report|
|----------------|-----------|-------------|-----------------|-------------|----------------|
|-Sparkn Protocol|   -       |       -     |     1           |  Solidity   | [Potential DOS due to Gas Exhaustion](https://www.codehawks.com/report/cllcnja1h0001lc08z7w0orxx#L-06)        |
|-DittoETH       |   -       |       -     |      2          |  Solidity   | [ L-08. Unlimited Approval Risk in BridgeSteth Contract](https://www.codehawks.com/report/clm871gl00001mp081mzjdlwc)|
|                |   -       |       -     |                 |             | [L-07. Lack of Duplicate ID Check in combineShorts Function](https://www.codehawks.com/report/clm871gl00001mp081mzjdlwc)
|Password Store#1|      1    |         -   |      -          | Solidity    | [Missing Ownership Verification in setPassword Function](https://www.codehawks.com/report/clnuo221v0001l50aomgo4nyn#H-01)
|Puppy Raffle#2  |      2    |      2      |     1           | Solidity    | [H-02. Reentrancy Vulnerability In refund() function]                                                                                                                       
|                |           |             |                 |             | [H-05. Typecasting from uint256 to uint64 in PuppyRaffle.selectWinner() May Lead to Overflow and Incorrect Fee Calculation]|
|                |           |             |                 |             | [Inefficient Duplicate Check in enterRaffle Function Leads to High Gas Costs and Potential Unusability] |
|                |           |             |                 |             | [Strict Balance Equality Check in withdrawFees Function](https://www.codehawks.com/report/clo383y5c000jjx087qrkbrj8)|
|Thunder loan #3 |   1       |             |                 |             | [Detect missing events for critical arithmetic parameters](https://www.codehawks.com/report/clocopz26004rkx08q1n61wnz)

