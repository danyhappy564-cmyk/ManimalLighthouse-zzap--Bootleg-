<p align="center">
  <a href="README.md"><img alt="한국어" src="https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-%ED%95%9C%EA%B5%AD%EC%96%B4%EB%A1%9C%20%EB%B3%B4%EA%B8%B0-6e7681?style=for-the-badge"></a>
  <a href="README.en.md"><img alt="English (this page)" src="https://img.shields.io/badge/English-This%20page-1f6feb?style=for-the-badge"></a>
</p>

# Manimal Lighthouse Rework Backport (zzap bootleg)

### ⚠️ IMPORTANT NOTICE / DISCLAIMER

- **Original Author:** Manimal (danauraborealis)
- **Original Repository:** ManimalLighthouse
- **Original Link:** https://github.com/danauraborealis/ManimalLighthouse
- **License:** MIT (as listed on the original Forge page; the original repository has no license file)
- **This Port By:** R_F (danyhappy564-cmyk) — unofficial, AI-assisted port. Not affiliated with or endorsed by the original author.

1. **Reflection & Take-Downs:** I deeply reflect on the ECOT incident. As an AI-assisted "vibe coder," I will immediately delete files if the original authors ask.
2. **No Re-Distribution:** These ported builds are unverified, temporary fixes. Please do NOT re-upload or share them anywhere else.
3. **Do Not Pester Original Authors:** Never report bugs or pester original modders regarding issues from my unofficial ports.
4. **Full Credit & Respect:** I will always credit original creators on GitHub and prioritize their decisions above all else.
5. **Support Original Creators:** Instead of using my ports, please visit the original authors' Forge pages to leave kind words or tips.

---

## Install the original mod first

This build only **overwrites the original Manimal's 1.0 Lighthouse Rework Backport**. It does not contain the original files (map bundles etc.).
**Install the original mod first, then extract this build over it.**

- Original mod: https://sp-mod.com/mod/3022/manimals-10-lighthouse-rework-backport
- **zzap-v2 is for original 1.0.8.** Do not put zzap-v2 over 1.0.7 (zzap-v1 was the 1.0.7 build).

What the zzap build changes on top of the original:

- Edited server db json files (locations, loot, items) only print a warning instead of stopping the mod, so the game still starts.
- Area lights inside a Lighthouse raid no longer build a new scene-name string every frame.

## Changelog

The full changelog (5 entries) is in the [`changelog/`](changelog/) folder, 10 per file (higher number = newer, latest: [`CHANGELOG-001.md`](changelog/CHANGELOG-001.md)). Per-release summaries: [Releases](../../releases).
