# JavaScript

文档地址：https://tc39.es/ecma262/

## 语法 Grammar

### Lex

位置在 ECMA2019 chapter 附

InputElement

- WhiteSpace
- LineTerminator
- Comment
- Token
  - IdentifierName（是 Identifier 和 Keywords 合并的）
  - Keywords (ES2019 未设计)
  - Punctuator
  - NumericLiteral
  - StringLiteral
  - RegularExpressionLiteral (ES2019 未设计)
  - Template

### Syntax

- Atom
- Expression
- Structure
- Script & Module

## 语义 Semantics

## 运行时 Runtime

### Type

- Null
- Undefined
- Number
- String
- Boolean
- Symbol
- Object
- 内部类型
  - Reference
  - Completion Record
  - ECMA 里面自找 。。。

### 执行过程

- Job
- Script/Module
- Promise
- Function
- Statement
- Expression
- Literal
- Identifier

## Note

零宽空格 \uFEFF
