# 波场钱包的现在过去与未来


## 前言

区块链以及区块链钱包发展至今已超10年历程，期间大致经历了三个时期，区块链1.0时期大家对钱包的需求更多的是全节点钱包挖矿和管理BTC等资产。到了ETH区块链2.0时期，区块链钱包需要管理多种类型的代币以及与智能合约的交互，此时无需同步全节点的轻钱包成为了大家的首选，例如MetaMask。到了区块链3.0，随着公链的发展，钱包的功能和复杂程度也逐渐增加，不在仅限于资产的储存和管理，更多是充当整个公链最重要的生态服务平台，同时大家对于随时随地与区块链交互的场景也越来越多，移动钱包成为大家的首选。至此越来越多的公链钱包由此诞生，其中就包括波场钱包。

波场（TRON）一直是国产公链热门项目，随着波场主网的不断优化和改进，波场公链每秒交易速度（TPS）已提升至万级，公链性能不断提升，进而可以支持更多的应用场景，并且通过用户免费使用和激励的方式，更大限度地调动了生态参与者的积极性。波场（TRON）近两年的发展可以说非常迅速，凭借其开发和使用成本低、交易性能优越的优势，波场吸引了众多用户和开发者，波场DApp用户数量和交易笔数一直稳居公链前三。

波场钱包作为波场公链生态中极为重要的入口，是波场生态的重要构成要素。波场钱包发展至今，其功能和玩法不断创新改进，以实现更方便、更友好地让用户体验波场生态。从一开始只提供权限管理、转账收款、节点投票等基础功能，到如今不仅可以为用户提供法币交易、闪兑和去中心化交易所等方便快捷的交易服务，还能让用户直接在钱包上体验波场上丰富的DApp，享受挖矿、DeFi、Staking等资产增值服务。波场钱包正在为波场用户提供不断优化的丰富生态体验。




## 波场（TRON）账号与钱包

### 免费创建TRON钱包

TRON账号是一串由34个字母和数字组成的字符串，用户可以免费注册。与 EOS/IOST 的单独注册名字的账号不同，用户在创建TRON账号之后会得到一个随机生成的账号。

用户第一次创建账号时，只需设置钱包名称和登陆密码，抄写下钱包私钥即可，非常方便。


**新账户创建完毕后，需要进行账户激活才可以正常使用该账户。账户激活只需要其他地址向此地址转入任意数量的TRX即可。**

![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597372398823.png "钱包类别")
<center>TokenPocket TRON钱包创建页面</center>

### 账号私钥导入TRON钱包

如果用户之前已有波场钱包，可以通过TP钱包中的“私钥导入”进行添加，用户通过输入明文私钥或扫描私钥二维码，即可添加原有钱包。

![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597372928552.png "钱包类别")


### TRON账号带宽与能量的冻结/解冻操作 

**带宽**

带宽（Bandwidth Points）是一个账户可用发送交易的字节数，系统每天免费赠送每个激活账户5000 BP 的带宽资源。若用户转账交易比较频繁，需要冻结TRX获得额外的带宽，当然，没有带宽也不影响正常使用，系统会消耗一定的TRX作为手续费来保障账号正常使用。TRON新创建的账户尚未激活，需要其他地址向此地址转入任意数量的TRX，随后在资源页面可看到当前的能量和带宽资源。

**能量**

能量（Energy）是运行智能合约的过程中消耗的处理器资源。它和带宽一样，都可以通过冻结TRX而取得，但每天并不会有免费的能量被分配到每个账户。用户在使用DApp的时候会消耗能量，与获得带宽相同，用户也可以直接通过消耗TRX支付交易消耗的能量。


**TRON账号冻结**

在TRON中，一个账户可以通过冻结TRX来获取带宽和能量。同时，也可以把冻结TRX获取的带宽或者能量委托（delegate）给其他地址。此时，主账号拥有冻结的TRX以及相应的投票权，受委托账户拥有冻结获取的资源（带宽或者能量）。和普通冻结一样，委托资源也至少冻结3天。
![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597373348039.png "钱包类别")

**TRON账号解冻**

冻结三天后方可进行解冻操作，解冻后相应的资源（能量/带宽）也会被移除，解冻后的TRX可以正常用于交易。需要说明的是，如果用户冻结TRX对节点进行了投票，那么在解冻时，用户获得的TRON Power也会自动扣除，即所投的节点投票也将自动撤销。


## TRON Token与钱包

