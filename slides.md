---
theme: default
title: 小满 · 餐饮 AI 智能经营助手
info: |
  ## 小满 · 客户解决方案
  连接餐厅已有经营数据，在现有经营系统之上增加 AI 能力。

  **让现有系统负责记录，让 AI 负责理解，让老板负责决策。**
transition: slide-left
drawings:
  persist: false
class: text-left
---

<div class="xm-cover">
  <div class="xm-cover-grid"></div>
  <div class="xm-cover-glow"></div>
  <div class="xm-cover-inner">
    <div class="xm-cover-kicker"><span class="xm-cover-dot"></span>餐饮门店 · AI 智能经营助手</div>
    <h1>小满</h1>
    <p class="xm-cover-sub">连接餐厅已有的经营数据，在现有经营系统之上增加一层 AI 能力。<br>解决两件事：<b>不断货，不漏单</b>。</p>
    <div class="xm-cover-pillars">
      <div><span class="n">01</span><b>让现有系统负责记录</b></div>
      <div><span class="n">02</span><b>让 AI 负责理解</b></div>
      <div><span class="n">03</span><b>让老板负责决策</b></div>
    </div>
  </div>
  <div class="xm-cover-foot"><span>智能补货</span><span>库存风险预测</span><span>经营分析</span><span>AI 店长</span><span>AI 前台</span></div>
</div>

<!--
开场：一句话定位。
"小满不是一套新的 ERP，也不是要替换大家已经在用的收银、库存、采购系统。
它做的事情是——把餐厅已经产生的经营数据接过来，让 AI 读懂它，然后直接告诉老板该做什么。"
-->

---
layout: default
---

# ERP × 小满：谁记录，谁判断


<table class="xm-table mt-1">
<thead><tr><th></th><th class="col-ls">ERP · 经营数据底座</th><th class="col-xm">小满 · AI 智能经营层</th></tr></thead>
<tbody>
<tr><td>定位</td><td class="col-ls">记录已发生的业务事实</td><td class="col-xm">理解事实、做出判断</td></tr>
<tr><td>负责</td><td class="col-ls">销售、库存、采购、报损、供应商、菜品配方的准确记录与留存</td><td class="col-xm">读取这些数据 → 分析 → 预测 → 生成可执行的建议</td></tr>
<tr><td>回答</td><td class="col-ls">「现在库存多少？最近卖了多少？采购了多少？」</td><td class="col-xm">「明天可能卖多少？什么时候可能缺货？应该采购多少？」</td></tr>
<tr><td>输出</td><td class="col-ls">准确、可追溯、可核对的经营数据</td><td class="col-xm">老板一看就懂、可直接确认或调整的决策建议</td></tr>
</tbody>
</table>

<!--
职责边界页。这句话建议逐字念出来：
"ERP 负责记录事实，小满负责理解事实、做出判断。"
让客户明白我们没有越界，也不是要接管他们的业务系统。
-->

---
layout: default
---

# 智能补货：一个完整的经营闭环


<div class="flex gap-2 flex-wrap justify-center">
  <span class="xm-chip"><span class="i-carbon-chart-line xm-ico"></span>销售</span>
  <span class="xm-chip"><span class="i-carbon-inventory-management xm-ico"></span>库存</span>
  <span class="xm-chip"><span class="i-carbon-purchase xm-ico"></span>采购</span>
  <span class="xm-chip"><span class="i-carbon-warning-alt xm-ico"></span>报损</span>
  <span class="xm-chip"><span class="i-carbon-book xm-ico"></span>菜品配方</span>
  <span class="xm-chip"><span class="i-carbon-delivery xm-ico"></span>外卖</span>
  <span class="xm-chip"><span class="i-carbon-calendar xm-ico"></span>预订</span>
</div>

<div class="flex justify-center text-[#94a3b8] my-1.5"><div class="i-carbon-arrow-down text-base"></div></div>

