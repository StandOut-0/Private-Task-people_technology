# 갤럭시워치 라이프로그 수집 모니터링 시스템


스마트워치 기반 라이프로그 데이터 수집·관리 솔루션 설계 문서

산출물 모음
https://docs.google.com/spreadsheets/d/1Qgu2bLnQG3w2WF_bGuQZ_ZTa9mTFLGd1GMYIWTshXjY/edit?gid=278481539#gid=278481539

스토리보드
https://docs.google.com/presentation/d/17iNTmOrqaRmydnQQ9OtsPM4iqUwVAD0Q/edit?slide=id.g3f4f544f2be_0_190#slide=id.g3f4f544f2be_0_190


## 개요

재택환자에게 할당된 갤럭시워치를 통하여 환자의 생체신호, 활동, 운동, 수면 데이터를 수집하여 의료진이 환자의 상태를 모니터링하고 임상적 연구 데이터로 활용하기 위한 시스템 설계입니다.

### 프로젝트 목표

- 스마트워치(갤럭시워치)를 통해 스마트폰으로 수집되는 라이프로그 데이터를 수집·전송·관리하는 솔루션 설계
- 연구 참여자 또는 대상자로부터 수집되는 활동, 수면, 심박수 등 생체·행동 데이터를 서버로 전송·저장·관리할 수 있는 체계 설계
- 향후 디지털 바이오마커 연구 및 임상실증 수행에 활용 가능한 기반 시스템 확보


## 시스템 구성도
<img width="1865" height="1116" alt="1  시스템 구성도" src="https://github.com/user-attachments/assets/a3fdce8a-e52d-4972-9e03-c47a378e760f" />

## 사이트맵
<img width="1865" height="1116" alt="2  사이트맵" src="https://github.com/user-attachments/assets/abadbf46-edb5-4a32-a035-cbf07c03e6c6" />

## 화면목록
<img width="663" height="507" alt="3  화면목록(googlesheet 캡쳐본)" src="https://github.com/user-attachments/assets/350f2f7f-9bfe-4c54-b0e0-72dd20c0313d" />

## 기능정의
<img width="659" height="712" alt="4  기능정의(googlesheet 캡쳐본)" src="https://github.com/user-attachments/assets/56e0c117-6b9f-42ab-b180-81cf7c6a2666" />

## 권한정의
<img width="763" height="446" alt="5  권한 정의(googlesheet 캡쳐본)" src="https://github.com/user-attachments/assets/c60b2102-aa83-4f11-b345-ee88f5f1f319" />

## 사용자 흐름
<img width="1865" height="1116" alt="6  사용자 흐름" src="https://github.com/user-attachments/assets/fd24b5cf-9941-4b07-bfc8-aad1c702e8d5" />
<br><br><br>


## 데이터 정의
<img width="3749" height="2244" alt="2  ERD" src="https://github.com/user-attachments/assets/0a15004f-2696-4907-af51-2fe7da36dc33" />
<br><br><br>

## 와이어프레임

<img width="1865" height="1116" alt="5  화면 이동 흐름 - 1" src="https://github.com/user-attachments/assets/959c3506-406b-4ea1-bdae-a8504a5bd8e2" />
<img width="1865" height="1116" alt="5  화면 이동 흐름 - 2" src="https://github.com/user-attachments/assets/e85b85da-f3ea-4c89-bcca-25930105038d" />

<img width="1394" height="1127" alt="A-01 로그인 화면" src="https://github.com/user-attachments/assets/c9d2ef23-0147-4648-a37b-6db48a02e3f2" />
<img width="1394" height="1127" alt="A-02 홈 화면" src="https://github.com/user-attachments/assets/fbc3d089-3989-4f50-81d8-8c3b6ebb3e7f" />
<img width="1394" height="1127" alt="A-03 전송 이력 화면" src="https://github.com/user-attachments/assets/71f4bcdc-5246-4e53-9e63-157d8b10764c" />
<img width="1394" height="1127" alt="A-04 내 정보 화면" src="https://github.com/user-attachments/assets/8a4564e9-4bca-4d9d-b026-8413953fec2c" />
<img width="1394" height="1127" alt="A-05 설정 화면" src="https://github.com/user-attachments/assets/ab4d9ba6-f14a-4117-bdeb-7455e8b76418" />

