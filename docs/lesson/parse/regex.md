Radium中的字符串字面量支持原始字符串字面量，使用 `#` 字符作为前缀，这意味着字符串字面量中的特殊字符将不会被转义。这在处理正则表达式、文件路径等需要保留原始格式的文本时非常有用。例如：

```swift
let regexPattern = #"(\d{3})-(\d{2})"#
```