<div class="flex items-stretch gap-1">
  <div class="xm-node flex-1"><div class="xm-node-idx">1</div><div class="text-[0.84rem] font-700">需求预测</div><div class="xm-note mt-0.5">明天 / 未来一周卖多少</div></div>
  <div class="xm-flow-arrow"><div class="i-carbon-arrow-right text-sm"></div></div>
  <div class="xm-node flex-1"><div class="xm-node-idx">2</div><div class="text-[0.84rem] font-700">库存风险</div><div class="xm-note mt-0.5">什么时候可能缺货</div></div>
  <div class="xm-flow-arrow"><div class="i-carbon-arrow-right text-sm"></div></div>
  <div class="xm-node flex-1" style="border-color:#cdeee0;background:var(--xm-brand-soft)"><div class="xm-node-idx" style="background:#fff">3</div><div class="text-[0.84rem] font-700">补货建议</div><div class="xm-note mt-0.5">买多少 / 找谁买</div></div>
  <div class="xm-flow-arrow"><div class="i-carbon-arrow-right text-sm"></div></div>
  <div class="xm-node flex-1" style="border-color:#0a1628;background:#0a1628;color:#fff"><div class="xm-node-idx" style="background:rgba(255,255,255,.16);color:#fff">4</div><div class="text-[0.84rem] font-700">老板确认</div><div class="text-[0.72rem] mt-0.5" style="color:rgba(255,255,255,.6)">一键确认或调整</div></div>
  <div class="xm-flow-arrow"><div class="i-carbon-arrow-right text-sm"></div></div>
  <div class="xm-node flex-1"><div class="xm-node-idx">5</div><div class="text-[0.84rem] font-700">执行采购</div><div class="xm-note mt-0.5">生成采购单</div></div>
</div>

<div class="flex items-center gap-2.5 mt-2 text-[0.75rem] text-[#94a3b8]">
  <div class="i-carbon-arrow-left text-sm"></div>
  <div class="flex-1 border-t border-dashed border-[#cbd5e1]"></div>
  <span>到货入库 → 更新库存数据 → 进入下一轮判断</span>
  <div class="flex-1 border-t border-dashed border-[#cbd5e1]"></div>
</div>

<div class="grid grid-cols-[1.4fr_1fr] gap-3 mt-3">
  <div class="xm-card-flat" style="padding:14px 18px">
    <div class="xm-label mb-1.5">小 满 的 建 议 长 这 样</div>
    <div class="flex items-center text-[0.78rem] pb-1 border-b border-[#eef2f7]"><span class="font-600" style="width:42px;flex:none">牛肉</span><span style="width:122px;flex:none">建议采购 <b class="text-[#0a7d57]">+15 kg</b></span><span class="text-[#94a3b8]">供应商甲 · 周三配送 · 次日达</span></div>
    <div class="flex items-center text-[0.78rem] py-1 border-b border-[#eef2f7]"><span class="font-600" style="width:42px;flex:none">生菜</span><span style="width:122px;flex:none">建议采购 <b class="text-[#0a7d57]">+8 kg</b></span><span class="text-[#94a3b8]">供应商乙 · 每日 22:00 前下单</span></div>
    <div class="flex items-center text-[0.78rem] py-1 border-b border-[#eef2f7]"><span class="font-600" style="width:42px;flex:none">虾滑</span><span class="text-[#d98207]" style="width:122px;flex:none">库存偏高 · 暂缓</span><span class="text-[#94a3b8]">供应商丙 · 起订量 10 箱，未达量</span></div>
    <div class="xm-note mt-1.5">依据：近 4 周周六销量 · 已确认预订 12 桌 · 在途未到货 · 供应商配送周期</div>
  </div>
  <div class="xm-card-flat" style="padding:14px 18px">
    <div class="xm-label mb-1.5">建 议 要 先 过 这 几 关</div>
    <div class="flex text-[0.78rem] py-0.5"><span class="font-600" style="width:60px;flex:none">供应商</span><span class="xm-note">报价 · 账期 · 供货是否稳定</span></div>
    <div class="flex text-[0.78rem] py-0.5"><span class="font-600" style="width:60px;flex:none">供货方式</span><span class="xm-note">配送日 · 起订量 · 到货时效</span></div>
    <div class="flex text-[0.78rem] py-0.5"><span class="font-600" style="width:60px;flex:none">在途库存</span><span class="xm-note">已下单未到货的，不重复买</span></div>
    <div class="flex text-[0.78rem] py-0.5"><span class="font-600" style="width:60px;flex:none">库容保质</span><span class="xm-note">放不下、放不久的，少买</span></div>
  </div>
</div>


<!--
核心业务闭环页，全场的重心。
强调：这不是一个"自动下单"的功能，而是一个"AI 建议 + 老板确认"的闭环。
保留人工确认，既是安全边界，也是客户最容易接受的落地方式。

