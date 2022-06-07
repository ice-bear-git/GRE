## GRE数学 --【数据分析】部分

#### 1. 描述数据的图形方法
- 【考点】分解质因数
  1. 分解质因数：把一个正整数分解成多个质数相乘的形式
      - 有“2”
  2. 分解因数：把一个正整数分解成多个正整数相乘的形式
      - 可以有“1”与“其本身”

- 【考点】因数&质数的性质
  1. 一个数字有奇数个数的正整数因数 -- 这个数是：***完全平方数***
      - 因为奇数个positive factors只能是 奇数X奇数，那么质因数的指数本身(奇数-1)为 偶数X偶数。可以拆分成两个相同数的乘积。
  2. 一个数有 ***三个正整数因数*** --- 这个数是： ***质数的平方***
      - A=b^2, has 2+1=3 positive factors
  3. 质数平方的个数
      - How many integers from 1 to 900 inclusive have exactly 3 positive divisors?  
      Ans:10; 2 3 5 7 11 13 17 19 23 29 [相当于问在1-30中间的质数]

- 【考点】整除关系的判断
  1. A是B的倍数
      - A is multiple of B = B is a factor of A = A is divisible by B = A/B is an integer
      - 判断方法
        1. 分解质因数
        2. 分子分母约分

#### 2. 描述数据的数值方法
- 【考点】数值的位置
  1. 四分位数：quartiles
      - 从小到大排列，按个数平分成4等份：first quartile, second quartile, third quartile
      - 平分的是个数！不是大小！
  2. 四分位距：interquartile range
      - interquartile range = third quartile - first quartile
      - Boxplots or box-and whisker plots: show medium with interquartile range.
  3. 百分位数：percentile
      - percentile也是从个数的角度切割了100份，所以 ***不能*** 通过 n_th percentile 推断出他的value

- 【考点】数值的集中趋势
  1. 算数平均值：arithmetic mean (average, mean)
  2. 中位数： median
      - 整个数列个数位奇数项时：取中间的数字；如果为偶数项：取两个数字的算数平均值
      - 1-99中：median=(1+99)/2=50
      - 1-100中：median = (50+51)/2 = 50.5
  3. 众数：mode
      - 众数可以不止一个
  4. 加权平均数：weighted mean

- 【考点】数值的离散趋势
  - 极差：range = max-min >=0
  - 标准差：standard deviation
      - 标准差越大，数字越分散；标准差越小，数字越集中
  1. 求值
      - 尤其是等差数列的mean；等比数列的median
  2. 数据变化的影响
      - 若 ***整体移动*** range与standard deviation不变
      - 若 ***整体缩放*** range与standard deviation也同时乘/除缩放比
      - range与standard deviation：数据 ***加减不变，乘除***
  3. 标准方差的性质
      - a standard deviation ***above/below*** the mean is : mean +- std = a value
      - a standard deviation ***of/from*** the mean is : (mean + std) and (mean - std) = two boundary values
      - ***within/between*** 1 standard deviation ***of/from*** the mean is: (mean + std) ~ (mean - std) = a Range of values
  4. 最大最小的 可能值
      - Greatest possible value = Total - 反向极限值的和[其余项都最小时的和]
      - Least possible value = Total - 反向极限值的和[其余项都最大时的和]
      - 关键是：数字可以相同嘛？数字只能是整数嘛？
        > the average of 5 different positive integers is 8, what might be the greatest possible value of the 5 integers?  
        Ans: 8*5-(1+2+3+4) = 40-10 = 30;


#### 3. 统计方法 [集合/Venn/双维度分类]
- Venn diagram; set; members or elements; infinite set and finite set; empty set; nonempty set; subset; universal set
- the number of subset = 2^(# of members in the set)
- set中，各个元素是互异的
- sets relation: intersection, union, disjoint or mutually exclusive
- Venn disgram = A+B+A^B - (No A) ^ (No B)
  - 一定要考虑 非A非B的情况！要考虑两个圈圈最多相交(一个包含另一个)，以及最少相交(可能非A非B=0)
  - 双维度分类：用Table把横竖两个坐标代替AB的Venn图 ***适合有明确的点数/百分数的情况***

#### 4. 概率--比例问题
- sample space; event
- 时刻考虑相交最多与相交最少的极端情况
- 【考点】等可能性事件 -- random experiment
  1. 考虑放回：Put it back/ with replacement
  2. 不考虑放回：without replacement/simultaneously/未交代

- 【考点】互斥事件/对立事件 -- mutually exclusive & complementary events
  1. mutually exclusive event A&B: Sum <=1
      - P(AUB) = P(A)+P(B)
  2. complementary events A&B: Sum=1

- 【考点】相互独立事件 -- independent events
  1. P(A^B) = P(A)*P(B)
      - P(AUB) = P(A)+P(B) - P(A)*P(B)


#### 5. 数据分布、随机变量和正态分布
##### 5.1 数据分布
##### 5.1 随机变量
##### 5.1 正态分布
