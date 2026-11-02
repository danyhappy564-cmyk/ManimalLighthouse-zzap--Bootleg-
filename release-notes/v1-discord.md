## Manimal Lighthouse zzap v1

**- 다른 맵(연구소 등) 쓰레기 메모리 감소, db 파일을 고쳐도 게임이 켜짐**

■ 바뀐 것
- 등대가 아닌 맵에서 1분에 20~58MB씩 생기던 쓰레기 메모리 — 조명마다 매 프레임 장면 이름을 새로 만들던 것 수정 (연구소 실측 20.5MB → 0.1MB)
- db 폴더 json을 고치면 서버가 모드를 멈춰 접속이 막히던 것 → 경고만 띄우고 그대로 씀 (서버 재시작 필요, 수정본으로는 미실험)
- 원작자가 나중에 넣은 부표 깜빡임 수정 포함

■ 설치
- 원본 모드를 먼저 받아 설치해야 작동 (이 압축엔 맵 없음): <https://sp-mod.com/mod/3022/manimals-10-lighthouse-rework-backport>
- Manimal-Lighthouse-1.0.7-zzap-v1.zip 풀어서 SPT 폴더에 덮어쓰기 (설정 유지)

■ 주의
- 이상하면 원본 모드 압축을 다시 덮어쓰면 원래대로
- 원작자분께 문의하지 말아 주세요

^^7

-----------------
@알림 @테스터

원본모드 : https://github.com/danauraborealis/ManimalLighthouse
다운로드 : https://github.com/danyhappy564-cmyk/ManimalLighthouse-zzap--Bootleg-/releases/tag/zzap-v1
