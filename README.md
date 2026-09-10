SVT-AV1のビルド版の配布です。

ソースコードは改変していません。

Zen3に強く最適化をかけています。

他のCPUでは動作確認をしていません。

Zen5を使用してもAVX512は動作しません。


------------------------
エンコードオプション
------------------------
--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2

出力フレームレート 60fps

出力色域 10bit

*入力ソース動画:東京夜景.mp4 1920x1080p AVC 29.97fps 3分59秒 8bit

------------------------------------------------
***********rigaya氏ビルド版107***********
------------------------------------------------

svtAV1guiEx 2.15 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)

video: 0:03:59.400 60/1(60.000) fps

audio: 0:03:59.400 2ch 44.1kHz 10557540 samples

svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_4.2.0-107_x64_clang.exe" を使用します。

opus (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。

mkvmergeとして "C:\ProgramData\aviutl2\Plugin\exe_files\mkvmerge.exe" を使用します。

converting YC48 -> yuv420p(10bit), using AVX AVX2

svt-av1 options...

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 14364 -w

1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\0000.av1" -i stdin --progress 2

-------------------------------------------

SVT-AV1 Encoder Lib v4.2.0-107-g8983dbe5f

Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

LIB Build date: Sep  1 2026 12:18:07

-------------------------------------------

Level of Parallelism: 5

Number of PPCS 140

[asm level on system : up to avx2]

[asm level selected : up to avx2]

-------------------------------------------

main profile	tier (auto)	level (auto)

width / height / fps numerator / fps denominator 		: 1920 / 1080 / 60 / 1

bit-depth / color format 					: 10 / YUV420

preset / tune / pred struct 					: 4 / PSNR / random access

gop size / mini-gop size / key-frame type 			: 321 / 32 / key frame

BRC mode / rate factor 					: CRF / 32.00 

AQ mode / Variance Boost 					: 2 / 0

film grain synth / denoising / level / adaptive blocksize 	: 1 / 0 / 10 / True

sharpness / luminance-based QP bias 				: 0 / 0

QP scale compress strength 					: 0

-------------------------------------------

Encoding: [33m14364/14364 Frames[0m @ [32m25.06[0m fps | [35m3754.84 kb/s[0m | Size: [31m112.36 MB[0m

[38;5;248m[112.36 MB][0m | Time: [36m0:09:33[0m [38;5;248m[-0:00:00][0m 

SUMMARY ----------------------------------------------------

Total Frames		Frame Rate		Byte Count		Bitrate

14364		60.00 fps		 112363512		3754.84 kbps

Average Speed:		25.058 fps

Total Encoding Time:	573228 ms

Total Execution Time:	573346 ms

Average Latency:	5561 ms

Max Latency:		10924 ms

CPU使用率: Aviutl: 4.65% / svt-av1: 87.08%

Aviutl 平均フレーム取得時間: 7.114 ms

-------------------------------------------------------------
svt-av1エンコード時間 : 0時間 9分33.5秒
--------------------------------------------------------------


------------------------------------------------------------
********N7@8_22(LTO+PGO)*****
------------------------------------------------------------

svtAV1guiEx 2.15 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)

video: 0:03:59.400 60/1(60.000) fps

audio: 0:03:59.400 2ch 44.1kHz 10557540 samples

svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_N7@8_22_.exe" を使用します。

opus (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。

mkvmergeとして "C:\ProgramData\aviutl2\Plugin\exe_files\mkvmerge.exe" を使用します。

converting YC48 -> yuv420p(10bit), using AVX AVX2

svt-av1 options...

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 14364 -w

1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\0000.av1" -i stdin --progress 2

Svt[info]: --------------------------------

SVT-AV1 Encoder Lib v4.2.0-120-gc6cb4d0c2

Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

LIB Build date: Sep 10 2026 08:49:02

-------------------------------------------

Level of Parallelism: 5

Number of PPCS 140

[asm level on system : up to avx2]

[asm level selected : up to avx2]

-------------------------------------------

main profile	tier (auto)	level (auto)

width / height / fps numerator / fps denominator 		: 1920 / 1080 / 60 / 1

bit-depth / color format 					: 10 / YUV420

preset / tune / pred struct 					: 4 / PSNR / random access

op size / mini-gop size / key-frame type 			: 321 / 32 / key frame

BRC mode / rate factor 					: CRF / 32.00 

AQ mode / Variance Boost 					: 2 / 0

film grain synth / denoising / level / adaptive blocksize 	: 1 / 0 / 10 / True

sharpness / luminance-based QP bias 				: 0 / 0

QP scale compress strength 					: 0

-------------------------------------------

[33m14364/14364 Frames[0m @ [32m26.62[0m fps | [35m3754.86 kb/s[0m | Size: [31m112.36 MB[0m

[38;5;248m[112.36 MB][0m | Time: [36m0:09:00[0m [38;5;248m[-0:00:00][0m 

SUMMARY --------------------------------------

Total Frames		Frame Rate		Byte Count		Bitrate

14364		60.00 fps		 112364038		3754.86 kbps

Average Speed:		26.620 fps

Total Encoding Time:	539596 ms

Total Execution Time:	539709 ms

Average Latency:	5234 ms

Max Latency:		9520 ms

CPU使用率: Aviutl: 4.98% / svt-av1: 85.90%

Aviutl 平均フレーム取得時間: 7.296 ms

------------------------------------------------------------------------------------------
[09/10 10:17:24] [INFO] [Plugin::svtAV1guiEx.auo2] svt-av1エンコード時間 : 0時間 9分 0.1秒
-------------------------------------------------------------------------------------------


