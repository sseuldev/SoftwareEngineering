# Requirement List

| No. | Requirement | Use case |
| --- | ----------- | -------- |
| 1   | 관리자와 회원은 ID와 비밀번호로 로그인합니다. | 로그인 |
| 2   | 관리자와 회원은 로그아웃 버튼을 눌러 로그아웃합니다. | 로그아웃 |
| 3   | 관리자는 대여소 이름, 위치, 자전거 보관 가능 수량, 운영 시간 등을 입력하여 대여소를 등록합니다. | 대여소 등록 |
| 4   | 관리자는 등록된 대여소 목록을 조회합니다. 이때 대여소 목록에서 특정 대여소를 선택해서 삭제할 수 있습니다. | 대여소 목록 조회 |
| 5   | 관리자는 특정 대여소의 상세 정보를 조회합니다. | 대여소 상세 정보 조회 |
| 6 | 관리자는 자전거 ID, 자전거 제품명, 유형, 소속 대여소, 상태 등을 입력하고 자전거 정보를 등록합니다.| 자전거 등록|
| 7 | 관리자는 등록된 자전거 목록을 조회합니다. 목록에서 선택하여 자전거를 삭제할 수 있습니다. | 자전거 목록 조회 |
| 8 | 관리자는 특정 자전거의 상세 정보를 조회합니다. | 자전거 상세 정보 조회 |
| 9 | 관리자는 자전거 대여 정보를 반납 시간 기준 최근순으로 조회합니다. 지역별 기준 정렬을 선택하여 지역별 기준으로 조회할 수 있습니다. | 자전거 대여 정보 조회 |
| 10 | 관리자는 자전거 대여 금액 및 대여횟수의 조회 기간을 선택합니다. 선택한 조회 기간에 따라 최근 1주일, 1개월, 1년 기준으로 조회할 수 있습니다. | 기간별 통계 조회 |
|  11  | 필수 입력 정보(ID, 비밀번호, 전화번호, 결제 수단, 선호 자전거 유형(일반/전기) 등)을 입력해 회원으로 가입합니다.                                                                                                                                                                             | 회원가입              |
|  12  | 회원을 탈퇴합니다.                                                                                                                                                                                                                                                                          | 회원 탈퇴             |
|  13   | 회원은 현재 자신이 대여 중인 자전거 리스트를 확인합니다. 이때 회원은 자전거를 반납할 수 있고, 요금은 자동 결제됩니다. 또한 사용자 위치 정보를 기반으로 근처 식당을 추천 받아 예약할 수 있는 외부 서비스와 연결될 수 있습니다. 반납 시 대기 1순위 회원에게 예약되었다는 이메일이 발송됩니다. | 대여 중인 자전거 조회 |
|   14  | 회원은 자전거 대여 시간 및 요금을 확인합니다.                                                                                                                                                                                                                                               | 요금 조회             |
|  15   | 회원이 대여소 이름을 입력해 대여소를 검색하면 조건에 맞는 대여소 리스트들을 출력합니다                                                                                                                                                                                                      | 대여소 검색 및 출력   |
|  16   | 해당 대여소에 관한 상세 정보(대여소 이름, 대여소 위치, 사용 가능 자전거 목록 등)을 조회합니다. 자전거가 남아있는 경우 즉시 대여, 없는 경우 예약 대기를 신청할 수 있고, 문자 알림을 통해 해당 내용을 전송합니다.                                                                             | 대여소 상세 정보 조회 |
|  17   | 회원이 자전거 예약 대기를 신청한 내용을 조회하면 자전거 예약 대기 정보(대여소 이름, 대여소 위치, 자전거 ID, 자전거 제품명, 자전거 유형) 리스트를 출력합니다. 각 예약 대기 신청에 대해 취소할 수 있습니다.                                                                                   | 예약 대기 정보 조회   |
|  18   | 회원이 과거 자전거 대여 기록을 조회하면 날짜별로 정렬된 대여 기록이 화면에 출력됩니다. 대여소별로도 정렬해 조회할 수 있습니다. 특정 대여 항목을 선택해 삭제할 수 있습니다.                                                                                                                  | 이용 내역 조회        |
