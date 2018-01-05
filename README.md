# TTSController
各種 Text-to-Speech エンジンを統一的に操作するライブラリです。

## 対応プラットフォーム
- Windows 10 (64bit)

## TODO

### 対応(予定) の TTS

- [x] VOICEROID+ EX
- [x] VOICEROID2
- [ ] CeVIO
- [x] SAPI5 (おまけ程度)

### 制御機能
- [x] 話者の一覧取得
- [x] 話者に応じたTTS切り替え

### 音声コントロール
- [x] 再生
- [x] 音量の取得・変更
- [x] 話速の取得・変更
- [x] ピッチの取得・変更
- [x] 抑揚の取得・変更
- [x] 発話中の音声停止
- [ ] 連続して文字列が入力されたときの対応
- [ ] 音声合成対象の文字列の途中に .wav ファイルを差し込み
- [ ] 音声合成対象の文字列の途中に音声コントロールを埋め込み
- [ ] 音声出力デバイス選択