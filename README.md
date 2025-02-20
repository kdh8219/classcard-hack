# 📗 Classcard Hack
언어: [![Language](https://shields.io/badge/TypeScript-3178C6?logo=TypeScript&logoColor=FFF&style=flat-square)](https://www.typescriptlang.org/)<br>
**:warning: 악용금지! 학습 목적으로만 사용해주세요.**   

## 📙 설명
* 클래스카드 자동화
* 클래스카드 모바일 앱에서 사용하는 api를 사용합니다. (브라우저를 쓰는 것보다 안전함.[^w])

- [x] 암기 학습
- [x] 리콜 학습
- [x] 스펠 학습
- [x] 테스트
- [x] 매칭 게임
- [x] 스크램블 게임
- [x] 퀴즈배틀
   
**퀴즈배틀 게임 중 스크램블게임과 헌트게임은 지원하지 않습니다.**

## 📄 사용법
**아래 스텝 진행 전 [discord.dev](https://discord.dev)에서 봇을 만들고 intent를 다 킨 후 토큰을 발급받고 진행하셔야 합니다.**<br>
1. `npm i`를 실행합니다.
2. `npm start`를 실행 후 생성된 config.json 파일을 수정합니다. (디스코드 봇 토큰, 디스코드 봇 소유자 id, 서버 id)
3. `node index.js`를 실행합니다.
4. 봇을 디스코드 서버에 초대합니다.
5. 디스코드 서버에서 `!setup`을 전송합니다.
6. `#사용`채널에서 버튼을 누르고 사용하시면 됩니다.

## 📸 사진
![SS](./images/Screenshot_2022-08-06_191853.png)

[^w]: 브라우저를 사용하는 핵들은 대부분 자바스크립트를 쓰는데 오류가 난다면 클래스카드에 오류 내용을 자동 전송하고 선생님께 알림이 갈 수도 있기 때문.