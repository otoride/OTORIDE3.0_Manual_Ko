---
title: "차량 등록하기"
permalink: /registerVehicle/
toc: true
---

차량을 등록하기 위해서는 아래 항목의 사전등록이 완료되어야 합니다. 
- **단말기등록, 구역등록 , 지점등록, 모델등록**
- 단말기등록은 차량에 단말기장착이 완료되면 시스템관리자에서 진행합니다.

## 차량관리
### 신규 차량을 등록하는 방법

> 차량관리 > 차량관리 > ‘신규등록’ 클릭

차량에 단말기가 장착이 완료되고 시스템 관리자가 단말기와 차대번호를 맵핑하여 사전에 등록을 합니다. 단말기 장착이 완료된 차량만 등록이 가능하며, 단말기 등록이 완료되었지만 아직 등록하지 않은 차량은 차대번호를 눌러서 확인할 수 있습니다.

-  차량 정보 입력
차량정보에 입력한 정보는 모바일앱 > 차량상세정보에 표시되는 내용을 포함하고 있습니다.
앱에 표시되는 정보 : 제조사, 모델, 연식, 변속기, 색상, 승차정원, 유류타입, 차량이미지
	-  클래스: 예약 단위가 클래스인경우, 차량이 속할 클래스를 선택합니다.
	-  차량알림: 차량에 발생하는 알림을 관리자에게 발송할지 선택합니다.
	-  차대번호: 차량의 고유값으로, 단말기 등록이 완료된후 자동으로 리스트업 됩니다.
	-  차량구분: 정상, 정비, 사고, 매각, 기타 중에 선택합니다. 정상인 경우에만 서비스 운영에 활용할 수 있습니다.
	-  제조사, 모델명: 사전에 차량관리>모델관리에서 등록한 모델을 선택합니다.
	-  차량번호: 단말기 장착이 완료된 차량의 경우 자동으로 리스트가 제공됩니다.
	- 운전면허유형: 등록하는 차량의 운전 가능한 면허를 선택합니다. 이곳에 등록한 운전면허보다 낮은 레벨의 운전면허를 가진 사용자는 해당 차량을 예약할 수 없습니다. 
	-  초기주행거리: 단말기가 차량에서 자동으로 불러오는 정보입니다.
	-  이미지: 앱에 표시되는 차량 이미지로 미등록 시 기본 이미지를 제공합니다.
	-  전기차 여부 : 차량의 전기차 여부를 선택합니다.
	-  저전압경고: 저전압 경고 알림을 받을 기준치를 등록합니다. 차량의 전압이 입력한 하한선 수치로 내려갔을 때 알림이 발송되며, 상한선 이상으로 다시 올라왔을 때 알림 발송 해제됩니다.

-  차량 장비 입력
	-  입력한 정보는 모바일앱 > 차량상세정보에 표시됩니다.
	-  차량에 장착되어 있는 장비를 입력합니다.
	-  EX) 에어백, 후방감지센서, 운전보조장치, 블랙박스, 열선시트 등

