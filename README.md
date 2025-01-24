# MSW를 Next.js 15에 적용

### Reference
[msw-with-next^15](https://github.com/mswjs/examples/tree/with-next/examples/with-next)

0. npx create-next-app@latest 설치 (All Enter)
1. npx msw init public 실행
2. public/MockServiceWorker.js을 붙여넣기
3. mocks 폴더를 만들고 `browser`, `node`를 다음 파일과 같이 작성
4. app/msw-provider.tsx와 같이 컴포넌트 만들기
5. app/layout.tsx에 node 환경에서 msw를 실행시키도록 코드 작성
6. msw 즐겁게 사용 