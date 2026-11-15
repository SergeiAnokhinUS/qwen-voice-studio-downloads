# Voice-over for video (Qwen Voice Studio)

**English** · [Русский](README.ru.md)

A local voice-over studio for video lessons: ready-made voices and your own (cloned from a short sample),
long scripts with fixes to single sentences, subtitles and chapters for YouTube, video translation with
voice-over. Everything runs on your computer: texts, recordings and videos are never sent anywhere.

This repository only holds the program archives for download. The program's interface is in Russian.

## Download

Open the [latest release](../../releases/latest) and download the archive for your computer:

| Computer | File |
|---|---|
| Mac with Apple Silicon (M1 or later), macOS 14+ | `QwenVoiceStudio-…-macos.zip` |
| Windows 10/11, 64-bit (an NVIDIA graphics card with 6 GB or more is better) | `QwenVoiceStudio-…-windows.zip` |

You need about 12 GB of free disk space and 16 GB of RAM or more.

## Install

1. Unpack the archive. On Windows — into a folder with a short path, for example `C:\QwenVoice`.
2. Run `Start.command` (Mac) or `Start.cmd` (Windows). The first start downloads everything it needs into
   the same folder: 10–40 minutes, an internet connection is required. You can stop it — the download
   will continue next time.
3. After that, start «Озвучка для видео» (Voice-over for video) in the program folder. No internet needed
   any more.

More details — `README.txt` in the archive.

## Update

In the program: **«? Справка» → «Проверить обновления»** (Help → Check for updates). The program replaces
only itself; voices, the dictionary, the voice-over history and the models stay in place. Don't replace
the folder by hand.

If you have version 0.17 or older (there is no section with the version number in «Справка»): unpack
the new archive and run **«Обновить.command»** (Mac) or **«Обновить.cmd»** (Windows) in it — it asks
where the old program is and updates it.

`SHA256SUMS.txt` in every release holds the checksums of the archives; the program checks them by itself.

## License

The program is free, including for commercial use (MIT license). The Qwen3-TTS models are Apache 2.0.
Other people's voices — only with the owner's consent. Details — `app/docs/LEGAL.md` in the archive.
