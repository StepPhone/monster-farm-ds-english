# Monster Farm DS — English Translation

By **StepPhone of the StepHackerZ**. **v0.1-beta — work-in-progress beta.**

An unofficial English translation patch for **Kaite Shabette Hajimeyou! Monster Farm DS (Japan)** on Nintendo DS, game code **AFMJ**. Supply your own clean Japanese ROM. No ROM, BIOS, emulator or save is included.

## Download and patch

**[Download the patch ZIP](https://github.com/StepPhone/monster-farm-ds-english/releases/download/v0.1-beta/Monster-Farm-DS-English-v0.1-beta.zip)** · [Release notes](https://github.com/StepPhone/monster-farm-ds-english/releases/tag/v0.1-beta)

1. Extract the ZIP to get the BPS patch.
2. Open [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/).
3. Select your clean Japanese `.nds` ROM and the `.bps` patch, then apply it.
4. For existing development saves, keep the output name `Monster Farm DS (English Text Draft).nds` and the matching save filename.
5. Start the patched game normally and use Continue to load an in-game save.

Apply every update to the original Japanese ROM. Restart the emulator after updating: older save states can retain old text and code. Back up your saves. No Python or translation tools are needed to play.

## Included

- Reviewed English for all 860 nonempty event-script entries and 499 system/menu messages outside the encyclopedia and debug text.
- English descriptions for all 95 items and all 25 traits.
- Translated interface graphics across farm care, training, monster data, items, expeditions and battle screens.
- Dialogue wrapping, revised destination/training-name layouts, and English training results.

## Known limitations

**This is not a complete English translation.** The latest scan found 180 referenced Japanese entries: 72 tournament entries, 30 wild-monster entries and 78 ending/staff entries. Additional readable Japanese remains in overlays, including wireless messages and drawing-pattern labels. Text embedded in other graphics may remain.

Most encyclopedia descriptions and some names/moves are machine-assisted drafts requiring further source review and layout checks. There has been no complete campaign playthrough, physical-hardware test or two-system wireless test. Please expect translation errors, missed Japanese and occasional layout problems.

The build verifies installed text, known layout bounds, resource integrity and byte-for-byte BPS reconstruction. These checks do not replace in-game testing.

## Supported ROM

Both source and output are 67,108,864 bytes (64 MiB).

| File | SHA-256 |
|---|---|
| Clean Japanese source | `e32069db40dbdcd3b1a3d2e51c7e573904398dc8a9e21282435db142d0bc2d7f` |
| Patched v0.1-beta | `65afe245f7afc5cbcf41de2a7adedbb5253c859ced3811a8af3bd67d99e961c9` |

Patch checksums are in [SHA256SUMS.txt](SHA256SUMS.txt). Release verification is in [verification.json](verification.json).

## Report an issue

[Open an issue](https://github.com/StepPhone/monster-farm-ds-english/issues/new/choose) with the version, emulator or hardware, location, reproduction steps and a screenshot. Say whether you used a fresh boot, Continue or a save state. Do not upload ROMs, BIOS files or extracted game assets.

Translation project: **StepPhone of the StepHackerZ**, with AI-assisted translation and tooling. [Support StepPhone](https://ko-fi.com/stepphone).

Original game and artwork belong to their respective rights holders. This is an unofficial fan project.

Also see [Zoids Dash](https://github.com/StepPhone/zoids-dash-english), [Zoids Battle Colosseum](https://github.com/StepPhone/zoids-battle-colosseum-english), and [Dragon Tamer: Sound Spirit](https://github.com/StepPhone/dragon-tamer-sound-spirit-english).
