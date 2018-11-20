# Disten.se

### Distense is a for-profit company that runs on the Ethereum blockchain.

Contributors earn DID, an Ethereum token which is issued immediately after work is approved by other contributors. DID are immediately exchangeable into ETH.

### Tasks

```c++
struct Task {
    string title;
    address createdBy;
    uint256 reward;
    RewardStatus rewardStatus;
    uint256 pctDIDVoted;
    uint64 numVotes;
    mapping(address => bool) rewardVotes;
    uint256 taskIdsIndex;
}

// https://github.com/Distense/distense-contracts/blob/c328f6197acc5eed8a6cc29521040b1f3ece1072/contracts/Tasks.sol#L18-L27
```

#### Lifecycle

```c++
enum RewardStatus {
    TENTATIVE,
    DETERMINED,
    PAID
}
```



##### How do the tokens get minted?

Tasks have a default Reward which can be voted up or down by existing DID holders – the DID Reward gets rewarded to the worker when the workers' Pull Request is approved.

##### How do I select a Task?

You can select any task which does not have the `RewardStatus` of  `PAID` –– be mindful that these tasks may already have [Pull Requests](https://disten.se/pullrequests) open so be sure to check the list also.

#### Governance

`Default task reward` is a votable governance parameter.





# @TODO



### Competitors

##### Aragon

Provides a milestone model or salary model for DAOs.

For creating your own organization

- How to test the milestones have been achieved

Aragon Grants:

- Any technolgoy that improves the ecosystem they will fund.