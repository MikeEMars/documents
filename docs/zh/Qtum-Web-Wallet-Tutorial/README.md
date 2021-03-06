# Qtum web钱包使用教程

- [地址](#地址)
- [设置](#设置)
    - [设置语言](#设置语言)
    - [设置网络](#设置网络)
    - [设置模式](#设置模式)
- [创建钱包](#创建钱包)
    - [创建文件钱包](#创建文件钱包)
    - [创建密语钱包](#创建密语钱包)
- [恢复钱包](#恢复钱包)
    - [从加密文件恢复](#从加密文件恢复)
    - [从密语恢复](#从密语恢复)
    - [从私钥恢复](#从私钥恢复)
    - [从手机钱包恢复](#从手机钱包恢复)
    - [使用Ledger恢复](#使用ledger恢复)
- [查看钱包及备份](#查看钱包及备份)
- [转账](#转账)
    - [普通转账](#普通转账)
    - [使用Ledger转账](#使用ledger转账)
    - [Token转账](#token转账)
- [离线挖矿](#离线挖矿)
    - [添加委托](#添加委托)
    - [取消委托](#取消委托)
    
# 地址
QTUM web钱包的唯一官方地址为: [https://qtumwallet.org/](https://qtumwallet.org/)

# 设置
设置界面可以进行语言设置，网络设置和模式设置。选择选项后，点击下方的"确认"按钮，进行保存。

## 设置语言
语言可以选择三种语言，中文，英文和韩文。

## 设置网络
这个选项可以选择是在主网操作还是在测试网络操作。对于一些不确定的操作，或者一些测试操作，可以在这里切换到测试网络。

## 设置模式
这个选项是在做安全转账时使用，具体的使用方法在介绍安全转账时进行介绍。默认使用"正常模式"。

# 创建钱包
如果你没有QTUM钱包，那么你可以通过web钱包提供的创建文件钱包或者创建密语钱包来创建一个新钱包。在web钱包里面，一个钱包也就是一个QTUM地址。

## 创建文件钱包
文件钱包实质上是一个保存使用密码加密了的wif的文件。

1. 选择"创建新钱包"按钮。
2. 弹出一个密码框。这个密码框输入的密码是用来加密你的浏览器给你生成的私钥的，请谨慎输入并牢记。如果丢失那么你的加密文件没有任何办法能够解锁。
3. 输入密码完成后，会看到一个按钮，点击这个按钮，就能下载你的加密文件。以后可以使用[从加密文件恢复](#从加密文件恢复)功能恢复你的钱包。

## 创建密语钱包
1. 选择"创建密语钱包"按钮。
2. 弹出一个密码框，输入密码。这个密码将会跟你后续生成的密语结合，生成你的钱包。此密码同样也是需要牢记的，如果丢失将无法恢复你的钱包。
3. 在输入完成密码后，记录下为你生成的密语。最好使用纸笔进行抄写并妥善保管。
4. 验证密码和密语。

# 恢复钱包
如果之前创建过钱包，或者是在QTUM的其他钱包客户端上有钱包，或者使用了Ledger，则可以直接通过恢复钱包来操作你的钱包账户。

## 从加密文件恢复
1. 选择"从加密文件恢复"按钮。
2. 上传保存的加密文件。
3. 输入加密文件解锁密码。
4. 解锁成功。

## 从密语恢复
1. 选择"从密语恢复钱包"按钮。
2. 按顺序输入密语。注意，密语中的空格或者其它不可见字符也会被当做密语的一部分，如果是复制过来的，请特别注意。
3. 输入对应密码。
4. 解锁成功。

从密语恢复钱包，不论是输入什么样的密语和密码都一定能解锁出一个钱包来，所以如果输入结束后解锁出的钱包不是你期望的，那么请确认你的密语和密码，然后重试恢复。

## 从私钥恢复
如果打算在web钱包中解锁qt客户端钱包的地址，那么可以在qt客户端钱包中导出私钥，然后用这个模式恢复钱包。

1. 选择"从私钥恢复钱包"按钮。
2. 输入你的私钥。
3. 解锁成功。

## 从手机钱包恢复
如果你想在web钱包中解锁QTUM手机钱包的地址，那么可以使用这个模式恢复钱包。

1. 选择"从手机钱包恢复"按钮。
2. 输入秘钥，并解锁。
3. 由于手机钱包的一组秘钥对应多个地址，所以请在列出的地址中选择想要解锁的那个地址。
4. 解锁成功。

## 使用Ledger恢复
如果你使用ledger保存你的钱包，那么使用这个模式也可以操作你的账户。

1. 选择"使用Ledger"按钮。
2. 请确认你的Ledger是最新的软件版本，然后用usb连接到你的电脑。进入Qtum APP，然后点击页面上的按钮尝试连接。
3. 如果没有Qtum APP，那么请先[安装](https://www.ledgerwallet.com/apps/manager)。
4. 如果连接成功了，那么会看到地址选择界面。因为Ledger是可以解锁多个地址，所以需要先选择地址路径和地址。

# 查看钱包及备份
解锁钱包成功后，可以查看钱包信息。可以查看当前钱包的QTUM数量，以及token数量。也可以查看钱包的私钥。

同样，在解锁钱包后，也可以把钱包备份为加密文件的形式。

# 转账
解锁钱包成功后，就可以操作钱包，对钱包进行转账。

## 普通转账
1. 进入转账界面。
2. 填入要转账的地址，已经要转账的QTUM数量。
3. 转账手续费可以调整，不过如果调整得太小的话，也会存在转账交易不被接受的情况。 
4. 确认信息后，会需要你再次确认转账地址，避免转账错误。因为区块链转账转账错误后没法回滚。
5. 确认转账地址和数量后，会把签名后的交易展示出来，进行最后的确认。这个确认后，转账交易将会发出，没法撤销。
6. 如果转账成功，会有提示，并告诉你交易id，可以到QTUM浏览器上查询交易。

## 使用Ledger转账
使用Ledger转账，整个过程类似普通转账，不过有个区别是签名时需要在Ledger上进行确认。按照UI界面提示操作即可。

## Token转账
1. 如果要给Token转账，在转账界面下，在输入金额的那一栏，点击"QTUM"，可以切换要转账的Token。
2. 如果列表中没有要转账的Token，那么可以自己添加，输入Token的合约地址就可以添加。
3. 在Token转账模式下，需要填入Gas Price和Gas Limit，这两个值已经默认填好了。如果钱包中的QTUM数量太小，可以适当调低Gas Limit。不过不建议太低，如果太低的话可能会存在Gas不够的情况，这种情况会导致QTUM消耗了但是转账失败的情况。如果Gas Limit需要的Gas在转账后用不完，会以挖矿的形式退回，不用担心。

# 离线挖矿
解锁钱包后，可以对钱包当前地址委托进行相关操作。

## 添加委托
每个地址只能委托出一次，若当前地址已被委托，则不可再进行委托操作。委托具体流程如下：
1. 进入离线挖矿界面，点击添加按钮
2. 填写 **Super Staker** 地址，也可以选择性修改其他参数
3. 填写完成后点击确认即可发送合约，系统会反馈当前交易地址，用户可以点击查看交易详情
4. 在交易未被确认前，不可进行添加 / 删除操作
5. 待添加成功，点击刷新按钮，即可更新当前状态

## 取消委托
地址被委托后，也可以进行取消操作，具体操作流程如下：
1. 进入离线挖矿界面，点击取消按钮
2. 选择性修改合约参数
3. 点击确认即可发送合约，系统会反馈当前交易地址，用户可以点击查看交易详情
4. 在合约被确认前不可进行添加委托操作
5. 待取消成功后，点击刷新按钮，可再次进行添加委托操作