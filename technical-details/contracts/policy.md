# Policy

{% hint style="info" %}
The Policy contract is used to manage privileged permissions for content moderation. Users having their Web3 wallet registered with the Policy contract and the NaoNao platform gain administrative permissions offchain according to the SMAs onchain. See also [Github](https://github.com/NaoNaoOnline/contracts).
{% endhint %}

<details>

<summary><a href="https://sepolia.etherscan.io/address/0x7FC9a5730381DdF44C7D762d82A4aabC90fAE786">Sepolia</a></summary>

**address**

```
0x7FC9a5730381DdF44C7D762d82A4aabC90fAE786
```

**deploy**

```
npx hardhat run --network sepolia scripts/deploy_policy.ts
```

**verify**

```
npx hardhat verify --network sepolia 0x7FC9a5730381DdF44C7D762d82A4aabC90fAE786 0
```

</details>

