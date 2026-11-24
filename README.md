# Star Predict System

스마트폰 밤하늘 사진에서 별과 별자리를 인식하고, 천문 좌표로 결과를 검증하는 팀 프로젝트입니다[cite: 3].

## 시연 영상

- [Orion 시연 영상 보기 (`Orion 시연.mp4`)](Orion%20%EC%8B%9C%EC%97%B0.mp4)[cite: 4]

## 프로젝트 구조

- `Constellation/`: 데이터 수집, 영상처리, Plate Solving, WCS 검증, YOLO 학습·평가[cite: 3, 4]
- `front/`: 사용자가 사진을 올리고 결과를 확인하는 React 화면[cite: 3, 4]

## 상세 문서

설치 방법, 데이터 출처, 01~36단계의 역할, 최신 성능과 남은 작업은 [Constellation 상세 README](Constellation/README.md)에 정리되어 있습니다[cite: 3, 4].

> 원본 사진, 학습 데이터, API 키와 모델 가중치는 GitHub에 포함하지 않습니다[cite: 3].