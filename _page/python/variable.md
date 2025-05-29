---
layout: page
title: 變數與資料型態
permalink: /python/variables/
---

# 🧠 變數與資料型態（Variables & Data Types）

在 Python 中，我們可以直接使用變數，不需要事先宣告資料型態。這讓初學者能夠快速開始編寫程式。

```python
x = 5
name = "Alice"
is_valid = True
```

---

## 🧾 常見資料型態

| 資料型態 | 範例值        | 說明             |
|----------|----------------|------------------|
| `int`    | `1`, `-20`      | 整數             |
| `float`  | `3.14`, `-0.5`  | 小數（浮點數）   |
| `str`    | `"Hello"`       | 字串（文字）     |
| `bool`   | `True`, `False` | 布林值（真假）   |

---

## 🔍 使用 `type()` 查看型態

```python
a = 100
b = 3.14
c = "Python"
d = False

print(type(a))  # int
print(type(b))  # float
print(type(c))  # str
print(type(d))  # bool
```

---

## 💡 小練習：你會嗎？

觀察下面程式碼，思考輸出的型態是什麼：

```python
x = "123"
y = 123

print(type(x))
print(type(y))
```

👉 **提示**：引號的有無會影響型別！

---

## 🧩 小結

- Python 是**動態型別語言**：變數型態會自動根據你給的值決定
- 使用 `=` 可以將值指定給變數
- 使用 `type()` 可檢查變數的資料型態
- 資料型態錯誤會導致執行階段錯誤，請小心！

---

## 🚀 延伸挑戰（選做）

請試著將下列不同資料型態相加，並觀察結果：

```python
print(1 + 2)
print("1" + "2")
print("Age: " + str(18))
```

---

✅ 回到 [Python 主目錄](/python/) 繼續學習其他主題！
