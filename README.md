# homework3_14_15
# 수치해석(Matlab)
## 데이터 각각의 정보(표준편차 등) 구하기
![14 4-1](https://user-images.githubusercontent.com/58453290/70115558-76648180-16a3-11ea-8739-bbfff1e4b86d.JPG)

![14 4-2](https://user-images.githubusercontent.com/58453290/70115561-79f80880-16a3-11ea-96a4-2677d28190c9.JPG)

![14 4-15](https://user-images.githubusercontent.com/58453290/70115564-7bc1cc00-16a3-11ea-9687-39e2ee65020d.JPG)

x=[2 4 6 7 10 11 14 17 20];

y=[4 5 6 5 8 8 6 9 12];

x0=linspace(1,20,20);

s=[x y];

std=std(s)

median=median(s)

mode=mode(s)

var=var(s)

hist(s)