<img width="1394" height="1127" alt="W-01 관리자 로그인 화면" src="https://github.com/user-attachments/assets/0784f9a3-6396-40c3-aad8-b7d838d0feb2" />
<img width="1394" height="1127" alt="W-02 대시보드 화면" src="https://github.com/user-attachments/assets/e4b5d9da-2fd7-472d-afbf-97e82568b1ad" />

<img width="1394" height="1127" alt="W-03 대상자 관리 화면 - 1" src="https://github.com/user-attachments/assets/b874669f-26a5-4df9-9adc-f757f3dd10e1" />
<img width="1394" height="1127" alt="W-03 대상자 관리 화면 - 2" src="https://github.com/user-attachments/assets/385b38fb-8ec6-4124-bcfc-f55288235589" />

<img width="1394" height="1127" alt="W-04 장치 관리 화면 - 1" src="https://github.com/user-attachments/assets/a8cbd43e-9c2b-4a52-97d1-9698751beebc" />
<img width="1394" height="1127" alt="W-04 장치 관리 화면 - 2" src="https://github.com/user-attachments/assets/5e62eec2-decd-45bb-b2ad-587bf6a27efc" />

<img width="1394" height="1127" alt="W-05 대상자-장치 매핑 화면 - 1" src="https://github.com/user-attachments/assets/75724b6a-9b6e-482e-b2b5-0569bf9a9b02" />
<img width="1394" height="1127" alt="W-05 대상자-장치 매핑 화면 - 2" src="https://github.com/user-attachments/assets/1be419e8-f19b-40c5-8e36-06187a67afe6" />

<img width="1394" height="1127" alt="W-06 라이프로그 조회 화면" src="https://github.com/user-attachments/assets/a752eb82-b7b5-4337-8cc1-726dd5451080" />
<img width="1394" height="1127" alt="W-07 수집 이력 화면" src="https://github.com/user-attachments/assets/f757bd4e-4c22-41f2-90c8-74f480bf9138" />
<img width="1394" height="1127" alt="W-08 CSV 다운로드 화면 - 1" src="https://github.com/user-attachments/assets/cac44cc6-b33f-409b-9d81-53ce33cd47cf" />
<img width="1394" height="1127" alt="W-09 관리자 계정 화면 - 1" src="https://github.com/user-attachments/assets/49126202-3697-4016-8180-6035efd74f49" />
<img width="1394" height="1127" alt="W-09 관리자 계정 화면 - 2" src="https://github.com/user-attachments/assets/0b44641b-508b-4ff6-891e-a4fe2ee08fa8" />


<br><br><br>


