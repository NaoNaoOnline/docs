# Premium Subscriptions

<details>

<summary>Which Premium Features are available today?</summary>

#### <mark style="color:green;">`oneliner`</mark>

Custom lists and notifications to discover and organize online events.

#### <mark style="color:blue;">`extended`</mark>

Here is a breakdown of premium features currently available.&#x20;

* Custom event lists. By default users can only have a single list. Premium Subscribers can have many custom lists in order to organize online events that they care about most. With this feature you can see all events in one place that are matching the interests you care about the most.
* Custom home feed. By default users see the latest events added to the platform regardless their host and category labels. Premium Subscribers can set their own home feed to one of their lists. With this feature the first thing you see when you open NaoNao is your favourite list.
* Opt-In list notifications. By default users do not see the notification badge in the sidebar once new events got added to the platform. Premium subscribers can choose for which of their lists to see the notification badge for. With this feature it is easy to see which events are about to happen.
* Longer event retention. By default users see events for the past week. Premium Subscribers see events for the past 3 months. With this feature you have a better point of reference of what happened in the past.&#x20;

</details>

<details>

<summary>How do Premium Subscriptions work?</summary>

#### <mark style="color:green;">`oneliner`</mark>

Every month users pay a subscription fee directly to content creators onchain.

#### <mark style="color:blue;">`extended`</mark>

In order to get access to premium features, users have to pay a subscription fee onchain. All value transfers happen in a peer-to-peer fashion without any intermediary or custodian. You do always own your funds, whether you are a producer or consumer. NaoNao will never have control over your money nor your private keys. When users want to subscribe for premium features, they have to sign a transaction against a smart contract that sends the subscription fee directly to the selected content creator. You choose which content creators to pay, which means you can directly say "thank you" to the content creators that added events to the platform which you enjoyed most. It is possible to send your subscription fee to 1, 2, or 3 content creators at the same time. The smart contracts facilitating the subscription process are deployed on various L2s so that you can choose your favourite network to transact.

And surprise, the rest of the month in which you subscribe for the first time is for free! If you subscribe for the first time on the 1st of April, then you pay for all of Mai and get the full month of April for free. If you subscribe on the 25th of April, then you pay for all of Mai and get the rest of the hand full of days in April for free.&#x20;

And surprise again, if you added at least 10 online events to the platform that all together generated at least 15 clicks on the event link, then you get a premium subscription for the current month for free as well!

</details>

<details>

<summary>Why would any user pay for NaoNao?</summary>

#### <mark style="color:green;">`oneliner`</mark>

Because users find value in discovering activities they did not know about before.

#### <mark style="color:blue;">`extended`</mark>

Users will find value in discovering online activities that they find interesting and enjoy participating in. This is about the human need to feel something. We are all looking for shared experiences. And usually people like more than one thing. It becomes convenient to organize personalized lists of events so that users can easily find what they are looking for in the moment. While anyone can use NaoNao for free, premium features to discover and organise shared experiences are reserved for premium subscribers. Once a user reaches the critical mass for joining events, users will be more likely to subscribe in order to discover more and organize in more convenient ways. For the majority of users out there, what matters is the value received in exchange for value paid for. NaoNao's mission here is to maximize the user's value received.&#x20;

Another angle here is [Retroactive-Public-Goods-Funding](https://medium.com/ethereum-optimism/retroactive-public-goods-funding-33c9b7d00f0c), which means that Premium Subscribers can directly say "thank you" to the content creators that brought the best online events to the platform.&#x20;

</details>

<details>

<summary>Can I gift a Premium Subscription to a friend?</summary>

#### <mark style="color:green;">`oneliner`</mark>

Yes you can!

#### <mark style="color:blue;">`extended`</mark>

The subscription smart contract is designed to configure the subscription receiver. That means the user paying for the subscription and the user receiving the subscription can be different individuals. Maybe you can make somebody smile by gifting them a NaoNao Premium Subscription. You know how the saying goes. If you can be anything, be kind.

</details>

<details>

<summary>How much does the Premium Subscription cost?</summary>

#### <mark style="color:green;">`oneliner`</mark>

`0.003` ETH per month, which is 6 USD at an ETH price of 2000 USD.

#### <mark style="color:blue;">`extended`</mark>

The subscription fee is denominated in [ETH](https://ethereum.org/en/what-is-ethereum). The goal for the subscription fee is to not exceed the equivalent of 8 USD per month, considering the currently available feature set. With fluctuating ETH prices the amount of ETH required may be adjusted. Future feature sets changing the unit economics of NaoNao's business model may require further adjustments of the monthly subscription fee.

</details>

<details>

<summary>How much Gas Cost do Subscribers pay?</summary>

#### <mark style="color:green;">`oneliner`</mark>

Subscribers pay roughly 0.20 - 0.40 USD in Gas per month.

#### <mark style="color:blue;">`extended`</mark>

Paying for transactions when subscribing via `subThr` is the most expensive operation for users. This transaction splits payments for 3 content creators at the same time and consumes about `200,000` gas. On Arbitrum or Optimism, the napkin math equates to roughly 0.4 USD of a user's monthly gas cost to be a premium subscriber.&#x20;

```
200,000 * ( 0.5 + 0.5 ) = 200,000 gwei = 0.0002 ETH ( 0.4 USD @ 2000/ETH )
```

Note that directing your subscription fee to only 1 content creator reduces gas costs by roughly 50%, because the smart contract logic does then only have to split payments for 1 address instead of 2 or 3. Further note that these gas costs are expected to go down significantly in the future with L1 protocol upgrades like [EIP-4844](https://www.eip4844.com).

</details>
