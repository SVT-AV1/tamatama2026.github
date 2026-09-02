SVT-AV1のビルド版の配布です。
ソースコードは改変していません。
Zen3に強く最適化をかけています。
他のCPUでは動作確認をしていません。

エンコードオプション
--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2
フレームレート
60fps

10bit

N7@8_02(LTO+PGO)

[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] ------------------------------------------------------------------------------------------------------------------------------
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] [I:\VD\FIX\009.mp4]
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] ------------------------------------------------------------------------------------------------------------------------------
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] svtAV1guiEx 2.14 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] video: 0:02:05.183 60/1(60.000) fps
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] audio: 0:02:05.183 2ch 44.1kHz 5520585 samples
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2]  svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_N7@8_02_.exe" を使用します。
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2]  AAC (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2]  mp4boxとして "C:\Program Files\GPAC\mp4box.exe" を使用します。
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] converting YC48 -> yuv420p(10bit), using AVX AVX2
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1 options...
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2]   --preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 7511 -w
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] 1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\009.av1" -i stdin --progress 2
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [version]:	SVT-AV1 Encoder Lib v4.2.0
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [build]  :	Clang 23.1.0-rc2 (https://github.com/llvm/llvm-project.git 561093d94eb7156dea780c1c71a779824ef90e5b)	 64 bit
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: LIB Build date: Sep  2 2026 05:54:33
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[warn]: SVT-AV1 has an integrated mode decision mechanism to handle scene changes and will not insert a key frame at scene changes
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[warn]: If you are using tiles with the intent of increasing the decoder speed, please also consider using --fast-decode 1
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2]            or 2, especially if the intended decoder is running with limited multi-threading capabilities.
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: Level of Parallelism: 5
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: Number of PPCS 140
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: [asm level on system : up to avx2]
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: [asm level selected : up to avx2]
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: main profile	tier (auto)	level (auto)
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: width / height / fps numerator / fps denominator 		: 1920 / 1080 / 60 / 1
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: bit-depth / color format 					: 10 / YUV420
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: preset / tune / pred struct 					: 4 / PSNR / random access
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: gop size / mini-gop size / key-frame type 			: 321 / 32 / key frame
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: BRC mode / rate factor 					: CRF / 32.00 
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: AQ mode / Variance Boost 					: 2 / 0
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: film grain synth / denoising / level / adaptive blocksize 	: 1 / 0 / 10 / True
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: sharpness / luminance-based QP bias 				: 0 / 0
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: QP scale compress strength 					: 0
[09/02 13:23:42] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] Encoding: [33m7511/7511 Frames[0m @ [32m23.02[0m fps | [35m2016.06 kb/s[0m | Size: [31m31.55 MB[0m [38;5;248m[31.55
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] MB][0m | Time: [36m0:05:26[0m [38;5;248m[-0:00:00][0m 
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] SUMMARY -----------------------------------------------------------------
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] Total Frames		Frame Rate		Byte Count		Bitrate
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2]         7511		60.00 fps		  31547074		2016.06 kbps
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] 
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] 
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] Average Speed:		23.017 fps
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] Total Encoding Time:	326322 ms
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] Total Execution Time:	326434 ms
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] Average Latency:	6030 ms
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] Max Latency:		11184 ms
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] CPU使用率: Aviutl: 5.66% / svt-av1: 86.21%
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] Aviutl 平均フレーム取得時間: 13.788 ms
[09/02 13:29:09] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1エンコード時間 : 0時間 5分26.8秒
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


rigaya氏ビルド版

[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] ------------------------------------------------------------------------------------------------------------------------------
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] [I:\VD\FIX\009.mp4]
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] ------------------------------------------------------------------------------------------------------------------------------
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] svtAV1guiEx 2.14 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] video: 0:02:05.183 60/1(60.000) fps
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] audio: 0:02:05.183 2ch 44.1kHz 5520585 samples
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2]  svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_4.2.0-98_x64_clang.exe" を使用します。
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2]  AAC (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2]  mp4boxとして "C:\Program Files\GPAC\mp4box.exe" を使用します。
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] converting YC48 -> yuv420p(10bit), using AVX AVX2
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1 options...
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2]   --preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 7511 -w
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] 1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\009.av1" -i stdin --progress 2
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [version]:	SVT-AV1 Encoder Lib v4.2.0-98-g069628233
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [build]  :	Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: LIB Build date: Aug 28 2026 23:06:18
[09/02 13:15:44] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[warn]: SVT-AV1 has an integrated mode decision mechanism to handle scene changes and will not insert a key frame at scene changes
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[warn]: If you are using tiles with the intent of increasing the decoder speed, please also consider using --fast-decode 1
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2]            or 2, especially if the intended decoder is running with limited multi-threading capabilities.
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: Level of Parallelism: 5
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: Number of PPCS 140
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: [asm level on system : up to avx2]
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: [asm level selected : up to avx2]
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: main profile	tier (auto)	level (auto)
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: width / height / fps numerator / fps denominator 		: 1920 / 1080 / 60 / 1
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: bit-depth / color format 					: 10 / YUV420
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: preset / tune / pred struct 					: 4 / PSNR / random access
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: gop size / mini-gop size / key-frame type 			: 321 / 32 / key frame
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: BRC mode / rate factor 					: CRF / 32.00 
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: AQ mode / Variance Boost 					: 2 / 0
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: film grain synth / denoising / level / adaptive blocksize 	: 1 / 0 / 10 / True
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: sharpness / luminance-based QP bias 				: 0 / 0
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: QP scale compress strength 					: 0
[09/02 13:15:45] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] Encoding: [33m7511/7511 Frames[0m @ [32m20.33[0m fps | [35m2016.03 kb/s[0m | Size: [31m31.55 MB[0m [38;5;248m[31.55
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] MB][0m | Time: [36m0:06:09[0m [38;5;248m[-0:00:00][0m 
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] SUMMARY -----------------------------------------------------------------
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] Total Frames		Frame Rate		Byte Count		Bitrate
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2]         7511		60.00 fps		  31546692		2016.03 kbps
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] 
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] 
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] Average Speed:		20.333 fps
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] Total Encoding Time:	369395 ms
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] Total Execution Time:	369518 ms
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] Average Latency:	6828 ms
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] Max Latency:		13728 ms
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] CPU使用率: Aviutl: 5.17% / svt-av1: 87.70%
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] Aviutl 平均フレーム取得時間: 14.654 ms
[09/02 13:21:54] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1エンコード時間 : 0時間 6分 9.9秒
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
