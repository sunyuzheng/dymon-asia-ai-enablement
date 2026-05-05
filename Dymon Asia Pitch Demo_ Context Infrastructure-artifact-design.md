# **Artifact Design**

这一节解释 demo 现场会用到的 artifact:它们的设计目标、内容结构,以及它们之间如何串成一个自洽的故事。

## **设计标准:贴近客户场景,不是逼真**

Artifact 设计的目标不是"看不出来是 demo"——demo 本来就是 demo,无所谓——而是 让客户能往自己的场景里代入。Dymon 的 PM 看到这份 transcript / one-pager / Excel,应该觉得"这跟我们公司里发生的事很像",从而能立即把 demo 的能力 associate 到自己日常工作的具体场景。

这两个标准方向相同但视角不同:前者是观众视角(代入),后者是制作视角(逼真),前者更直接服务 sell 目标。

## **Meeting 设定**

主题:Dymon Asia 内部 onboarding 流程审阅会议(audit / review 性质)。  
会议性质:内部 review,不是 client-facing。一群 PM 和 associate 一起过一份 Q2 准备给 new joiner 用的 onboarding 材料,看哪里需要补、哪里需要改。

为什么选这个主题:

* 完全 ops-flavored,没有任何投资判断元素,观众不会被 derail 到 domain 争论  
* 但话题足够有内容——onboarding 涉及流程、人、客户、合同、SOP,能自然牵扯出 tribal knowledge  
* friction 抱怨在 review 过程中**穿插出现**,不作为议程项,避免编排痕迹  
* onboarding deck review 是 hedge fund 内部高频事件,观众的"我也想要"反应更直接

Demo 介绍 transcript 时的 verbal 长度:一句话

Yan 在 demo 现场介绍 transcript 时,只说一句:"这是上周我和团队对内部 onboarding 流程做的一次审阅会议——大家觉得 deck 哪里需要补、哪里需要改。" 不展开角色、不解释批评内容、不讲 transcript 里发生了什么具体讨论。然后直接让 AI 跑 summary,屏幕上出现 4-5 个 action items,Yan 用手指点一下 action item 1 和 action item 2,说"这两个 action 我现在就处理掉"。

这种处理方式的好处:观众的 cognitive load 在 setup 阶段被压到最低,所有注意力预算保留给后面 Beat 1 / Beat 2 的 demo 动作。Transcript 在屏幕上是视觉证据(让观众相信这是真实工作),不是理解对象(不需要观众读懂)。

参与者(transcript 文件里有,但 demo 介绍时不讲):

* Yan:senior PM,deck owner  
* Priya Nair:另一个 senior PM,被请来 review 的同事  
* Sarah Lim:associate-level,Action Item 2 的 executor

Sarah 定位为 associate 而不是 ops/admin/秘书:Dymon 这种规模的 hedge fund(多 PM、机构化运作),"associate handle 操作性 prep work" 这个模式比 "ops/admin" 更符合观众对自己组织的预期。Action Item 2 是 senior PM 把 prep work 委派给 associate 这个常见 workflow,观众一眼就能 associate 到自己组织里类似角色。

## **Meeting Transcript 内容骨架**

Transcript 全文 1500-1800 字(模拟 25-30 分钟会议),按 5-6 段组织,每段对应一个 action item 的诞生。

段落 1(开场,\~2 分钟):议程设定。Yan 简要说今天 review 的目的(Q2 onboarding 材料 v1 哪些需要补)。Priya 一句:"框架在,但有几个地方需要 align。"

段落 2(\~3 分钟):工作流程章节 — Action Item 1 在此诞生

* Priya 提出工作流程章节写得太抽象,new joiner 看完不知道周一具体干嘛  
* Yan 同意,提到 Yan 自己 team 和 Priya team 的做法不一样(buddy system vs case-driven),deck 里写法应该统一  
* Yan: "这事我们俩单独约个时间 align。"  
* → **Action Item 1**:Yan \+ Priya 下周找时间 align onboarding 流程

  friction 抱怨穿插点 1:Yan 顺嘴说一句"上次跟你约个会发四五封邮件对时间"——这句话是后面 demo 时 AI 自动找 slot 的精确反面 callback。

段落 3(\~3 分钟):工具栈章节 — Action Item 2 在此诞生

* Priya 提出工具栈这一节列了软件名但没说 new joiner 实际会卡在哪  
* Yan: "我想加几个具体 case。比如上次 Tom 进来卡在 Bloomberg 权限等了 3 天,这种事写进去才有用。"  
* Priya: "还有上次跟 ABC Capital 那个合规 onboarding,我们差点没赶上 deadline,SOP 4.2 节本来有但没 cross-reference 进 deck。"  
* Yan: "那这一节得整一下,Tom case \+ ABC Capital \+ SOP 4.2 串进去。这事我让 Sarah 先整理。"  
* → **Action Item 2**:Sarah 整理工具栈章节补充材料

  friction 抱怨穿插点 2:Yan 说"我自己整这事要翻 Tom follow-up email、找 ABC correspondence、翻 SOP——半小时找资料,所以一直拖着"——这是 Beat 2 demo 时跨文档自动拉的精确反面 callback。

