SVT-AV1のビルド版の配布です。

ソースコードは改変していません。

Zen3に強く最適化をかけています。

他のCPUでは動作確認をしていません。


--------------------------------------------------------------------------------------------------

エンコードオプション

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2

フレームレート 60fps

色域 10bit

****rigaya氏ビルド版107

----------------------------------------------

[I:\VD\FIX\001.mp4]

----------------------------------------------

svtAV1guiEx 2.14 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)

video: 0:02:05.183 60/1(60.000) fps

audio: 0:02:05.183 2ch 44.1kHz 5520585 samples

svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_4.2.0-107_x64_clang.exe" を使用します。

AAC (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。

mp4boxとして "C:\Program Files\GPAC\mp4box.exe" を使用します。

converting YC48 -> yuv420p(10bit), using AVX AVX2

svt-av1 options...

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 7511 -w

1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\001.av1" -i stdin --progress 2

--------------------------------------

SVT [version]:	SVT-AV1 Encoder Lib v4.2.0-107-g8983dbe5f

SVT [build]  :	Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

Svt[info]: LIB Build date: Sep  1 2026 12:18:07

Svt[info]: --------------------------------------

Level of Parallelism: 5

Number of PPCS 140

[asm level on system : up to avx2]

[asm level selected : up to avx2]

--------------------------------------
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

Encoding: [33m7511/7511 Frames[0m @ [32m24.19[0m fps | [35m2016.03 kb/s[0m | Size: [31m31.55 MB[0m [38;5;248m

[31.55MB][0m | Time: [36m0:05:11[0m [38;5;248m[-0:00:00][0m 

SUMMARY -----------------------------------------------

Total Frames		Frame Rate		Byte Count		Bitrate

      7511        60.00 fps     31546732     2016.03 kbps

Average Speed:		24.185 fps

Total Encoding Time:	310560 ms

Total Execution Time:	310674 ms

Average Latency:	5740 ms

Max Latency:		9937 ms

CPU使用率: Aviutl: 5.80% / svt-av1: 86.14%

Aviutl 平均フレーム取得時間: 6.890 ms

svt-av1エンコード時間 : 0時間 5分11.0秒

---------------------------------------------------------------------------------------------------------

****N7@8_08(LTO+PGO)

-------------------------------------------------------

[I:\VD\FIX\001.mp4]

--------------------------------------------------------

svtAV1guiEx 2.14 / Windows 11 x64 (26200) / AMD Ryzen 5 5600 6-Core Processor [4.67GHz] (6C/12T)

video: 0:02:05.183 60/1(60.000) fps

audio: 0:02:05.183 2ch 44.1kHz 5520585 samples

svt-av1として "C:\ProgramData\aviutl2\Plugin\exe_files\SvtAv1EncApp_N7@8_08_.exe" を使用します。

AAC (ffmpeg)として "C:\ProgramData\aviutl2\Plugin\exe_files\ffmpeg.exe" を使用します。

mp4boxとして "C:\Program Files\GPAC\mp4box.exe" を使用します。

converting YC48 -> yuv420p(10bit), using AVX AVX2

svt-av1 options...

--preset 4 --input-depth 10 --crf 32 --enable-mfmv 1 --film-grain 10 --scd 1 --tile-rows 2 --tile-columns 2  -n 7511 -w

1920 -h 1080 --fps-num 60 --fps-denom 1 -b "I:\VD\FIX\001.av1" -i stdin --progress 2

-------------------------------------------

SVT [version]:	SVT-AV1 Encoder Lib v4.2.0-107-g8983dbe5f

SVT [build]  :	Clang 22.1.8 (https://github.com/msys2/MINGW-packages 6e4e79c2f86eeb534e324e583f2057dc9fd5ecab)	 64 bit

LIB Build date: Sep  5 2026 15:48:09

-------------------------------------------

SVT-AV1 has an integrated mode decision mechanism to handle scene changes and will not insert a key frame at scene changes

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

Encoding: [33m7511/7511 Frames[0m @ [32m24.47[0m fps | [35m2016.03 kb/s[0m | Size: [31m31.55 MB[0m [38;5;248m[31.55

MB][0m | Time: [36m0:05:07[0m [38;5;248m[-0:00:00][0m 

SUMMARY -----------------------------------------------

Total Frames		Frame Rate		Byte Count		Bitrate

       7511	    	60.00 fps		  31546720		2016.03 kbps

Average Speed:		24.470 fps

Total Encoding Time:	306946 ms

Total Execution Time:	307072 ms

Average Latency:	5672 ms

Max Latency:		10221 ms

CPU使用率: Aviutl: 5.77% / svt-av1: 86.46%

Aviutl 平均フレーム取得時間: 6.823 ms

svt-av1エンコード時間 : 0時間 5分 7.4秒

----------------------------------------------------------------------------------------------------------------
