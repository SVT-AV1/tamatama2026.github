SVT-AV1のビルド版の配布です。
ソースコードは改変していません。
Zen3に強く最適化をかけています。
他のCPUでは動作確認をしていません。
----------------------------------------------------------------------------------------------------------

エンコードオプション

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2

フレームレート

60fps

10bit

*N7@8_02(LTO+PGO)

Svt[info]: SVT [version]:	SVT-AV1 Encoder Lib v4.2.0

Svt[info]: SVT [build]  :	Clang 23.1.0-rc2 (https://github.com/llvm/llvm-project.git 561093d94eb7156dea780c1c71a779824ef90e5b)	 64 bit

Svt[info]: LIB Build date: Sep  2 2026 05:54:33

Svt[info]: -------------------------------------------

Svt[info]: [asm level on system : up to avx2]

Svt[info]: [asm level selected : up to avx2]

Svt[info]: -------------------------------------------

[INFO] [Plugin::svtAV1guiEx.auo2] SUMMARY -----------------------------------------------------------------

[INFO] [Plugin::svtAV1guiEx.auo2] Total Frames  Frame Rate  Byte Count  Bitrate

[INFO] [Plugin::svtAV1guiEx.auo2]        7511   60.00 fps    31547074    2016.06 kbps

[INFO] [Plugin::svtAV1guiEx.auo2] Average Speed:		23.017 fps

[INFO] [Plugin::svtAV1guiEx.auo2] Total Encoding Time:	326322 ms

[INFO] [Plugin::svtAV1guiEx.auo2] Total Execution Time:	326434 ms

[INFO] [Plugin::svtAV1guiEx.auo2] Average Latency:	6030 ms

[INFO] [Plugin::svtAV1guiEx.auo2] Max Latency:		11184 ms

[INFO] [Plugin::svtAV1guiEx.auo2] CPU使用率: Aviutl: 5.66% / svt-av1: 86.21%

[INFO] [Plugin::svtAV1guiEx.auo2] Aviutl 平均フレーム取得時間: 13.788 ms

[INFO] [Plugin::svtAV1guiEx.auo2] svt-av1エンコード時間 : 0時間 5分26.8秒

-----------------------------------------------------------------------------------------------------------------

*rigaya氏ビルド版

Svt[info]: SVT [version]:	SVT-AV1 Encoder Lib v4.2.0-98-g069628233

Svt[info]: SVT [build]  :	Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

Svt[info]: LIB Build date: Aug 28 2026 23:06:18

Svt[info]: -------------------------------------------

[INFO] [Plugin::svtAV1guiEx.auo2] SUMMARY -----------------------------------------------------------------

[INFO] [Plugin::svtAV1guiEx.auo2] Total Frames		Frame Rate		Byte Count		Bitrate

[INFO] [Plugin::svtAV1guiEx.auo2]         7511		60.00 fps		  31546692		2016.03 kbps

[INFO] [Plugin::svtAV1guiEx.auo2] 

[INFO] [Plugin::svtAV1guiEx.auo2] 

[INFO] [Plugin::svtAV1guiEx.auo2] Average Speed:		20.333 fps

[INFO] [Plugin::svtAV1guiEx.auo2] Total Encoding Time:	369395 ms

[INFO] [Plugin::svtAV1guiEx.auo2] Total Execution Time:	369518 ms

[INFO] [Plugin::svtAV1guiEx.auo2] Average Latency:	6828 ms

[INFO] [Plugin::svtAV1guiEx.auo2] Max Latency:		13728 ms

[INFO] [Plugin::svtAV1guiEx.auo2] CPU使用率: Aviutl: 5.17% / svt-av1: 87.70%

[INFO] [Plugin::svtAV1guiEx.auo2] Aviutl 平均フレーム取得時間: 14.654 ms

[INFO] [Plugin::svtAV1guiEx.auo2] svt-av1エンコード時間 : 0時間 6分 9.9秒

------------------------------------------------------------------------------------------------------------------------