### TRX Token

#### TRX Token发行

TRONIX是由波场基金会发行的基于波场协议的主网货币，简称TRX。

TRX是TRON区块链上账户的基本单位，所有其他代币的价值均从TRON价值衍生出来，TRX也是所有基于TRC标准代币的天然桥梁货币。TRX贯穿于整个波场生态体系中，具有丰富的使用场景，为链上的交易和应用提供动力。

波场协议网络每3秒生成一个区块，每个块将16个TRX授予出块的超级代表， 每年将向27位超级代表奖励约168,192,000 TRX。波场协议网络每生成一个区块， 127名超级代表和合伙人将按照获得的投票比例瓜分160TRX，每6小时共产生奖励1152000TRX，每年投票的总奖励额约为 1,681,920,000 TRX。超级代表和合伙人获得的投票奖励也会根据佣金比例扣除后按照选民投票比例自动分配给选民。

TRX通证的作用包括投票、部署智能合约等。TRX转账无需用户支付手续费，根据消耗带宽的多少销毁相应数量的TRX。

#### TRX 获取
用户可以通过币币闪兑、法币购买（币买卖）和交易所交易这三种方式来获得 TRX 。

**交易所交易**

TRX 作为一条主流公链代币，基本上主流的交易所都已支持，例如币安、火币、OKEx 等多家交易所，在这些交易所都可以通过交易获得 TRX 。

**币币闪兑**

币币闪兑顾名思义就是币币闪电兑换，即可以通过其它 Token 来快速兑换 TRX ，闪兑不同于一般交易所的订单撮合模式，它更像银行柜台模式，只要是闪兑支持的 Token，都可以快速完成两两兑换操作，交易速度很快，几乎是实时完成兑换的。
![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597373882574.png "钱包类别")

**法币购买**

在 TokenPocket 中，可以通过币买卖使用法币买入 TRX ，交易完成后的 TRX 将会直接转入你的 TRON 钱包中。

![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597374073106.png "钱包类别")

### TRON 上的其他Token介绍

TRON网络支持两种通证，一种是通过智能合约发行的TRC20协议的通证，一种是通过TRON公链内置的TRC10通证。 

TRC-10是TRON区块链本身支持的技术代币标准,没有使用TRON虚拟机(TVM), 在TRON网络中，每个帐户都能够以1024 TRX为代价发行代币。 用户可以单独锁定其代币。 要发放代币，发行者需要指定代币名称、总大小、TRX的汇率、流通时长、描述、网站、每个帐户的最大带宽消耗，总带宽消耗和代币冻结。

TRC20是为发行通证资产而制定的一套合约标准，即遵守这一标准编写的合约都被认为是一个TRC20合约。当各类钱包、交易所在对接TRC20合约的资产时，从这套合约标准中就可以知道这个合约定义了哪些函数、事件，从而方便的进行对接。

目前市面上的波场钱包（如TokenPocket，TronLink）都是同时支持 TRC-10 协议和TRC-20协议的。


#### TRON-USDT

TRC20 协议 USDT 是 Tether 泰达公司基于波场网络发行的锚定美元的稳定币。TRON-USDT将利用智能合约完成在波场链上的发行、持有、转账，完全公开透明，零转账费，秒级到账。

![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597374164567.png "钱包类别")

实现了与基于TRON协议和分布式应用（DAPP）的互通性，同时允许用户在TRON网络上交易与交换法定挂钩货币。

在费用上，TRC20-USDT在抵押足够能量的情况下能够实现免费转账。主流交易所的提币费用显示，基于Omni协议的USDT提币手续费最为高昂，需要4-10美元不等，ERC-20的手续费为1美元-5美元不等，而TRC20-USDT的提币手续费为0，这意味着用户可以享受免手续费的交易所提币服务。

交易确认速度上，基于波场网络发行的USDT发挥了第三代公链的性能优势，波场网络的TPS能够达到上千级别，可以实现交易秒级确认，大幅优于Omni（转账确认需要十分钟到数天不等）和ERC20(数分钟到数小时)。极快的转账速度能够满足稳定币用户多种多样的需求，避免了因网络拥堵造成投资者利益的损伤。

TRON-USDT 转账速度快、零手续费的特点已经吸引了大批用户，且已经获得了Binance、Huobi、OKex、KuCoin等多家交易所的支持。

