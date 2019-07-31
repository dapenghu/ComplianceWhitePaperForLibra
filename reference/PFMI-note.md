# <center> Principles for Financial Market Infrastructures

## <center> 0. Overview
PFMI 从10方面阐述了原则

1. General organisation  组织结构
2. Credit and liquidity risk management  信用与流动性风险
3. Settlement 结算
4. Central securities depositories and exchange-of-value settlement systems CSD与结算
5. Default management  违约风险管理
6. General business and operational risk management  一般运营与业务风险管理
7. Access   访问权限
8. Efficiency  效率
9. Transparency  透明度
10. Responsibilities of central banks, market regulators, and other relevant authorities 监管层的责任义务


## <center> 1. Introduction

- FMI的重要性

Financial market infrastructures (FMIs) that facilitate the clearing, settlement, and recording of monetary and other financial transactions can strengthen the markets they serve and play a critical role in fostering financial stability. However, if not properly managed, they can pose significant risks to the financial system and be a potential source of contagion, particularly in periods of market stress.

FMI 在金融稳定扮演关键作用，但是如果没有合适的管理与设计，会产生重大的风险，在金融市场动荡的时候成为风险的传染源。

### <center> 1.1 什么是FMI: definition, organisation, and function

    FMI is defined as a multilateral system among participating institutions, including the operator of the system, used for the purposes of clearing, settling, or recording payments, securities, derivatives, or other financial transactions.

    FMI 是由多个参与方构成的多边系统

    FMIs typically establish a set of common rules and procedures for all participants, a technical infrastructure, and a specialised risk-management framework appropriate to the risks they incur. 

    FMIs provide participants with centralised clearing, settlement, and recording of financial transactions among themselves or between each of them and a central party to allow for greater efficiency and reduced costs and risks.

    FMIs also allow participants to manage their risks more efficiently and effectively, and, in some instances, eliminate certain risks. 
    
    FMIs can also promote increased transparency in particular markets. Some FMIs are critical to helping central banks conduct monetary policy and maintain financial stability

- Payment systems 支付系统

    A payment system is a set of instruments, procedures, and rules for the transfer of funds between or among participants; the system includes the participants and the entity operating the arrangement. 
    
    Payment systems are typically based on an agreement between or among participants and the operator of the arrangement, and the transfer of funds is effected using an agreed-upon operational infrastructure. 
    
    A payment system is generally categorised as either a retail payment system or a large-value payment system (LVPS). 
    
    - A retail payment system is a funds transfer system that typically handles a large volume of relatively low-value payments in such forms as cheques, credit transfers, direct debits, and card payment transactions. 
  
        Retail payment systems may be operated either by the private sector or the public sector, using a multilateral deferred net settlement (DNS) or a real-time gross settlement (**RTGS**) mechanism.

    - An **LVPS** is a funds transfer system that typically handles large-value and high-priority payments. 
        
        In contrast to retail systems, many LVPSs are operated by central banks, using an RTGS or equivalent mechanism

- Central Securities Depositories CSD 中央证券托管 - 最有可能被分布式账本代替的部分

    A central securities depository provides **securities accounts**, **central safekeeping services**, and **asset services**, which may include the administration of corporate actions and redemptions, and plays an important role in helping to ensure the integrity of securities issues (that is, ensure that securities are not accidentally or fraudulently created or destroyed or their details changed)
    
    A CSD can hold securities either in physical form (but immobilised) or in dematerialised form (that is, they exist only as electronic records). 
    
    The precise activities of a CSD vary based on jurisdiction and market practices. For example, the activities of a CSD may vary depending on whether it operates in a jurisdiction with a direct or indirect holding arrangement or a combination of both. 
    
    A CSD may maintain the definitive record of legal ownership for a security; in some cases, however, a separate securities registrar will serve this notary function. 
    
    In many countries, a CSD also operates a securities settlement system, but unless otherwise specified, this report adopts a narrower definition of CSD that does not include securities settlement functions.


