# DeFi  🚀

## 传统金融机构

### 银行：
作用：通过提供价值转移（存、取、转账）、提高信贷额度（贷款）等服务，使资金能在世界流转

缺点：
容易受到human-related风险

Defi优化了：
1.支付和清算系统（汇款）
2.可获取性
3.中心化和透明度

- 1.支付与清算系统

	- 银行：
1.时间久
2.手续费高
3.可能涉及证明文件、反洗钱、隐私等法律
	- 加密货币：
1.交易速度快
2.手续费低
3.交易无条件处理

- 2.可获取性

	- 银行：
1.验证流程冗长
2.贫困地区难申请
	- Defi：
1.流程简单
2.无国界、无障碍、无审查

- 3.中心化&透明度

	- 中心化金融的缺点：
1.权利、资金集中
2.投资者无法充分了解金融机构的运作

## Defi是什么

### 1.Defi是一场能让用户无需依靠中心化实体的金融服务运动
2.Dapp提供这些金融服务
3.大部分应用部署在以太坊平台上
4.用户通常需要将抵押品锁定在智能合约中
5.Dapp中锁定抵押品累计价值被称为锁定总价值

- Defi生态
- Defi的去中心化程度如何

	- 中心化

		- 特征：
托管、中心化喂价（centralized price feeds）、中心化地决定利率、追加保证金时中心化地注入流动性

	- 半去中心化

		- 拥有一个或多个，而非全部上述特征

	- 完全去中心化

		- 目前还没有完全去中心化的Defi协议

- Defi的主要类别

	- 稳定币

		- 1.为缓和加密货币的剧烈波动，锚定美元等稳定资产而被创造出来。
2.比如USDT，每枚USDT在其发行机构账户上都有1美金作为背书。
3.去中心化稳定币是通过超额抵押（overcollateralization）的方法以去中心化形式创建，完全在去中心化账本上运行，由去中心化自治组织管理。其准备金可以由任何人公开审计。
4.稳定币是稳定的价值存储手段。

	- 借贷

		- 去中心化借贷的一些优势：
1.取消信用评级
2.无需抵押品
3.无需银行账号
4.通过抵押数字资产获得贷款
5.把数字资产注入借贷池获得收益

	- 交易所

		- 中心化交易所：
Coinbase、Binance

			- 交易资产的中介、托管方
			- 交易所用户不能完全控制资产
			- 交易所可能被攻击或无法偿还债务

		- 去中心化交易所

			- 用户无需存入资产

	- 衍生品

		- 衍生品是一种价值来源于股票、商品、货币、指数、债券或利率等其它标的资产的合约

	- 基金管理

		- 基金管理是监管你的资产并管理其现金流以产生投资回报的过程

			- 传统基金管理

				- 主动型：管理团队/经理决策
				- 被动型：指数决定

			- Defi

				- 被动型

	- 彩票

		- 1.Defi的彩票可将资金次的托管转移到以太坊的自能合约上。
2.比如：将参与者资金汇集到一起，再将汇集的资金投资到Defi的贷款Dapp中。以设定的时间间隔将利息交给中奖者。选中中奖者后，所有购买者将拿回下注的资金

	- 支付

		- 进行无需信任、去中心化的转账

	- 保险

		- 所有智能合约中锁定的代币都容易受到智能合约漏洞的影响，永远无法知道该智能合约是否真的安全

## 去中心化层：以太坊

### 以太坊：面向去中心化应用的全球开源平台

- 大部分Dapps搭建在以太坊区块链上
- 开发人员可以在以太坊上编写智能合约，
智能合约通过一套标准对数字价值（digital value）进行控制
- 世界上任何地方可以访问
- 软件工程师编写的智能合约是这些Dapps的组件，这些智能合约被部署到以太坊网络，并在网络中全天候24小时运行。该网络会持续维护数字价值账本，并跟踪其最新的状态。

### 智能合约：可编程合约

- 允许交易双方设置交易条件
- 交易的执行无需信任第三方
- 遵循“if this, then that”原则
- 多个智能合约组成Dapp

### Ether(ETH)：以太坊区块链的原生数字货币

- 基于当前市价购买物品、服务
- 支付智能合约和Dapp在以太坊上运行的费用（在以太坊上执行只能合约，需要支付Gas fee）

	- 

### Gas

- Gas指的是执行某项操作或某个智能合约 所需计算资源的度量单位（the unit of measure on the amount of computational effort）

	- 完全以ETH支付
	- Gas fee依赖于当前网络需求

		- 网络计算资源有限

			- 更多的人在以太坊区块链上交互：Gas fee上涨
			- 网络未被充分利用：Gas fee降低

	- Gas fee可以手动设置

		- Gas fee高，优先被验证，验证通过即可被添加到区块链中
		- Gas fee低，会被排入队列，需要一段时间才能被打包

	- Gas fee的单位为gwei
