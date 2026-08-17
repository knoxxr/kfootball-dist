# kfootball-dist

K-Football의 배포 파일만 두는 공개 저장소입니다. 소스는 별도의 비공개 저장소에 있습니다.

- `latest.json` — 게임이 읽는 버전 정보
- `kfootball.apk` — 최신 빌드

게임 안의 업데이트 버튼이 `latest.json`을 읽어 `versionCode`를 비교하고, 더 높으면
`url`에서 받아 설치 화면을 띄웁니다.
