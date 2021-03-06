---
title: "시스템관리자 매뉴얼"
permalink: /SystemAdmin/
toc: true
---

## 고객사관리 
### 신규 고객사를 등록하는 방법
>고객사관리 > 신규등록 

- 기본정보를 입력합니다.
	- 아래의 정보는 필수 입력값입니다. 
		* 고객사명
		* 주소

| 필드 | 설명 |
|--|--|
|OTORIDE ID | 임의의 값을 입력하여 사용합니다. 오토라이드가 고객사를 식별하기 위한 고유값입니다. |
| OTOPLUG CLIENT ID | 사전에 발급받은 값을 입력합니다. 오토플러그에서 고객사를 식별하기 위한 고유값입니다. |
|OTOPLUG SECURITY CODE | 사전에 발급받은 값을 입력합니다. |
| PG사 | GMO를 선택합니다. |
| PG 계정 |발급받은 값을 입력합니다.  |
| PG 인증키 | 발급받은 값을 입력합니다. |
| 구글지도키 | 유효한 구글지도키를 입력합니다. |
| 서비스메뉴 | CS(카셰어링)를 선택합니다. (관제서비스(FMS),카셰어링서비스(CS), 영상관제서비스(DVR)) |
|메뉴구성 | 메뉴관리에서 사전에 구성한 메뉴 중 한가지를 선택합니다. |



- 계약 정보를 입력합니다. 
	- 신규로 등록하는 고객사의 비즈니스 타입을 선택합니다. 
	- Vehicle Type : 차량의 타입을 선택합니다.
	- Device Type : 디바이스 타입을 선택합니다.
	- 사용 ACC : 추가적으로 사용하는 악세사리를 선택합니다. 
	- 예약단위: 차량단위로 운영하는 고객사인지, 클래스단위로 운영하는 고객사인지 선택합니다. 

- 고객담당자 정보를 입력합니다. 

- 마스터ID 생성 
	- 등록하는 고객사의 슈퍼 관리자(마스터)의 ID를 등록합니다. 마스터ID는 중복되어선 안됩니다. 


## 메뉴관리

### 신규 메뉴셋을 등록하는 방법
> 메뉴관리 > ‘메뉴등록 ' 

 - 시스템 코드를 택일합니다. 
	 - CS : 카셰어링
	 - FMS : 차량관제
	 - DVR : 영상관제 
 - 카셰어링 새로운 메뉴셋을 구성하기 위해선 CS를 선택합니다. 
 - 기본적으로 모든 메뉴가 제공되는 형태로 표시됩니다. 
 - 사용/사용안함을 선택하여 고객사에게 선별적으로 메뉴를 제공할 수 있습니다. 

 
## DEVICE관리

### 신규 디바이스를 등록하는 방법
> DEVICE 관리 > ‘신규등록'

고객사가 차량을 등록하기 위해선 시스템관리자가 사전에 디바이스를 등록해줘야 합니다. 

 - 제원정보를 입력합니다. 
	 - 사용/비사용 : ‘사용’을 선택합니다. 추후에 디바이스를 사용하지 않는 경우엔 비사용으로 바꿀수있습니다. 
	 - 고객사 : 디바이스를 등록하려는 고객사를 입력합니다. 
	 - 주행거리 방식 : 단말이 차량으로부터 주행거리를 가져올 수 있는 경우에는 Device를 선택합니다. 가져오지 못하는 경우에는 GPS를 선택합니다. 
	 - 차대번호 : 차대번호를 입력합니다.
	 - Terminal ID: 차량의 단말이 통신하기 위한 고유 코드로서 사전에 발급받은 값을 입력합니다. 
	 - Fuel Type: 연료타입을 선택합니다. 연료타입은 공통코드에서 관리할 수 있습니다. 
	 - 초기주행거리 : 주행거리방식을 GPS를 선택한 경우 초기주행거리 값을 입력해줍니다. Device를 선택한 경우에는 입력하지 않아도 됩니다.

 
- Device 정보를 입력합니다. 
	- Device 기종 : CS를 선택합니다.
	- 그 외의 정보는 필수입력이 아니며, 관리차원에서 입력하여 활용하시기 바랍니다. 

- 디바이스가 성공적으로 등록된 경우에는 고객사의 차량관리 페이지에 리스트업 됩니다.

## 공통코드 관리 
### 공통코드를 추가하는 방법 

오토라이드 시스템 내에서 유동적으로 값을 추가하거나 수정/삭제 할 수 있도록 코드형태로 관리되는 데이터가 있습니다.

*면허종류/
FAQ 종류/
DEVICE 종류 /
악세사리 /
PC사 /
연료타입/
변속기/
차량상태/
메뉴 프리셋/
1:1문의 상태/
계약 종류/
메뉴구성/
국가 종류*	

그 외의 코드를 추가적으로 등록하여 활용할 수 있습니다. 

## 랜드마크관리
### 랜드마크를 추가하는 방법
- 시스템관리자가 랜드마크를 등록하여 고객사의 지점과 맵핑할 수 있습니다.
- 랜드마크관리 > 신규등록을 클릭합니다. 
- 랜드마크명을 입력합니다. 
- 입력한 랜드마크에 맵핑하고자 하는 지점을 선택할 수 있습니다. 


## 공휴일관리 
### 공휴일을 추가하는 방법
- 구글캘린더에서 공휴일 정보 가져오기 
- 좌측 아래에 ‘ 캘린더 불러오기’를 클릭합니다. 
- 기본적으로 구글캘린더로부터 일본의 기본 공휴일 정보를 가져올 수 있습니다. 
- 수정한 공휴일 정보는 고객사 운영관리자의 페이지에 즉시 반영됩니다. 
- ‘삭제’를 클릭하여 특정 공휴일을 삭제할 수 있습니다. 
- ‘신규등록’을 클릭하여 공휴일을 추가할 수 있습니다. 


## FAQ관리
고객사들의 시스템 사용을 돕기 위해 FAQ를 만들어서 제공할 수 있습니다. 이곳에서 등록한 FAQ는 운영관리자가 우측 상단의 물음표(?) 버튼을 눌러서 확인합니다. 

### 신규 FAQ를 등록하는 방법 

- 카테고리관리 : 카테고리를 등록할 수 있습니다.
- 신규등록을 클릭합니다. 
- 카테고리를 선택합니다. 
- 제목과 내용을 입력하고 ‘등록’을 클릭합니다. 