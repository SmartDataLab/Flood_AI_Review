# Flood_AI_Apply
山洪AI申请书

```bash
pandoc -s paper.tex --bibliography=paper.bib --csl=ieee.csl -o foo.docx
```

## 课题要求

### 基于人工智能的山洪灾害监测与损失评估研究

研究背景：山洪灾害是我国最为严重的自然灾害之一，严重地威胁着人民生命财产安全，给国民经济造成重大损失。传统的山洪灾害监测方法分为地面观测和遥感监测两种，由于山洪灾害空间分布具有多发、少发和不发等频度变化大的特性，所以设立的有限地面监测站点只能代表局部地点的信息，缺乏宏观性和代表性，难以满足山洪灾害全空间区域的监测。随着机器学习等人工智能技术的广泛应用，基于人工智能技术和大数据驱动新一代水文模型成为水文学研究的热点。将人工智能方法与气象降水和水文监测产品以及遥感产品相结合应用于暴雨洪水灾害监测与损失评估成为了山洪灾害防御的核心技术难点。因此，建立山洪灾害识别与损失评估系统在山洪灾害监测具有重大意义。

研究内容：梳理目前国内外山洪识别的方法，开展基于人工智能的山洪识别研究，对山洪灾害的损失进行评估。依托水文模型确定山洪灾害致灾临界降雨量，利用逐日的河流水位和流量、逐小时降雨数据对水文模型进行参数率定，预报子流域（或格网点）的径流过程、洪峰等洪水特征，根据流域河流防洪标准，发布洪水预警，从而推算出河流达到警戒水位、保证水位的流域临界面雨量，建立小流域山洪风险评估模型。依据气象预报相关产品进行流域面雨量预报，对山洪灾害的可能发生的强度和影响范围进行监测和损失评估。

基本成果要求：（1）提交山洪自动化识别模型并进行损失评估和风险评估模型及技术报告；（2）提交一份基于人工智能的小流域山洪灾害监测与风险评估研究的示范应用报告。

## 申请书主要结构

### 二、立项依据

（一）立项目的和意义



（二）概念与内涵（详细阐述本研究涉及相关理论和技术的概念与内涵）


（三）国内外研究现状和发展趋势
（国内外研究现状与发展趋势的技术方法总结）

- AI监控与预警山洪（可以是机器学习方法以及实际case）

Towards learning universal, regional, and local hydrological behaviors via machine learning applied to large-sample datasets
LSTM;此外，我们还提出了一种标准LSTM体系结构的适应性，我们称之为实体感知LSTM（EA-LSTM），它允许在深度学习模型中将流域相似性作为特征层进行学习。

Deep learning and machine learning in hydrological processes climate change and earth systems a systematic review
人工智能方法和应用在水文过程、气候变化和地球系统的建模和预测方面显示出巨大的贡献。其中，深度学习和机器学习方法主要用于实现更高的精度、鲁棒性、效率、计算成本和整体模型性能。本文介绍了机器学习和深度学习方法在这一领域的现状和应用，并对其发展趋势进行了讨论。通过一种新的方法分类，综述了机器学习和深度学习的进展。论文的结论是，深度学习仍处于发展的初级阶段，研究仍在进行中。另一方面，机器学习方法已经在该领域建立起来，通过集成技术和杂交技术，新的具有更高性能的方法正在出现。

rovement of global hydrological model-based flood simulatEvaluation and machine learning impions
基于全球水文模型（GHMs）的洪水模拟的准确性和改进还不足以满足大多数应用。在混合物理-机器学习方法中，采用长短时记忆单元（LSTM）来改进基于GHMs的洪水模拟.结果表明，将经典洪水模拟和机器学习技术相结合，可能是一种更加稳健和自信的洪水风险评估方法。




- AI山洪风险评估与损失估计（risk 、 vulune 、 loss）

Hybrid machine learning framework for hydrological assessment
基于混合机器学习（无监督聚类技术和监督分类技术）的水文评估工具
经证实，HAT可以进行准确的过程线评估，因为性能评级的一致性率为98%。

- 缺失水域数据场景下多源数据协同的山洪监控（remote sensing、 lack data 、 ungauged、 scarse、 data-sparse）



"What role does hydrological science play in the age of machine learning?"



### 三、研究方案

（一）研究目标、研究内容和拟解决的关键问题

（二）拟采取的研究方法、技术路线、实验方案及可行性分析（须具体翔实，包括理论分析、计算、实验方法、实验步骤等）

（三）主要创新点（技术方法的优势与效率分析）

（四）研究计划及预期进展（包括研究进度计划及阶段目标）

（五）预期研究成果和考核指标（含预期产生的专利、著作、技术方法、软件产品等，须具体、明确、可考核）

### 五、研究基础

（一）与申请课题有关的研究工作基础和已取得成绩（包括已经取得的知识产权，如专利、著作、技术秘密等）
（二）现有研究条件情况
（三）申请者和主要成员研究工作简历（包括近期承担与本课题有关的预研项目、基金项目和其它项目情况，及发表论著目录等）