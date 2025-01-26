# 人口增长模型

### 修正的 Logistic 模型:
*（Logistic 模型 + 外部冲击模型）*

**Logistic 模型公式：**
<img width="300" alt="Screenshot 2025-01-24 at 11 30 03 PM" src="https://github.com/user-attachments/assets/e615ffcf-38de-41f9-a2d5-f47e49abb3d6" />

**修正模型公式：**
<img width="300" alt="Screenshot 2025-01-24 at 11 30 23 PM" src="https://github.com/user-attachments/assets/c17f47f8-8655-467c-a19e-748413e9dd38" />

**模型说明：**
- Logistic 模型解释了人口的稳定增长。
- 外部冲击模型解释了如 2022 年疫情等突发事件对人口增长的影响。

**参考文献：**

[点击此处阅读原文-Logistic](https://www.sciencedirect.com/science/article/abs/pii/S0160738309000954?casa_token=S7tpN1HQracAAAAA:eKfmhV37bzxkM91U59ydC0fQry0OpFcJFzpzgOwTGbL-siOvDENziEEf7kVP9I03OH2wqx8vQQ)

[点击此处阅读原文-外部冲击模型](https://www.sciencedirect.com/science/article/abs/pii/S0167223176800036)

---

# 收入模型：

**Main Idea**： 将收入进行分解，拆分成多个收入组合。

<img width="400" alt="Screenshot 2025-01-25 at 12 17 56 AM" src="https://github.com/user-attachments/assets/16849acf-2da7-4ab2-a2f0-6af98a9164e9" />

- **R(cruise)**: 邮轮游客收益
- **R(Land)**: 自由行游客收益
- **R(Tax)**: 税收

### 模型收益细分：

接下来对每个收益进行进一步定义+细分：

  1. **邮轮游客收益**

<img width="400" alt="Screenshot 2025-01-25 at 12 22 03 AM" src="https://github.com/user-attachments/assets/2f71ecf9-61b6-4ec5-ad4c-c06ff381569e" />

  *P(c): 选择邮轮的游客比例。*
  
  2. **自由行游客收益**

<img width="300" alt="Screenshot 2025-01-25 at 12 23 28 AM" src="https://github.com/user-attachments/assets/e23c2fcd-ca77-4db0-b068-d6af3701fe1e" />

  *P（l）:选择自由行的游客比例。*
  
  3. **游客附加税收**

<img width="200" alt="Screenshot 2025-01-25 at 12 24 08 AM" src="https://github.com/user-attachments/assets/5f7b5d35-ea0b-4e87-9708-6d8da96cc6a4" />

  4. **基础设施和环保投资**

<img width="200" alt="Screenshot 2025-01-25 at 12 32 37 AM" src="https://github.com/user-attachments/assets/47eaecf8-1f62-4fac-8f3c-6b5c6d58f7da" />


  - C0: 固定成本
  - γ：每位游客导致的额外成本（如废物管理、资源消耗）。



### 动态因子分析：
**1. 邮轮游客消费因子：**

<img width="200" alt="Screenshot 2025-01-25 at 1 04 22 AM" src="https://github.com/user-attachments/assets/9dba5a9f-5229-4e46-9668-44c28331fcaa" />

<img width="364" alt="Screenshot 2025-01-25 at 1 10 11 AM" src="https://github.com/user-attachments/assets/500b9f52-2c80-4465-b1c0-1d688216c69b" />



**2. 自由行游客消费因子：**:

<img width="200" alt="Screenshot 2025-01-25 at 1 04 36 AM" src="https://github.com/user-attachments/assets/0a0698fa-04d6-480d-a706-61cb1d9e46c0" />

<img width="426" alt="Screenshot 2025-01-25 at 1 10 42 AM" src="https://github.com/user-attachments/assets/4394d325-3c0e-46f3-9dbb-289256d8d04d" />

**3. 动态税率**:

<img width="200" alt="Screenshot 2025-01-25 at 1 04 44 AM" src="https://github.com/user-attachments/assets/772fdbba-d79e-4058-ae49-28e5c76d681f" />
<img width="360" alt="Screenshot 2025-01-25 at 1 11 10 AM" src="https://github.com/user-attachments/assets/27395899-bb6a-4686-b902-529f942f7a51" />


### 加入动态因子之后每个收入的模型：

<img width="600" alt="Screenshot 2025-01-25 at 1 12 18 AM" src="https://github.com/user-attachments/assets/d9d022d9-2a9d-4821-86f0-b80d0ecfbfca" />

### 最终公式：

<img width="1624" alt="Screenshot 2025-01-25 at 1 14 38 AM" src="https://github.com/user-attachments/assets/4d54b022-c90e-4a8c-87d5-bce420c7c628" />

---

# 综合环境影响模型
*Integrated Environmental Impact Model, IEIM*

### 目标函数：

<img width="400" alt="Screenshot 2025-01-25 at 1 50 08 AM" src="https://github.com/user-attachments/assets/455fd9ff-ff32-4698-9ebd-355c89bd95fc" />

1. **对于E（Transport）：** <br><br>
   
<img width="500" alt="Screenshot 2025-01-25 at 1 51 44 AM" src="https://github.com/user-attachments/assets/235615ea-1b71-4b61-ac2e-be6ad1428b98" />



2. **对于E（Resource）**：
   
<img width="500" alt="Screenshot 2025-01-25 at 1 52 21 AM" src="https://github.com/user-attachments/assets/bf921c5a-ed83-4ba4-a501-352699da3310" />



3. **对于E（Waste）**

<img width="500" alt="Screenshot 2025-01-25 at 1 57 40 AM" src="https://github.com/user-attachments/assets/069f821c-a395-4e9d-8fa9-7168be6bccd3" />



### 最终函数：

<img width="650" alt="Screenshot 2025-01-26 at 11 55 46 AM" src="https://github.com/user-attachments/assets/925cb9c7-fbb7-467a-91e1-fd931a5c3074" />


### 参考文献：(每个文献对应一个公式，作为 supporting document)

[分项环境成本模型](https://pubs.acs.org/doi/10.1021/es101316v)

[交通相关碳排放](https://documents1.worldbank.org/curated/pt/826921468766156728/pdf/Transportation-and-CO2-emissions-flexing-the-link-a-path-for-the-World-Bank.pdf)

[资源消耗的环境影响](https://w.tboake.com/2013/EF_Reading_Assignment_1of2.pdf)

[废弃物处理的环境影响](https://journals.sagepub.com/doi/full/10.1177/0734242x12437569)

---

# 社会负担模型：

### 目标函数：

<img width="679" alt="Screenshot 2025-01-26 at 4 54 23 PM" src="https://github.com/user-attachments/assets/03d195d1-aa28-4578-90f1-cfb768ae77f6" />

### 目标函数拆解：
**1.拥挤成本模型**：

<img width="227" alt="Screenshot 2025-01-26 at 5 07 14 PM" src="https://github.com/user-attachments/assets/50cee3c4-9390-4f06-b6cd-9bc769b888bf" />

- **m 的取值一般是1.5-2.5**

**2.住房成本模型**：

<img width="200" alt="Screenshot 2025-01-26 at 5 08 03 PM" src="https://github.com/user-attachments/assets/d28400ad-be81-4d57-9041-427c676822e4" />

**3.基础设施压力模型**

<img width="250" alt="Screenshot 2025-01-26 at 6 23 13 PM" src="https://github.com/user-attachments/assets/ac0de205-f5fe-4796-bbf9-5dd3067a084a" />

**4.游客不良行为模型**

<img width="220" alt="Screenshot 2025-01-26 at 6 23 36 PM" src="https://github.com/user-attachments/assets/1e90ed6d-bd2f-4295-9151-f6dbc75f389c" />


### 综合社会负担模型：（带入）

<img width="500" alt="Screenshot 2025-01-26 at 6 26 02 PM" src="https://github.com/user-attachments/assets/e1518e3a-54a5-413b-bc7e-f8ecf65d7eb1" />

### 参考文献

[住房拥挤模型-非线性](https://d1wqtxts1xzle7.cloudfront.net/61005314/The_Economics_of_Urban_Transportation20191024-2394-b3dsou-libre.pdf?1571926385=&response-content-disposition=inline%3B+filename%3DThe_Economics_of_Urban_Transportation.pdf&Expires=1737891979&Signature=ZbSk6OVCQ1t~EKE3oJHb~v7e8xv7hdOcOx0QKNxSEc15TmG8gS~f-KiC9VrXjd~RqzODs1NxwxCaLPjV4EW6sk2JSG28OCrn7GGptpzUd8GuHPA5cCOmfsY3NuYKXQ83PAOCqBe55Umlb9Tau9rb4QB6z6rEvx2cm5rVIC-PO6aYMmNHSFeEupplnDnLNOAum9XLSl79bL7UGM0VEePXZxEns-1Ups5qD5Hq-nicYLDCf3~m0jHuljGzzcg-GwnXyLjzLgPUfnw01o-WpuvS4m1yc-LLYU5tfOP-vhQLieia5XFafVl~F8790hiFEBcY27ibZ-Bdjj2lbf5fqKTKjA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)

[住房成本模型](https://www.nber.org/system/files/working_papers/w10124/w10124.pdf)

[基础设施压力模型](https://www.europarc.org/wp-content/uploads/2020/03/A_Tourism_Carrying_Capacity_Indicator_fo.pdf)

[游客不良行为模型](http://repo.lib.sab.ac.lk:8080/xmlui/bitstream/handle/123456789/1641/9780203875872_webpdf-1-19.pdf?sequence=1)

[综合社会负担模型](https://www.mdpi.com/2071-1050/10/12/4384) **综合分析了游客流量对拥挤、住房和社会压力的多方面影响。论证社会负担是由多方面组成**


# 优化参数：

**1. 游客数量N(t)**

**2. 基础设施投资C(t)**

**3. 环保税T(t)**

**4. 推广预算P(t)**



