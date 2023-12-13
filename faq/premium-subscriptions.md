# Premium Subscriptions

<details>

<summary>How much Gas Cost do Subscribers pay?</summary>

#### <mark style="color:green;">`oneliner`</mark>

Subscribers pay roughly 0.20 - 0.40 USD in Gas per month.

#### <mark style="color:blue;">`extended`</mark>

Paying for transactions when subscribing via `subThr` is the most expensive operation for users. This transaction would split payments to 3 content creators and would consume about `200,000` gas. On Arbitrum or Optimism, the napkin math equates to roughly 0.4 USD of a user's monthly gas cost to be a premium subscriber.&#x20;

```
200,000 * ( 0.5 + 0.5 ) = 200,000 gwei = 0.0002 ETH ( 0.4 USD @ 2000/ETH )
```

Note that directing your subscription fee to only one content creator reduces gas costs by roughly 50%, because the smart contract logic does then only have to split payments for 1 address instead of 2 or 3. Further note that these gas costs are expected to go down significantly in the future with L1 protocol upgrades like [EIP-4844](https://www.eip4844.com).

</details>