(1gwei = 0.000000001ETH)

		- Gas fee = 需支付的Gas量 * Gas的市场均价

### Dapps

- Dapps是区块链与用户交互的接口

	- 优势

		- 不变性Immutability
一旦信息保存在区块链上，不能被任何人更改
		- 防篡改Tamper-proof
发布在区块链上的智能合约，不能在其他区块链参与者不知情的情况下被篡改
		- 透明性Transparent
智能合约驱动的Dapp是公开可审计的
		- 可用性Availability
只要以太坊网络保持活性，在其之上搭建的Dapp将保持活性和可用性

	- 劣势

		- 不变性Immutability
人为错误是不可避免的 ，而不可变的智能合约有可能会将错误放大
		- 透明性Transparent
源码能被黑客查看
		- 可扩展性Scalability
Dapp的带宽受制于所在区块

### 以太坊的其他用处

- 创建去中心化自治组织（DAO）

	- 完全自治，不由个体管理，只通过代码管理
	- DAO代码基于智能合约运行
	- 透明
	- DAO管理决策通过代币投票决定

- 作为平台发行其他加密货币

	- ERC-20：
可互换代币，意味着代币间是可互换的并具有相同的价值
	- ERC-721：
不可互换代币，意味着代币是唯一的且不可互换的

## 以太坊钱包

### 1.链接区块链网络的用户友好接口
2.管理私钥
3.接收、储存、发送加密货币

- 钱包分类

	- 托管：
将控制权交给第三方，风险在第三方
	- 非托管：
自己控制钱包，风险在自身

- 钱包选择

	- 移动端用户：Argent

		- Argent卫士

			- 可验证使用者身份的人
			- 可验证使用者身份的设备
			- 可验证使用者身份第三方服务

		- 日交易限额
		- 免费交易（待考证）

	- 桌面端：MetaMask

		- Metamask是浏览器扩展程序
		- Metamask可以保存以太币和ERC20代币
		- Metamask可作为与以太坊网络中的Dapps交互的桥梁
		- 类似Metamask的交互桥梁免去了必须下载整个庞大的以太坊区块链节点的工作。
		- Metamask通过往浏览器注入web3.js的库来让用户轻松与以太坊网络进行交互

## 去中心化稳定币

### 为缓解加密货币价格的波动，价格锚定稳定资产被创造出来

- 稳定币的类型

	- 法币抵押型

		- 储备金储存在金融机构中
		- 用户必须信任该类型币作为一个实体，确实拥有其声称的准备金数额

	- 加密货币抵押型

		- 该类型币的价值，是由一个DAO表决的协议和智能合约来实现与1美元的锚定
		- 在任何时间，用于生成该类型币的抵押品都可以被用户验证

- Maker

	- Maker是一个运行在以太坊区块链上的智能合约平台
	- Maker拥有3种代币

		- Sai

			- 单抵押Dai
			- 仅由ETH作为抵押品背书

		- Dai

			- 多抵押Dai
			- 目前由ETH、BAT作为抵押品背书，并计划以后增加其他类型资产作为抵押品

		- Maker

			- Maker的治理代币

	- Sai和Dai的区别

		- 单抵押 Dai = 遗留 Dai = Sai
		- 多抵押 Dai = 新型 Dai = Dai

	- Maker如何进行系统自治

		- MKR在DAO中的用途

			- MKR持有者在该DAO组织中拥有与自己持有MKR代币数量成正比的投票权
			- MKR持有者可以对治理Maker协议的参数进行投票

		- Dai稳定币生态中3个关键参数

			- 抵押率Collateral Ratio

				- 可铸造的Dai数量取决于抵押率

					- ETH抵押率 = 150%
					- BAT抵押率 = 150%

			- 稳定费Stability Fee

				- 借款人除Maker金库债务本金外所要支付的利率

			- Dai存款利率Dai Savings Rate（DSR）

				- 持有Dai一段时间后所获得的利息

	- 发行DAI的目的

		- 3种可能的场景

			- 现在需要资金，并拥有一种你相信未来会升值的加密资产

				- 将加密资产存入Maker金库
				- 通过发行Dai立即获得资金

			- 现在需要资金，但不想因出售加密资产触发纳税事件的风险（？）

				- 通过发行Dai来提取贷款

			- 投资杠杆

	- 如何获得一些Dai

		- 铸造Dai

			- 

				- 预留空间保证抵押率在150%以上，以防止金库被清算和被收取13%的清算处罚

		- 交易Dai

			- 二级市场交易

	- 黑天鹅事件

		- 可能造成严重后果的一类不可预测极端事件

	- 为什么使用Maker

		- 稳定币之间的核心区别在于他们的协议
		- Maker完全运行在分布式账本上

			- 安全
			- 不可篡改
			- 透明性

		- Maker的基础设施通过基于实时信息且全面的风险协议和机制，加强了系统的安全性

