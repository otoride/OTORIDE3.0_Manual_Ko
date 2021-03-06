---
title: "카셰어링 시스템 공통정책"
permalink: /policy/
toc: true
---

1. 회원 자격
	- 만21세 이상 

2. 운전 자격
	- 운전면허 취득 1년 이후 이용 가능 (취득 1년 미만의 운전면허증이더라도 시스템에 등록할 수는 있으며, 운전면허증을 관리자가 승인해주면 차량 예약이 가능합니다.) 

3. 회원의 구분 
	- 법인회원: 법인 소속으로 업무용으로 차량을 이용하는 회원 (법인관리자가 등록한한 법인카드로 요금 결제)
	- 개인회원: 법인 소속으로 개인용으로 차량을 이용하는 회원 (개인이 요금 결제)
	- 일반회원: 법인회원과 개인회원을 제외한 모든 회원

4. 이용조건 
	- 일반회원 : 가입 후 관리자의 면허승인과 결제카드 등록이 필요
	- 법인회원 : 가입 후 관리자의 회원승인과 면허승인이 필요
	- 개인회원 : 가입 후 관리자의 회원승인, 면허승인과 결제카드 등록이 필요

5. 차량 예약
	- 예약 시간 단위 : 10분
	- 최소 예약 시간 : 30분
	- 최대 예약 시간 : 30일 (720시간)
	- 최대 예약 가능한 미래 일자 : 대여종료일 기준 90일까지
	- 현재 시간의 이후로만 차량 예약 가능
		- 차량 검색시점 기준 5분 이후의 차량 예약 가능(10분 단위)
		-조회일시가 9:33경우, 9:40 이후 예약 가능한 차량이 조회
		-조회일시가 9:37경우, 9:50 이후 예약 가능한 차량이 조회
	- 두 예약 건 사이의 최소 간격은 20분
		-9:00까지 예약된 차량은 14:20부터 예약 가능
		-반납처리 유예시간 10분 + 다음 사용자의 예약 시간 확보하기 위한 10분
	- 반납 완료 차량은 바로 예약이 가능한 상태로 전환 (예약 유효성검사 프로세스와 동일)
		-14:21 에 반납완료된 차량은 14:30부터 예약 가능
		-14:26 에 반납완료된 차량은 14:40부터 예약 가능

6. 예약 변경
	- 변경 가능 : 시간변경, 보험, 옵션 변경만 가능 
	- 예약 변경시, 기존 결제 취소 이후 새 결제 진행
	- 변경 불가 : 차량 (차량을 변경하는 경우에는 예약을 취소) 

7. 예약 취소
	- 이용시작시간 전 취소 가능
	- 이용시작시간 전이더라도 차량제어를 시작했다면 취소 불가 (스마트키 이용시작 버튼 누른 시점)

8. 요금 결제 시점
	- 대여요금: 사용자 예약 완료 시점에 결제가 동시에 진행 (결제 실패 시 차량 예약이 되지 않습니다)
	- 주행요금: 반납 완료 후 10분 이내 자동 결제
	- 연장요금: 대여중 대여종료시간을 연장한 경우, 반납 완료 후 주행요금과 함께 자동 결제
	- 예약취소수수료: 예약취소를 시도한 시점에 자동 결제
	- 추가과금: 패널티, 범칙금, 실패한 결제건 등에 대해서 관리자가 수동으로 결제 시도

9. 차량의 제어
	- 이용 시작시간 5분전 부터 차량 제어가능
	- 사용자가 차량을 반납하면 차량 제어 불가능
	- 반납이 지연되더라도 스마트키 제어 가능

10. 차량 반납 조건
	- 차량시동 OFF, 도어락, 미등OFF
	- 지정된 반납 위치에 주차 (관리자 설정시에만)
	- 전기차의 경우 충전플러그에 연결되어 있어야 한다. 
	- 키박스가 연결되어져 있는 경우 키박스가 ‘반납’상태로 되어 있어야 한다. 