建议必须落到现实约束上，否则只是"算了个数"，老板没法照着执行：
- 供应商：不只说买多少，还要说清找谁买、报价与账期、这家供得稳不稳
- 供货方式：供应商的配送日、起订量、到货时效，直接决定"今天要不要下单、一次下多少"
- 在途库存：已经下单还没到的货不能再买一遍，否则建议重复、占压现金
- 库容与保质期：放不下、放不久的品类要主动往下压

客户最关心的是"这条建议明天能不能真的执行"，所以建议里必须带供应商和到货方式。
右侧「建议要先过这几关」就是把这条说清楚 —— 小满给的不是一个数字，是一个可执行的采购动作。
-->

---
layout: default
---

# 整体架构：五层各管一件事

<div class="flex flex-col gap-3 mt-1">

  <div class="xm-layer" style="padding:14px 22px">
    <div class="xm-layer-title" style="font-size:0.76rem">角色交互层</div>
    <div class="text-[0.85rem]" style="color:var(--xm-ink-soft)">人在这里提问、看建议、拍板</div>
    <div class="ml-auto xm-note">老板 · 店长 · 客户</div>
  </div>
  <div class="xm-flux" style="gap:1.2rem"><span>↓ 人提问</span><span>↑ AI 返回建议</span></div>

  <div class="xm-layer xm-layer-brand" style="padding:26px 28px;align-items:flex-start">
    <div class="xm-layer-title" style="color:rgba(255,255,255,.72);font-size:0.84rem;padding-top:6px">AI 能力层</div>
    <div class="flex-1 flex flex-col gap-1.5">
      <div class="text-[1.12rem] font-800">一个 AI 底座，服务所有角色</div>
      <div class="flex items-center gap-2"><span class="xm-cell xm-cell-glass">AI 调度器</span><span class="xm-cell xm-cell-glass">统一 AI 底座</span><span class="text-[0.72rem] ml-auto" style="color:rgba(255,255,255,.6)">全系统只有一套，角色差异放在配置里</span></div>
    </div>
  </div>
  <div class="xm-flux" style="gap:1.2rem"><span>↑ 整理好的经营数据</span></div>

  <div class="xm-layer" style="padding:16px 22px;align-self:center;width:86%">
    <div class="xm-layer-title">系统层</div>
    <div class="text-[0.9rem]" style="color:var(--xm-ink-soft)">把现有系统的数据整理成一套口径</div>
    <div class="ml-auto xm-note">数据接入 · 归一化 · 清洗</div>
  </div>

  <div class="xm-layer" style="padding:15px 22px;align-self:center;width:74%">
    <div class="xm-layer-title" style="font-size:0.76rem">数据源层</div>
    <div class="text-[0.85rem]" style="color:var(--xm-ink-soft)">现有系统照常跑，数据从这儿来</div>
    <div class="ml-auto xm-note">联锁云 ERP · 美团外卖 · 收银 POS · 供应商 / 预订</div>
  </div>

  <div class="xm-layer xm-layer-support xm-layer-tight" style="padding:15px 22px;align-self:center;width:62%">
    <div class="xm-layer-title" style="font-size:0.76rem">数据与知识底座</div>
    <div class="text-[0.85rem]" style="color:var(--xm-ink-soft)">给上面每一层提供数据</div>
    <div class="ml-auto xm-note">业务数据 · SOP / 规则 · 按意思找资料</div>
  </div>
</div>


<!--
架构页。前面已经把边界（谁记录、谁判断）和核心场景（智能补货）讲完了，这里再展开整体形状，把方案立住。
按"数据源层 → 系统层 → AI 能力层 → 角色交互层"自下而上讲，最后补一句底座的定位。
这一页的字号是有意分级的，讲的时候顺着这个分级走：
1. 全页只有一个重点 —— 中间那条深色的「AI 能力层」（字号最大）。
   一句话就讲它：一个 AI 底座，服务所有角色。调度器只转达、不自己回答，角色差异全放进配置里。
   上面四页讲的能力，都长在这一条上。
2. 中等字号的「系统层」是给 AI 供料的：把现有系统的数据整理成一套口径（接入 → 归一化 → 清洗）。
   它不产生判断，只负责把数据弄干净。这里可以顺势重复一遍第 2 页的边界。
