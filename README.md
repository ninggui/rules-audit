<div align="center">

# rules-audit

**每周一自动审计：你给 AI 定的规则，它到底执行了多少？**

<p>
  <a href="#"><img src="https://img.shields.io/badge/cron-weekly%20Monday%202:30-blue" alt="Weekly audit" /></a>
  <a href="#"><img src="https://img.shields.io/badge/method-AAR%204--step-orange" alt="AAR" /></a>
</p>

[问题](#问题) · [审计方法](#审计方法)

</div>

---

## 问题

规则定了 1-2 天执行好，3-4 天衰减，一周忘。根因：memory 容量有限 + 对话规则不落文件 + 无定期审计。

## 审计方法

每周一 02:30 自动跑，按 AAR 四步出报告：

1. **预期 vs 实际**：规则本该怎样 vs 实际执行了什么
2. **差异根因**：为什么变形（载体没同步/协议没固化/执行时遗忘）
3. **补救措施**：该补到哪个文件、该删哪个失效规则
4. **下周检查点**：哪条规则要重点盯

## License

MIT
