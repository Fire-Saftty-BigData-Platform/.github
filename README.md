# FireFlow AI

**소방안전 데이터와 AI 기술을 활용한 화재 대피 안내 및 현장 정보 요약 웹서비스**

FireFlow AI는 화재 발생 상황에서 시민에게는 상황별 대피 안내를 제공하고,  
소방관에게는 신고 내용과 건물 정보를 기반으로 현장 대응 우선순위를 요약해주는  
AI 기반 소방안전 웹앱 프로젝트입니다.

---

## Project Goal

화재 상황에서 흩어진 정보를 빠르게 정리하고,  
시민과 소방관이 더 빠르고 안전하게 판단할 수 있도록 돕는 서비스를 개발합니다.

---

## Main Features

### Citizen Mode

- 현재 위치 및 상황 입력
- 연기 여부, 계단 이용 가능 여부, 갇힘 여부 선택
- AI 기반 상황별 대피 안내 제공

### Firefighter Mode

- 건물 주소 및 신고 내용 입력
- 건물 기본 정보 확인
- AI 기반 현장 상황 요약
- 위험도 및 대응 우선순위 제공

---

## Tech Stack

### Frontend

- React
- Vite
- JavaScript
- CSS

### Backend

- FastAPI
- Python
- Pydantic

### Future Integration

- OpenAI API
- Kakao Map API
- 소방안전 빅데이터
- 건축물대장 API
- 건물 도면 / BIM / 실내지도 데이터

---

## Repository Structure

| Repository | Description |
|---|---|
| `fireflow-ai` | Main MVP web application |
| `.github` | Organization profile |

---

## Current Status

현재는 최소 실행 가능한 MVP를 개발하는 단계입니다.

- 시민용 대피 안내 기능
- 소방관용 상황 요약 기능
- 더미 건물 데이터 기반 시연
- 지도 placeholder UI

향후 실제 공공데이터 및 AI API를 연동하여 확장할 예정입니다.

---

## Slogan

> 화재 현장의 정보를 더 빠르게,  
> 시민의 대피 판단을 더 안전하게.

---

## License

This project is developed for a fire safety data and AI service contest.
