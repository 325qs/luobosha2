# 候选选题池

> **本文件由 `/yang-trends` 写入热点抓取结果，由 `/yang-recommend` 读取并排序。
> 也可手动编辑——把候选标题贴成 H3 entry 即可。**

---

## 使用说明

每个候选项是一个 H3 entry（`### [tier] 标题`），下面带 metadata bullets。最简版本只需要 title 一行。

### 字段含义速查

- **id**：12 位 hash，用于跨文件去重。手加 entry 留空，`/yang-trends` 自动算
- **source**：来源标识，格式 `<adapter-type>:<source-name>`
- **snapshot_at**：抓取 / 录入时间
- **tier**：粗分类 `tier1` / `tier2` / `tier3` / `skip` / `risky` / `done`
- **read_status**：`unread` / `skimmed` / `deep_read` / `done`
- **composite (vN)**：当前 rubric 下的综合分
- **predicted bucket**：粗预测桶
- **note**：备注

### 手加 entry 的最简格式

```markdown
### 标题
- snapshot_at: YYYY-MM-DD
```

---

## 候选项

（暂无——运行 `/yang-trends` 或手动添加候选选题后自动累积）

---

## 维护建议

- **保持 < 100 条 active**（tier1+tier2+tier3，不含 skip/done）
- **定期清理 skip**：超过 6 个月的 skip 可以剔除
- **risky 标签认真用**：`/yang-recommend` 会高亮 risky 项