-  정보 입력
	-  차량은 반드시 하나의 지점에 소속되어 있어야 합니다.
	-  사전에 지점관리에서 등록한 지점 중에 선택이 가능합니다.
	-  새로운 구역을 추가하고 싶으면 지점관리 > [구역관리](#구역관리) 에서 등록해주세요.
	-  새로운 지점을 추가하고 싶으면 지점관리 > [지점관리](#지점관리) 에서 등록해주세요.

-  요금제정보
	-  차량의 요금제를 선택합니다.
	-  등록시에 선택하지 않고 추후에 선택할 수 있습니다.
	-  ‘상세확인’을 눌러서 요금제의 상세 정보를 확인할 수 있습니다.

-  옵션정보
	-  차량에 보험상품과 옵션상품을 추가하는 방법
	-  차량에 추가하여 판매할 보험상품과 옵션상품을 지정할 수 있습니다.
	-  보험과 옵션 등록시 ‘필수’로 지정된 경우에는 차량에서 판매를 해제할 수 없습니다.
	-  옵션정보에 추가된 정보는 유저앱에서 차량 예약시 표시됩니다.

-  이용 정보
	-  특정 법인 소속 회원에게만 차량을 보이게 하는 방법
	-  이용대상을 선택합니다. 법인차량 선택시, 선택한 법인회원들만 이용 가능합니다.
	-  복수의 법인이 이용하는 차량의 경우에는 ‘법인추가’를 클릭해 추가할 수 있습니다.
	-  일반차량을 선택하면, 일반회원에게만 차량이 표시됩니다.

-  취소정보
	-  차량 예약시에 적용할 취소 정책을 선택합니다.

-  단말기 정보
	-  차량에 장착된 단말기 정보로서 선택한 차대번호 에 따라 자동으로 입력됩니다.

-  보험 정보

	-  차량이 가입되어있는 보험을 선택합니다.
	-  사전에 보험관리에서 등록한 보험 중에 선택이 가능하며, 선택시 보험정보가 자동으로 표시됩니다.

-  주유카드 정보

	-  차량 내 비치된 주유 카드정보를 등록하여 관리합니다.

-  사용/비사용

	-  차량을 서비스에서 제외하고 싶은 경우 ‘비사용’을 선택합니다.
	-  차량을 비사용으로 선택시 서비스 운영에 이용할 수 없습니다


### 차량을 일괄로 등록하는 방법

> 차량관리 > 차량관리 > ‘차량일괄등록’ 클릭

엑셀 파일을 업로드해서 차량을 일괄로 등록할 수 있습니다.

-  엑셀 양식 다운로드
-  엑셀 파일 작성
-  다운받은 양식에 맞춰 정보를 입력합니다.
-  ‘찾아보기’로 파일을 선택한 후 ‘업로드’ 클릭하여 업로드합니다.

## 클래스 관리

### 클래스를 등록하는 방법

클래스 관리는 클래스 단위로 차량 예약을 받는 경우 사용하는 메뉴입니다.

-  클래스 정보 입력
	-  클래스명, 클래스설명, 이미지는 모바일앱에서 클래스 상세 정보에 표시되는 내용입니다.

-  지점 정보 선택

	-  클래스를 표시할 구역과 지점을 선택합니다.
	-  전체구역과 전체지점 선택 시, 모든 지점에서 해당 클래스를 예약할 수 있습니다.
	-  클래스를 등록할 때 선택한 구역과 지점은 변경할 수 없습니다.
	-  선택한 지점에 따라 선택할 수 있는 요금제, 보험, 옵션 등이 달라집니다.

-  차량정보

	-  차량 정보를 입력합니다. 입력한 정보 (제조사,모델명, 색상, 변속기, 유류타입, 승차정원)는 모두 모바일앱의 클래스 상세정보에 표시됩니다.

-  차량장비

	-  입력한 정보는 모바일앱 > 클래스상세정보에 표시됩니다.
	-  차량에 장착되어 있는 장비를 입력합니다.
	-  EX) 에어백, 후방감지센서, 운전보조장치, 블랙박스, 열선시트 등

-  요금제 정보 선택

	-  클래스에 적용할 요금제를 선택합니다.
	-  요금제를 아직 만들지 않은 경우 나중에 선택할 수 있습니다.

-  옵션 정보 선택

	-  클래스에 판매할 옵션과 보험을 선택합니다.
	-  차량에 추가하여 판매할 보험상품과 옵션상품을 지정할 수 있습니다.
	-  보험과 옵션 등록시 ‘필수’로 지정된 경우에는 차량에서 판매를 해제할 수 없습니다.
	-  옵션정보에 추가된 정보는 유저앱에서 차량 예약시 표시됩니다.

-  차량 등록

	-  해당 클래스에 속하는 차량을 선택합니다.
	-  사용자가 클래스를 예약시 선택한 차량들 중에서 임의로 배정이 되며, 나중에 수동으로 차량을 변경할 수 있습니다.
	-  클래스에 맵핑된 차량을 수정하는 방법
	-  클래스에 등록하고 싶으면 체크박스에 체크를 한 후에 오른쪽 화살표를 클릭하여 우측으로 이동시킵니다. 해당 클래스에 맵핑된 차량을 해제 하고 싶으면 우측의 리스트에서 삭제를 선택합니다.

### 클래스를 삭제하는 방법

> 차량관리 > 클래스관리 > 클래스를 선택 > 클래스상세

- 페이지 하단 좌측에 ‘삭제’버튼을 누릅니다.

## 옵션관리

보험과 옵션을 등록하여 차량을 예약하는 사용자에게 판매할 수 있습니다.

### 옵션을 등록하는 방법

> 운영관리 > 옵션관리 > ‘신규등록’ 을 클릭합니다.

-  기본정보

	-  옵션구분: ‘상품’에 체크합니다.
	-  필수/선택: 등록하는 옵션을 모든 차량 전체에 필수로 판매할지 선택합니다. 필수인 경우 차량의 옵션에서 삭제가 불가능하고, 선택인 경우에는 차량 옵션 등록시 삭제가 가능합니다.
	-  본사관리자가 ‘필수’로 등록한 옵션은 구역이나 지점의 관리자가 삭제할 수 없습니다.
	-  보유개수 : 보유하고 있는 옵션의 개수를 입력합니다
	-  최대선택개수 : 사용자가 예약할 때 최대 선택할 수 있는 옵션의 개수를 입력합니다.
	-  업로드한 이미지는 사용자 앱의 옵션상세정보에 표시됩니다.

-  판매기간
	-  판매 시작일과 판매 종료일을 입력하면 해당 기간 내에만 옵션이 표시됩니다.
	-  판매기간 중이더라도 ‘중지’를 클릭하면 옵션이 표시되지 않습니다

-  요금정보
	-  일요금제: 일단위 과금 방식
	-  일 요금제일 경우, 양 일에 걸쳐 대여한 시간이 연속 6시간 초과 시 2일 요금으로 과금됩니다.
	-  시간요금제: 시간당 과금 방식
	-  최대요금: 사용자가 옵션 대여시 입력한 금액을 초과하지 않습니다.
-  조정요금
	- 입력한 누적대여일 이상 대여시 할인되는 요금입니다. 1일은 24시간입니다.
	- 누적대여일:3, 할인요금: 10,000원 입력하면, 3일이상(72시간) 대여시 전체금액에서 10,000원을 할인해줍니다.

-  지점정보
	-  옵션을 판매할 지점을 선택합니다.
	-  전체구역/전체지점 : 모든 지점에서 판매

### 보험을 등록하는 방법

> 운영관리 > 옵션관리 > ‘신규등록’

-  기본정보

	-  보험을 등록하는 방법은 옵션을 등록하는 방법과 동일하며 옵션구분에서 보험을 선택하면 됩니다.
	-  옵션구분: ‘보험’에 체크합니다.
	-  약관 추가 : 약관 추가를 클릭하여 약관을 입력할 수 있으며 입력한 약관의 내용은 사용자 앱의 보험은 상세정보에 표시됩니다. 보험별로 약관은 하나만 추가 가능합니다.

## 구역관리

> 지점관리 > 구역관리

구역은 지점을 관리하는 상위 그룹 체계로, 지점을 등록하기 위해서는 반드시 1개 이상의 구역이 등록되어져 있어야 합니다.

### 구역을 등록하는 방법
-  ‘구역추가’를 클릭하면 빈 필드가 생성됩니다.
-  필드에 구역명을 입력하고 저장을 누릅니다.

### 구역을 삭제하는 방법
-  구역을 삭제하기 위해서는 해당 구역에 연결되어 있는 지점이 없어야 합니다.
-  연결된 지점이 없는 구역을 먼저 ‘비사용’처리 합니다.
-  비사용처리를 하면 사이트에 표시되지 않습니다.
-  ‘삭제’를 클릭해 구역을 삭제하고 ‘저장’을 누릅니다.

## 지점관리

지점은 차량 등록 시 필수로 입력되어져야 하는 정보로, 반드시 1개 이상의 지점을 등록해야 합니다. 지점을 등록하기 위해서는 반드시 하나 이상의 구역이 만들어져 있어야 합니다. ‘ (지점관리 > 구역관리) ’

### 지점을 등록하는 방법

> 지점 관리 > 지점 관리 > 신규등록

-  지점정보 입력
	-  구역명: 지점의 상위 분류 개념 (내부적으로 사용하는 용어로 변경 가능합니다.)
	-  지점코드: 지점코드는 영문과 숫자를 사용하여 임의로 입력합니다.
	-  대표자명, 연락처: 해당 지점의 현장관리 대표자의 정보를 입력합니다.
	-  이벤트 SMS 수신 : 정비, 이벤트, 도난의심 등에 따른 문자 알림을 수신 받는 여부를 선택합니다. Y로 체크하면 해당지점의 관리자 전원에게 알림을 발송합니다.
	-  개점일시와 폐점일시: 개점일시와 폐점일시 내에만 사용자가 차량을 예약할 수 있습니다.
	
-  관리자 정보 입력
	-  해당 지점의 관리자를 최대 10명까지 추가 가능합니다.
	-  관리자 개별 SMS 알림수신 여부를 선택합니다.
	
-  위치 정보 입력
	-  상세주소를 입력하면 지도에 핀이 표시됩니다.
	-  지점의 주소를 입력한 후 위도/경도의 필드를 클릭하면 입력한 주소의 위경도가 자동으로 입력되고, 지도상에 핀이 표시됩니다.
	-  반납거리: 사용자가 차량 반납시 반납 처리의 기준이 되는 거리로, 입력한 거리에 들어와야만 차량이 반납됩니다.
	-  도난알림 거리: 차량이 운영시간 외에 해당지점의 위경도를 중심으로 일정 거리 이상 벗어났을 경우 알림이 발송되는 되는 기준입니다.
	-  주행영역 거리: 차량이 운영시간 중 일정 거리 이상을 이탈해 주행했을 경우 알림이 발송되는 기준입니다.
	
-  주차장 위치 (선택입력)
	-  차량이 특정 위치에 주차되어 있는 경우 입력합니다.
	-  이 필드를 입력할 경우, 사용자가 모바일앱에서 차량을 반납할 때 주차위치를 선택할 수 있습니다.
	
-  추가정보
	-  유저앱 > 메인지도(예약하기) > 지점 선택 > 지점상세정보에서 표시되는 내용입니다.
	-  지점 1곳당 URL 1개를 등록할 수 있습니다.(선택)
	-  URL은 반드시 http:// 또는 https://를 포함하여 입력해야 합니다.
	-  사용자가 모바일앱에서 URL을 클릭하면 브라우저가 열리고 페이지로 이동합니다.
	-  ‘설명&이미지’를 추가하여 지점에 대한 상세 정보를 자유롭게 입력할 수 있습니다.
	
-  랜드마크정보
	-  지점과 연결되어 있는 랜드마크가 표시됩니다.
	-  지점의 랜드마크를 연결하는 것은 랜드마크관리에서 해주세요.

### 예약 알림 발송 주기를 관리하는 방법

지점의 예약알림발송을 관리하기 위해선 지점의 신규등록을 완료하고 나서 지점상세 화면으로 진입해야합니다.

> 지점관리 > 지점관리 > 지점 선택 > 지점상세화면 하단의 ‘예약알림관리’ 클릭

-  차량을 예약한 사용자에게 배차 알림을 수동/자동 으로 보낼지 선택합니다.
-  설정된 발송 주기에 따라 예약 회원에게 배차알림 메일을 자동발송합니다.
-  발송주기보다 짧은 시간 내 예약시, 예약완료 시점에 바로 발송합니다.

### 지점별 운영시간을 관리하는 방법

-  지점의 운영시간을 관리하기 위해선 지점의 신규등록을 완료하고 나서 지점상세 화면으로 진입해야합니다.	

> 지점관리 > 지점관리 > 지점 선택 > 지점상세화면 하단의 ‘운영시간관리’ 클릭

-  유저앱 > 메인지도(예약하기) > 지점 선택 > 지점상세정보에서 표시되는 내용입니다.
-  지점에 소속되어 있는 차량은 운영시간에만 차량을 대여할 수 있습니다.
-  운영시간 외의 차량은 차량 검색시 표시되지 않습니다.

### 지점별 영업일을 관리하는 방법

지점의 영업일을 관리하기 위해선 지점의 신규등록을 완료하고 나서 지점상세 화면으로 진입해야합니다.

> 지점관리 > 지점관리 > 지점 선택 > 지점상세화면 하단의 ‘영업일관리’ 클릭

-  지점별로 영업일을 관리할 수 있습니다.
-  기본적으로 모든 날짜가 영업일로 지정되어 있습니다. (영업일 핑크색)
-  월달력에서 일자별로 클릭해서 영업일<>비영업일 전환합니다.
-  전체/평일/주말공휴일 선택 후, 영업일/비영업일 선택하고 ‘적용’을 클릭하면 선택된 조건대로 일괄 적용됩니다.
-  ex) 평일 선택 & 영업일 선택 후 ‘적용’ 클릭 → 팝업에 보이는 월달력의 모든 평일을 영업일로 적용
-  영업일 지정이 끝났으면 ‘저장하기’를 누릅니다.

## 모델관리

### 차량의 모델을 등록하는 방법
모델은 차량 등록 시 필수로 입력되어져야 하는 정보로, 반드시 1개 이상의 모델을 등록해야 합니다.
> 운영관리 > 모델관리

-  차량 모델 별로 저전압 발생 및 해제 값을 입력합니다.
-  입력된 값을 기준으로 관리자에게 ‘저전압 경고’알림이 발송됩니다.
-  저전압 경고 알림 기능을 사용하지 않는 경우, 모두 0으로 입력합니다.

## 랜드마크 관리

시스템에 등록된 여러지점을 랜드마크로 묶어서 관리하면 사용자가 랜드마크로 지점을 쉽게 검색할 수 있습니다.

### 랜드마크를 등록하는 방법

> 지점관리 > 랜드마크 관리 > ‘신규등록’

-  랜드마크명을 입력합니다.
-  ‘지점추가’를 클릭해서 랜드마크에 연결할 지점을 추가합니다.
-  복수의 지점을 추가할 수 있습니다.