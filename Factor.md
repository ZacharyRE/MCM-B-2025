# 1 人口增长模型：

#### Carrying Capacity K
1. **取值范围**：20,000 - 25,000 人/日。
2. **相关文献**：City and Borough of Juneau (2023). *Cruise Ship Passenger Impact Report*.  
   - 以七艘大型邮轮同时停靠的游客承载能力作为上限（每艘邮轮约载 3,000 人，合计 21,000）。



#### Initial Population N0
1. **取值范围**：10,000 - 15,000 人/日。
2. **相关文献**：City and Borough of Juneau (2020). *Tourism Statistics Report*.  
   - 提供了疫情前朱诺市日均游客数量的估计。



#### Intrinsic Growth Rate r
1. **取值范围**：0.05 - 0.1。
2. **相关文献**：City and Borough of Juneau (2023). *Cruise Ship Passenger Impact Report*.  
   - 根据 2014-2019 年游客数量增长数据（年均增长率约为 6.3%）。



#### Initial Flow-Out δ
1. **取值范围**：10,000 - 15,000 人/日。
2. **相关文献**：City and Borough of Juneau (2021). *Post-COVID Tourism Recovery Report*.  
   - COVID-19 爆发期间，朱诺市的游客流失量接近 90%。



#### Decay Rate γ
1. **取值范围**：0.5 - 0.7。
2. **相关文献**：City and Borough of Juneau (2022). *Post-Pandemic Tourism Recovery Report*.  
   - 提到 2022 年朱诺市游客数量已恢复至接近疫情前水平。

---
# 2:社会负担模型

#### **Total Revenue (\(R(t)\))**
1. **意义**：总收入，表示每天由游客产生的经济效益，包括人均消费和其他收入。
2. **取值范围**：\$300,000 - \$2,000,000/日（根据朱诺市游客数量范围及平均消费水平计算）。
3. **相关文献**：City and Borough of Juneau (2023). *Cruise Ship Passenger Impact Report*.  
   - 提到邮轮游客对当地经济的每日贡献接近 \$1,000,000。



#### **Visitor Number N(t)**
1. **意义**：每日游客数量，受到承载力和政策限制影响。
2. **取值范围**：5,000 - 20,000 人/日。
3. **相关文献**：City and Borough of Juneau (2023). *Cruise Ship Passenger Impact Report*.  
   - 提到 2023 年高峰时期每日游客数量约为 20,000。



#### **Cruise Ship Visitor Revenue R(cruise)**
1. **意义**：邮轮游客的平均消费金额，包括岸上观光、购物、餐饮等支出。
2. **取值范围**：\$100 - \$200/人。
3. **相关文献**：City and Borough of Juneau (2023). *Cruise Ship Passenger Impact Report*.  
   - 提到邮轮游客的日均消费金额约为 \$150，但受船公司控制范围的限制，其支出通常低于自由行游客。



#### **Independent Traveler Revenue R(land)**
1. **意义**：自由行游客的平均消费金额，包括住宿、交通、餐饮、购物和娱乐支出。
2. **取值范围**：\$200 - \$400/人。
3. **相关文献**：City and Borough of Juneau (2023). *Independent Traveler Spending Overview*.  
   - 提到自由行游客的平均消费显著高于邮轮游客，特别是在住宿和高端体验项目上，自由行游客通常消费 \$250 - \$350。



#### **Tourist Tax T**
1. **意义**：每位游客支付的环境税，用于支持环保和基础设施建设。
2. **取值范围**：\$5 - \$15/人。
3. **相关文献**：City and Borough of Juneau (2023). *Tourism Tax Revenue Report*.  
   - 提到游客税的收入为城市基础设施提供了重要支持。



#### **Operational Cost C(t)**
1. **意义**：每天的运营成本，包括基础设施维护、交通、废弃物处理等。
2. **取值范围**：\$50,000 - \$500,000/日。
3. **相关文献**：City and Borough of Juneau (2023). *Infrastructure Impact Report*.  
   - 提到旅游高峰期的日常运营成本显著增加。



#### **Environmental Cost E(t)**
1. **意义**：每天因游客活动产生的环境影响成本（如碳排放、垃圾处理）。
2. **取值范围**：\$10,000 - \$200,000/日。
3. **相关文献**：City and Borough of Juneau (2023). *Environmental Impact Study*.  
   - 提到朱诺市游客活动对垃圾处理和碳排放的影响成本估算。



#### **Tourism Promotion Budget P(t)**
1. **意义**：用于吸引游客的推广预算，包括广告和活动支出。
2. **取值范围**：\$5,000 - \$50,000/日。
3. **相关文献**：City and Borough of Juneau (2023). *Tourism Marketing and Promotion Report*.  
   - 提到市政府在广告和推广活动中的预算安排。

---

# 3: 综合环境影响模型

### **Average Travel Distance d(average)**
1. **意义**：游客平均旅行距离，用于估算碳排放量。
2. **取值范围**：100 - 2,000 公里/人。
3. **相关文献**：City and Borough of Juneau (2023). *Tourism Carbon Footprint Report*.  
   - 朱诺市游客大部分来自北美（较长距离），部分来自阿拉斯加州内（短距离）。



### **Unit Emission Factor e(unit)**
1. **意义**：单位距离的碳排放因子，表示每公里每位游客的平均碳排放量。
2. **取值范围**：0.1 - 0.5 公斤CO₂/公里。
3. **相关文献**：City and Borough of Juneau (2023). *Tourism Carbon Footprint Report*.  
   - 提到邮轮游客的单位碳排放量较高，自由行游客的排放因子较低。



### **Local Emission Factor e(local)**
1. **意义**：本地旅游活动产生的平均碳排放量。
2. **取值范围**：5 - 50 公斤CO₂/人。
3. **相关文献**：City and Borough of Juneau (2023). *Environmental Impact Study*.  
   - 朱诺市的主要排放来自游览巴士和观光直升机等高排放活动。




### **Cost of Activity ci**
1. **意义**：单个活动（如观光、购物等）产生的环境成本。
2. **取值范围**：\$5 - \$50/人。
3. **相关文献**：City and Borough of Juneau (2023). *Activity Impact Assessment Report*.  
   - 不同旅游活动对环境的成本估算，例如直升机观光的环境成本最高。



### **Participation Rate ri**
1. **意义**：参与特定活动的游客比例。
2. **取值范围**：0.1 - 0.7。
3. **相关文献**：City and Borough of Juneau (2023). *Tourism Activity Participation Report*.  
   - 提到邮轮游客更倾向于选择短时间、高强度的活动，自由行游客参与率较低。


### **Local Environmental Impact Factor γ**
1. **意义**：本地环境影响因子，综合表示非活动因素对环境的总体影响。
2. **取值范围**：\$10 - \$100/人。
3. **相关文献**：City and Borough of Juneau (2023). *Comprehensive Environmental Impact Report*.  
   - 估算朱诺市本地居民和游客的环境压力来源。