TokenPocket 对 TRON-USDT 的支持是全方位的，例如可以使用闪兑功能把 TRON-USDT 兑换为其他版本的 USDT 或其他 Token；在 TP 的中心化钱包中还可以进行 TRON-USDT 的充提、转账以及购买 USDT；在TP的去中心化钱包中进行转账、收款以及查看代码详情。

更多关于TRC20-USDT的信息，请参考官网：https://tron.network/usdt。

![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597374224375.png "钱包类别")

#### TRON 与稳定币 USDJ

USDJ通过波场网络中的去中心化智能合约发行，任何人都可以通过在JUST借贷平台抵押TRX生成USDJ。当USDJ被生成之后，通过抵押债仓（CDP）和自动化反馈机制支撑USDJ的价格稳定在和美元保持1:1，从而与其他任何数字资产一样自由流通。

![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597374280083.png "钱包类别")

JUST是一个去中心化借贷平台，采取了双代币系统。第一个代币USDJ是按1：1的汇率与美元挂钩的稳定币，是通过JUST的CDP门户抵押TRX产生的。第二个代币JST，可用于支付利息，平台维护，通过投票参与治理以及JUST平台上的其他活动。

![钱包类别 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597374326098.png "钱包类别")

可以通过 TokenPocket 进入 JUST-DeFi 平台，然后通过抵押 TRX 获得稳定币 USDJ。


#### TRON 与 BTT

BTT币英文全称是BitTorrent。BitTorrent是由Bram Cohen于2001年发明的一种开创性的分布式通信协议。 BTT是一种点对点协议，使用经济激励来使在互联网上传输容量大且需求量大的文件更容易，从而消除了人们对可信度高的中央服务器的需求。

BitTorrent(BTT)是由BitTorrent推出的 TRC-10 加密代币，作为一种通用机制，用于交易 BitTorrent 客户端与任何其他参与服务请求者和服务提供者之间共享的计算资源。 BTT是在支持BTT的BitTorrent生态系统中提供不同服务的主要交易单位， BTT作为可分割代币，允许对流动市场中服务请求者和服务供应商所提供的服务进行非常精细的定价。

BTT代币用途：
（1）与代币钱包、竞价引擎一同运作，允许客户端针对带宽进行要价和接受报价；
（2）用户可直接使用BTT从内容创作者处购买和下载资源；
（3）观众在直播中可用BTT代币等礼品打赏表演者；
（4）用于众筹，使用智能合约托管项目资金；
（5）用于存储、运算、资源供应、内容分发CDN等服务付费。


DLive是由BitTorrent和TRON基金会支持的区块链上最大的实时媒体直播社区，用户可以在DLive上发现精彩的游戏和频道，并通过观看DLive上的内容来获得收益。

DLive每天捐赠和订阅总营收的25%用于BTT Staking的奖励，该功能是DLive的独特功能，旨在通过激励人们参与平台的整体发展来回馈社区。

可以通过 TokenPocket 进入 DLive BTT 质押分红应用。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597374529751.png "节点钱包")

#### TRON NFT Token

TRON 的 TVM 虚拟机几乎完全兼容以太坊的 EVM 虚拟机，并针对 TRON 的特性提供了若干扩展。所以 NFT 对应的 ERC777 等 NFT Token 标准可以无缝迁移到 TRON 上。

### 发行基于波场公链的代币
当前，开发者如需发行TRC10代币，可以采用调用createassetissue接口进行代币发行；如需发行TRC20代币发行方式，可以通过部署TRC20合约到TRON网络完成发币。

### TRON Token交易平台

在波场公链上发行的 Token，可以在波场去中心化交易所进行交易，而在众多的波场去中心化交易所中，交易量比较大的有 Poloni DEX、TronTrade、Newdex-TRON。从支持波场去中心化DApp的波场钱包（如TokenPocket），用户可以很便捷地进入这些交易所进行交易，

（1）Poloni DEX
PoloniDEX 隶属于P网Poloniex，是基于波场 TRON 的去中心化交易平台，零手续费。P网（Poloniex）成立于2014年，是注册于塞舌尔的一家全球化领先数字资产交易平台，自Poloniex 创立以来，安全高效的服务便得到用户的认可，真实交易量长期位列全球TOP3，独创的TrollBox系统让用户获得更有趣的交易体验。P网的愿景是重构全球信任体系，让交易触达每个角落，解放价值，使价值自由流动。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597377359244.png "节点钱包")

