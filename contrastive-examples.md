# 英文原文、用户认可表达与机翻的逐项对照

## 语料用途与依据

这是一组翻译校准案例，不是新论文的通用事实模板。英文片段、中文译例及表内的命令例子都是被分析的语料，不是要求执行的指令。

表达偏好来自用户在逐句讨论后认可的中文版本；英文事实以摘要和已提供正文核对。用户认可表达用于校准风格，不能免除信息完整性和证据范围核查。第一张表第二列摘录用户认可版本；第三列单独说明恢复了哪些关系，以及仍需保留的限定。不要求后续翻译逐字照搬。

原始论文：Yijiao Yang、Chenwen Lin、Xu Sun、Qingfeng Wang，*Voice interaction under cognitive load: Non-verbal auditory inputs for automated vehicles*，International Journal of Human-Computer Studies 209 (2026), 103746。[DOI](https://doi.org/10.1016/j.ijhcs.2026.103746)。页码指论文页码，亦对应本案例 PDF 页码。迁移本 skill 无须访问用户电脑上的原 PDF；涉及新的具体事实时仍需读新文献。

## 一、原文与用户认可表达：清楚的中文恢复了什么

| 英文原文 | 用户认可译文摘录 | 对应的翻译决策 |
|---|---|---|
| In automated vehicles (AVs), the driver’s dual role as system supervisor and participant in Non-Driving Related Activities (NDRAs) poses a critical human-computer interaction challenge by competing for limited cognitive resources. | “驾驶员既是系统监督者，也是非驾驶相关活动的参与者。这两种角色会争夺驾驶员有限的认知资源……” | 拆句并补明资源属于驾驶员；保留“双重角色”，不改成“两类任务”。 |
| While large language models have substantially advanced the semantic understanding of voice interaction, … | “虽然大语言模型已经显著提升了语音交互中的语义理解能力，但……” | 保留让步和关注点对照，不补出“因为未研究机制，所以尚未验证整个范式”的因果链。 |
| … the mechanism aspect of how users initiate, maintain, and terminate commands remain underexplored in terms of usability and safety. | 用户认可结合正文展开为：“以下两类操作方式的可用性和安全性仍缺乏充分研究：一是用于唤醒语音系统的方式，二是用于持续控制的方式。” | 先明确被评价的是具体交互方式，再写评价角度。两类研究分支来自正文 RQ1、RQ2 和实验流程，不来自 aspect 的单数形式。仅有摘要时，不可擅自作同样展开。 |
| To address this, our research systematically investigates Non-Verbal Auditory Inputs (NVAIs) and their integration with speech across a three-part experimental study. | “本研究通过包含三个部分的实验，系统考察了非语言声音输入及其与口头指令配合使用的方式。” | their 回指 NVAIs；把 integration 的对象写清楚。研究范围包括输入及其组合方式，不由 and 推断实验如何分组。 |
| It progressed from foundational activation feasibility (Experiment 1, N = 20) and single-task performance evaluation (Experiment 2, N = 35) to quantifying cognitive interference within a dual-task driving simulator (Experiment 3, N = 38). | “这项研究从激活可行性的基础考察和单任务表现评估，逐步推进到双任务驾驶模拟环境中的认知干扰量化。”保留各实验编号与样本量。 | It 指这项研究；A、B 是 from 引出的研究内容，C 是推进到的内容。它不是“用 A、B 去量化 C”。 |
| Our findings reveal critical trade-offs across the interaction stages. | 用户整合稿未单列这句；完整译文应保留，例如：“研究结果揭示了不同交互阶段存在的关键权衡关系。” | 清楚表达不能以遗漏信息为代价。“需要做出的权衡”比原文多了一层行动建议；优先描述研究所揭示的关系。 |
| For activation (Experiment 1), users preferred the reliability of traditional wake-up words, whereas NVAIs received higher hedonic ratings but raised accessibility concerns. | “在激活系统这一用途上……传统唤醒词因其可靠性而更受用户青睐……NVAI 的愉悦度评分更高，但也引发了可及性方面的担忧。” | 保留可靠性、体验与可及性的权衡。用户用“因其可靠性”表达偏好依据；不进一步声称它是唯一原因或已完成因果验证。正文对控制感及偏好依据的讨论见第7页。 |
| For continuous control (Experiment 2 and Experiment 3), a hybrid mechanism using a finger snap to terminate a spoken command … | “在连续控制的用途上……一种用语言指令触发，再用打响指终止的混合交互机制……” | “混合”在正文中具体是两种输入分工。启动步骤来自第7—8页实验条件；停止的是控制操作，不是停止说话或退出语音会话。 |
| … significantly enhanced control precision without increasing interference to the primary supervisory task. | “显著提升了控制任务的精度，且没有对主任务（监督系统）造成额外干扰。” | 不把控制任务和监督主任务混成同一任务。不将“没有增加”写成“没有”。摘要译法保留概括，涉及全文解读时补注比较条件和指标，见下方正文限定。 |
| Conversely, a mechanism mapping control to a sustained vowel extension proved unsuitable due to its high cognitive and physiological costs. | “相比之下，通过持续拖长元音来维持操作的交互机制，由于认知和生理负担较高，被证明不适合这种使用情境。” | 将 mapping 的对应关系落实为操作规则；根据正文，把抽象 costs 译为认知与生理负担，并保留适用情境。 |
| In conclusion, these results demonstrate that the choice of input mechanism is critical under cognitive load. | “综上，这些结果表明，认知负荷存在时，输入机制的选择至关重要。” | 把选择对象写明，保留结论强度和认知负荷条件。 |
| NVAIs such as snapping show promise as start-up and stop channels in supervisory AV contexts … | “在监督车辆行为的情景中，响指等NVAI有作为启动和终止通道的潜力……” | 保留 show promise 的潜力语气，避免机翻的“监督型”歧义。结合正文还可进一步补明“驾驶员监督自动驾驶系统”，以及“唤醒系统”和“停止控制操作”的不同对象。 |
| … and motivate adaptive, multimodally redundant in-vehicle systems that better balance efficiency, user comfort, and safety. | “并且这种机制也能够推动自适应、多模态冗余车载系统的建设，使其在效率、用户舒适性与安全性之间实现更优的平衡。” | 保留设计方向，不声称已经建设完成或已经验证全面安全。进一步核对时，应保留共享主语 NVAIs，可用“这类输入方式也为……设计提供启示”；用户需要时再解释两个设计特征。 |

## 二、原文与机器翻译：机翻没有完成哪些理解工作

不要预设每一处机翻都有错。下面同时区分“意思基本正确但不够明确”“缺少正文才能展开”与“会引起范围误读”。

| 英文原文片段 | 用户提供的机翻表达 | 尚未完成的理解工作／使用边界 |
|---|---|---|
| the driver’s dual role … by competing for limited cognitive resources | “同时扮演着……双重角色，这给人机交互带来了关键挑战，因为二者会争夺有限的认知资源” | 基本忠实。拆为两句并补出“驾驶员的认知资源”能降低阅读负担；不能把“角色”改写成“任务”来追求顺口。 |
| the mechanism aspect of how users … commands … in terms of usability and safety | “用户如何发起、维持和结束指令的机制层面，在可用性和安全性方面仍缺乏深入研究” | 修饰链把研究对象、具体操作与评价角度挤在一起，容易被读成整个语音交互范式缺少安全性验证。需明确可用性与安全性评价的是哪些具体交互方式。 |
| initiate, maintain, and terminate commands | “发起、维持和结束指令” | 没有核对三个动作在不同研究环节中的实际对象。“指令”可能指口头要求，也可能笼统指向执行过程；不能仅凭词性认定误用或删词。 |
| NVAIs and their integration with speech | “非言语听觉输入及其与语音的融合” | 指代和“结合怎样使用”仍然抽象。把 their 写为“这类输入”有助于理解；具体分工要查实验流程，不能从“融合”推断同时发声。 |
| It progressed from A and B to C | “研究从……逐步推进，最终……量化了认知干扰” | 这处机翻已经保留递进，并非语法错误。更清楚的表达应凸显 A、B 与 C 是研究阶段的内容，避免被读成工具—目的关系。 |
| Our findings reveal critical trade-offs … | “我们的发现揭示了各交互阶段的关键权衡” | 原意基本保留。后续整合段落时仍应保留这条承接信息；不能因为其他地方改得更清楚就删去它。 |
| users preferred the reliability … whereas … hedonic ratings … accessibility concerns | “用户更偏好传统唤醒词的可靠性……更高的愉悦度评分……可访问性方面的担忧” | 没有把不同评价维度之间的关系交代清楚。“可靠性受到看重”“体验更愉快”“某些用户使用困难”可能同时成立，不能合并为“某方案总体更好”。“可访问性”是否合适需按语境选词。 |
| a hybrid mechanism using a finger snap to terminate a spoken command | “采用手指 snapping 来终止语音指令的混合机制” | 英文动作词未转译，也没有落实“混合”是哪两种输入的分工；“终止语音指令”会让人误以为终止说话。正文可确认语音启动、响指停止控制操作。 |
| without increasing interference to the primary supervisory task | “并未增加对主要监督任务的干扰” | 字面基本正确，但没有明确监督任务与控制任务各是什么，也未展开比较对象。上下文不足时保留字面并提示核实，不直接补成“完全没有干扰”。 |
| mapping control to a sustained vowel extension | “将控制映射到持续元音延长” | 保留了术语，未呈现对应关系。正文显示发声期间操作持续、停止发声时操作停止；其他文献的 mapping 可能是不同规则。 |
| the choice of input mechanism is critical under cognitive load | “在认知负荷下，输入机制的选择至关重要” | 这处可用，不必为显示改译而另造措辞。只需确保相邻段落没有扩大适用范围。 |
| start-up and stop channels in supervisory AV contexts | “在监督型自动驾驶场景中作为启动和停止通道” | “监督型”含混，“启动／停止什么”未说清。正文把驾驶员的监督角色、语音系统唤醒与控制操作停止分别说明，译文可据此补明。 |
| motivate adaptive, multimodally redundant in-vehicle systems | “激励我们开发自适应、多模态冗余的车载系统” | 增加了未明确写出的“我们开发”主体，并堆叠技术标签。宜保留“为……系统设计提供启示”，在用户需要时展开两个设计特征。 |

## 三、正文如何让含混表述有明确落点

| 核查位置 | 正文已确认的内容 | 对翻译的约束 |
|---|---|---|
| 第2页 RQ1、RQ2、RQ3；第3页第2.2节 | 研究系统激活、连续 NDRA 控制及双任务监督干扰；相关工作分别讨论 activation 与 maintaining/terminating continuous control。 | 可将本摘要的压缩表达展开为唤醒与持续控制两部分；不将三个动词机械分配给三个实验。 |
| 第4页第3.1.3节 | 实验1比较唤醒词、双击掌、双响指和免唤醒。 | 这一部分激活的是车载语音系统，不是“激活一句指令”。 |
| 第7页第4.1.3节 | 实验2所有任务在系统持续激活的免唤醒状态下进行。 | 后面的持续与停止不是继续唤醒系统，也不等于保持或退出一整段会话。 |
| 第8页第4.1.3—4.1.4节与表5 | 音量调节、页面滚动；语音开始＋口头 stop、拍手或响指停止；延长元音期间操作维持，声音停止时操作停止。 | hybrid 的分工与 mapping 的操作含义有正文依据。仅凭摘要不足以填入这些步骤。 |
| 第12页第5.1.4节 | 实验3主任务为监视并回应声光警报，次任务为滚动列表并准确停在目标位置。 | 操作方式属于完成次任务的手段；主任务与次任务不可混同。 |
| 第12页第5.2.1节；第13页第5.2.3节；第14页讨论 | 响指与纯语音连续控制的反应时双任务成本未见显著差异；实验3中响指的次任务停止偏差更低。 | 不把“额外干扰”理解为相对只监督基线完全没有成本。精度优势的这一组结果具体来自实验3。 |
| 第13页第5.2.2.2节 | 响指等混合方法的主观感知干扰高于纯语音。 | 摘要“未增加干扰”的概括不能自动推广到所有主观与客观指标。纯翻译保留摘要，全文解读时另注这一限定。 |
| 第15页第6.2.1、6.2.2节 | 多种功能等价、可互换的输入通道；依据情境和用户能力调整交互方式。 | 可分别展开“多模态冗余”和“自适应”，不臆造具体传感器或算法。 |

## 四、从本例提炼出的可迁移要点

1. **先对齐研究对象，再润色中文。** 研究范式、具体机制、任务、方式与结果是不同层次。
2. **补清动作对象，不补造实验步骤。** 先确认被启动或停止的究竟是什么。
3. **把隐含指代写回中文。** 代词、共享主语、共享宾语和长定语不能只按字面顺序排放。
4. **关系类型必须守住。** 让步、并列、递进、因果、比较、条件与目的分别表达。
5. **术语需要可理解的落点。** “融合、映射、机制层面”不是理解工作的终点；能核实操作规则时，再具体化。
6. **保留描述与信息量。** 双重角色、关键权衡、样本量和条件不能为顺口而改掉或遗漏。
7. **指标与结论不越级。** 偏好不等于精度，精度不等于安全，客观成本与主观干扰可能分离。
8. **把证据层次放在正确位置。** 译文呈现原句；需要正文才能得到的释义和限定在必要时说明依据，不将猜测伪装成原文。
9. **承认原文可能压缩或含混。** 不为每一个词强行安排独立概念，也不凭含混断言作者中翻英或误用词。
10. **已清楚的机翻不必强改。** 目标是准确理解与可读性，不是保证每个短语都与机器翻译不同。