## 去中心化借贷

### 资金借贷

- 人们可以通过通过借贷获得启动资金

	- 企业家通过抵押企业，借入创立企业所需的前期资金
	- 家庭可以通过抵押房子贷款买房

- 积累的财富可以作为资本借给贷款人

	- 借贷制度降低了借款人携款潜逃的风险

### 传统资金借贷体系的缺陷

- 需要某种形式的信任和中介

	- 中介：银行
	- 信任：复杂的信用系统

- 导致的质疑和缺陷

	- 约束性的筹资标准Restrictive Funding Criteria
	- 获取银行服务的地理位置、法律限制、贷款审批的高壁垒（high barriers）
	- 富人独享低风险高回报的放贷福利

### DeFi

- 不需要银行，上述壁垒不复存在
- 只需要足够的抵押，任何人可以做任何资金借贷

	- 往去中心化流动性池注资
	- 由算法确定利率

### Compound

- Compound Finance是一个基于以太坊的开源货币市场协议，任何人都可以在其中无摩擦（frictionlessly）地提供或借入加密货币

	- Compound作为一个建立在以太坊区块链上的流动性池运作

		- 流动性提供者向池子提供资产并赚取利息
		- 借款人从池子贷款并支付债务利息
		- 利率按照年利率表示，不同的资产间存在差异

	- 你将支付或获得多少利息

		- 不同资产有不同的年利率（APY）
		- APY根据资产供需通过算法设定

			- 借款需求高：APY高
			- 借款需求低：APY低

	- Compound不需要注册账户
	- 开始在Compound上赚取利息

		- 向协议提供资产
		- 提供的资产必须是Compound接收的币种
		- 资产存入Compound后开始计算利息

			- 用户能不断累计得到cToken
			- cToken可以兑换出其代表的标的资产和利息

		- cToken

			- cToken代表用户在协议中的余额
			- 利息不会立即分配，而是在cToken上累积
			- cToken是ERC-20代币，若有人想接替成为流动性提供者，你可以轻易转移你提供资产的所有权

	- 开始在Compound上借款

		- 向系统提供资产作为抵押品
		- 抵押资产越多，借款能力就越强
		- 借来的资产将直接发往钱包
		- 借款会收取手续费

	- 抵押资产的价格变动

		- 抵押资产升值

			- 抵押率上升
			- 可以提取更多的贷款

		- 抵押资产贬值

			- 抵押率下降
			- 抵押率现低于所要求的抵押率，发生清算：系统将会部分变卖抵押资产，以维持最低抵押率，并收取5%的清算手续费

	- 清算

		- 确保资金的提取或借出总是有超额的兑现能力
		- 保护借款人免受违约的风险
		- 清算手续费为5%

## Dex

### 交易所分类

- CEX

	- 允许在流动性充裕的情况下进行大宗交易
	- 用户并不拥有资产所有权

- DEX

	- 通过智能合约和链上交易来减少和消灭中介
	- 类型

		- 基于订单簿Order-Book-Based

			- 类似CEX，用户按市价、限价提交订单
			- 交易资产可以保管在自己的钱包里
			- 流动性差，订单簿中的订单可能会等很久才成交

		- 基于流动性池Liquidity-Pool-Based

			- 流动性本质是只能合约中的代币准备金
			- DEX流动性池可以跨多个DEX平台共享，将推高单个平台的可用流动性

### Uniswap

- 流动性池Liquidity Pools

	- 机制：
	- 奖励：
流动性提供者会获得Uniswap 0.3%交易费中的相应比例
	- 流动性提供者：
1.任何人可以作为提供者
2.必须提供ETH和与之进行兑换的交易代币
	- 价格计算：
流动性池中资产的价格通过AMM算法计算得出

- 自动做市商机制Automated Market Maker Mechanism（AMM）

	- 池子里假设有：
100ETH
20000DAI

		- 原理：
依据资金池两侧的流动性，保持一个恒定乘积
ETH liquidity (x) * DAI liquidity (y) = Constant Product (k)
		- 溢价：
为了确保池子的流动性（上述的乘积），ETH订单越大，溢价越多

- 在Uniswap新增一种代币

	- 任何ERC-20代币可以由任何人上架到Uniswap
	- 提供流动性就可以交易