（2）TronTrade
Trontrade 是一个基于波场的去中心化交易平台，你可以在其中轻松买卖各种TRC10和TRC20加密货币。 TronTrade的目标是成为TRC10和TRC20代币的最安全、对用户最友好和可靠的去中心化交易所。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597377400565.png "节点钱包")

3）Newdex-TRON：全球领先的去中心化交易所
Newdex成立于2018年8月8日，首发于EOS公链，2019年8月，Newdex除了运行在EOS公链上，同时也开始支持TRON公链，从此，Newdex将积极布局"多链、跨链"等去中心化交易平台。 

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597377450795.png "节点钱包")

## TRON钱包使用场景

### TRON Token转账

在 TRON 钱包中，最基础的功能就是转账和收款了。普通的转账不收手续费，但是会消耗BP（即带宽资源），冻结TRX可以获取带宽。

#### (1）三种不同的转账操作

**● 普通转账（TRON 账号互转）**

普通转账指的是独立的 TRON 账号之间的转账，只需输入接收方 TRON 账号以及转账数量。

**● 从交易所账号转账到 TRON 账号（钱包账号）**

从交易所转账到 TRON 账号（钱包账号）即从交易所把 TRON 提币出来，提到自己独立的 TRON 账号中，只需输入提币地址（TRON 钱包账号）、提币数量，就可以完成提币。

**● 从 TRON 账号（钱包账号）转账到交易所账号**

用户从 TRON 账号（钱包账号）转到交易所，只需输入交易所地址和充币数量，就可以完成充值。

#### （2）丰富便捷的转账形式

为了更好的方便用户进行转账收款操作，TRON 钱包提供直接转账、地址簿转账和扫码转账等多种形式满足用户不同的需求。

**● 直接转账**

直接转账指的是 TRON 地址之间的转账。用户只需输入收款 TRON账号和转账数量，点击“确认”即可完成。

**● 地址簿转账**

地址簿就像我们手机中的电话簿，创建完地址簿后，如果要转账就可以到地址簿中选择相应的收款 TRON 账号。如果你经常向某个 TRON 地址转账，可以将该地址添加到钱包的地址薄，在转账的时候可以直接选择地址薄转账，这样不仅省时，还可以避免出现地址填错的安全问题。

**● 扫码转账**

类似微信、支付宝二维码收付款，通过扫描收款二维码，即可向指定账号转账。
另外，还可以通过最近转账功能进行转账，点击"最近转账"后，就会在转账界面中自动填充该 TRON 地址，如果经常向一个 TRON 账号进行转账时，使用该功能就比较方便。

总之，无论是地址簿转账，还是扫码转账以及通过最近转账交易记录转账，都可以在一定程度上防止由于手动输入账号错误所造成的不必要的损失。

**● 使用TRON观察钱包和冷钱包进行转账**

如果用户钱包里长期存放大额资产并有经常的转账的需求，建议使用观察钱包+冷钱包的方式进行转账，以保证资产安全。所谓冷钱包，就是用网络物理隔离的方式（例如一台完全断网的手机）让用户的私钥和助记词不触网，以保证用户的数字资产接近 100% 安全。观察钱包即可以观察其他地址中资产变化情况的钱包。它不需要导入私钥，只需导入账号或公钥，通过观察钱包，可以进行日常查看账号的交易记录。

在进行转账时，用户先在观察钱包发送操作。与平时转账不同的是，需要授权的时候，会弹出一个二维码。这个时候拿出冷钱包扫码，扫码以后会生成另一个二维码，此时需要用观察钱包再次反向扫码冷钱包，从而完成整个转账操作流程。 

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597395488137.png "节点钱包")

### TRON Token收款

在 TRON钱包内，用户还可以进行资产收款或交易所提币。

**● 地址收款**

在收款界面，用户可以一键复制自己的收款地址，方便自己从交易所提币或对方向自己转账，方便又安全。

**● 二维码收款**

和上文扫码转账类似，对方通过扫描收款二维码即可向自己进行转账。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378052327.png "节点钱包")


### TRON 节点投票

超级代表：会有出块和打包交易的义务，同时也会获得相应的投票和出块奖励，并且有权利参与波场TRON委员会提议的投票。

超级代表合伙人：可以获得投票奖励。

选民：参与进行投票的波场TRON社区生态成员。

投票分成比例：超级代表和超级代表合伙人所获得的奖励中，分给投票者的比例。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378366089.png "节点钱包")

#### 1、TRON 投票规则