- Securities settlement systems SSS

    证券结算包括证券的结算和资金的清算两个方面，它是证券交易的最后一个环节。

    A securities settlement system enables securities to be transferred and settled by book entry according to a set of predetermined multilateral rules. 
    
    Such systems allow transfers of securities either free of payment or against payment. When transfer is against payment, many systems provide delivery versus payment (DvP), where delivery of the security occurs if and only if payment occurs. 
    
    An SSS may be organised to provide additional securities clearing and settlement functions, such as the confirmation of trade and settlement instructions. 
    
    The definition of an SSS in this report is narrower than the one used in the RSSS, which defined an SSS broadly to include the full set of institutional arrangements for confirmation, clearance, and settlement of securities trades and safekeeping of securities across a securities market. 
    
    For example, the RSSS definition for SSSs included CSDs and CCPs, as well as commercial bank functions involving securities transfers. In this report, CSDs and CCPs are treated as separate types of FMIs. As noted above, in many countries, CSDs also operate an SSS.

- Central counterparties

    清算所介入金融合约交易的对手方之间，成为买方的卖方、卖方的买方，从而使期货合约买卖双方的对手都被替换成了作为中央对手方的清算所。
    
    按专业说法，中央对手方主要有四个功能：重新分配合约对手方风险，防止多边净额结算失败；降低结算参与人的风险；提高结算效率和资金使用效率；提高市场流动性。

    相较于双边清算，通过中央交易对手进行清算具有明显的好处。中央交易对手介入两个原始交易对手之间，使原始交易对手相互隔离，一方面可以降低金融机构之间的关联性，另一方面还有助于防止金融违约，从而促进金融稳定。当然，集中清算也会将金融风险集中于中央交易对手，因此，中央交易对手自身的稳健性至关重要。 中央交易对手清算机制是否具有分散风散的功能取决于两大关键因素：一是采用该清算机制的成员所投入的资本量；二是与未偿付的风险敞口相匹配的原始抵押值。针对此，中央交易对手会要求其成员至少每天根据头寸价格变动情况对抵押品进行调整。

    A central counterparty interposes itself between counterparties to contracts traded in one or more financial markets, becoming the buyer to every seller and the seller to every buyer and thereby ensuring the performance of open contracts. 
    
    A CCP becomes counterparty to trades with market participants through novation, an open-offer system, or through an analogous legally binding arrangement. 
    
    CCPs have the potential to reduce significantly risks to participants through the multilateral netting of trades and by imposing more-effective risk controls on all participants. For example, CCPs typically require participants to provide collateral (in the form of initial margin and other financial resources) to cover current and potential future exposures. CCPs may also mutualise certain risks through devices such as default funds. As a result of their potential to reduce risks to participants, CCPs also can reduce systemic risk in the markets they serve. The effectiveness of a CCP’s risk controls and the adequacy of its financial resources are critical to achieving these risk- reduction benefits.

