# Python 程式筆記-資料型態

# 資料型態

### tags: `#Python` `#程式筆記` `#變數`

---

## 定義

> 變數是跟電腦呼叫記憶體空間儲存資料，但是每一種資料需要儲存的記憶體空間大小不同，這個就叫做資料型態。

---

Python中資料類型： 

- 整數型 Integer (int)
- 浮點數型 Float (float)
- 字串 String (str)
- 布林值 Boolean (bool)
- 串列 List (list)
- 字典 Dictionary (Dict)
- etc...

這些資料類型與其他語言(C, C++, Java, etc..)差不多，但是在Python中使用這些資料型態 **不用提前宣告**

```c
//C, C++, Java, etc..語法
int number = 15  // 要先進行宣告資料型態才能成功建立變數
num = 20         // 這樣就會出現error
```

```python
#Python
number = 15   # 這樣就完成變數的建立了
```

更不一樣的是，在其他語言（C, C++, Java, etc..）中，定義變數並宣告資料型態後，是不可以被改變的；但是Python沒有這個困擾。

```c
//C, C++, Java, etc..語法
int number = 15
number = "Hello"   //error
```

```python
＃Python
number = 15
number = "Hello"   #legal
```

---

對於Python程式設計而言

> 優點：靈活性高，不用害怕一開始就定義與宣告錯變數，寫作的流暢性up up!

> 缺點：一開始定義變數就必須跟電腦要較大的記憶體空間，使資源運用過多且過冗，執行效率低下，尤其是在非常大的專案中更是如此。

對過去電腦來說，記憶體小，Python寫出的程式機器無法負荷；對現代而言，電腦發展程度高，Python開發速度較快。

`但是對於撰寫程式的終極目標來說，效率高、使用資源低還是最重要的。因此Python無法取代C/C++等可以觸及記憶體空間的語法。`