---
layout  : wiki
title   : 대역폭(Bandwidth)
summary : 단위 시간 동안 전달 가능한 최대 데이터 양
date    : 2019-07-09 16:22:04 +0900
updated : 2020-02-03 23:59:28 +0900
tag     : network performance
toc     : true
public  : true
parent  : [[what]]
latex   : false
---
* TOC
{:toc}

## 인용
### (책) TCP/IP 완벽 가이드

* 2 . 네트워크 성능 문제와 개념. 35쪽.

> 대역폭(Bandwidth)은 네트워크나 데이터 전송 매체의 데이터 운반 능력을 가리키는 데 널리 쓰이는 용어다.
이것은 단위 시간 동안 한 지점에서 다른 지점으로 전달될 수 있는 최대 데이터 양을 의미한다.
이 용어는 전자기 방사 연구에서 나왔는데 원래는 데이터를 전송하는 데 쓰이는 주파수 대역의 크기를 가리켰다.
항상 그렇지는 않지만, 일반적으로 대역폭은 이론적인 뜻으로 쓰인다.  
대역폭은 주파수 대역폭과 데이터 용량이라는 두 가지 의미로 쓰인다.
예를 들어 무선 기술에서는 라디오 주파수가 쓰이는데, 이러한 기술의 대역폭은 라디오 주파수 대역이 얼마나 넓은지를 나타낸다.
하지만 이보다 더 많이 쓰이는 대역폭의 뜻은 **네트워크를 통해 전송되는 데이터의 양**이다.

### (책) 시스템 성능 분석과 최적화

* 9장. 디스크. 434쪽.

> 대역폭: 저장장치 트랜스포트나 컨트롤러의 최대 데이터 전송률을 말한다.

* 10장. 네트워크. 521쪽.

> 대역폭(bandwidth): 어떤 네트워크 유형에서 최대 데이터 전송 비율(시간당 전송량)을 말하며, 보통 초당 비트 수(bps)로 이야기한다. "10GbE"란 10Gb/s 인 이더넷을 의미한다.

## 참고문헌

* TCP/IP 완벽 가이드 / 찰스 M. 코지에록 저/강유, 김진혁, 민병호, 박선재 역 / 에이콘출판사 / 2007년 01월 25일 / 원제 : The TCP/IP Guide: A Comprehensive, Illustrated Internet Protocols Reference
* 시스템 성능 분석과 최적화 / 브렌든 그레그 저 / 오현석, 서형국 공역 / 위키북스 / 초판 2015년 12월 15일

## 함께 읽기

* [[latency]]{지연시간(Latency)}