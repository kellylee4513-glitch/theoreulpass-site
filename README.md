# theoreulpass-site

**https://theoreulpass.com** 을 서비스하는 저장소예요. 코드는 여기 두지 않아요.

- 실제 코드: [kellylee4513-glitch/oreumpass](https://github.com/kellylee4513-glitch/oreumpass) 의 `main`
- 배포할 때마다 `.github/workflows/deploy.yml` 이 oreumpass `main`을 가져와 GitHub Pages(커스텀 도메인 theoreulpass.com)로 올려요.
- 옛 주소 https://kellylee4513-glitch.github.io/oreumpass/ 는 oreumpass 저장소가 그대로 서비스해요. **oreumpass 저장소에는 CNAME을 넣지 않아요.**
- 언제 배포되나: ① oreumpass 에서 `bash tools/sync-site.sh` 실행(SOURCE 파일을 바꿔 올림) ② Actions 탭에서 손으로 실행 ③ 매시간 자동 확인(바뀐 게 있을 때만)
- 지금 올라가 있는 커밋: https://theoreulpass.com/deployed.txt
