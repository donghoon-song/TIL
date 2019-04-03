---
layout: post
title: "TIL(Today I learned)(190330)"
date: 2019-03-30
blog : true
author : Donghoon Song
summary : "Today I learned"
permalink : /TIL/:year/:month/:day/:title
comments: true
tag: TIL
---

# React의 장점

## UI 상태 자동 관리
UI의 추적과 상태 관리는 힘들고 시간이 많이 드는 일.
리액트는 UI의 마지막 상태만 신경쓰면 된다.
리액트가 나머지 모두를 알아서 관리

## 번개같이 빠른 DOM 조작
리액트는 가상DOM을 만들어 조작한다.
가상DOM의 조작은 매우 빠르며, 리액트는 적절한 시점에만 실제 DOM을 갱신. 변경돼야 하는 부분만 파악해 최소한의 DOM변경만 수행한다.(비교조정)

## 결합이 용이한 UI를 지원하는 API
여러 컴포넌트로 작게 쪼개도록 권장

## 자바스크립트로 정의하는 비주얼
자바스크립트만으로 UI를 정의하면 템플릿 안에서 모든 종류의 작업을 자바스크립트가 제공하는 풍부한 기능을 사용해 할 수 있다.

## MVC 아키텍처에서의'V'
비주얼한 요소와 그 상태를 최신으로 유지하는 데 중점을 두는 뷰레이어에서 작동한다. M과 C에 해당하는 부분은 무엇이든 원하는 대로 자유롭게 사용할 수 있다.


## JSX를 브라우저가 이해할 수 있는 평범한 자바스크립트로 변환하는 방법

1. 노드와 그 외 빌드 툴 등으로 구성된 개발 환경을 구축한다. 이 경우, 빌드를 수행할 때마다 JSX의 모든 사항이 자동으로 자바스크립트로 변환되며, 다른 일반적인 자바스크립트 파일처럼 참조할 수 있도록 파일이 디스크에 저장된다.

2. JSX를 자동 변환하는 자바스크립트 라이브러리를 사용한다. 이 경우 다른 자바스크립트의 경우처럼 JSX를 직접 지정하면 되고, 나머지는 브라우저가 알아서 처리한다.
