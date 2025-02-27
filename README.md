# 사랑은 냉장고를 타고: 한상

## 개요
공유냉장고를 효과적으로 관리하고 활성화하기 위해 크롤링과 딥러닝을 활용한 공유냉장고 통합관리 서비스 **한상**을 개발하였습니다.

## 프로젝트 소개
공유냉장고는 누구나 음식을 채우고 가져갈 수 있는 공공시설입니다. 본 프로젝트는 딥러닝과 데이터 크롤링 기술을 활용하여 공유냉장고의 실시간 재고를 관리하고, 보다 효율적인 이용을 돕는 서비스를 제공합니다.

## 주요 기능
- **공유냉장고 위치 시각화**: 지역 내 공유냉장고 위치를 지도에 표시
- **실시간 재고 확인**: 냉장고 안의 식품 목록 및 유통기한을 제공
- **자동 등록 기능**: YOLOv5 및 CNN을 활용한 식품 인식 및 자동 등록
- **바코드 시스템**: 바코드를 통한 간편한 식품 수령 및 기록 관리
- **알림 서비스**: 유통기한 알림 및 새로운 식품 등록 알림 제공
- **지역 화폐 마일리지**: 기부(채움) 사용자에게 지역 화폐 제공을 통한 공유냉장고 활성화

## 기술 스택
### 프론트엔드
- Figma (UI/UX 디자인)

### 백엔드 및 데이터 처리
- Python
- YOLOv5 (이미지 인식)
- CNN (딥러닝 모델)
- 데이터 크롤링을 활용한 공유냉장고 정보 수집

### 개발 환경
- Google Colab
- Spyder
- VS Code
- Windows OS

## 프로젝트 수행 방법
### 업무 분장
| 이름 | 역할 및 담당 업무 |
|------|-----------------|
| 안세준 | 팀장, 데이터 전처리 및 모델 설계 (YOLOv5) |
| 송무근 | 데이터 수집 및 시각화 |
| 이한나 | CNN 모델 학습 및 데이터 가공 |
| 정수연 | 데이터 전처리 및 문서 작성 |
| 정지은 | 프로젝트 일정 관리 및 분석 |
| 최연정 | UX/UI 디자인 및 프로토타입 제작 |

### 개발 일정
1. 프로젝트 기획 및 분석
2. 데이터 수집 및 모델 학습
3. 서비스 설계 및 구현
4. 테스트 및 개선 작업

## 기대 효과 및 활용
- **식품 폐기물 감소**: 유통기한 관리 기능을 통해 낭비 방지
- **공유냉장고 활성화**: 위치 제공 및 실시간 재고 확인 기능
- **복지 사각지대 해소**: 음식 나눔을 통한 지역사회 복지 강화
- **환경 보호**: 온실가스 배출량 및 폐기물 처리 비용 절감
- **일자리 창출**: 공공근로사업과 연계한 공유냉장고 관리 지원

## 문제점 및 해결 방안
### 문제점
- 공유냉장고의 위생 및 안전 문제
- 이용자 간 불균형 (채움이 < 받음이)
- 고령층의 스마트폰 사용 어려움

### 해결 방안
- **데이터베이스를 활용한 관리 시스템**
- **이용 규칙 설정 및 홍보 강화**
- **공공근로사업 활용하여 관리 지원**
- **태블릿/키오스크 도입으로 접근성 향상**
