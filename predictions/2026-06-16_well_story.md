# 各位，你们村那口井，底下可能不是水 — 预测日志

---

**Article ID**: `ee347cb2b65c`
**Title**: 各位，你们村那口井，底下可能不是水
**Rubric Version**: **v0**
**预测时间**: 2026-06-16（基于最终稿）
**Script Path**: `scripts/2026-06-16_well_story.md`
**Script Hash**: `sha256:ee347cb2b65c`
**Target Duration (s)**: 480 (8min)
**Actual Script Length**: 3016 字符
**Calibration Samples (at predict time)**: 0
**Confidence**: 🔴 极低（中枢 ±40%，冷启动首条，无历史数据）
**Scored By**: `claude`
**User Override**: `none`
**预测时数据状态**: **blind**（未看任何B站实际播放数据）

---

## 输入快照

**分数 (v0)**: 钩子=4.5 / 信息密度=4.5 / 人设/情绪=5.0 / 传播力=4.5 / 叙事结构=5.0 → composite=**9.30**

**用户改写要点 vs Claude 草稿**:
- **风格重写**：用户要求从"跳脱式跳入跳出"改为"郭德纲式铺平垫稳"，后又要求从"劝人方"转为"深夜茶馆讲鬼故事"
- **核心改动**：竹竿探底从"没有水"→"拔不出来了"；结尾从"这是人性"→"不在罐子里"；新增"罐子是热的""勿启"被抹掉等细节
- **节奏**：比初稿更紧凑，恐怖密度从3层增加到5层

---

## 预测

> ⚠️ **本段是 immutable**——写完不可改。如要重做请创建 `_redo.md`，原文件保留。

**Bucket**: **3-20w**（B站刻度）

**内心概率分布**:
- `<3w` → 55%
- **`3-20w` → 30%**（中枢 ~8000）
- `20-80w` → 10%
- `>80w` → 4%
- `>150w` → 1%

**一句话 reason**:
> 脚本质量在9.30分属上乘，但0粉冷启动首条 + 民俗恐怖属中频赛道 + B站算法对新账号无推荐历史 → 大概率落在基础盘/命中区间（<3w）。中枢8000是基于"好内容但无流量基础"的折中判断。若有流量扶持或踩中推荐窗口，3-20w可期。

**互动预测**:

| 维度 | 预测值 | 置信区间 (±40%) | 置信度 |
|------|--------|-----------------|--------|
| 播放量 | 8,000 | 4,800 - 11,200 | 低 |
| 点赞率 | 3.5% | 2.1% - 4.9% | 中 |
| 评论率 | 0.8% | 0.5% - 1.1% | 中 |
| 投币率 | 1.5% | 0.9% - 2.1% | 低 |
| 收藏率 | 2.5% | 1.5% - 3.5% | 中 |
| 完播率 | 38% | 23% - 53% | 低 |
| 涨粉 | 20 | 12 - 28 | 低 |

---

## 推理因素

| 因素 | 方向 | 置信度 | 说明 |
|---|---|---|---|
| 钩子力（4.5/5） | 强 + | 中 | 开场"夜深了列位，胆小现在关"直接建立恐怖预期，但前30秒无画面纯口播在B站可能流失 |
| 人设/情绪（5.0/5） | 强 + | 中 | 说书人身份贯穿始终，但0粉新号无人设认知积累，观众不知道"你是谁" |
| 内容独特性（单口相声×民俗恐怖） | 强 + | 中 | 赛道空白，差异化明显，但需时间验证受众是否存在 |
| 叙事结构（5.0/5） | 中 + | 中 | 5层恐怖递进+结尾冲击，但8分钟时长对冷启动偏长 |
| 0粉冷启动 | 强 - | 高 | 无粉丝基础，无推荐历史，纯靠算法分发——首条硬上限约5000-10000 |
| 民俗恐怖赛道 | 弱 ? | 低 | 有对标验证（刘波119w），但刘波有动画+粉丝基数，纯口播版待验证 |
| 结尾互动"您信不信" | 中 + | 中 | 自然驱动的评论区互动，比生硬求赞有效 |

---

## 锚点对比

> 校准池只有 0 个样本，无 composite 邻近样本。**锚点对比 N/A**——注意本次预测 confidence 是 🔴 极低，bucket 中枢仅供参考。

---

## 反事实场景（复盘用）

**如果爆 `>20w`**（10% 预期）:
- 验证：单口相声×民俗恐怖这个赛道存在真实需求，且算法愿意给新号推荐
- 推翻：0粉冷启动=低播放的假设
- 可能新增 rubric 维度：内容形式独特性权重