段落 4(\~2 分钟):文化与价值观章节 — Action Item 3 诞生。文化章节太 corporate 缺具体故事,Sarah 收集 3-5 个内部小故事。(此 action 在 demo 中不演示)

段落 5(\~2 分钟):第一周 expectation 章节 — Action Item 4 诞生。first-week expectation 给的太满,Yan \+ Priya 下次 v2 review 时再讨论校准。(此 action 在 demo 中不演示)

段落 6(\~1 分钟):收尾。Yan 总结 4 个 action,散会。

## **Action Items**

总共 4 个,demo 时只演示 1 和 2。多 action 的好处是让 transcript 看起来不是为 demo 量身定做的——真实会议本来就有多个 action,我们只演示其中两件。

| \# | 内容 | Owner | Mechanism | Demo 演示? |
| :---- | :---- | :---- | :---- | :---- |
| 1 | Yan \+ Priya 下周 align onboarding 工作流程的统一做法 | Yan | 30 min meeting | 是, Beat 1 |
| 2 | Sarah 整理工具栈章节补充材料(Tom case / ABC KYC / SOP 4.2) | Sarah | One-pager \+ kickstart | 是, Beat 2 |
| 3 | Sarah 收集 3-5 个内部故事补入文化章节 | Sarah | Async collection | 否 |
| 4 | 重新校准 first-week expectation 任务量 | Yan \+ Priya | 下次 v2 review 时讨论 | 否 |

## **Beat 1 演示流程**

Yan 对 AI 说:"Action item 1 这个我得跟 Priya 当面 align 一下。看看她下周哪个 30 分钟空档我俩都有,发个 invite,邮件正文把 onboarding 流程这件事说一下,让她带她那边 buddy system 现行做法的资料过来。"

AI 执行链:

1. Google Calendar(read self):读 Yan 下周日程  
2. Google Calendar(read shared):读 Priya 下周日程  
3. Slot finder:找下周双方都空的 30 分钟 slot  
4. Outlook calendar(create invite):title "Onboarding flow alignment \- Q2 deck v2",30 分钟,加 video link  
5. Gmail send email:发邮件给 Priya,正文 \~150 字,说明背景 \+ 这次会要 align 什么 \+ 请她带的资料  
6. Push notification 给 Yan:"Done — invite sent to Priya, email delivered"

观众屏幕上看到:左边 transcript \+ meeting summary,右边并排 Google Calendar(invite 弹出)、Gmail(邮件发出),Yan 收到 desktop notification。

## **Beat 2 演示流程**

Yan 对 AI 说:"Action item 2 整理一下背景做个 one-pager。把上次 Tom 那个 onboarding case、ABC Capital KYC 流程、SOP 4.2 节相关条款都串进去,生成 one-pager,publish 到 Google Docs,share 给 Sarah,再发她一封短邮件让她按这份 one-pager kickstart。"

AI 执行链:

1. Cross-document retrieval — 同时查三个 source

   \- 本地 research / case notes:找 "Tom Liu Q1 onboarding follow-up"  
   \- Google Drive:找 "ABC Capital KYC correspondence Mar-Apr 2026"  
   \- Confluence:找 "SOP section 4.2 \- external compliance onboarding"

1. One-pager 生成:按 onboarding deck 第四节需要的结构组织,每段引用源文档(inline link 形式,便于 Sarah double check)  
2. Google Docs(publish):Markdown → Google Docs  
3. Google Docs(share):share 给 Sarah  
4. Gmail send email:短邮件给 Sarah,\~80 字,包含背景一句 \+ Doc 链接 \+ 一句明确 kickstart 内容  
5. Push notification 给 Yan:"Done — one-pager published, shared with Sarah, kickstart email sent"

观众屏幕上看到:左边 transcript,右边并排 Google Docs(one-pager 弹出 \+ share 通知)、Gmail(给 Sarah 的邮件发出)。

## **Beat 2 引用的三份 Background Docs**

这三份文档是 demo 必须事先准备的真实工作产物。每份的内容必须能精确支撑 one-pager 里对应的 claim。

Doc 1: Tom Liu Q1 onboarding follow-up note

* 格式:本地 research/case note,markdown,看起来像随手记  
* 长度:\~600 字  
* 内容要点:Tom 是 2026 Q1 进来的 new joiner,第一周卡在 Bloomberg 终端权限(IT ticket 走了 3 天),第二周卡在 internal research repo 命名规则,第三周才开始真正干活。Yan 自己的 takeaway:"下次 onboarding 必须把 IT 权限和 repo 规则写在 day-1 checklist 里"

Doc 2: ABC Capital KYC correspondence

* 格式:几封 email 的拼接(从 Gmail 导出的样子,带 from/to/timestamp/subject)  
* 长度:\~800 字(3-4 封 email)  
* 内容要点:2026-03 / 04 之间 ABC Capital compliance team 要求 Dymon onboarding 流程 cross-reference 他们的 KYC 框架,涉及 source-of-funds 文档追加,差点没赶上 2026-04-10 deadline。隐含 takeaway:这种 client-specific KYC 要求需要在 onboarding deck 里 explicit 提示

