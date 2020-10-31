---
layout  : wiki
title   : 수의 정밀도
summary : 실제로 갖고 있지 않은 정보를 창조하면 안된다
date    : 2019-11-06 21:23:53 +0900
updated : 2020-03-11 23:08:17 +0900
tag     : 
toc     : true
public  : true
parent  : [[math]]
latex   : true
---
* TOC
{:toc}

## 인용: 생각한다면 과학자처럼

> 수의 정밀도는 그 수에 들어 있는 유효숫자의 개수로 표현된다.
유효숫자의 개수를 결정하는 간단한 방법은 다음과 같이 수를 과학적 표기로 적어보는 것이다.
$$1,000 = 1 \times 10^3$$, $$1000.1 = 1.0001 \times 10^3$$, $$0.0045 = 4.5 \times 10^{-3}$$.
그런 다음에 앞에 오는 수의 자릿수를 세면 된다. 이 사례에서는 각각 1, 5, 2 개다.  
여러 측정값으로부터 한 값을 계산해낼 때 필요한 중요한 규칙은 결과를 '가장 덜 정밀한 측정값의 유효숫자 개수 더하기 1'의 정밀도로 제시하는 것이다.
만약 이보다 더 적은 자릿수를 사용한다면, 당신이 받은 정보의 일부를 버려라.
더 많은 자릿수를 사용한다면, 그것은 당신이 실제로 가지지 않은 정보를 '창조'해내는 짓이다.  
무슨 뜻인지 설명하기 위해 비율 2/3을 예로 들어보자.
이 분수를 0.66666666667로 근사하는 것은 수학적으로 옳다.
하지만 수 2와 3이 제한된 정밀도로 얻은 측정값이라면, 비율 계산을 더욱 보수적으로 해야 한다.
가령 한 과학자가 보고하기를, 움직이는 한 물체의 속력이 3초에 2미터 이동하는 값이라고 하자.
이때 그 물체의 속력에 대한 올바른 표시는 0.66666666667이 아니라 0.67m/s 이다.
0.66666666667m/s 이라는 표현은 소수점 아래 11자릿수의 정밀도를 갖기에 과학자가 속력을 1조 분의 1단위까지 안다는 것을 암시한다.
사실, '2미터'와 '3초'는 둘 다 정밀도가 유효싯자 한 개일 뿐이다.
그러므로 위에서 언급한 기준에 따라 답은 유효숫자 두 개로 제시돼야 한다.
따라서 2/3은 적절하게 반올림을 해서 0.67로 나타낸다.
데이터가 3.005초에 2미터라고 보고됐더라도 마찬가지다.
유효숫자가 네 개인 3.005초와 비교해서 2미터는 유효숫자가 한 개이므로 가장 덜 정밀한 측정값이다.
가장 덜 정밀한 수가 결과의 정확도를 결정하므로 또한 보고해야 할 수의 정밀도를 결정하게 된다.[^david]

## 참고문헌

*  생각한다면 과학자처럼 / 데이비드 헬펀드 저/노태복 역 / 더퀘스트 / 2017년 09월 15일

## 주석

[^david]: 생각한다면 과학자처럼. 7 거짓말, 역겨운 거짓말, 그리고 통계. 223쪽.