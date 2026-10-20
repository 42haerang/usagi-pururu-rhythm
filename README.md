# 푸루루! 리듬 소동

우사기 랩 팬 리듬게임. 빌드 과정 없이 실행하는 HTML/CSS/JavaScript 프로젝트입니다.

## 실행

Node.js가 설치된 환경에서 다음 명령을 실행한 뒤 http://localhost:4173 을 여세요.

```sh
npm start
```

## 조작

S/D/F/J/K: 이·야·하·우·라, L: 푸루루, A: 인어 코러스, 스페이스: 보너스 연타. 화면 버튼과 내려오는 블록도 누를 수 있습니다. 외침 구간은 보너스 버튼을 연타합니다. 음원은 YouTube 플레이어로 재생하며 원곡 오디오는 저장소에 포함하지 않습니다.

## 채보

dist/assets/solo-chart.json에 시간·버튼·파트·검증 상태를 기록합니다. 실행 페이지의 SONG 데이터와 함께 갱신해야 합니다. 파형 기반의 추정 시점을 포함하며 전곡 청취 검증을 마친 채보는 아닙니다. 자세한 변경 내용은 docs/part-audit.md를 참고하세요.

## 파일

- dist/index.html: 게임 화면과 판정·보정 로직
- dist/assets/: 채보, 인어 이미지, 춤추는 우사기 영상
- scripts/serve.cjs: 로컬 정적 서버

춤 영상 출처: https://tenor.com/view/usagi-dance-chiikawa-tease-hehe-gif-7163663705603193535
원곡 재생: https://www.youtube.com/watch?v=wFOjWCLPDDM

팬 프로젝트이며 외부 캐릭터·이미지·음악의 권리는 각 권리자에게 있습니다.

