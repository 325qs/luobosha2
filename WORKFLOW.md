# 工作流速查（Yang.skills）

> 这是 `/yang-init` 在你的项目根创建的速查文档。完整规范在 Yang.skills 的 `SKILL.md` 和 `shared-protocols/`。
> 本文件给"忘了下次该说什么"的时候用——不需要从头读完。

---

## 一句话流程

```
找选题
  ├─ 没发过历史的 → /yang-seed brainstorm（兴趣 × 热点）
  └─ 发过历史的    → /yang-seed brainstorm（兴趣 × 热点 × 你过去做过什么）
  ↓
yang-seed 写草稿到 → scripts/<日期>_<id>_<short>.md
  ↓
用户改写 scripts/<日期>_<id>_<short>.md
  ↓
/yang-score scripts/<日期>_<id>_<short>.md → 看 rubric 评分
  ↓
/yang-predict scripts/<日期>_<id>_<short>.md → 写 immutable 预测到 predictions/
  ↓
拍摄完 → /yang-shoot → buffer +1
  ↓
发布 → /yang-publish + URL → buffer -1
  ↓
T+3 天 → /yang-retro → 复盘 → 校准池 +1
  ↓
累计 ≥10 同向偏差 → /yang-bump（升级 rubric）
```

---

## 五个阶段对应触发词

### ① 选题阶段

| 想做什么 | 触发词 |
|---|---|
| 看 candidates.md 排序后的推荐 | "推荐选题" / "下一篇做什么" |
| 抓今天的热点拓展 candidates | "抓热点" / "今天有什么可做的" |
| 看当前状态 | "状态" |

### ② 打分 + 预测

| 想做什么 | 触发词 |
|---|---|
| 看一份稿子的 rubric 分 | "打分这篇 path/to/draft.md" |
| 给最终稿写正式 immutable 预测 | "启动预测 path/to/draft.md" |

### ③ 发布登记

```
"已发布 https://..."
```

### ④ 复盘

```
"复盘 predictions/YYYY-MM-DD_xxx.md"
```

### ⑤ Rubric 升级

```
"升级 rubric"
```

---

## 三条不可妥协的原则

1. **盲预测**：预测段写在看到任何数据之前，写完不可改。
2. **升级 = 全量重打**：bump 必须校准池全量重打分 + 跨模型独立审。
3. **rubric 是工作台不是博物馆**：被吸收 / 被推翻的观察都删掉。git history 是档案。

---

## 默认配置

| 设置 | 默认 | 何时改 |
|---|---|---|
| `RETRO_WINDOW_DAYS` | 3 | 长文 / 慢平台改 7 |
| `MIN_SAMPLES_FOR_BUMP` | 10 | 不要降 |
| `TREND_SOURCES` | ["manual-paste"] | 用 `enabled_trend_sources` 字段加新源 |

---

## 文件结构

```
<your-content-project>/
├── rubric_notes.md          # 评分规则真实来源
├── WORKFLOW.md              # 本文件
├── STATUS.md                # 看板
├── candidates.md            # 候选池
├── benchmark.md             # 对标账号
├── .yang-state.json         # 状态文件
├── scripts/                 # 拍前的所有草稿
├── predictions/             # immutable 预测日志
└── videos/                  # 拍后才建
```