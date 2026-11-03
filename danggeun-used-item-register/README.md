# 당근마켓 중고물품 등록 화면 프로토타입

당근마켓 중고 물품 등록 시나리오(성공 13단계 + 예외 케이스 11개)를 화면으로 만든 프로토타입의 소스입니다.
화면 ID와 화면명은 엑셀 화면목록(`dg_…` 번호 체계)과 같습니다.

- 작성일: 2026-11-03
- 열람(Claude 아티팩트): https://claude.ai/artifact/Me8dhGgLgEXrWB5UGmeMCS

## 폴더 구성

| 경로 | 내용 |
|---|---|
| `project/Main.dc.html` | 프로토타입 본체. 왼쪽 화면 목록 + 오른쪽 휴대폰 화면, 테스트 설정, 전체 화면 펼쳐 보기 |
| `project/s01~s13-*.dc.html` | 성공 시나리오 단계별 보드 |
| `project/e*-*.dc.html` | 실패(예외) 케이스 보드 |
| `project/HomeScreen·WriteScreen·ListScreen·DetailScreen.dc.html` | 보드가 함께 쓰는 공용 화면 |
| `project/canvas.json` | 캔버스 배치·보드 제목 |
| `assets/danggeun-bi-flat.png` | 스플래시에 쓴 플랫 BI 이미지 |

## 알아 둘 점

- `.dc.html` 파일은 Claude 디자인 캔버스에서 실행되는 형식입니다. 이 저장소에서 브라우저로 바로 열면 동작하지 않습니다. 위 아티팩트 링크에서 확인하세요.
- 스플래시 이미지는 캔버스에 올린 이미지(`/_blob/…`)를 가리킵니다. 다른 환경에서 쓰려면 `assets/danggeun-bi-flat.png`로 경로를 바꿔야 합니다.
- 사진 기준(10MB·10장·형식 3종), 카테고리 8개, 금칙어 5개는 임시 값입니다.
