## 人口增长模型

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

## 收入模型：

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

<img width="400" alt="Screenshot 2025-01-25 at 12 23 28 AM" src="https://github.com/user-attachments/assets/e23c2fcd-ca77-4db0-b068-d6af3701fe1e" />

  *P（l）:选择自由行的游客比例。*
  
  3. **游客附加税收**

<img width="200" alt="Screenshot 2025-01-25 at 12 24 08 AM" src="https://github.com/user-attachments/assets/5f7b5d35-ea0b-4e87-9708-6d8da96cc6a4" />

  4. **基础设施和环保投资**

<img width="200" alt="Screenshot 2025-01-25 at 12 32 37 AM" src="https://github.com/user-attachments/assets/47eaecf8-1f62-4fac-8f3c-6b5c6d58f7da" />


  - C0: 固定成本
  - γ：每位游客导致的额外成本（如废物管理、资源消耗）。

### 整体收益模型：

带入logistic 的人口预测增长函数之后，整体收入模型：

<img width="800" alt="Screenshot 2025-01-25 at 12 54 19 AM" src="https://github.com/user-attachments/assets/091ab4c4-6e0f-4a63-8114-044f05475989" />

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

