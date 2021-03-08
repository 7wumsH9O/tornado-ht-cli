### 火币生态链
1. 在.env文件添加你自己的私钥 `PRIVATE_KEY`

挖矿例子(需要安装 node v15.10.0):
```bash
$ npm install
$ # 存币挖矿命令
$ ./cli.js deposit HT 0.1 --rpc https://http-mainnet.hecochain.com

Your note: tornado-eth-0.1-42-0xf73dd6833ccbcc046c44228c8e2aa312bf49e08389dadc7c65e6a73239867b7ef49c705c4db227e2fadd8489a494b6880bdcb6016047e019d1abec1c7652
Tornado HT balance is 0
Sender account HT balance is 10
Submitting deposit transaction
Tornado HT balance is 0.1
Sender account HT balance is 9.899
$ 此时您的账户将多0.1 的AYT 合约地址:0xf01d10d64c91fbf652afc4942de46057eb15679d
```

```bash
$ # 取币命令
$ ./cli.js withdraw tornado-eth-0.1-42-0xf73dd6833ccbcc046c44228c8e2aa312bf49e08389dadc7c65e6a73239867b7ef49c705c4db227e2fadd8489a494b6880bdcb6016047e019d1abec1c7652 (你的提币地址 不要和充币一样 地址需要有0.1的AYT) --rpc https://http-mainnet.hecochain.com

```
