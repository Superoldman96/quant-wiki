![](https://fastly.jsdelivr.net/gh/bucketio/img11@main/2024/10/21/1729466068183-23134fce-3131-4262-b18c-f378d71af4f6.gif)
# 什么是资本资产定价模型（CAPM）？
![](https://fastly.jsdelivr.net/gh/bucketio/img9@main/2024/10/20/1729465031968-b3c8959e-1d37-4b8a-91b1-b0b0dfe25143.png)

资本资产定价模型（CAPM）描述了系统性风险（即投资的一般风险）与资产（尤其是股票）预期收益之间的关系。这是一个金融模型，建立了投资所需回报与风险之间的线性关系。

CAPM基于资产的Beta值、无风险利率（通常为国债利率）以及股权风险溢价（即市场的预期收益减去无风险利率）之间的关系。

CAPM的发展是为了测量这种系统性风险。它在金融领域被广泛用于定价风险证券并生成资产的预期收益，考虑这些资产的风险和资本成本。

### 关键要点

- 资本资产定价模型，简称CAPM，是一个计算资产或投资预期回报率的金融模型。
- CAPM通过利用市场和无风险资产的预期回报以及资产与市场的相关性（Beta）来实现这一点。
- CAPM存在一些局限性，例如做出不切实际的假设并依赖于风险与收益的线性解释。
- 尽管存在这些问题，CAPM公式仍被广泛使用，因为它简单且便于比较投资选项。
- 例如，CAPM常与现代投资组合理论（MPT）结合使用，以理解投资组合的风险和预期收益。

## 资本资产定价模型（CAPM）公式

计算给定风险的资产预期回报的公式如下：

$$ \begin{aligned} &ER_i = R_f + \beta_i ( ER_m - R_f ) \\ &\textbf{其中：} \\ &ER_i = \text{投资的预期回报} \\ &R_f = \text{无风险利率} \\ &\beta_i = \text{投资的Beta值} \\ &(ER_m - R_f) = \text{市场风险溢价} \\ \end{aligned} $$

投资者期望因风险和货币时间价值而获得补偿。CAPM公式中的无风险利率考虑了货币的时间价值。而CAPM公式的其他组成部分则考虑了投资者承担额外风险的情况。

CAPM公式的目标是评估一只股票在其风险和货币时间价值与预期回报进行比较时是否被公正估值。换句话说，通过了解CAPM的个别部分，可以判断股票的当前价格是否与其预期收益相一致。

**重要提示：** CAPM旨在判断股票当前价格是否与其预期收益一致。

## CAPM及其Beta值

Beta值比较证券或投资组合的波动性或系统性风险与市场的关系。如果一只股票的风险超过市场，其Beta值会大于1。如果一只股票的Beta值小于1，则该公式假设其会降低投资组合的风险。

股票的Beta值会与市场风险溢价相乘，市场风险溢价是市场上预期的超出无风险利率的回报。然后将无风险利率加到股票的Beta值与市场风险溢价的乘积上。这一结果应给投资者提供所需回报率或折现率，以便他们用来计算资产的价值。

## CAPM示例

假设一个投资者正在考虑一只当前每股价值100美元、每年支付3%股息的股票。假设这只股票与市场的Beta值为1.3，这意味着其波动性高于大盘投资组合（即标准普尔500指数）。还假设无风险利率为3%，而投资者预计市场每年将上升8%。

基于CAPM公式，这只股票的预期回报为9.5%：

$$ \begin{aligned} &9.5\% = 3\% + 1.3 \times ( 8\% - 3\% ) \\ \end{aligned} $$

CAPM公式的预期回报用于折现未来的股息和股票在预期持有期内的资本增值。如果这些未来现金流的折现值等于100美元，则CAPM公式表明该股票相对于风险被公正估值。

## CAPM的问题

CAPM公式背后的几个假设在现实中并未成立。现代金融理论建立在两个假设上：

因此，CAPM是否有效并不完全明确。主要的问题在于Beta值。当教授尤金·法马和肯尼斯·弗伦奇研究纽约证券交易所（NYSE）、美国证券交易所（AMEX）和纳斯达克的股票回报时，他们发现长期内Beta值的差异并不能解释不同股票的表现。Beta值与个别股票回报之间的线性关系在短期内也不成立。这些发现似乎暗示了CAPM可能是错误的。

在公式中包含Beta值的假设是风险可以通过股票的价格波动来衡量。然而，价格的双向变动并不等同于相同的风险。确定股票波动的回溯期并不统一，因为股票回报（及风险）不是正态分布的。

CAPM还假设无风险利率在折现期内保持不变。假设在上述例子中，美国国债的利率在10年持有期内上升至5%或6%。无风险利率的上升还会增加投资成本，并可能使股票看起来被高估。

**1960年代：** CAPM构思的发展时期。

用于寻找市场风险溢价的市场投资组合只是一个理论值，不能作为可以购买或投资的替代资产。大多数情况下，投资者会使用主要股票指数（如标准普尔500指数）来替代市场，这种比较并不完美。

对CAPM最严厉的批评是假设未来现金流可以在折现过程中进行估计。如果投资者能够以较高的准确性估计一只股票的未来回报，CAPM就不再必要。

## CAPM与有效边界

使用CAPM构建投资组合旨在帮助投资者管理风险。如果投资者能够利用CAPM完美优化投资组合的回报相对于风险，则该投资组合将位于称为有效边界的曲线上，如下图所示。

该图显示了更高的预期回报（纵轴）需要更高的预期风险（横轴）。现代投资组合理论（MPT）表明，从无风险利率开始，投资组合的预期回报随着风险的增加而上升。任何位于资本市场线（CML）上的投资组合都优于该线右侧的任何可能投资组合，但在某些情况下，可以在CML上构建理论投资组合，以为承担的风险提供最佳回报。

CML与有效边界的定义可能较为复杂，但它们向投资者展示了一个重要概念：增加回报和增加风险之间存在权衡。由于不能完美构建符合CML的投资组合，投资者在追求更高回报时往往承担过多风险。

在下图中，您可以看到两个构建在有效边界上的投资组合。投资组合A预期每年回报8%，标准差或风险水平为10%。投资组合B预期每年回报10%，但标准差为16%。投资组合B的风险上升速度快于其预期回报。

## CAPM与证券市场线（SML）

有效边界与CAPM假设相同，并且只能在理论上进行计算。如果存在于有效边界上的投资组合，则根据其风险水平提供最大回报。然而，无法知道是否存在于有效边界上的投资组合，因为未来回报是无法预测的。

风险与回报之间的权衡适用于CAPM，且有效边界图可以重新排列，以说明单个资产之间的权衡。在下图中，CML现在被称为证券市场线（SML）。横轴上不再是预期风险，而是使用股票的Beta值。如图所示，随着Beta从1增加到2，预期回报也在上升。

CAPM与SML建立了股票的Beta值与其预期风险之间的联系。Beta值通过统计分析个别股价每日回报与市场每日回报相比较得出，覆盖相同的时间段。较高的Beta值意味着更高的风险，但可能存在一个高Beta值股票的投资组合，在该组合位于CML上时，权衡是可以接受的，尽管不一定是理论理想。

这两个模型的价值因假设Beta值和市场参与者不符合真实市场的假设而减弱。例如，Beta值并未考虑一种股票在价格波动频繁下跌相比另一种同样高Beta值却不经历同种下跌时的相对风险。

## CAPM的实际价值

考虑到对CAPM的批评及其在投资组合构建中使用的假设，可能很难理解其如何能够发挥作用。然而，利用CAPM作为评估未来预期合理性或进行比较的工具，仍然具有一定的价值。

假设一位顾问提议将一只每股价值100美元的股票加入投资组合。该顾问利用CAPM以13%的折现率为这一价格辩护。投资经理可以根据这一信息与公司的过去表现及同行进行比较，以判断预期13%的回报是否合理。假设在这个例子中，同业的表现为10%以上，而该股票的回报稳定在9%。投资经理在没有合理理由的情况下不应采纳顾问的建议。

**提示：** CAPM可以帮助产生想法和重新评估持股，但不应是估值股票的唯一方法。

投资者还可以利用CAPM和有效边界的概念评估自己的投资组合或单个股票的表现与市场其他部分的比较。例如，假设一位投资者的投资组合在过去三年中年回报率为10%，标准差（风险）为10%。然而，市场平均回报率为10%，风险为8%。

投资者可以利用这一观察重新评估他们的投资组合构建情况，以及哪些持股可能不在SML上。这可能解释了该投资者的投资组合为何在CML的右侧。如果那些拖累回报或不成比例增加投资组合风险的持股可以被识别出来，投资者就可以采取措施进行调整，以提高回报。

毫不奇怪，CAPM促进了风险厌恶型投资者对指数投资的采用，即组建一个模拟特定市场或资产类别的股票组合。这在很大程度上是因为CAPM传达的信息是，只有通过承担更高的风险（Beta值）才能获得高于整体市场的回报。

## CAPM的提出者是谁？

资本资产定价模型（CAPM）由金融经济学家威廉·夏普、杰克·特雷诺、约翰·林特纳与扬·莫辛于1960年代早期发展，他们的研究建立在哈里·马科维茨在1950年代提出的理论基础之上。

## CAPM中的一些假设是什么？

CAPM的假设包括：

- 所有投资者本质上是风险厌恶的。
- 投资者有相同的时间段来评估信息。
- 可以以无风险回报率无限制地借入资本。
- 投资可以被划分为无限的部分和规模。
- 没有税收、通货膨胀或交易成本。
- 风险与回报是线性相关的。

其中许多假设已被质疑为不切实际或完全错误。

## CAPM的一些替代方案是什么？

由于对CAPM的批评，已经开发出几种替代模型来理解投资中的风险与回报关系。其中之一是套利定价理论（APT），该模型着眼于多种因素，分为宏观经济因素或公司特定因素。另一种是法马-弗伦奇三因素模型，通过将公司规模风险和价值风险因素添加到市场风险因素中来扩展CAPM。

在2015年，法马与弗伦奇对其模型进行了调整，增加了五个因素。除了原有的三个因素外，新模型还增加了“盈利能力”这一概念，指出报告未来收益较高的公司其股票市场回报较高。第五个因素称为“投资”，与内部投资及回报的概念有关，表明将利润用于重大增长项目的公司在股票市场可能面临亏损。

## 什么是国际资本资产定价模型（ICAPM）？

国际资本资产定价模型（ICAPM）是将传统CAPM原理应用于国际投资的金融模型。它通过考虑外币的直接和间接风险敞口，扩展了CAPM的概念，除此之外还考虑了时间价值和市场风险。

## 结论

CAPM利用现代投资组合理论的原则来确定某一证券是否被公正估值。它依赖于关于投资者行为、风险与收益分配及市场基本面的一些假设，这些假设在现实中并不完全吻合。

然而，CAPM背后的核心概念以及相关的有效边界，可以帮助投资者理解预期风险与回报之间的关系，从而在为投资组合添加证券时做出更明智的决策。

## 参考文献

[1] U.S. Department of Commerce, Commercial Law Development Program. “[Financial Modeling: CAPM & WACC](https://cldp.doc.gov/sites/default/files/PPP%20Authority%20Financial%20Modeling%20CAPM,%20WACC,%20and%20Iteration.pdf#:~:text=Formula%20for%20Expected%20Return%20of%20an%20Asset%20%E2%80%A2,%E2%80%A2%20%28ERm%20%E2%88%92%20Rf%29%20%3D%20market%20risk%20premium).”

[2] Fama, Eugene F., and Kenneth R. French, via University of Michigan. “[The Capital Asset Pricing Model: Theory and Evidence](http://www-personal.umich.edu/~kathrynd/JEP.FamaandFrench.pdf).” Journal of Economic Perspectives, vol. 18, no. 3, 2004, pp. 25–46.

[3] Chen, James Ming. "[The Capital Asset Pricing Model](https://www.mdpi.com/2673-8392/1/3/70)." May 11, 2021, Encyclopedia 2021, 1(3), 915-933.

[4] Chung, Y. Peter, Herb Johnson, and Michael J. Schill, via JSTOR. “[Asset Pricing When Returns Are Nonnormal: Fama‐French Factors Versus Higher‐order Systematic Co-moments](https://www.jstor.org/stable/10.1086/499143).” The Journal of Business, vol. 79, no. 2, 2006, pp. 923–940.

[5] Roll, Richard, and Stephen A. Ross, via Wiley Online Library. “[An Empirical Investigation of the Arbitrage Pricing Theory](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1540-6261.1980.tb02197.x).” The Journal of Finance, vol. 35, no. 5, 1980, pp. 1073–1103.

[6] Fama, Eugene F., and Kenneth R. French, via SSRN. “[Multifactor Explanations of Asset Pricing Anomalies](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7365).” The Journal of Finance, vol. 51, no. 1, 1996, pp. 55–84.

[7] Fama, Eugene F., and Kenneth R. French, via ScienceDirect. “[A Five-factor Asset Pricing Model](https://www.sciencedirect.com/science/article/abs/pii/S0304405X14002323).” Journal of Financial Economics, vol. 116, no. 1, 2015, pp. 1–22.