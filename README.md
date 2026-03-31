# MicroSoft x 성균관대 부트캠프 1기 / Ainuri 팀
공공기물 파손 신고, 위치 공유, 관리 상태 확인을 지원하는 모바일 플랫폼
<br><br>

## 프로젝트 소개
기존 공공기물 파손 신고는 접수 이후 처리 흐름이 사용자에게 잘 보이지 않고,
주변 시민이 위험 정보를 미리 인지하기도 어렵습니다.
<br><br>
저희 팀은 파손 신고를 단순 접수에서 끝내지 않고,
지도 기반 공유, 관리 상태 확인, 알림 기능까지 연결해
신고 → 공유 → 예방으로 이어지는 흐름을 목표로 했습니다.
<br><br>

## 주요 기능
- 공공기물 파손 신고 등록
- 지도 기반 파손 위치 확인
- 관리 상태 조회
- 사용자 랭킹
- 공지사항 확인
- 푸시 알림 기반 주변 위험 정보 전달
- AI 음성 신고 기능
- AI를 활용한 파손 여부 판단
<br><br>

## 프로젝트 구조
```text
MS_Project_Ainuri
├─ city_snap/         # Expo 기반 React Native 앱
├─ Project_Backend/   # FastAPI BackEnd 및 DB 연동
└─ ai/                # AI 실험 및 학습/추론 관련 코드
```
<br><br>

## 주요 기술 스택
### Front-End
- React native
- Expo
### Back-End
- FastAPI
- uvicorn
- OracleDB
- Docker
### AI
- Azure Machine Learning
- ChatGPT
- OpenAI Whisper
<br><br>

## 담당 역할
- 송성엽: 팀장, Backend 총괄 및 DB 설계
- 문병욱: Frontend 총괄, UI/UX 개발
- 이유준: whisper AI 구현, Frontend 보조
- 이재원: AI 서버 구축 및 학습
- 유영찬: AI 모델 설계 및 DB 연동
<br><br>

## 시스템 아키텍처
<img width="2095" height="1331" alt="image" src="https://github.com/user-attachments/assets/85f96cff-6e72-4f73-9d96-d842482583f8" />
<br><br>

## 시연 사진
<img width="1456" height="955" alt="image" src="https://github.com/user-attachments/assets/31cc07f4-97f2-4857-ab26-839340dd7788" />
<img width="1560" height="907" alt="image" src="https://github.com/user-attachments/assets/6fbd0bc0-541b-4cfe-89e0-8a68174a2896" />




