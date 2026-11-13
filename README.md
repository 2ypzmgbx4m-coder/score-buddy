# 扒谱宝 ScoreBuddy

放进钢琴、吉他的录音或者一整首流行歌（文件或视频），AI 自动扒成谱子：吉他会同时写出五线谱和六线谱（TAB），整首歌会编成钢琴谱（简单版 / 完整版，带和弦名）；可以在谱子上直接修改、播放，下载 PDF / MIDI / MusicXML。中文 / English 都可以，电脑、手机、平板都能用。

Turn a piano or guitar recording, or a whole pop song, into sheet music with AI (guitar gets standard notation plus TAB; a song becomes a piano arrangement, simple or full, with chord names). Edit it right on the staff, play it back, and download PDF / MIDI / MusicXML, all in your browser. Chinese and English, on computers, phones and tablets.

**在线使用 / Try it:** https://2ypzmgbx4m-coder.github.io/score-buddy/

## 怎么用 / How it works

1. 放进声音：拖进录音或视频文件，或者录下视频网站播放的声音（电脑上的 Chrome / Edge）。
2. 选乐器和扒法：钢琴有「快速」（一个钢琴 AI 听一遍）和「精准」（再请第二个钢琴 AI 复查，错音更少）；吉他用通用 AI，自动排好把位；整首歌也有「快速」（直接听整首歌）和「精准」（先把人声、鼓、贝斯和其他乐器分开再听，旋律准很多；第一次要下载约 170 MB，最好用电脑上的 Chrome 或 Edge），再编成钢琴谱。
3. 看谱改谱：点音符选中、改音高和长短、换调、改速度；橙色的音是 AI 不太确定的。
4. 下载：PDF、MIDI、MusicXML（可以用 MuseScore 打开继续改）。

- 声音只在你的浏览器里处理，不会上传。Your audio never leaves your browser.
- 谱子自动保存在你自己的浏览器里，下次打开还在。Your work is saved in your own browser.

## 用到的开源成果 / Credits

- Google Magenta: Onsets and Frames (Apache-2.0)
- ByteDance: High-resolution Piano Transcription, Kong et al. (CC BY 4.0); ONNX conversion from Hugging Face `Clement11800/pianino-model`
- Spotify: Basic Pitch (Apache-2.0)
- Meta: Demucs (MIT); browser version demucs-web by timcsy (MIT)
- OpenSheetMusicDisplay (BSD-3-Clause), jsPDF (MIT), TensorFlow.js, ONNX Runtime Web
- Piano samples: MIDI.js Soundfonts (via midicube); guitar samples: FluidR3 GM via gleitz/midi-js-soundfonts (CC BY 3.0)
