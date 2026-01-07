# 账户模型

## 组成

- Mint Account
- Associated Token Accounts(ATA)

## Mint Account

- 存储代币的基本信息
  ![Mint Account Detail](./img/mintAccountDetail.png)
  例子
  ![Mint Account](./img/mintAccount.png)

## ATA

- 可以追踪用户有多少某种代币 类似于`user1有usdc 100个`
- 推导方法
  `user_wallet_address + token_mint_address => associated_token_account_address`

![ATA](./img/ATA.png)