**如果落在 `3-20w`**（30% 预期）:
- 基准线验证：脚本质量（9.30）与实际表现基本匹配
- 下一次可考虑：能否通过标题AB测试提升点击率

**如果跌到 `<3w`**（55% 预期）:
- 推翻：9.30分脚本在B站新号的转化效率
- 核心问题待诊断：是标题点击率低？还是完播率低导致推荐断流？
- 需要复盘时对比同赛道对标数据

**如果 `<<1000`**（15% 预期）:
- 极端场景：B站算法对纯口播民俗恐怖内容无分发意愿
- 需考虑：是否需要加视觉元素（画面/字幕/动画）辅助
- Rubric 可能需要为"冷启动适配"新增维度

---

## 关键校准假设

校准池为0，无可对照样本。但仍写下本次核心赌注：

**我押**：这篇的本体（故事本身 + 恐怖设计）足以驱动传播，但瓶颈在于"被发现"——标题和封面是首条的第一道坎。

**如果评论中出现以下信号 → 验证了脚本的恐怖设计**：
- 观众提到"竹竿""罐子是热的""不在罐子里"等具体细节
- 观众自发在评论区续写/讨论"我们村也有类似的地方"

**如果评论集中在"声音好听""讲故事不错" → 说明恐怖设计没打中**：
- 观众把内容当成ASMR/助眠，而非恐怖故事
- 需要重新评估恐怖元素的呈现力度

**如果播放量极低（<500）但互动率极高（>5%点赞）→ 内容没问题，是分发问题**：
- 标题和封面需要优化，而非修改脚本
- 考虑用刘波式的"动画/画面"辅助提高点击率

---

## 平台适配预测

> 视觉形式：AI皮影戏风格（shadow puppet style）序列帧 + 配音
> 发布策略：B站首发 → 验证后裁剪短版分发快手/抖音/视频号

### B站（主平台）

使用默认预测段（见上方）。皮影戏风格画面是加分项——比纯口播多了视觉锚点，但比刘波的动画门槛低。

**画面带来的额外因素**：
- 皮影戏风格 + 单口相声 = 视觉和听觉的双重"传统感"，可能同时吸引民俗爱好者和国风受众
- 首次出现皮影戏讲恐怖故事的B站内容，有差异化优势
- 风险：AI皮影画面一致性不够，可能显得廉价——需要精选输出

### 快手（短版，60-90s）

**适配维度**: 钩子=0.40 / 人设/情绪=0.35 / 叙事结构=0.25
**Bucket 刻度**: `<500` / `500-5000` / `5000-5w` / `>5w` / `>20w`

**内心概率分布**:
- `<500` → 30%
- `500-5000` → 40%（中枢 ~2000）
- `5000-5w` → 20%
- `>5w` → 8%
- `>20w` → 2%

**平台特有因素**: 快手民俗内容天然匹配，但新号首条冷启动；短版只保留"竹竿被拽"一个高潮，可能不够

### 抖音（短版，90-120s）

**适配维度**: 钩子=0.45 / 人设/情绪=0.30 / 传播力=0.25
**Bucket 刻度**: `<500` / `500-5000` / `5000-5w` / `>5w` / `>20w`

**内心概率分布**:
- `<500` → 40%
- `500-5000` → 35%（中枢 ~1500）
- `5000-5w` → 18%
- `>5w` → 5%
- `>20w` → 2%

**平台特有因素**: 抖音算法对"皮影戏+恐怖"这种新形式可能给试探流量，但也可能因为非主流格式被降权

### 视频号（中版，3-5min）

**适配维度**: 钩子=0.30 / 人设/情绪=0.25 / 传播力=0.30 / 叙事结构=0.15
**Bucket 刻度**: `<500` / `500-3000` / `3000-3w` / `>3w` / `>10w`

**内心概率分布**:
- `<500` → 25%
- `500-3000` → 35%（中枢 ~1500）
- `3000-3w` → 25%
- `>3w` → 10%
- `>10w` → 5%

**平台特有因素**: 视频号社交裂变强，民俗故事易被转发到家族群；但皮影戏风格对中老年用户可能"太新"

---

## AI皮影画面生成方案

### 风格设定

```
核心风格：中国皮影戏（Chinese shadow puppet theater）
色调：暖黄灯光透射的皮质纹理感，深红+暗金+墨黑
人物：皮影剪影风格，关节可动，镂空雕刻细节
场景：传统皮影戏舞台质感，布景有层次感
```

