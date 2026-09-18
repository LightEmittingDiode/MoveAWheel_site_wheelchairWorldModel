# 자율주행 휠체어 월드 모델 아키텍처

센서 입력부터 인지, 특징 공학, 통합 월드 모델, 위험도 평가 및 디지털 트윈까지의 전체 구조를 인터랙티브 다이어그램으로 시각화한 프로젝트입니다.

## Demo

https://lightemittingdiode.github.io/MoveAWheel_site_wheelchairWorldModel/

## 주요 구성

- 센서 입력
- 인지 출력
- 월드 모델용 특징 공학
- 통합 월드 모델
- 위험도 및 통과 가능 여부 평가
- 경로 탐색
- 디지털 트윈

## 기능

- 노드별 연결 관계 시각화
- 마우스 오버 시 직접 연결된 1-hop 관계 하이라이트
- 전체 다이어그램 PNG 내보내기
- 전체 다이어그램 SVG 내보내기
- GitHub Pages 기반 웹 공유

## 실행

별도의 설치 과정 없이 `index.html`을 브라우저에서 열면 됩니다.

로컬 웹 서버를 사용하는 경우 저장소 루트에서 다음과 같이 실행할 수 있습니다.

```bash
python -m http.server 8000
```

그런 다음 브라우저에서 `http://localhost:8000`을 엽니다.

## 기술

- HTML
- CSS
- Vanilla JavaScript
- SVG
- Noto Sans KR
- html2canvas
- html-to-image

## GitHub Pages 배포

`main` 브랜치에 변경 사항을 푸시하면 `.github/workflows/pages.yml`이 저장소 루트의 정적 파일을 GitHub Pages에 자동 배포합니다.

처음 한 번은 GitHub 저장소의 **Settings → Pages → Build and deployment → Source**에서 **GitHub Actions**를 선택해야 합니다.

## 권장 저장소 정보

- Repository name: `MoveAWheel_site_wheelchairWorldModel`
- Description: `자율주행 휠체어의 센서·인지·월드 모델·디지털 트윈 구조를 시각화한 인터랙티브 아키텍처 다이어그램`
- Topics: `autonomous-driving`, `wheelchair`, `world-model`, `digital-twin`, `sensor-fusion`, `robotics`, `architecture`, `visualization`
