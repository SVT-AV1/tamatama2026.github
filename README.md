SVT-AV1のビルド版の配布です。

ソースコードは改変していません。

Zen3に強く最適化をかけています。

他のCPUでは動作確認をしていません。


--------------------------------------------------------------------------------------------------

エンコードオプション

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2

フレームレート 60fps

色域 10bit

rigaya氏ビルド版107

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] ----------------------------------------------

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] [I:\VD\FIX\001.mp4]

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] ----------------------------------------------

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] svtAV1guiEx 2.14 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] video: 0:02:05.183 60/1(60.000) fps

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] audio: 0:02:05.183 2ch 44.1kHz 5520585 samples

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2]  svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_4.2.0-107_x64_clang.exe" を使用します。

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2]  AAC (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2]  mp4boxとして "C:\Program Files\GPAC\mp4box.exe" を使用します。

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] converting YC48 -> yuv420p(10bit), using AVX AVX2

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1 options...

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2]   --preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 7511 -w

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] 1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\001.av1" -i stdin --progress 2

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: --------------------------------------

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [version]:	SVT-AV1 Encoder Lib v4.2.0-107-g8983dbe5f

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [build]  :	Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: LIB Build date: Sep  1 2026 12:18:07

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: --------------------------------------

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[warn]: SVT-AV1 has an integrated mode decision mechanism to handle scene changes and will not insert a key frame at scene changes

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[warn]: If you are using tiles with the intent of increasing the decoder speed, please also consider using --fast-decode 1

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2]            or 2, especially if the intended decoder is running with limited multi-threading capabilities.

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: Level of Parallelism: 5

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: Number of PPCS 140

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: [asm level on system : up to avx2]

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: [asm level selected : up to avx2]

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: --------------------------------------

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: main profile	tier (auto)	level (auto)

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: width / height / fps numerator / fps denominator 		: 1920 / 1080 / 60 / 1

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: bit-depth / color format 					: 10 / YUV420

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: preset / tune / pred struct 					: 4 / PSNR / random access

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: gop size / mini-gop size / key-frame type 			: 321 / 32 / key frame

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: BRC mode / rate factor 					: CRF / 32.00 

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: AQ mode / Variance Boost 					: 2 / 0

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: film grain synth / denoising / level / adaptive blocksize 	: 1 / 0 / 10 / True

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: sharpness / luminance-based QP bias 				: 0 / 0

[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: QP scale compress strength 					: 0
[09/05 16:03:43] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] Encoding: [33m7511/7511 Frames[0m @ [32m24.19[0m fps | [35m2016.03 kb/s[0m | Size: [31m31.55 MB[0m [38;5;248m[31.55

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] MB][0m | Time: [36m0:05:11[0m [38;5;248m[-0:00:00][0m 

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] SUMMARY -----------------------------------------------

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] Total Frames		Frame Rate		Byte Count		Bitrate

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2]         7511		60.00 fps		  31546732		2016.03 kbps

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] 

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] 

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] Average Speed:		24.185 fps

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] Total Encoding Time:	310560 ms

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] Total Execution Time:	310674 ms

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] Average Latency:	5740 ms

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] Max Latency:		9937 ms

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] CPU使用率: Aviutl: 5.80% / svt-av1: 86.14%

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] Aviutl 平均フレーム取得時間: 6.890 ms

[09/05 16:08:54] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1エンコード時間 : 0時間 5分11.0秒

---------------------------------------------------------------------------------------------------------

N7@8_08(LTO+PGO)

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] -------------------------------------------------------

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] [I:\VD\FIX\001.mp4]

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] --------------------------------------------------------

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] svtAV1guiEx 2.14 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] video: 0:02:05.183 60/1(60.000) fps

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] audio: 0:02:05.183 2ch 44.1kHz 5520585 samples

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2]  svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_N7@8_08_.exe" を使用します。

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2]  AAC (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2]  mp4boxとして "C:\Program Files\GPAC\mp4box.exe" を使用します。

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] converting YC48 -> yuv420p(10bit), using AVX AVX2

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1 options...

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2]   --preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 7511 -w

[09/05 16:10:47] [INFO] [Plugin::svtAV1guiEx.auo2] 1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\001.av1" -i stdin --progress 2

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [version]:	SVT-AV1 Encoder Lib v4.2.0-107-g8983dbe5f

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [build]  :	Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: LIB Build date: Sep  5 2026 15:48:09

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[warn]: SVT-AV1 has an integrated mode decision mechanism to handle scene changes and will not insert a key frame at scene changes

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[warn]: If you are using tiles with the intent of increasing the decoder speed, please also consider using --fast-decode 1

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2]            or 2, especially if the intended decoder is running with limited multi-threading capabilities.

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: Level of Parallelism: 5

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: Number of PPCS 140
[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: [asm level on system : up to avx2]

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: [asm level selected : up to avx2]

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: main profile	tier (auto)	level (auto)

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: width / height / fps numerator / fps denominator 		: 1920 / 1080 / 60 / 1

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: bit-depth / color format 					: 10 / YUV420

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: preset / tune / pred struct 					: 4 / PSNR / random access

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: gop size / mini-gop size / key-frame type 			: 321 / 32 / key frame

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: BRC mode / rate factor 					: CRF / 32.00 

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: AQ mode / Variance Boost 					: 2 / 0

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: film grain synth / denoising / level / adaptive blocksize 	: 1 / 0 / 10 / True

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: sharpness / luminance-based QP bias 				: 0 / 0

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: SVT [config]: QP scale compress strength 					: 0

[09/05 16:10:48] [INFO] [Plugin::svtAV1guiEx.auo2] Svt[info]: -------------------------------------------
[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] Encoding: [33m7511/7511 Frames[0m @ [32m24.47[0m fps | [35m2016.03 kb/s[0m | Size: [31m31.55 MB[0m [38;5;248m[31.55

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] MB][0m | Time: [36m0:05:07[0m [38;5;248m[-0:00:00][0m 

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] SUMMARY -----------------------------------------------

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] Total Frames		Frame Rate		Byte Count		Bitrate

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2]         7511		60.00 fps		  31546720		2016.03 kbps

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] 

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] 

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] Average Speed:		24.470 fps

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] Total Encoding Time:	306946 ms

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] Total Execution Time:	307072 ms

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] Average Latency:	5672 ms

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] Max Latency:		10221 ms

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] CPU使用率: Aviutl: 5.77% / svt-av1: 86.46%

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] Aviutl 平均フレーム取得時間: 6.823 ms

[09/05 16:15:55] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1エンコード時間 : 0時間 5分 7.4秒

----------------------------------------------------------------------------------------------------------------
