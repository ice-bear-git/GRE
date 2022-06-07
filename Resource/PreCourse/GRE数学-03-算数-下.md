## GRE数学-【算数】部分

#### 1. Factors & multiples
- 【考点】分解质因数
  1. 分解质因数：把一个正整数分解成多个质数相乘的形式
      - 有“2”
  2. 分解因数：把一个正整数分解成多个正整数相乘的形式
      - 可以有“1”与“其本身”

- 【考点】质因数&因数的个数问题
  1. 质因数：Prime divisors
      - How many prime divisors does 16000 has? Ans: 2 (only 2 and 5)
      - Method: 种类数
  2. 因数：positive divisors / positive factors
      - How many positive divisors does 16000 has? Ans: 32
      > As 16000=2^4 * (2^3)(5^3)=(2^7)(5^3). you always have one more choice for each multiple item: Ans=8*4=32  

      - Method: 各个质因数的指数+1 相乘
  3. 用 distinct prime numbers给信息，然后问 # of positive factors
      - 注意关键词！ Distinct; Odd; prime
      > As a and b are distinct odd prime numbers:  
      The number of positive factors of 2ab^2 and a^2b^3 are the same, equally 12=2*2*3=3*4

      - distinct odd prime numbers 里面唯独没有2，包含余下的所有Prime


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

#### 2. 最小公倍数 与 最大公约数
- Least common multiple 最小公倍数
- Greatest common divisor 最大公约数
- "least common multiple" is multiple of "Greatest common divisor"