## 스토리보드
<img width="1906" height="1070" alt="A-01 로그인 화면" src="https://github.com/user-attachments/assets/3deaace5-3510-4f40-b717-5d544efb1bed" />
<img width="1906" height="1070" alt="A-02 홈 화면" src="https://github.com/user-attachments/assets/39ac9ceb-68de-4f76-99d5-53f8a21daf35" />
<img width="1906" height="1070" alt="A-03 전송 이력 화면" src="https://github.com/user-attachments/assets/e0d22495-ca78-499b-afa5-b8399b1e6bbe" />
<img width="1906" height="1070" alt="A-04 내 정보 화면" src="https://github.com/user-attachments/assets/491281f0-8357-4396-b453-231196687563" />
<img width="1906" height="1070" alt="A-05 설정 화면" src="https://github.com/user-attachments/assets/1408f64b-0d92-4878-b176-7def53d1e3fe" />
<img width="1906" height="1070" alt="W-01 관리자 로그인 화면" src="https://github.com/user-attachments/assets/96241478-0b09-44e7-85ff-73ee74b31cc1" />
<img width="1906" height="1070" alt="W-02 대시보드 화면" src="https://github.com/user-attachments/assets/e0ee54bc-12ed-427b-88ec-045b19ca4f6a" />
<img width="1906" height="1070" alt="W-03 대상자 관리 화면 - 1" src="https://github.com/user-attachments/assets/ba7badfe-c5c1-4931-8ced-3bde137d8eb1" />
<img width="1906" height="1070" alt="W-03 대상자 관리 화면 - 2" src="https://github.com/user-attachments/assets/f6a86575-2b15-435c-8def-35094600ec98" />
<img width="1906" height="1070" alt="W-04 장치 관리 화면 - 1" src="https://github.com/user-attachments/assets/402b1faf-f0d3-4aa8-a4cc-fc9f47f68cbe" />
<img width="1906" height="1070" alt="W-04 장치 관리 화면 - 2" src="https://github.com/user-attachments/assets/329b2e4f-7835-4fef-9806-b0396b43c166" />
<img width="1906" height="1070" alt="W-05 대상자-장치 매핑 화면 - 1" src="https://github.com/user-attachments/assets/2b967af5-ff3f-4693-91d1-1496b9259bcd" />
<img width="1906" height="1070" alt="W-05 대상자-장치 매핑 화면 - 2" src="https://github.com/user-attachments/assets/189cc205-6f6f-4ea6-bbf7-85821386e510" />
<img width="1906" height="1070" alt="W-06 라이프로그 조회 화면" src="https://github.com/user-attachments/assets/bd68aa0d-df44-4a19-90bb-b47ea30ed73c" />
<img width="1906" height="1070" alt="W-07 수집 이력 화면" src="https://github.com/user-attachments/assets/deeba568-c791-4936-816c-0187fc2a8aba" />
<img width="1906" height="1070" alt="W-08 CSV 다운로드 화면 - 1" src="https://github.com/user-attachments/assets/b182e7e8-681e-4998-a4cf-3b7f2358a378" />
<img width="1906" height="1070" alt="W-08 CSV 다운로드 화면 - 2" src="https://github.com/user-attachments/assets/4d1a23e7-e8bf-4316-b522-ecf9e8c74b32" />
<img width="1906" height="1070" alt="W-09 관리자 계정 화면 - 1" src="https://github.com/user-attachments/assets/fc5ba61b-488b-4bdf-815f-15de37f475b2" />
<img width="1906" height="1070" alt="W-09 관리자 계정 화면 - 2" src="https://github.com/user-attachments/assets/bd526855-7d61-469b-ae9d-d9f9ebd2c1c1" />







<br><br><br>




## 시스템 구조

```
Galaxy Watch
      ▲
      │ https restapi 
      ▼
Android App
      ▲
      │ https rest api
      ▼
Backend API
   │ sql      │ metrics logs
   ▼          ▼
Database  Monitoring Web(Admin)
```

### 구성 요소

- **안드로이드 앱**: 참여자용 데이터 수집 앱
- **백엔드 서버**: 데이터 수집 및 관리 API 서버
- **모니터링 웹**: 관리자용 수집 상태 확인 및 CSV 다운로드

## 문서 구조

### IA (Information Architecture)
- `1. 시스템 구성도`: 전체 시스템 구조 및 데이터 흐름
- `2. 사이트맵`: 화면 구조 및 계층
- `3. 화면목록`: 전체 화면 목록 및 ID
- `4. 기능정의`: 주요 기능 정의
- `5. 권한 정의`: 사용자 역할별 권한
- `6. 사용자 흐름`: 참여자 및 관리자 사용자 흐름

### 데이터 정의
- `2. ERD(DBML 기반)`: 데이터베이스 엔티티 관계도
- `3. 테이블 정의`: 주요 테이블 정의 및 설명
- `4. 컬럼 정의`: 테이블별 컬럼 상세 정의
- `5. 코드 정의`: 코드 테이블 정의 (상태, 역할 등)
- `6. 관계 설명`: 테이블 간 관계 설명