3. 最小字号的「角色交互层」「数据源层」和虚线框的「数据与知识底座」是配角，一笔带过即可：
   人在这提问和拍板；数据从现有系统来，不另建一套；底座横向支撑上面每一层，
   用虚线框就是为了让它看起来"不在流程里"。
4. 数据源不止联锁云 —— 联锁云是经营数据底座，美团、收银、供应商、预订都是来源。
   客户问起来要能答"再加一个来源，加一块就行"，不用推倒重来。
5. 底部这句话是全场定位：叠加，不是替换。客户最怕的是再来一套系统要人伺候。
-->

---
layout: default
---

# AI 系统设计：全公司只有一个 AI



<div class="xm-tree">
  <div class="xm-tree-entry">同一个入口<span>有事直接开口问 —— 先搞明白要办什么事，再去查、去动；它只在门口接单，答案不在门口给</span></div>
  <div class="xm-tree-stem"></div>
  <div class="xm-tree-root"><b>一个 AI</b><span>听得懂话 · 记得住事 · 会查资料 · 能干活 —— 全公司就这一个</span></div>
  <div class="xm-tree-stem"></div>
  <div class="grid grid-cols-3 gap-4" style="width:78%">
    <div class="xm-card-flat xm-tech-sq">
      <div class="flex items-center gap-2.5">
        <div class="xm-ico-box xm-ico-brand" style="width:34px;height:34px;font-size:1.15rem"><div class="i-carbon-chat"></div></div>
        <div class="text-[1.02rem] font-800">听得懂大白话</div>
      </div>
      <div class="xm-tech-sq-bullets">
        <div class="b"><span>一句话就能问，不用开报表、不用会筛选</span></div>
        <div class="b"><span>问得含糊，它会追问一句，不自己瞎猜</span></div>
        <div class="b"><span>昨天说过的今天接得上，不用重新交代</span></div>
      </div>
      <div class="mt-auto pt-3"><span class="xm-chip">怎么说话都能用</span></div>
    </div>
    <div class="xm-card-flat xm-tech-sq">
      <div class="flex items-center gap-2.5">
        <div class="xm-ico-box xm-ico-brand" style="width:34px;height:34px;font-size:1.15rem"><div class="i-carbon-tool-kit"></div></div>
        <div class="text-[1.02rem] font-800">真能动手干活</div>
      </div>
      <div class="xm-tech-sq-bullets">
        <div class="b"><span>查销量、查库存、出补货单、回消息，都是它来</span></div>
        <div class="b"><span>能动什么、不能动什么，规矩都提前定好</span></div>
        <div class="b"><span>以后接新系统，就是再多给它一件工具</span></div>
      </div>
      <div class="mt-auto pt-3"><span class="xm-chip">规矩管住动作</span></div>
    </div>
    <div class="xm-card-flat xm-tech-sq">
      <div class="flex items-center gap-2.5">
        <div class="xm-ico-box xm-ico-brand" style="width:34px;height:34px;font-size:1.15rem"><div class="i-carbon-book"></div></div>
        <div class="text-[1.02rem] font-800">只用你家的账本</div>
      </div>
      <div class="xm-tech-sq-bullets">
        <div class="b"><span>菜品、SOP、制度、规则，学的是你家自己那一套</span></div>
        <div class="b"><span>找不出依据就不答，每句都报得出出处</span></div>
        <div class="b"><span>确认过的事它记得，下次直接接着用</span></div>
      </div>
      <div class="mt-auto pt-3"><span class="xm-chip">不编，不乱说</span></div>
    </div>
  </div>
</div>

<div class="xm-flow-io mt-3.5">
  <div><span class="i-carbon-arrow-down"></span> <b>喂给它的</b> —— 全是真实的经营数字（联锁云 · 美团 · POS）</div>
  <div><b>它交出来的</b> —— 补货建议 · 缺货预警 · 顾客回复 <span class="i-carbon-arrow-up"></span></div>
</div>

<!--
AI 系统设计页，这页故意不讲术语，就一句大白话：全公司只有一个 AI，不是每个部门各建一套。
1. 主干：上面那扇门只接单 —— 先搞明白要办什么事；真正答题的，是中间这一个 AI。
2. 下面三个方块是它好用的三件事：
   听得懂大白话 —— 一句话就能问，问不清会追问，前后说过的接得上；
   真能动手 —— 查数、出单、回消息，能动什么被提前定好的规矩管着；
   只用你家的账本 —— 答的每一句都有店里的数据和制度作依据，没依据就不答。
