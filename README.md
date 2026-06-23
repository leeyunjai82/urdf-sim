# URDF Web Simulator

브라우저에서 바로 돌아가는 URDF 로봇 시뮬레이터. 설치 없이 URDF + STL 파일 업로드만으로 동작.

데모: https://leeyunjai82.github.io/urdf-sim/

<img src="test.gif" width="480">

## 기능

- 3D 뷰어 (회전·이동·줌)
- 관절 슬라이더, URDF limit 값 자동 적용
- 포즈 JSON 저장·불러오기
- 타임라인 기반 모션 편집
- 와이어프레임·좌표축 토글
- 스크린샷 저장

## 사용법

1. 데모 링크 열기
2. URDF 파일 선택
3. `meshes/` 폴더의 STL 파일 다중 선택
4. `로드` 버튼 클릭

## 예시 데이터

`data/` 폴더에 바로 써볼 수 있는 예시 로봇 포함. 각 폴더의 `meshes` zip을 풀어서 STL과 함께 올리면 됨.

- `data/arm4` — 4축 데스크탑 로봇팔
- `data/pibo` — Pibo 휴머노이드
- `data/g1` — Unitree G1 (29 DOF)

## 구성

Three.js(r128) 기반 단일 HTML 파일. 빌드·의존성 설치 없음.
