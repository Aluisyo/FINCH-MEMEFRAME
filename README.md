# FINCH-MEMEFRAME

https://finch-ao.ar-io.dev

$FINCH is A social meme coin on AO. FINCH aims to create opportunities for users to experience AO and onboard more users to the AO ecosystem.

Join the FINCH community. Mint $FINCH Tokens using $CRED, then Stake them for voting on the next Webpage to show on the FINCH page.

Total Supply: 100000 FINCH

### How to Mint/Buy

```
FINCH = "rik3eCayInKVNzSMdoxeSEfpxNd5U7tx1H8NAveg4o8"
```

```
Send({Target = CRED, Action = "Transfer", Quantity = "1000", Recipient = FINCH  })
```

### How to stake

```
Send({Target = FINCH, Action = "Stake", Quantity = "1000", UnstakeDelay = "1000"})
```


### How to Unstake

```
Send({Target = FINCH, Action = "Unstake", Quantity = "1000" })
```


### How to see Staked Balance

```
Send({Target = FINCH, Action = "Stakers"})
```


### How to Propose a MemeFrame Change

```
Send({ Target = "FINCH", Action = "Vote", Side = "yay", VoteID="[TX ID of the Arweave Page you want to be displayed]" })
```


### How to Vote YES

```
Send({ Target = "FINCH", Action = "Vote", Side = "yay", VoteID="[TX ID of the Arweave Page you want to be displayed]" })
```


### How to Vote NO


```
Send({ Target = "FINCH", Action = "Vote", Side = "nay", VoteID="[TX ID of the Arweave Page you dont want to be displayed]" })
```