3. 底部两行收尾：喂进去的是真实经营数字，交出来的是能直接执行的建议和回复。
4. 这页和架构页"一个 AI 底座、差异放配置"是同一个意思，只是这页全说大白话 ——
   客户要是问"底座/调度器去哪了"，答：就是上面这扇门和这一个 AI，名字起复杂了反而不好讲。
-->

---
layout: default
---

# AI 店长：老板直接问，AI 直接答


<div class="grid grid-cols-[1.02fr_1fr] gap-4">
  <div class="xm-phone">
    <div class="xm-phone-bar"><div class="i-carbon-chat text-base" style="color:var(--xm-brand-dark)"></div>小满 · 经营助手</div>
    <div class="flex flex-col gap-3.5">
      <div class="xm-bubble xm-bubble-user">这个月毛利怎么掉了？</div>
      <div class="xm-bubble xm-bubble-ai"><div class="xm-ai-name"><div class="i-carbon-machine-learning-model"></div>小 满</div>本月毛利率 <b>52.1%</b>，比上月下降 <b style="color:#d98207">3.2pt</b>。主要原因：牛肉采购价上涨 8%，以及报损率从 2.1% 升到 3.4%（集中在叶菜）。</div>
      <div class="xm-bubble xm-bubble-user">周六要不要多备点牛肉？</div>
      <div class="xm-bubble xm-bubble-ai"><div class="xm-ai-name"><div class="i-carbon-machine-learning-model"></div>小 满</div>建议 <b style="color:var(--xm-brand-dark)">+15 kg</b>。依据：近 4 周周六牛肉销量均值 18.6kg，本周六已有 12 桌预订（含 3 桌牛肉锅），天气转凉带动锅类销量上行。</div>
    </div>
  </div>
  <div class="flex flex-col gap-4">
    <div class="xm-card-flat flex items-start gap-2.5"><div class="xm-ico-box xm-ico-brand"><div class="i-carbon-analytics"></div></div><div><div class="text-[0.88rem] font-700">经营分析</div><div class="xm-note mt-0.5">营业额、毛利、菜品结构、报损，一句话问出结论。</div></div></div>
    <div class="xm-card-flat flex items-start gap-2.5"><div class="xm-ico-box xm-ico-amber"><div class="i-carbon-warning-alt"></div></div><div><div class="text-[0.88rem] font-700">库存风险预警</div><div class="xm-note mt-0.5">提前告知哪道菜、哪个原料快卖断。</div></div></div>
    <div class="xm-card-flat flex items-start gap-2.5"><div class="xm-ico-box xm-ico-brand"><div class="i-carbon-shopping-cart"></div></div><div><div class="text-[0.88rem] font-700">补货建议</div><div class="xm-note mt-0.5">给出品类、数量、到货时间与判断依据。</div></div></div>
    <div class="xm-soft">
      <div class="xm-note"><b class="text-[#0a1628]">所有回答都基于真实经营数据。</b>小满只读联锁云里已发生的销售、库存、采购与报损，不猜测、不虚构。</div>
    </div>
  </div>
</div>

<!--
AI 店长交互页。用真实对话代替功能罗列。
如果客户追问"数据从哪来"，回答：全部来自联锁云已经记录的事实，AI 只做理解和推断。
-->

---
layout: default
---

# AI 前台：把每一次咨询接住，也把需求变成数据