### 分镜画面（13张关键帧）

| 序号 | 时间 | 画面描述 | AI Prompt |
|------|------|---------|-----------|
| 1 | 0:00 | 醒木落下，皮影戏舞台幕布拉开 | `Chinese shadow puppet theater stage, curtains opening, warm amber light, a storyteller's wooden block on the table, traditional dark red and gold colors, theatrical atmosphere --ar 16:9` |
| 2 | 0:20 | 村庄全景，一棵老槐树，树下一口井 | `Chinese shadow puppet style, rural village at dusk, an ancient locust tree, a well beneath it, dark silhouettes, eerie golden light filtering through, leather texture, carved details --ar 16:9` |
| 3 | 0:50 | 两个小孩（我+二蛋）拿着竹竿跑向井边 | `Chinese shadow puppet art, two small children running with bamboo poles, approaching an old well under a twisted tree, childlike innocence mixed with foreboding, warm amber against deep black shadows --ar 16:9` |
| 4 | 1:10 | 特写：井口石板上的"镇"字 | `Chinese shadow puppet close-up, a stone slab covering a well, a single Chinese character "镇" (suppress) carved into the stone, moss growing around it, ominous atmosphere, red and black contrast --ar 16:9` |
| 5 | 1:30 | 竹竿伸进井里，被什么东西拽住 | `Chinese shadow puppet horror, a bamboo pole being pulled into a dark well, an unseen force tugging from below, tension in the scene, the pole bending, dramatic lighting with red undertones --ar 16:9` |
| 6 | 2:10 | 回头看见竹竿自己往下沉 | `Chinese shadow puppet eerie scene, a bamboo pole slowly sinking into a well by itself, two children watching from a distance in fear, night falling, crescent moon, deep shadows --ar 16:9` |
| 7 | 2:40 | 第二天，"镇"字被从底下顶出来 | `Chinese shadow puppet detail shot, the Chinese character "镇" pushed outward from beneath a stone slab, cracks forming, moss peeled away, something emerging, terrifying implication, red glow from below --ar 16:9` |
| 8 | 3:10 | 姥姥在灶台揉面，手里拿着剪刀 | `Chinese shadow puppet interior scene, an elderly woman kneading dough at a kitchen stove, reaching for a pair of scissors, warm firelight contrasting with concern on her silhouette face, traditional rural kitchen --ar 16:9` |
| 9 | 3:50 | 县志翻开，泛黄书页上写着"形似人，非人" | `Chinese shadow puppet style, an ancient county chronicle book opening, yellowed pages, Chinese calligraphy "形似人，非人" (human-like, not human), candlelight flickering, dust motes in the air --ar 16:9` |
| 10 | 4:30 | 被抹掉的"勿启"二字，墨痕模糊 | `Chinese shadow puppet close-up, two Chinese characters "勿启" (do not open) smeared and blurred on aged paper, ink stains, the word barely visible, sense of urgent warning erased, dark atmosphere --ar 16:9` |
| 11 | 5:20 | 拆迁现场，施工队从井底挖出陶罐 | `Chinese shadow puppet scene, demolition site, construction workers pulling a clay jar from a deep well, modern machinery contrasting with ancient artifact, the jar sealed, ominous feeling --ar 16:9` |
| 12 | 6:00 | 特写：陶罐，封口上刻着"镇"，罐子在发光/发热 | `Chinese shadow puppet extreme close-up, an ancient clay jar, sealed, the character "镇" carved on it, a faint red glow emanating from within, the jar appears warm, leather texture of the puppet art, dread --ar 16:9` |
| 13 | 7:00 | 终场画面：醒木落下，幕布拉上，只有井口留在黑暗中 | `Chinese shadow puppet theater, the storyteller's wooden block striking down, stage curtains closing, behind the curtain only the silhouette of a well and an empty jar, darkness swallowing everything, finality --ar 16:9` |

### 动画化处理

| 画面 | 动画效果 |
|------|---------|
| 竹竿被拽 | 竹竿倾斜+轻微抖动，2-3秒循环 |
| 竹竿下沉 | 竹竿缓慢向下平移，背景静止 |
| "镇"字被顶出 | 石板裂纹扩散+字向外凸出 |
| 罐子发热 | 罐子边缘红色光晕脉动，2-3秒循环 |
| 幕布开合 | 开场/结尾的幕布平移动画 |

---

## 复盘

> ⚠️ **以下段落由 `/yang-retro` 在 T+3d 天后追加**。

（待填——T+3天后跑 `/yang-retro`）