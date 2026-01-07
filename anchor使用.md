# anchor 初始化项目

```shell
anchor init project1
cd project1
anchor build
```

# 配置 solana 在 localhost 上运行

```shell
solana config set --url localhost
```

# 启动测试节点

```shell
solana-test-validator
```

# 运行测试

```shell
anchor test --skip-local-validator
```

# 领取 airdrop

没有钱包要创建一个钱包

```shell
solana airdrop 100 *********
```