### 스토리보드
- `1. 화면별 와이어프레임`: 각 화면의 와이어프레임 및 시각화 방법
- `2. 화면 설명`: 화면별 상세 설명
- `3. 기능 설명`: 화면별 기능 상세 설명
- `4. 이벤트 및 예외 처리`: 이벤트 및 예외 처리 정의
- `5. 화면 이동 흐름`: 화면 간 이동 흐름
- `7. API 명세서`: RESTful API 상세 명세
- `8. 스토리보드`: 통합 스토리보드 문서

## 주요 기능

### 참여자 앱 (Android)
- **로그인**: 가명식별번호 + 인증번호 기반 인증
- **홈 화면**: 장치 상태, 데이터 수집 상태, 동기화 현황
- **전송 이력**: 데이터 전송 결과 및 오류 내역 조회
- **내 정보**: 참여자 기본 정보 조회
- **설정**: 알림 설정, 앱 버전 확인, 로그아웃

### 관리자 웹 (Monitoring Web)
- **대시보드**: 전체 운영 현황 (대상자, 장치, 수집률, 오류)
- **대상자 관리**: 참여자 등록, 수정, 비활성화
- **장치 관리**: 장치 등록, 수정, 상태 변경
- **대상자-장치 매핑**: 장치 배정 및 해제
- **라이프로그 조회**: 대상자별/기간별/항목별 데이터 조회
- **수집 이력**: 동기화 세션 및 오류 내역 조회
- **CSV 다운로드**: 데이터 추출 및 다운로드
- **관리자 계정**: 관리자 계정 관리

## 데이터 수집 항목

- 걸음 수
- 소모 칼로리
- 활동 시간
- 운동 기록
- 이동 거리
- 수면 세션
- 수면 단계
- 심박수
- 안정 시 심박수
- 산소포화도

## 주요 코드 정의

### 장치 상태 (DEVICE_STATUS)
- `ACTIVE`: 정상 연결
- `DISCONNECTED`: 연결 끊김
- `INACTIVE`: 사용 중지
- `ERROR`: 오류 상태

### 사용자 역할 (USER_ROLE)
- `ADMIN`: 일반 관리자 (담당 대상자 조회/다운로드)
- `SUPER_ADMIN`: 최고 관리자 (전체 관리 가능)

### 참여자 상태 (PARTICIPANT_STATUS)
- `ACTIVE`: 활성
- `INACTIVE`: 비활성
- `WITHDRAWN`: 탈퇴

## 로그인 방식

### 참여자 로그인
- 입력: `participantCode` (가명식별번호) + `loginCode` (인증번호)
- 인증: PARTICIPANT_ACCOUNT 테이블 기반

### 관리자 로그인
- 입력: `loginId` + `password`
- 인증: ADMIN_USER 테이블 기반

## 시각화 방법

### 차트 유형
- **도넛 차트**: 상태 분포 (대상자, 장치, 권한)
- **라인 차트**: 시계열 데이터 (일별 추이, 심박수)
- **바 차트**: 오류 유형별 건수
- **Progress bar**: 비율 표시 (배터리, 수집률, 상태)
- **이중 Progress bar**: 대비 표시 (성공/실패, 정상/오류)

### 데이터 그룹화
- 관련 데이터를 함께 배치 (대상자/장치 카드 그룹)
- 상태 표시를 상단바에 작게 표시 (동기화 상태, 진행 상태, 총 인원)

## 기술 스택

- **프론트엔드**: Android (참여자 앱), Web (관리자 웹)
- **백엔드**: RESTful API
- **데이터베이스**: 시계열 데이터 저장에 적합한 구조
- **통신**: HTTPS REST API

## 기대 효과

- 스마트워치 기반 라이프로그 수집체계를 통해 디지털 헬스 연구 수행 기반 마련
- 수집 → 전송·저장 → 다운로드로 이어지는 기본 데이터 파이프라인 확보
- 향후 복약 모니터링, 증상 추적, 디지털 바이오마커 탐색 등 다양한 연구로 확장 가능한 기반 확보

## 문서 작성 일지

- [Day02] 스토리보드 작성을 위해 API명세서를 추가
