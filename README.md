# 공존 키핑 시스템

## 개요

기존 레스토랑 공존은 수기로 술 키핑 업무를 수행하고있다. 이로 인하여 키핑하는 과정, 키핑 기록을 찾는 과정에서 많은 시간이 소요되고, 누락되는 키핑 주류도 생기는 상황이다. 이런 문제를 해결하고자 공존 대빵은 술 키핑 데이터를 전산, 자동화 시키고자 한다. 

현재 적립금 시스템은 쿠폰제로 결제금액 10,000원당 500원 쿠폰 도장으로 쿠폰 기부 시스템까지 구현되어있다. 다만 명함 형식의 실물 쿠폰을 이용하기 때문에 관리에 어려움을 겪고있다. 적립의 유효기간을 설정하고, 이를 카카오톡 알림톡을 통해 알림으로서 전달하고자한다.

## 주요 기능

1. 키핑 개수별 구분 
2. 결제금액 입력 → 적립금 계산 후 저장
3. 적립금 사용
4. 공존 n호점 database 연결 및 동시 사용

## 개발 환경

**macbook pro 13inch  intel i5**

VScode 

python3.11.2 64bit

PyQt5 5.15.8

PyQt5-Qt5 5.15.2

PyQt5-sip 12.11.1

PyQt-Qt5 5.15.2

pyinstaller 5.8.0

pyinstaller-hooks-contrib 2023.0

PyMySQL 1.0.2

Qt Designer

## 빌드 환경

Operating System : Windows 11 Pro

CPU : Intel(R) Core(TM) i5-7600 CPU @ 3.50GHz 3.50 GHz

RAM : DDR4 24GB

시스템 종류 : 64비트 운영 체제, x64 기반 프로세서

PyQt5 5.15.9

PyQt5-Qt5 5.15.2

PyQt5-sip 12.11.1

pyinstaller 5.8.0

pyinstaller-hooks-contrib 2023.0

PyMySQL 1.0.2

PyMysql 1.0.2

Qt Designer

## 사용 환경

Operating System : Windows 10 Enterprise 2016 LTSB(1607)

CPU : Intel(R) Celeron(R) CPU J1800 @ 2.41GHz 2.42GHz

RAM : 2GB

시스템 종류 32비트 운영 체제, x64 기반 프로세서

## 관리 환경

Database : AWS RDS

MySQL : Sequel Ace  /  workbranch

## How to build git?

### build

```python
pyinstaller -F --noconsol --version-file file_version.txt main.py
# -F : Onefile
# --noconsol : Without consol
# --versoin-file : Add version info
# file_version.txt : Version info
# main.py : Activative file
```

## How to use program?

![README_menual_1 0 0](https://user-images.githubusercontent.com/113882868/225732228-f0a2ecd1-99f9-4a54-b89e-28c3eb54aa8d.png)
