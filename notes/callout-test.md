---
title: "Callout test"
---

# Callout rendering test

<blockquote class="callout callout-note" markdown="1">
**基本 callout**

內含 **粗體** 與 [連結](https://example.com)
- 清單項目一
- 清單項目二

</blockquote>

<details class="callout callout-warning" markdown="1" open>
<summary>可摺疊(預設展開)</summary>

展開內容

</details>

<details class="callout callout-tip" markdown="1">
<summary>可摺疊(預設收合)</summary>

收合內容

</details>

<blockquote class="callout callout-note" markdown="1">
**外層**

外層內容

<blockquote class="callout callout-danger" markdown="1">
**內層**

巢狀內容

</blockquote>

</blockquote>

```mermaid
graph TD
  A[開始] --> B[結束]
```
