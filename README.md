SVT-AV1のビルド版の配布です。

ソースコードは改変していません。

Zen3に強く最適化をかけています。

他のCPUでは動作確認をしていません。

Zen5を使用してもAVX512は動作しません。

----------------------------------------------------
***********rigaya氏ビルド版107***********
------------------------------------------------

[I:\VD\FIX\001.mkv]

------------------------------------------------

svtAV1guiEx 2.15 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.65GHz] (6C/12T)

video: 0:03:59.400 60/1(60.000) fps

audio: 0:03:59.400 2ch 44.1kHz 10557540 samples

svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_4.2.0-107_x64_clang.exe" を使用します。

opus (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。

mkvmergeとして "C:\ProgramData\aviutl2\Plugin\exe_files\mkvmerge.exe" を使用します。

converting YC48 -> yuv420p(10bit), using AVX AVX2

svt-av1 options...

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 14364 -w

1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\001.av1" -i stdin --progress 2

Svt[info]: -------------------------------------------

Svt[info]: SVT [version]:	SVT-AV1 Encoder Lib v4.2.0-107-g8983dbe5f

Svt[info]: SVT [build]  :	Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

Svt[info]: LIB Build date: Sep  1 2026 12:18:07

-------------------------------------------

Svt[info]: Level of Parallelism: 5

Svt[info]: Number of PPCS 140

Svt[info]: [asm level on system : up to avx2]

Svt[info]: [asm level selected : up to avx2]

Svt[info]: -------------------------------------------

Svt[info]: SVT [config]: main profile	tier (auto)	level (auto)

Svt[info]: SVT [config]: width / height / fps numerator / fps denominator 		: 1920 / 1080 / 60 / 1

Svt[info]: SVT [config]: bit-depth / color format 					: 10 / YUV420

Svt[info]: SVT [config]: preset / tune / pred struct 					: 4 / PSNR / random access

Svt[info]: SVT [config]: gop size / mini-gop size / key-frame type 			: 321 / 32 / key frame

Svt[info]: SVT [config]: BRC mode / rate factor 					: CRF / 32.00 

Svt[info]: SVT [config]: AQ mode / Variance Boost 					: 2 / 0

Svt[info]: SVT [config]: film grain synth / denoising / level / adaptive blocksize 	: 1 / 0 / 10 / True

Svt[info]: SVT [config]: sharpness / luminance-based QP bias 				: 0 / 0

Svt[info]: SVT [config]: QP scale compress strength 					: 0

Svt[info]: -------------------------------------------

Encoding: [33m14364/14364 Frames[0m @ [32m24.35[0m fps | [35m3754.84 kb/s[0m | Size: [31m112.36 MB[0m

[38;5;248m[112.36 MB][0m | Time: [36m0:09:50[0m [38;5;248m[-0:00:00][0m 

SUMMARY -----------------------------------------------------------------

Total Frames		Frame Rate		Byte Count		Bitrate

14364		60.00 fps		 112363512		3754.84 kbps

Average Speed:		24.349 fps

Total Encoding Time:	589928 ms

Total Execution Time:	590044 ms

Average Latency:	5725 ms

Max Latency:		11368 ms

CPU使用率: Aviutl: 4.39% / svt-av1: 85.01%

Aviutl 平均フレーム取得時間: 6.338 ms

svt-av1エンコード時間 : 0時間 9分50.4秒

--------------------------------------------------------------

---------------------------------------------------------------

*********N7@8_18(LTO+PGO)*********

------------------------------------

[I:\VD\FIX\0000.mkv]

------------------------------------

svtAV1guiEx 2.15 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)

video: 0:03:59.400 60/1(60.000) fps

audio: 0:03:59.400 2ch 44.1kHz 10557540 samples

svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_N7@8_18_.exe" を使用します。

opus (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。

mkvmergeとして "C:\ProgramData\aviutl2\Plugin\exe_files\mkvmerge.exe" を使用します。

converting YC48 -> yuv420p(10bit), using AVX AVX2

svt-av1 options...

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 14364 -w

1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\0000.av1" -i stdin --progress 2

Svt[info]: -------------------------------------------

Svt[info]: SVT [version]:	SVT-AV1 Encoder Lib v4.2.0-118-g837210f49

Svt[info]: SVT [build]  :	Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

Svt[info]: LIB Build date: Sep  9 2026 15:05:32

Svt[info]: -------------------------------------------

Svt[info]: Level of Parallelism: 5

Svt[info]: Number of PPCS 140

Svt[info]: [asm level on system : up to avx2]

Svt[info]: [asm level selected : up to avx2]

Svt[info]: -------------------------------------------

Svt[info]: SVT [config]: main profile	tier (auto)	level (auto)

Svt[info]: SVT [config]: width / height / fps numerator / fps denominator 		: 1920 / 1080 / 60 / 1

Svt[info]: SVT [config]: bit-depth / color format 					: 10 / YUV420

Svt[info]: SVT [config]: preset / tune / pred struct 					: 4 / PSNR / random access

Svt[info]: SVT [config]: gop size / mini-gop size / key-frame type 			: 321 / 32 / key frame

Svt[info]: SVT [config]: BRC mode / rate factor 					: CRF / 32.00 

Svt[info]: SVT [config]: AQ mode / Variance Boost 					: 2 / 0

Svt[info]: SVT [config]: film grain synth / denoising / level / adaptive blocksize 	: 1 / 0 / 10 / True

Svt[info]: SVT [config]: sharpness / luminance-based QP bias 				: 0 / 0

Svt[info]: SVT [config]: QP scale compress strength 					: 0

Svt[info]: -------------------------------------------

Encoding: [33m14364/14364 Frames[0m @ [32m26.12[0m fps | [35m3754.86 kb/s[0m | Size: [31m112.36 MB[0m

[38;5;248m[112.36 MB][0m | Time: [36m0:09:10[0m [38;5;248m[-0:00:00][0m 

SUMMARY ----------------------------------------------------

Total Frames		Frame Rate		Byte Count		Bitrate

14364		60.00 fps		 112364038		3754.86 kbps

Average Speed:		26.119 fps

Total Encoding Time:	549946 ms

Total Execution Time:	550060 ms

Average Latency:	5332 ms

Max Latency:		10089 ms

CPU使用率: Aviutl: 4.75% / svt-av1: 84.92%

Aviutl 平均フレーム取得時間: 6.754 ms

svt-av1エンコード時間 : 0時間 9分10.2秒

-------------------------------------------------------------------

