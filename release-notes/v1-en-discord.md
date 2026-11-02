## Manimal Lighthouse zzap v1

**- Less garbage memory on other maps (Labs etc.), editing db files no longer blocks the game**

■ Changes
- Maps other than Lighthouse produced 20-58 MB of garbage a minute - every light built a new scene-name string every frame (Labs measured 20.5 MB → 0.1 MB)
- Editing a json in the db folder made the server stop the mod and the game could not connect - now it only warns and uses the file (restart the server; not yet tried with an edited file)
- Includes the original author's later buoy flicker fix

■ Install
- Install the original mod first (this zip has no map): <https://sp-mod.com/mod/3022/manimals-10-lighthouse-rework-backport>
- Extract Manimal-Lighthouse-1.0.7-zzap-v1.zip into your SPT folder and overwrite (settings kept)

■ Notes
- To go back, extract the original mod again
- Please don't contact the original author about this build

■ Credits
All praise to manimal1920 - the credit belongs to them.
Support manimal1920 : https://ko-fi.com/manimal1920

^^7

-----------------
@Foreigner

원본모드 : https://github.com/danauraborealis/ManimalLighthouse
다운로드 : https://github.com/danyhappy564-cmyk/ManimalLighthouse-zzap--Bootleg-/releases/tag/zzap-v1