<div class="grid grid-cols-[1.02fr_1fr] gap-4">
  <div class="xm-phone">
    <div class="xm-phone-bar"><div class="i-carbon-chat text-base" style="color:var(--xm-brand-dark)"></div>小满 · 顾客咨询</div>
    <div class="flex flex-col gap-4">
      <div class="xm-bubble xm-bubble-user">明晚 7 点，8 个人还有位置吗？</div>
      <div class="xm-bubble xm-bubble-ai"><div class="xm-ai-name"><div class="i-carbon-machine-learning-model"></div>小 满</div>明晚 19:00 还有位置，已为您预留 <b>8 人桌</b>。需要加一张儿童座椅吗？</div>
      <div class="xm-bubble xm-bubble-user">要的，另外你们招牌牛肉还有吗？</div>
      <div class="xm-bubble xm-bubble-ai"><div class="xm-ai-name"><div class="i-carbon-machine-learning-model"></div>小 满</div>有的。已备注 <b>儿童座椅 1 张</b>。要不要提前为您预留一份招牌牛肉锅？量有限，先备着更稳妥。</div>
    </div>
  </div>
  <div>
    <div class="grid grid-cols-2 gap-4">
      <div class="xm-card-flat"><div class="xm-ico-box xm-ico-brand mb-3"><div class="i-carbon-calendar"></div></div><div class="text-[0.86rem] font-700">预订接待</div><div class="xm-note mt-1.5">人数、时间、忌口一次问清</div></div>
      <div class="xm-card-flat"><div class="xm-ico-box xm-ico-brand mb-2"><div class="i-carbon-restaurant"></div></div><div class="text-[0.86rem] font-700">菜品咨询</div><div class="xm-note mt-0.5">招牌菜、口味、过敏原秒回</div></div>
      <div class="xm-card-flat"><div class="xm-ico-box xm-ico-brand mb-2"><div class="i-carbon-time"></div></div><div class="text-[0.86rem] font-700">排队与等位</div><div class="xm-note mt-0.5">告知等待时间，缓解高峰压力</div></div>
      <div class="xm-card-flat"><div class="xm-ico-box xm-ico-brand mb-2"><div class="i-carbon-idea"></div></div><div class="text-[0.86rem] font-700">推荐与加购</div><div class="xm-note mt-0.5">结合库存推荐更合适的菜</div></div>
    </div>
    <div class="xm-banner xm-banner-brand mt-5">
      <div class="i-carbon-flow text-[1.1rem]"></div>
      <div>这轮对话产生了 <b>1 条预订 + 1 条菜品意向</b> —— 回流成经营数据，计入明天的销量预测。</div>
    </div>
  </div>
</div>

<!--
AI 前台/客户交互页。
注意把"前台交互"和"经营数据"连起来 —— 这是小满区别于普通客服机器人的地方。
-->

---
layout: default
---

# 实施与数据接入：不改系统，先把数据用起来


<div class="grid grid-cols-2 gap-4">
  <div>
    <div class="xm-label mb-5">数 据 接 入 · 可 适 配 的 三 种 情 况</div>
    <div class="flex flex-col gap-5">
      <div class="xm-card-flat flex items-start gap-2.5"><div class="xm-chip-brand">情况一</div><div><div class="text-[0.86rem] font-700 mt-1">数据已在现有系统中</div><div class="xm-note mt-0.5">通过客户现有系统 / 联锁云读取，无需额外对接。</div></div></div>
      <div class="xm-card-flat flex items-start gap-2.5"><div class="xm-chip-brand">情况二</div><div><div class="text-[0.86rem] font-700 mt-0.5">有系统，但接口不好接</div><div class="xm-note mt-0.5">先定期导出表格对接，跑通业务再优化。</div></div></div>
      <div class="xm-card-flat flex items-start gap-2.5"><div class="xm-chip-brand">情况三</div><div><div class="text-[0.86rem] font-700 mt-0.5">数据源不在现有系统内</div><div class="xm-note mt-0.5">由小满直接接入对应数据源（如美团、收银、手工录入）。</div></div></div>
    </div>
  </div>
  <div>
    <div class="xm-label mb-5">实 施 路 径 · 从 单 点 场 景 切 入</div>
    <div class="flex flex-col gap-0">
      <div class="flex gap-3"><div class="flex flex-col items-center"><div class="xm-dot-num">1</div><div class="xm-dot-line"></div></div><div class="pb-12"><div class="text-[0.86rem] font-700">接入数据</div><div class="xm-note">打通销售、库存、采购等基础经营数据</div></div></div>
      <div class="flex gap-3"><div class="flex flex-col items-center"><div class="xm-dot-num">2</div><div class="xm-dot-line"></div></div><div class="pb-12"><div class="text-[0.86rem] font-700">理解数据</div><div class="xm-note">建立菜品、配方、供应商与单位的对应关系</div></div></div>
      <div class="flex gap-3"><div class="flex flex-col items-center"><div class="xm-dot-num">3</div><div class="xm-dot-line"></div></div><div class="pb-12"><div class="text-[0.86rem] font-700">跑通场景</div><div class="xm-note">从「智能补货」单点切入，先解决不断货</div></div></div>
      <div class="flex gap-3"><div class="flex flex-col items-center"><div class="xm-dot-num">4</div></div><div><div class="text-[0.86rem] font-700">扩展能力</div><div class="xm-note">逐步扩展到经营分析、AI 店长与 AI 前台</div></div></div>
    </div>
  </div>
