# ChotaGolaSimulator

[Appie-1019/GolaGolaSimulator](https://github.com/Appie-1019/GolaGolaSimulator)의 가장 작은 포크.

- **chota** = 힌두어로 "작다" + [chota.css](https://jenil.github.io/chota/) 레퍼런스
- **단일 HTML 파일 하나** (511KB) — 폰트/이미지/사운드/3D 모델 전부 base64 내장, 인터넷 없이도 동작
- 원본 Unity 로직(조작 방식 12종)을 JS로 이식, 원본 FBX 모델 + 텍스처 사용

## 링크
* [플레이](https://dfloat.github.io/ChotaGolaSimulator/)
* [원본](https://github.com/Appie-1019/GolaGolaSimulator)
* [안전빵 버전 (용량 최적화 전)](https://github.com/DFloat/ChotaGolaSimulator/blob/main/golagolasimulator.html)

## 기능
- 조작 방식 12종: 기본 / 관성 / 부드럽게 / 회전 / 반전 / 애피 슬라이드 / 발작 / 동상 / 추적 / 나이스한 컴퓨터 / 뚱뚱남 / 잔상
- 애피 슬라이드: 원본 `ThatBox_LowPoly.fbx` 파싱 데이터 + 원본 텍스처로 소프트웨어 3D 렌더
- 설정 (TAB): 조작 방식 / 토스트 / 배경색(RGB+HEX) / 볼륨 3채널
- 토스트 메시지 (원본 스택 메커니즘), 저장(localStorage), 인트로 경고 문구, 크레딧
- 원본 사운드 에셋 (GolaGola Voice, Tick/Tock, Bell 등)

## 조작
- `TAB` : 설정 메뉴
- `M` : 마우스 커서 토글
- 뚱뚱남 모드에서 클릭: 날려보내기

## 파일
| 파일 | 설명 |
|---|---|
| `index.html` | 프로덕션 (로직 경량화 + 데이터 최적화, 511KB) |
| `golagolasimulator.html` | 안전빵 (용량 최적화 전 버전) |
