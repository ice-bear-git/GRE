## GRE数学-【算数】部分

#### 1. Integral
- 【考点】Positive and negative
  1. 符号的判断
      - 负数的次方。
      - 系数为正，参数未知正负的情况。
  2. 未知数取值
      - 涉及完全平方数的根/底数的正负

- 【考点】odd and even 整数的子集
  1. 0是偶数
  2. 四则运算的奇偶性
      - 当两数差值为odd，其和为odd，积为even
  3. 指数运算的奇偶性
      - 总要警惕着0！zero is not Positive integer
      - 当n为正整数，x与x^n的奇偶性完全相同
          > for integer: x^2+y^2 = even ---> x+y=even --> x +- y =even  

- 【考点】连续整数
  1. 连续整数的个数
      - num of [a, b] = b-a+1
      - the n_th of a sequential: x+(n-1)
  2. 连续整数的平均数&中位数
      - 如果不提 consecutive odd/even，则默认公差为“1”
      - Median = 0.5*(least + greatest)
          > e.g. staring from x, in a group of 25 consecutive integrals, the median is 3 times the value of the least number:  
          3*[x] = Median = 0.5*(x+x+25-1)  

  3. 连续整数的和
      - sum = (least + greatest)*num/2，注意items的正负
      - consecutive integers at least contain 2 items, its product must be the even
      - Notice of zero
        > The sum of some consecutive integers (including 2-->require of positive items) is -11  
        As -11 = -11 = -5-6 --> num of consecutive integers is at least 2+ 4+1+4=11

  4. 连续整数乘积
      - 三个连续整数相乘的结果为2，3，6的倍数
        > If n is an integer greater than 1. What is the value of k that cannot make sure n(n^2-1)/k is an integer?  
        2, 3, 6 ok; while 4, is the choice  
        Notice: n(n^2-1)= (n-1)(n)(n+1)


- 【考点】Quotient and remainder
  1. 商与余数的定义
      - A / B = C ... D
      - When ***A*** is divided by ***B***, he quotient is ***C***, and remainder is ***D***; A=B*C+D
        > B is not zero!  
        C can be zero.  
        Reminder D must smaller than B

      - quotient(C) 商是从零开始的
  2. 根据双重 除数/余数，求被除数
      - n = 3x+2 = 5y+3
      - 列举出最小的n，然后根据两个quotient的最小公倍数，得到什么特性的n可以
        > n_min = 8, Least common multiple = 15  
        Then, general expression of item is n = 8 + 15k

  3. 指数幂的个位循环性
      - 底数的位数是2-9的时候，幂函数的个位数是有共性的循环的，最多4次一循环！
      - 如果讨论的是 tens digit 十位数，那么也存在循环，只要关注末2位就可以。
  4. 被除数 为高次幂时 求余数
      - 本质上跟上一个考点一致，先得到高次幂的个位，才能得到余数
      - 相信出题者，一定是有了loop，才敢出这种题目
      - ***当底数比较大*** 的时候,把底数拆分成 除数与另一个小数字。根据二项式定理拆分，只用管没有除数的那个小数字的高次幂就够了。
          > X = 123^4-123^3 ... what is the remainder when X is divided by 122?  
          rewrite 123=122+1. then (123^n)/122=...1

  5. 能被特殊数字整数 的数字的规律
      - 一个整数的各个数字之和可以被3or9整除，则整个数也可以。
      - 一个整数的 ***最后两位*** 能被 (4，或25，或20) 整除，则整个数也可以。
          > 724 因为结尾能被4整除，所以724是4的倍数

- 【考点】Prime and composite 质数与合数
  1. 基本定义与取值范围
      - Prime and composite only focus on Positive integers
      - ***1*** is ***neither Prime nor composite***
  2. 与奇偶性质结合的考点
      - 2是唯一一个既是Prime也是even的数
      - 两个质数相加为odd，那么一定包含了2
        > When ***n*** is any prime greater than 2, will n+5 be a prime also?  
        NO. when Prime n+5>2, it must be an odd. then n must be an even. If n is prime, n can only be 2, which is not allowed.

#### 2. fraction
- numerator, denominator, common denominator
- 【考点】numerator, denominator
  1. 比大小：试数，a-b的形式，a/b的形式
      - AB两个选项之间比大小，在保证都为正的情况下，直接用比例的大小来验证来比较AB的选项大小。最快
  2. 相反数与倒数: inverse, reciprocal.
      - 尤其注意负数的reciprocal

#### 3. 指数与根
- 对于5^2, 5 is the base, while 2 is exponent(指数)
- 【考点】指数与根的四则运算-比大小
  1. 注意指数的合并原则
  2. 可以举反例证明“两者大小不确定”
  3. 分母有理化
  4. 拆分与表达！

#### 4. 小数decimals
- 【考点】数位的表达
  1. before decimal：thousands digit, hundreds digit, tens digit, ones digit/units digit
  2. After decimal: tenths digit, hundredths digit, thousandths digit.
  3. 能看懂描述，然后用数学公式表达
      > abc = a*100+b*10+c

- 【考点】科学技术法 scientific/ base decimal notation
- 【考点】小数的有限性与循环性质--重点看分母的factors包含什么
  1. terminate, terminating decimal
  2. repeat, repeating decimal
  3. irratinal number 无限不循环小数 (unterniating irrepeating decimal)
  4. 分数一定是terminating decimal or repeating decimal， 然而irrational number一定不是fraction


#### 5. 实数
- real number, number line, interval, absolute value
- 【考点】数轴 number line
  1. Interval(inclusive/exclusive)
  2. the tick marks are equally spaced.
  3. locate exponent number on linear number line.

- 【考点】absolute value [distance from the number to zero on number line.]
  1. 面对绝对值方程/不等式：先去掉绝对值
      > |3x+2|<5 --> -5<3x+2<5

#### 6. Ratio
- proportion, corss multiplication
    > a/b = c/d  <---> ad=bc

- 【考点】读文字描述，建立proportion 关系式

#### 7. 百分数 Percent
- 【考点】谁是分母 -- than 后面的是分母
  1. A is x percent more than B
      > (A-B)/B = x%; A= B(1+x%)

  2. increase/decrease (to/by) ...
  3. What percent of A is B? [of 后面跟着的是分母]