</div>


<!--
实施页。客户最容易问的两个问题：
1. 我现在的系统能接上吗？ —— 三种情况都能接，不写死接口。
2. 要多久？ —— 从智能补货单点切入，先看到效果再扩展。
-->

---
layout: default
---

# 技术选型：都用成熟的东西，不从零造轮子


<div class="grid grid-cols-3 gap-4">

  <div class="xm-card-flat xm-tech-sq">
    <div class="flex items-center gap-3">
      <div class="xm-ico-box xm-ico-brand" style="width:40px;height:40px;font-size:1.4rem"><div class="i-carbon-function"></div></div>
      <div>
        <div class="xm-tech-sq-name">Node.js</div>
        <div class="xm-note mt-0.5">服务端 · 数据 / 工具 / 权限 / 接入</div>
      </div>
    </div>
    <div class="xm-tech-sq-bullets">
      <div class="b"><span>与前端同一套语言，接口、权限、数据口径在一个工程里对齐</span></div>
      <div class="b"><span>数据接入、工具服务、权限系统一套人马维护，不用养两支队伍</span></div>
      <div class="b"><span>生态最成熟的运行时之一，招得到人、查得到资料</span></div>
    </div>
    <div class="mt-auto pt-4"><span class="xm-chip">一套人马就能维护</span></div>
  </div>

  <div class="xm-card-flat xm-tech-sq xm-tech-sq-brand">
    <div class="flex items-center gap-3">
      <div style="width:40px;height:40px;border-radius:12px;background:rgba(255,255,255,.16);display:flex;align-items:center;justify-content:center;font-size:1.4rem;color:#fff"><div class="i-carbon-machine-learning-model"></div></div>
      <div>
        <div class="xm-tech-sq-name">pi</div>
        <div class="mt-0.5" style="font-size:0.74rem;color:rgba(255,255,255,.65)">AI 层 · Agent Harness，跑在服务端里</div>
      </div>
    </div>
    <div class="xm-tech-sq-bullets">
      <div class="b"><span>不自研 AI 框架，基于成熟的 pi 做二次开发</span></div>
      <div class="b"><span>小满只补业务定制：工具清单 · 角色权限 · 知识库</span></div>
      <div class="b"><span>模型按效果与成本随时替换，不绑死任何供应商</span></div>
    </div>
    <div class="mt-auto pt-4"><span class="xm-chip" style="background:rgba(255,255,255,.14);border-color:transparent;color:#fff">创新只发生在这一层</span></div>
  </div>

  <div class="xm-card-flat xm-tech-sq">
    <div class="flex items-center gap-3">
      <div class="xm-ico-box xm-ico-brand" style="width:40px;height:40px;font-size:1.4rem"><div class="i-carbon-mobile"></div></div>
      <div>
        <div class="xm-tech-sq-name">uni-app</div>
        <div class="xm-note mt-0.5">界面端 · 小程序 / H5 / App</div>
      </div>
    </div>
    <div class="xm-tech-sq-bullets">
      <div class="b"><span>一次开发、多端运行，微信小程序、H5、App 都覆盖</span></div>
      <div class="b"><span>与服务端同一套 JS 体系，前后端衔接没有切换成本</span></div>
      <div class="b"><span>生态成熟，主流平台全部支持</span></div>
    </div>
    <div class="mt-auto pt-4"><span class="xm-chip">一套代码，多端就绪</span></div>
  </div>

</div>

<div class="xm-banner xm-banner-brand mt-4">
  <div class="i-carbon-checkmark-outline text-[1.1rem]"></div>
  <div>工程承诺 —— <b>成熟技术打底，创新只发生在 AI 那一层。</b></div>
</div>

<!--
技术栈页。从左到右三块各答一个客户会问的问题：
Node.js 为什么是服务端 —— 与前端同一套语言和类型体系，接口、权限、数据口径在一个工程里，团队成本最低。
pi 为什么是 AI 层 —— 不自研 AI 框架，精力全放在业务定制（工具清单、角色权限、知识库）上；模型按效果与成本可替换。
uni-app 为什么是界面端 —— 一次开发覆盖小程序 / H5 / App，与服务端同一套 JS 体系，衔接顺畅。
收口：成熟技术打底，选型不绑死供应商；客户换收银、换外卖平台，小满照常运行。
-->

