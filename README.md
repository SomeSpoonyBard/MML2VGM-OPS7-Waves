# MML2VGM-OPS7-Waves
Waveform data taken from Chipsynth OPS7, for use in MML2VGM's YM2609 for FM synthesis

Credit to kuma4649 for the original waveform generation code, which I altered to generate sine and TX-style triangle waves

How to use:
	Place this file in the same directory as your project file, and copy-paste the following
	block of text into your project. Then, simply use the wave type command to assign a non-sine waveform
	to any of the four FM operators on a given channel.

使用方法
	このファイルをプロジェクトファイルと同じディレクトリに配置し、次のテキストブロックをコピーしてプロジェクトに貼り付けます。
	次に、「@ W」コマンドを使用して、特定のチャネルの4つのFM演算子のいずれかに非正弦波形を割り当てます。
  
 YM2609 FM Waveforms
 
'@ '+ "OPS7Waves.gwi"

 0 - Sine (正弦波)
 
 1 - Sine Var 1 (正弦波 V1)
 
 2 - Sine Var 2 (正弦波 V2)
 
 3 - Sine Var 3 (正弦波 V3)
 
 4 - Half Sine (50%正弦波)
 
 5 - Half Sine Var 1 (50%正弦波 V1)
 
 6 - Half Sine Var 2 (50%正弦波 V2)
 
 7 - Half Sine Var 3 (50%正弦波 V3)
 
 8 - Alternating Sine (2x 正弦波)
 
 9 - Alternating Sine Var 1 (2x 正弦波 V1)
 
 10 - Alternating Sine Var 2 (2x 正弦波 V2)
 
 11 - Alternating Sine Var 3 (2x 正弦波 V3)
 
 12 - Camel Sine (2x 整流正弦波)
 
 13 - Camel Sine Var 1 (2x 整流正弦波 V1)
 
 14 - Camel Sine Var 2 (2x 整流正弦波 V2)
 
 15 - Camel Sine Var 3 (2x 整流正弦波 V3)
 
 16 - Absolute Sine (整流正弦波)
 
 17 - Absolute Sine Var 1 (整流正弦波 V1)
 
 18 - Absolute Sine Var 2 (整流正弦波 V2)
 
 19 - Absolute Sine Var 3 (整流正弦波 V3)
 
 20 - Z Sine (Z 正弦波)
 
 21 - Z Sine Var 1 (Z 正弦波 V1)
 
 22 - Z Sine Var 2 (Z 正弦波 V2)
 
 23 - Z Sine Var 3 (Z 正弦波 V3)
 
 24 - Sawtooth (のこぎり波)
 
 25 - Sawtooth Var 1 (のこぎり波 V1)
 
 26 - Sawtooth Var 2 (のこぎり波 V2)
 
 27 - Sawtooth Var 3 (のこぎり波 V3)
 
 28 - Square (矩形波)
 
 29 - Square Var 1 (矩形波 V1)
 
 30 - Square Var 2 (矩形波 V2)
 
 31 - Square Var 3 (矩形波 V3)
 
 32 - Triangle (三角波)
 
 33 - Triangle Var 1 (三角波 V1)
 
 34 - Triangle Var 2 (三角波 V2)
 
 35 - Triangle Var 3 (三角波 V3)
