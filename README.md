## surge rule set

```text
RULE-SET 和 DOMAIN-SET 的不同
RULE-SET 可包含所有类型的子规则，执行效率和在主配置中的规则没有区别，
DOMAIN-SET 仅可使用 DOMAIN 和 DOMAIN-SUFFIX 两种形式的内容，使用了特别的逻辑进行优化，在内容非常多时性能有极大的提升。（千条以上，否则两者没有太大的区别）
```