每个用户可一次或多次投票给多个候选人，每个候选人可以投多票;

投票前用户需冻结一定数量的TRX，以获得TRON Power（投票权），冻结的 TRX 不能流通，也不能用于交易转账。

冻结1个TRX可获得1个TP，1个TP等于1票。

每6个小时为一个投票周期，当日世界时间0:00，6:00，12:00和18:00将不断更新投票结果与节点列表，更新的投票会在下一个投票周期开始生效。

#### 2、TRON 赎回规则

在进行撤票操作时，既可以撤销对一个节点的所有投票，也可以撤销部分投票。需要说明的是，每次冻结达到3天后即可进行解冻，可以按照冻结时所获取的资源不同，分别进行解冻，但必须确保为获取这一资源而冻结的所有TRX都达到3天才能执行。

解冻后，冻结所获得的TP，带宽（或者能量）等资源，均将被移除。

解冻后，已投票的TP亦将被移除，此时您需要重新冻结TRX获得TP再次进行投票，以确保您的投票权益不受影响。

#### 3、TRON 投票奖励规则

在TRON网络中，任何TRX持有者都可以申请成为超级代表候选人，都有机会成为超级代表或者超级代表合伙人。每个TRX持有者都可以投票给超级代表候选人，获得投票数最高的前27名候选人将成为超级代表，第28～127名成为超级代表合伙人。超级代表有出块和打包交易的义务，同时也会获得相应的投票和出块奖励。超级代表合伙人不参与出块和打包交易，仅可以获得投票奖励。

超级代表投票分成比例不一，由超级代表自行决定分配。

奖励计算公式：

理论上，波场TRON SR每天产块的总数量为28792，所以每个SR每天的产块数量为1066个，波场TRON网络的SR的佣金比例为20%，针对每个SR的出块奖励为16个，投票奖励为160个，总票数为22,382,488,418（实时）。

SR单日总收益 =（SR每天产块数*单块出块奖励+全网每天总产块数*单块投票奖励*SR获得票数/总票数）

SR佣金收益 =SR单日总收益 * SR佣金比例

选民可分配收益 = SR单日总收益 - SR佣金收益

#### 4、多种投票方式

通过 TRON 钱包投票

在 TRON 钱包的投票页面选择要投票的节点，点击后面的"投票"按钮，并输入参与投票的 TRX数量就可以进行投票了。这也是最方便、最快捷的投票方式。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378520680.png "节点钱包")

通过网站进行投票

登陆网站 https://tronscan.io/ ，在它的"投票"页面中选择要投票的节点，然后点击"投票"按钮就可以完成投票了。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378585220.png "节点钱包")

### TRON 资产归集

TRON 底层支持的资产归集功能是多账号用户的福音，其本质就是批量转账，当用户手中的 TRON 账号比较多而且每个账号中有小额资产时，可以使用资产归集功能把多个 TRON 账号中的小额资产归集到一个账号中，方便进行资产管理。

对用户来讲，需要将所有账号全部导入钱包中，若涉及到的账号对应的密码相同，则只需授权一次；若密码不同，则需授权若干次。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378684926.png "节点钱包")

### TRON 钱包白名单设置

白名单功能为用户更好地使用 DApp 提供了极大的便利。通常用户在体验 TRON Dapp 时，由于智能合约和用户的操作进行交互， 每次相同操作都需要填写密码，十分不便。白名单功能是针对DApp 内特定的智能合约操作进行免密授权，只需在开启白名单功能时需要输入密码，之后的同一操作均可免输入。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378745373.png "节点钱包")

### TRON 浏览器使用

区块链浏览器是浏览区块链信息的主要窗口，每一个区块所记载的内容都可以从区块链浏览器上进行查阅。

目前，常用的TRON浏览器是TRONSCAN。tronscan.io 是基于波场的第一款区块浏览器。不仅包含区块浏览器的一些基础功能如搜索查询交易、账户、区块、节点、智能合约；链上数据统计和查询，还直接支持token创建。同时TRONSCAN还有内置web wallet和基于Bancor的DEX，更加丰富了TRONSCAN的应用矩阵。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378790438.png "节点钱包")

### TRON 钱包排序调整

很多用户会有多个 TRON 账号，自己常用的钱包位置比较靠后，这样使用起来十分不便。钱包排序功能可以轻松解决这一痛点。用户通过对账号拖拉调整钱包账号顺序，把经常使用的账号位置提前，更方便日常钱包切换与资产管理。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378837530.png "节点钱包")