Doc 3: SOP 4.2 节 \- External Compliance Onboarding

* 格式:正式 SOP 文档(Confluence-style)  
* 长度:\~500 字  
* 内容要点:4.2.1 标准 KYC 步骤;4.2.2 客户特殊要求 ("若客户方有自己的 KYC 框架,联系 compliance manager 拉 cross-reference 表");4.2.3 escalation path;4.2.4 文档归档要求。这一节是 ABC Capital 那次本应被 cross-reference 但没人想起来的关键条款

三份文档的连接逻辑:

* Tom case \= "我们自己 new joiner 第一周会踩什么坑"  
* ABC Capital \= "我们的客户对 onboarding 有什么特殊要求"  
* SOP 4.2 \= "公司层面对 external compliance onboarding 的规范"  
* 这三件事串起来才能在 onboarding deck 第四节回答"new joiner 第一周该 surface 哪些高频问题",任何一份单独都不够

这是 cross-document retrieval 价值的具体兑现:不是简单做关键词检索,是把三份不同形式的工作记录串成一个 narrative,这正好是观众脑子里"如果我自己干要花 30 分钟"的那 30 分钟在做的事。

## **Beat 2 生成的 One-pager 结构**

One-pager 长度:\~600 字,1.5 页。结构:

* **Section 1 — 背景一段**(\~80 字):为什么需要补 onboarding deck 第四节,引用今早 review 会议的结论  
* **Section 2 — New joiner 第一周高频踩坑**(\~250 字):IT 权限申请流程(引用 Doc 1)、Internal repo 命名规则(引用 Doc 1)、客户特殊 onboarding 要求识别(引用 Doc 2)。每个子点末尾附"详见 \[link to source doc\]"  
* **Section 3 — SOP cross-reference**(\~150 字):在哪个 case 下要 trigger SOP 4.2;4.2.2 的 escalation path 是什么(引用 Doc 3\)  
* **Section 4 — Sarah 的 kickstart todo**(\~120 字):把 Section 2 的 3 个子点扩成 deck slide content;Section 3 的 SOP 引用做成 deck callout box;v2 完成后回到 Yan 做 final review

核心特点:每段都精确指向一份 background doc,observer 不需要"信任 AI 写得对"——所有引用都可以现场点 link 验证。Demo 时 Yan 可以做一个 "double check" 动作:鼠标悬停在某个 link 上,observer 看到 link 真的指向那份原文。

## **Compound Effect Excel 设计**

格式:.xlsx(或 Google Sheet),20 行 × 11 列。

Schema:

| 列名 | 含义 |
| :---- | :---- |
| date | 该 context 产生日期 |
| source | capture 形式(meeting / voice\_note / ai\_session / email / call\_transcript / research\_note) |
| participants | 涉及的人 |
| topic\_primary | 主话题 |
| topic\_secondary | 次话题/标签 |
| summary\_short | 一句话摘要 |
| linked\_context\_ids | 关联到哪些其他行 |
| derived\_artifact | 是否产出过 deliverable(one-pager / email / 空) |
| follow\_up\_status | 推进状态(done / pending / lost) |
| person\_owner | 负责人 |
| retrieval\_hint | 未来 query 时的 keyword |

20 行的内容设计:

* 6 行:本周(Demo "今天")的 context — 包含今早的 process review meeting、刚生成的 calendar invite、刚生成的 one-pager、给 Sarah 的 email、Yan 早上的 voice note、AI session  
* 5 行:上周 context,主要主题是 "China energy" — meeting / voice note / 客户电话 / research note / follow-up email  
* 4 行:再往前一周 — 包含 1 行 "印尼煤炭出口政策" 第一次出现(voice note,Yan)  
* 3 行:再往前 2-3 周 — 包含 1 行 "印尼煤炭出口" 第二次出现(客户电话,Priya 在场记录),1 行同主题第三次(AI session,某 macro analyst)  
* 2 行:更早 baseline context — 跟主题关系不大,只是让表格看起来不是为 demo 编出来的

关键约束:三行"印尼煤炭出口"的 derived\_artifact 列全部是空,这是 Pivot 2 "啊哈瞬间" 的 punchline:三个人想过同一件事,没有一次形成 deliverable。三行涉及的三个不同人(Yan / Priya / 一个 macro analyst),三行的 source 类型也不同(voice\_note / call / ai\_session)——证明这件事不是一个人在重复想,是 org 里多个人独立想到了同一件事。

预设 pivot 视图(demo 时直接打开,不要现场搜):

* View 1: filter "topic\_primary 包含 China energy 或印尼煤炭"  
* View 2: filter "topic\_primary 包含 印尼煤炭" AND "derived\_artifact 为空",group by person

这两个 pivot 是 demo 里最锋利的可视化:它们把开场说的 "miss opportunities" 从抽象 claim 变成观众面前的具体证据,直接兑现整个 sales line 的第二点。  
