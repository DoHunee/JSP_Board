## MO 프로젝트 서버부분!

## 실행 환경 세팅

// package.json이 포함된 루트 폴더에서 !
npm install 

// node_modulesnode/globals.global.d.ts 파일에서 

//declare var global: typeof globalThis;
declare interface Global {
    logger: Logger; // 예시로 Logger 타입이라 가정
}
declare var global: Global;
코드 이렇게 변경!!


// 터미널에 설치!
npm i --save-dev @types/cors

// 시작은 npm start로!!!