---
layout: default
---

# 报价：MVP 一次性交付


<div class="xm-price xm-price-row">
  <div>
    <div class="xm-label">M V P   一 次 性 交 付 价</div>
    <div class="xm-price-num"><span>¥</span>8<i>万</i></div>
  </div>
  <div class="xm-price-side">
    <div class="xm-label">交 付 周 期</div>
    <div class="text-[1.05rem] font-800">两个月</div>
  </div>
</div>

<div class="xm-label mt-3 mb-2">交 付 内 容</div>

<div class="flex flex-col gap-1.5">
  <div class="xm-deliver"><div class="i-carbon-checkmark-outline"></div><b>智能补货闭环</b><span>需求预测 → 库存风险判断 → 补货建议 → 老板确认 → 采购执行记录</span></div>
  <div class="xm-deliver"><div class="i-carbon-checkmark-outline"></div><b>客户咨询闭环</b><span>顾客咨询 → AI 回复 → 执行动作 → 系统记录</span></div>
  <div class="xm-deliver"><div class="i-carbon-checkmark-outline"></div><b>老板端</b><span>微信小程序 / H5，一次开发、多端运行</span></div>
  <div class="xm-deliver"><div class="i-carbon-checkmark-outline"></div><b>数据接入与归一化</b><span>数据 · 清洗 · 结构化 · 口径统一</span></div>
</div>

<div class="xm-formula mt-3">
  <div class="xm-label mb-1.5">计 价 依 据 · 中国软件行业协会《软件开发和服务项目价格构成及评估方法》</div>
  <div class="text-[0.8rem] mb-2" style="color:var(--xm-ink-soft)"><b>一句话：两个月（约 45 个工作日）的工作量，折算成 8 万。</b></div>
  <div class="xm-formula-row">
    <div class="xm-formula-eq">软件开发价格 ＝ 开发工作量 × 开发费用 / 人月　　｜　　开发工作量 ＝ 估算工作量经验值 × 风险系数 σ × 复用系数 τ</div>
    <div>估算工作量经验值 ＝ 两个月 ≈ 45 人天 ÷ 21.75 ≈ <em>2.07 人月</em>　｜　σ ＝ <em>1.5</em>（接入与 AI 效果的不确定性）　｜　τ ＝ <em>0.9</em>（复用 pi 骨架与成熟技术，不做重复开发）</div>
    <div>开发工作量 ＝ 2.07 × 1.5 × 0.9 ≈ <em>2.79 人月</em>　｜　开发费用 / 人月 ＝ 20,000 × 1.45 ≈ <em>29,000 元</em></div>
    <div>软件开发价格 ＝ 2.79 × 29,000 ≈ <b>8.0 万元</b></div>
  </div>
</div>

<!--
报价页，放最后。只给一个数：MVP 一次性交付价。
讲的时候先说范围、再说价 —— 让客户先确认"这就是我要的东西"，再落到数字上。

底部的计价依据是这一页的重点，用的是中国软件行业协会《软件开发和服务项目价格构成及评估方法》，
和国标 GB/T 36964 是同一套人月口径。公式里三个参数都要能当场解释：
- 估算工作量经验值 45 人天（两个月）：按上面四项交付内容逐项估出来的，不是拍脑袋
- 风险系数 σ 1.5：数据接入的不确定性和 AI 效果调优都算进去了；工期拉到两个月，接入与调优的空间也更大
- 复用系数 τ 0.9：基于 pi 骨架和成熟技术栈，不做重复开发，所以往下打折
开发费用/人月 29,000 元 = 人力成本基数 20,000 × 综合系数 1.45（含税与全部开销）。
这是单人交付的费率，没有组织级的管理费与办公费分摊，所以比软件公司的报价低。

口径要一致：45 人天（两个月）是"只做补货这一个闭环"的量，所以范围必须锁死。
客户一说"顺手把 AI 前台也做了"，人天立刻翻倍 —— 那就得按同一套公式重新算，不是在这一页上还价。

注意：这一页要展示的前提是锁死范围 —— 演示时不要临场加需求，加一项价格就得动。
如果客户要求让价，优先谈范围（先做哪些、后做哪些），不要直接砍总价，也不要动公式里的参数 ——
参数一动，这套方法的可信度就没了。
-->
