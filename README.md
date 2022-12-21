
<h2 font-size:40px align="center">Speech Recognition and Synthesis by using Deep Learning</h2>

<h3 align="center">by Siddhant Bikram Shah</h3>
<br>

This project is a speech recognition and synthesis system built by using Pytorch and the SV2TTS framework. The system extracts characteristics from a few samples of the speaker's voice, clone it and generate audio based on the given text. The performance of the program is determined by the naturalness of speech and the similarity between the speaker’s speech and the recreated speech.<br>

The three stages of the framework are as follows:
<br>1. An encoder that derives an embedding from the short utterance of a single speaker.
<br>2. A synthesizer that, conditioned on the embedding of a speaker, generates a spectrogram from text.
<br>3. A vocoder that infers an audio waveform from the spectrograms generated by the synthesizer.
<br>Various other details are present in the PPT and PDF report.

Thank you! If you have any questions, please feel free to reach out to siddhantshah3000@gmail.com.
<br>
<br>

<b>References:</b>

1. Corentin Jemine. Real-time Voice Cloning, 2018 https://matheo.uliege.be/bitstream/2268.2/6801/5/s123578Jemine2019.pdf
2. Dzmitry Bahdanau, Kyunghyun Cho, and Yoshua Bengio. Neural machine translation by jointly learning to align and translate. CoRR, abs/1409.0473, 2014. http://arxiv.org/abs/1409.0473.
3. Jan Chorowski, Dzmitry Bahdanau, Dmitriy Serdyuk, KyungHyun Cho, and Yoshua Bengio. Attention-based models for speech recognition. CoRR, abs/1506.07503, 2015. http://arxiv.org/abs/1506.07503.
