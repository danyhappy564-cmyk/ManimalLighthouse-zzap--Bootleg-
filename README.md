# Manimal Lighthouse Rework Backport (zzap 부트렉)

### ⚠️ IMPORTANT NOTICE / DISCLAIMER

- **Original Author:** Manimal (danauraborealis)
- **Original Repository:** ManimalLighthouse
- **Original Link:** https://github.com/danauraborealis/ManimalLighthouse
- **License:** 원본 저장소에 라이선스 파일 없음 — 원본 저장소 참고
- **This Port By:** R_F (danyhappy564-cmyk) — unofficial, AI-assisted port. Not affiliated with or endorsed by the original author.

1. **Reflection & Take-Downs:** I deeply reflect on the ECOT incident. As an AI-assisted "vibe coder," I will immediately delete files if the original authors ask.
2. **No Re-Distribution:** These ported builds are unverified, temporary fixes. Please do NOT re-upload or share them anywhere else.
3. **Do Not Pester Original Authors:** Never report bugs or pester original modders regarding issues from my unofficial ports.
4. **Full Credit & Respect:** I will always credit original creators on GitHub and prioritize their decisions above all else.
5. **Support Original Creators:** Instead of using my ports, please visit the original authors' Forge pages to leave kind words or tips.

---

## 설치 전에 꼭 — 원본 모드부터 (Install the original mod first)

이 저장소의 빌드는 **원본 등대 리워크(Manimal's 1.0 Lighthouse Rework Backport) 모드 위에 덮어쓰는 수정본**입니다. 맵 번들 같은 원본 파일은 들어 있지 않습니다.
**원본 모드를 먼저 받아 설치한 뒤, 이 저장소의 압축을 그 위에 덮어써야 작동합니다.**

- 원본 모드: https://sp-mod.com/mod/3022/manimals-10-lighthouse-rework-backport

This build only **overwrites the original Manimal's 1.0 Lighthouse Rework Backport** - it does not contain the original files (map bundles etc.).
**Install the original mod first, then extract this build over it.** Original: https://sp-mod.com/mod/3022/manimals-10-lighthouse-rework-backport

## 변경 이력 (zzap)

- 2026-11-02 — **연구소 등 다른 맵에서 메모리 쓰레기 20~58MB/분 수정.** 면광원(AreaLight) 초기화 함수가 면광원마다 매 프레임 불리는데(연구소 약 140개, 분당 70~80만 회), 등대 장면인지 확인하려고 매번 장면 이름 문자열을 새로 만들었습니다. 이제 '등대 장면이 아님'으로 판정한 장면은 기억해 두고 다시 묻지 않습니다(등대 장면 이름이 바뀌면 기억을 지움). 확인: 빌드 오류 0, 게임 미확인.
