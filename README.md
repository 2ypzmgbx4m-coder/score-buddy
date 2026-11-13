# 扒谱宝 ScoreBuddy

放进一段钢琴录音或视频，AI 自动扒成五线谱；可以在谱子上直接修改、播放，下载 PDF / MIDI / MusicXML。

Turn a piano recording into sheet music with AI. Edit it right on the staff, play it back, and download PDF / MIDI / MusicXML, all in your browser.

**在线使用 / Try it:** https://2ypzmgbx4m-coder.github.io/scorebuddy/

- 声音只在你的浏览器里处理，不会上传。Your audio never leaves your browser.
- 建议用电脑上的 Chrome 或 Edge。Works best in Chrome or Edge on a computer.

## 用到的开源成果 / Credits

- Google Magenta: Onsets and Frames (Apache-2.0)
- ByteDance: High-resolution Piano Transcription, Kong et al. (CC BY 4.0); ONNX conversion from Hugging Face `Clement11800/pianino-model`
- Spotify: Basic Pitch (Apache-2.0)
- OpenSheetMusicDisplay (BSD-3-Clause), jsPDF (MIT), TensorFlow.js, ONNX Runtime Web
- Piano samples: MIDI.js Soundfonts (via midicube)