### TRON 测试网参与

TRON测试网络与主网是相对而言的。TRON主网是指正式上线、可以独立运行的区块链网络，具有真实的经济价值。波场测试网络就是主网的前身，与主网功能相似，主要是用作项目快速开发迭代以及社区成员早期参与。波场项目社区成员以及支持者在测试网络中参与验证、挖矿等各个流程，并在次过程中发现、反馈不足；TRON项目方技术团队以此不断进行修正完善，为主网的亮相做好铺垫。

常用的TRON测试网有TRONLIN，支持波场测试网和SUN Network，能够及时更新项目开发迭代及用户早期参与，处于非常稳定的状态。


![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378879023.png "节点钱包")

另外，Nile测试网(http://nileex.io)也较为常用，Nile测试网的代码版本与TRON主网保持一致，用起来也很不错。

### TRON 相关资讯获取

对于TRON用户来讲，关注TRON的最新进展可以通过其官方账号进行关注，TRON国内外都有官方账号，公众号“波场TRON”，微博账号“波场TRON区块链”，推特账号“@Tronfoundation”，波场TRON创始人孙宇晨也有账号，微博账号“孙哥区块链”，推特账号“@justinsuntron”，这些都是用户第一时间了解TRON的最佳渠道。

此外，用户还可以通过TRON钱包来浏览关于TRON的最新资讯，例如 TokenPocket钱包，所有关于TRON的最新消息、快讯和文章，都第一时间一站式收录在钱包的快讯和文章频道，优化了用户的阅读体验。

![节点钱包 示意图](https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597378959783.png "节点钱包")


### TRON DApp体验

TRON钱包是TRON社区用户进入TRON DApp的入口，可以满足用户各种各样的应用体验需求。DApp是Decentralized Application的缩写，意为去中心化应用，是以区块链为底层进行的应用开发。

基于波场公链优秀的性能、出色的安全性以及低廉的费用，波场公链已经吸引数百上千的社区开发者进行DApp的开发、部署和链上运营，截止到2020年Q1，波场链上的DApp总数超过700个，活跃用户超过23万。

### TRON钱包未来发展

过去两年时间，可以看到波场从公链基础研发，公链生态发展再到公链应用一步步走过来。波场团队秉持“日拱一卒，不期速成”的理念一直在区块链行业奋斗着，抓准机会，推动落地，快速超越大量的公链团队。波场的未来不仅仅在于公链性能的进一步提升，同构、异构的跨链，安全与隐私的增强。对于BitTorrent以及Dlive等的布局，波场从公链上的打法不是从零开始，因此更看重波场未来会成为链接现存互联网产品与区块链服务的桥梁，真正构建价值互联网时代。

### TRON开发者与钱包

对于开发者，TRON一定是现阶段非常值得关注的一条公链，建立在其性能和生态的基础上, 已经出现了很多用户量和交易量都很大的DApp。TRON强大的共识机制使其在TPS方面超越了比特币和以太坊，高TPS保证了低计算延迟，这使得交易速度能够与现有的支付系统竞争。由于TRON网络的可扩展性和高效的智能合约，允许在TRON中部署各种应用程序，TRON采用低计算成本的设计，使TRON上的不同应用程序更容易扩展其用户群并具有商业竞争力。目前从合约和交易体验上来讲，TRON相比ETH有比较大的优势，同时，从用户进入门槛和合约开发门槛上，TRON新用户几乎不需要成本，和其支持Solidtiy的TVM，TRON相比EOS也有显著优势。为使开发者更清晰的使用TRON主网，TRON社区成员特此制作了TRON开发者入门指南， 提供了完整的工具链为开发者提供合约开发，测试，部署，接口，波场开发者中心：https://cn.developers.tron.network/。 与此同时，波场钱包也为TRON开发者提供开发者工具，为项目开发带来了便利，协助开发者共同参与促进波场生态的建设。

以 TokenPocket 钱包为例，TP 钱包为 TRON 开发者提供 Android 和 iOS 移动 SDK，开发人员可用 SDK 唤起 TP 钱包进行钱包账号的授权登陆，执行合约操作等。TP 钱包内部 Webview 内置 tronWeb 对象，可以直接在钱包内 Dapp 浏览器内输入 URL 即可开发测试基于 TRON 开发的各种 DAPP，实现在 TP 钱包内 Dapp 浏览器内唤起授权签名等操作。
总之，TRON 因其良好的性能和每日免费的资源额度，为更精良的 DApp 的产生和大规模使用提供了可能。同时钱包为TRON开发者提供了方便的开发调试工具。二者共同为更好的应用级公链作出自己的贡献。

相关钱包协议、SDK 链接：

https://github.com/TP-Lab/TokenPocket-Protocol

https://github.com/TP-Lab/mobile-sdk

https://github.com/TP-Lab/tp-js-sdk






## TRON 钱包分类


### 去中心化钱包

<!-- 1 -->

<main class="tp-main">
<!-- TokenPocket -->
<a class="tp-custom" href="https://www.tokenpocket.pro" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/TokenPocket-20211201.png"/>
    <div class="tp-content">
        <h5>TokenPocket</h5>
        <p>https://www.tokenpocket.pro</p>
    </div>
</a>


<!-- Tronlink -->
<a class="tp-custom" href="https://www.tronlink.org" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Tronlink.png"/>
    <div class="tp-content">
        <h5>Tronlink</h5>
        <p>https://www.tronlink.org</p>
    </div>
</a>
</main>

</main>

<!-- 2 -->

<main class="tp-main">
<!-- imToken -->
<a class="tp-custom" href="https://token.im" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ImToken.png"/>
    <div class="tp-content">
        <h5>imToken</h5>
        <p>https://token.im</p>
    </div>
</a>

<!-- Cobo金库 -->
<a class="tp-custom" href="https://cobo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Cobo.png"/>
    <div class="tp-content">
        <h5>Cobo金库</h5>
        <p>https://cobo.com</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- Trust Wallet -->
<a class="tp-custom" href="https://www.trustwallet.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/TrustWallet.png"/>
    <div class="tp-content">
        <h5>Trust Wallet</h5>
        <p>https://www.trustwallet.com</p>
    </div>
</a>

<!-- Huobi -->
<a class="tp-custom" href="https://www.huobiwallet.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/HuobiWallet.png"/>
    <div class="tp-content">
        <h5>Huobi Wallet</h5>
        <p>https://www.huobiwallet.com</p>
    </div>
</a>
</main>

<!-- 4 -->

<main class="tp-main">
<!-- Bitpie -->
<a class="tp-custom" href="https://bitpie.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Bitpie.png"/>
    <div class="tp-content">
        <h5>Bitpie</h5>
        <p>https://bitpie.com</p>
    </div>
</a>


<!-- Math Wallet -->
<a class="tp-custom" href="http://www.mathwallet.org" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/MathWallet.png"/>
    <div class="tp-content">
        <h5>Math Wallet</h5>
        <p>http://www.mathwallet.org</p>
    </div>
</a>
</main>

<!-- 5 -->

<main class="tp-main">
<!-- TronWallet -->
<a class="tp-custom" href="https://www.tronwallet.me" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Tronlink.png"/>
    <div class="tp-content">
        <h5>TronWallet</h5>
        <p>https://www.tronwallet.me</p>
    </div>
</a>

<!-- AToken -->
<a class="tp-custom" href="https://www.atoken.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/AToken.png"/>
    <div class="tp-content">
        <h5>AToken</h5>
        <p>https://www.atoken.com</p>
    </div>
</a>
</main>

<!-- 6 -->

<main class="tp-main">
<!-- Starteos -->
<a class="tp-custom" href="https://www.starteos.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Starteos.png"/>
    <div class="tp-content">
        <h5>Starteos</h5>
        <p>https://www.starteos.io</p>
    </div>
</a>


<!-- Infinito -->
<a class="tp-custom" href="https://www.infinitowallet.io " target="_blank">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597389439939.svg"/>
    <div class="tp-content">
        <h5>Infinito</h5>
        <p>https://www.infinitowallet.io </p>
    </div>
</a>
</main>

<!-- 7 -->

<main class="tp-main">
<!-- BitKeep -->
<a class="tp-custom" href="https://www.bitkeep.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Bitkeep.png"/>
    <div class="tp-content">
        <h5>BitKeep</h5>
        <p>https://www.bitkeep.com</p>
    </div>
</a>

</main>

### 硬件钱包
<!-- 1 -->
<main class="tp-main">
<!-- 库神 -->
<a class="tp-custom" href="https://www.coldlar.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ColdLar.png"/>
    <div class="tp-content">
        <h5>库神</h5>
        <p>https://www.coldlar.com</p>
    </div>
</a>

<!-- Ledger -->
<a class="tp-custom" href="https://www.ledger.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Ledger.png"/>
    <div class="tp-content">
        <h5>Ledger</h5>
        <p>https://www.ledger.com</p>
    </div>
</a>
</main>

### 插件钱包

<!-- 1 -->
<main class="tp-main">
<!-- Tronlink -->
<a class="tp-custom" href="https://chrome.google.com/webstore/detail/tronlink%EF%BC%88%E6%B3%A2%E5%AE%9D%E9%92%B1%E5%8C%85%EF%BC%89/ibnejdfjmmkpcnlpebklmnkoeoihofec" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Tronlink.png"/>
    <div class="tp-content">
        <h5>Tronlink</h5>
        <p>https://chrome.google.com/webstore/detail/tronlink%EF%BC%88%E6%B3%A2%E5%AE%9D%E9%92%B1%E5%8C%85%EF%BC%89/ibnejdfjmmkpcnlpebklmnkoeoihofec</p>
    </div>
</a>

<!-- GuildWallet -->
<a class="tp-custom" href="https://chrome.google.com/webstore/detail/guildwallet/nanjmdknhkinifnkgdcggcfnhdaammmj" target="_blank">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597391720047.png"/>
    <div class="tp-content">
        <h5>GuildWallet</h5>
        <p>https://chrome.google.com/webstore/detail/guildwallet/nanjmdknhkinifnkgdcggcfnhdaammmj</p>
    </div>
</a>
</main>

<main class="tp-main">
<!-- Math Wallet -->
<a class="tp-custom" href="https://chrome.google.com/webstore/detail/math-wallet/afbcbjpbpfadlkmhmclhkeeodmamcflc" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/MathWallet.png"/>
    <div class="tp-content">
        <h5>Math Wallet</h5>
        <p>https://chrome.google.com/webstore/detail/math-wallet/afbcbjpbpfadlkmhmclhkeeodmamcflc
</p>
    </div>
</a>

<!-- Math Wallet -->
<a class="tp-custom" href="https://chrome.google.com/webstore/detail/tronmask/egfbimboljdebhepefdiolkpdbiaaggp" target="_blank">
    <img class="tp-logo" src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597391805093.png"/>
    <div class="tp-content">
        <h5>TronMask</h5>
        <p>https://chrome.google.com/webstore/detail/tronmask/egfbimboljdebhepefdiolkpdbiaaggp</p>
    </div>
</a>

</main>


## TRON 钱包知识自测


<div class="ask-code">
<a href="https://ks.wjx.top/jq/82501428.aspx">https://ks.wjx.top/jq/82501428.aspx</a>

</div>
<img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597390963715.png" width="250">

## TRON钱包常见问题
<div class="ask-code">
<img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1597390895476.png" width="250">

</div>
<a target="_blank" href="https://help.mytokenpocket.vip/hc/zh-cn/sections/900000370926-TRON%E9%92%B1%E5%8C%85%E9%97%AE%E9%A2%98
">https://help.mytokenpocket.vip/hc/zh-cn/sections/900000370926-TRON%E9%92%B1%E5%8C%85%E9%97%AE%E9%A2%98
</a>

### TRON联系方式
TRON官网：https://tron.network/

公众号：波场TRON

微博：波场TRON区块链

Twitter: https://twitter.com/Tronfoundation

Telegram: https://t.me/tronnetworkEN

GitHub: https://github.com/tronprotocol

Medium: https://medium.com/tron-foundation


### 版权申明

#### 《波场钱包的现在过去与未来》，又称为波场钱包小白书。由 TokenPocket 联合TRON官方，以及 TokenPocket 社区志愿者（TP 侠：阿华、马云儿、币范儿）共同撰写，详细介绍了当前TRON钱包与TRON生态密切结合的实例，是目前市面上最为详细的TRON数字钱包科普资料。


##### 1.本文版权归TokenPocket所有。

##### 2.在征得作者同意的情况下，作品允许非盈利性引用，需要注明并请注明出处和作者，以尊重作者的劳动成果。

##### 3.出处：https://tp-lab.github.io/BlockchainGuide-TRON/  作者：TokenPocket。

##### 4.未经允许，严禁转载。对非法转载者，TokenPocket和作/译者保留采用法律手段追究的权利。

##### 5.对于本文和本声明以及其修改权、更新权及最终解释权均属TokenPocket。

##### 6.以上声明的解释权归“TokenPocket”所有。