- Trade repositories

    储存库是保存场外衍生工具交易记录的中央电子资料库。储存库会收集及向监管机构提供场外衍生工具交易的资料，为监管机构履行监察市场的职责提供重要支援，有助维持金融稳定。储存库亦有助提高市场的透明度，促进市场标准化，并在一定程度上保障交易资料的质素和可获取性。

    [香港场外衍生工具交易资料储存库](https://www.hkma.gov.hk/gb_chi/key-functions/international-financial-centre/infrastructure/otc-derivatives-trade-repository.shtml)

    A trade repository is an entity that maintains a centralised electronic record (database) of transaction data.

    TRs have emerged as a new type of FMI and have recently grown in importance, particularly in the OTC derivatives market. 
    
    By centralising the collection, storage, and dissemination of data, a well-designed TR that operates with effective risk controls can serve an important role in enhancing the transparency of transaction information to relevant authorities and the public, promoting financial stability, and supporting the detection and prevention of market abuse. 
    
    An important function of a TR is to provide information that supports risk reduction, operational efficiency and effectiveness, and cost savings for both individual entities and the market as a whole.

### <center> 1.2 Objectives: safety and efficiency  PFMI的目标：安全与效率

The main public policy objectives of the CPSS and the Technical Committee of IOSCO in setting forth these principles for FMIs are to enhance **safety and efficiency** in payment, clearing, settlement, and recording arrangements, and more broadly, to limit **systemic risk** and foster **transparency and financial stability**. 

Poorly designed and operated FMIs can contribute to and exacerbate systemic crises if the risks of these systems are not adequately managed, and as a result, financial shocks could be passed from one participant or FMI to others. 

The effects of such a disruption could extend well beyond the FMIs and their participants, threatening the stability of domestic and international financial markets and the broader economy. 

In contrast, robust FMIs have been shown to be an important source of strength in financial markets, giving market participants the confidence to fulfil their obligations on time, even in periods of market stress. 

In relation to CCPs, the objectives of safety and efficiency are even more pertinent because national authorities have required or proposed the mandatory use of centralised clearing in an increasing number of financial markets.

- Achieving the public policy objectives： **FMI 顶层设计的必要性**

    FMI 是一个多边系统，同时又有很强的负外部性。当金融风险产生的时候，就像击鼓传花一样，风险沿着金融工具传播，从一个参与者转移到另一个参与者，谁是最后一个接手的，那么谁倒霉。

    Market forces alone will not necessarily achieve fully the public policy objectives of safety and efficiency because FMIs and their participants do not necessarily bear all the risks and costs associated with their payment, clearing, settlement, and recording activities. 仅仅靠市场力量自身无法实现整体性的安全与效率目标，FMI每个成员结构没有责任承担风险与后果。    

    Moreover, the institutional structure of an FMI may not provide strong incentives or mechanisms for safe and efficient design and operation, fair and open access, or the protection of participant and customer assets. FMI的组织结构没有提供香相应的激励机制和制度保障。
    
    In addition, participants may not consider the full impact of their actions on other participants, such as the potential costs of delaying payments or settlements. 市场的参与者的行为也不会考虑整体金融系统的安全性，以及对他人的风险敞口。
    
    Overall, an FMI and its participants may generate significant negative externalities for the entire financial system and real economy if they do not adequately manage their risks. 总之，FMI和参与者会产生巨大的负外部性，他们往往能够把风险和转嫁给其它人承担。
    
    In addition, factors such as economies of scale, barriers to entry, or even legal mandates, may limit competition and confer market power on an FMI, which could lead to lower levels of service, higher prices, or under-investment in risk-management systems. 
    
    Caution is needed, however, as excessive competition between FMIs may lead to a competitive lowering of risk standards.


### <center> 1.3 Scope of the principles for FMIs 适用范围

## <center> 2. Overview of key risks in financial market infrastructures

### <center> 2.1 Systemic risk

### <center> 2.2 Legal risk

### <center> 2.3 Credit risk

### <center> 2.4 Liquidity risk

### <center> 2.5 General business risk

### <center> 2.6 Custody and investment risk

### <center> 2.7 Operational risk



## <center> 3. Principles for financial market infrastructures

### <center> 3.1 General organisation

### <center> 3.2 Credit and liquidity risk management
- Credit risk is the risk that a counterparty will be unable to meet fully its financial obligations when due or at any time in the future.
- Liquidity risk is the risk that a counterparty will have insufficient funds to meet its financial obligations when due, but may be able to do so at some time in the future.

由于分布式账本的支付是一种去中心化的点对点支付，在技术层面上有效的降低了信用风险和流动性风险。降低了质押抵押品、保证金等需求。

### <center> 3.3 Settlement

结算中可能的风险，相关的建议和原则

### <center> 3.4 Central securities depositories and exchange-of-value settlement systems
- CSD: 保证证券发行过程的完备性，防止非法的销毁与铸造证券，
- 资产托管风险：管理不善，资产挪用，欺诈，记录不完整等
- 

### <center> 3.5 General business and operational risk management

### <center> 3.6 Default management

### <center> 3.7 Access

### <center> 3.8 Efficiency

### <center> 3.9 Transparency
An FMI should have clear and comprehensive rules and procedures and should provide sufficient information to enable participants to have an accurate understanding of the risks, fees, and other material costs they incur by participating in the FMI.

分布式账本能够以公开、透明的方式运行智能合约，完成支付结算功能，帮助参与者

## <center> 术语

Committee on Payment and Settlement Systems (CPSS)
Technical Committee of the International Organization of Securities Commissions (IOSCO)



