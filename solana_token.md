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

# 命令

## 创建 mint

`spl-token create-token`

## 为钱包创建 token account

`spl-token create-account <TokenMint>`

## mint token 到本地钱包

`spl-token mint <TOKEN_MINT> 6000000`

# token2022 命令

`spl-token create-token --program-id TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb --enable-metadata`
