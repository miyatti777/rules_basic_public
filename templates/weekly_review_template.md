# Week {{iso_week}} Review

## ✔ 今週完了
{{#week_data.completed}}
- {{id}} {{title}}
{{/week_data.completed}}

## ⚠ 未完了／持越し
{{#week_data.remaining}}
- {{id}} {{title}} (Due: {{due}})
{{/week_data.remaining}}

## 📈 進捗率
- 完了 {{week_data.done_points}} / 合計 {{week_data.total_points}} pt ({{week_data.progress}}%)

## 🚀 次週フォーカス案
{{#week_data.next}}
- {{.}}
{{/week_data.next}}
