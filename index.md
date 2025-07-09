# xxx_demo

## Introdction

There two tasks that we will show you some examples.
## Speech Meta Analysis(SMA)
### Speaker Timbre Analysis
This task illustrates the effectiveness of a speaker's timbre analysis via the following prompt:
```bash
Qwen2.5Omni：Listen to the provided audio and produce a caption describing the speaker's timbre.
xxx: Write an audio caption describing the speaker's timbre.
```
<section class="hero">
    <table style="text-align: center;">
        <tr>
            <td style="text-align: center;"><p><b>Example 1</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A female voice speaking. </p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a clear and confident tone, her voice carrying a sense of authority and determination.</p><p style="text-align: center;"><audio controls><source src="data/audio/lqdBmAaxO78_219_90800000000002_229_908.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 2</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A male in his twenties speaks in Spanish. </p><p style="text-align: left;"><b>xxx</b>: A male speaker with a neutral tone delivers the audio, accompanied by faint background noise resembling a vehicle engine.</p><p style="text-align: center;"><audio controls><source src="data/audio/fiNsI10rlws_213_467_223_467.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 3</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A female is speaking in a neutral mood. </p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a clear and confident tone, her voice resonating in a quiet room.</p><p style="text-align: center;"><audio controls><source src="data/audio/eZNWN8wueV8_21_4264_31_4264.flac" type="audio/flac"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center;"><p><b>Example 4</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A female with a Spanish accent is speaking.</p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a car engine running in the background, indicating a conversation inside a moving vehicle.</p><p style="text-align: center;"><audio controls><source src="data/audio/HelMeXcLA9A_34_272549999999995_44_2725.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 5</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A man is speaking and music is playing.</p><p style="text-align: left;"><b>xxx</b>: A male speaker with a clear and articulate voice delivers the audio, exhibiting a neutral emotional tone.</p><p style="text-align: center;"><audio controls><source src="data/audio/UyVwZCyEufY_45_44_55_44.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 6</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A woman is speaking.</p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a clear and confident tone, her voice carrying a sense of authority and expertise.</p><p style="text-align: center;"><audio controls><source src="data/audio/f0C7iAzA0Nc_89_23315_99_2331.wav" type="audio/wav"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center;"><p><b>Example 7</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A man is speaking.</p><p style="text-align: left;"><b>xxx</b>: A male speaker with a clear and articulate voice dominates the audio, delivering his message in a neutral tone.</p><p style="text-align: center;"><audio controls><source src="data/audio/eQ0ohbOsZ2Y_252_66000000000003_262_66.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 8</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A male voice is speaking.</p><p style="text-align: left;"><b>xxx</b>: A male speaker with a clear and articulate voice delivers the audio in a neutral tone.</p><p style="text-align: center;"><audio controls><source src="data/audio/HDlbAuqr10A_85_0345_95_0345.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 9</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A male voice speaking in a neutral tone.</p><p style="text-align: left;"><b>xxx</b>: A man speaks with a faint buzzing sound in the background, possibly in a room or an indoor setting.</p><p style="text-align: center;"><audio controls><source src="data/audio/elPijwMmVsY_14_753050000000002_24_7531.flac" type="audio/flac"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center;"><p><b>Example 10</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A male voice speaking in English with a neutral mood.</p><p style="text-align: left;"><b>xxx</b>: A male speaker with a clear and articulate voice delivers his speech in an environment with moderate background noise.</p><p style="text-align: center;"><audio controls><source src="data/audio/mqTYKiVuEnU_43_33335_53_3334.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 11</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: The speaker's voice is characterized by a mature, experienced tone, suggesting a mature adult male.</p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a clear and confident tone, her voice resonating in a reverberant space.</p><p style="text-align: center;"><audio controls><source src="data/audio/39oK7RKDMQE_3_5600000000000005_13_56.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 12</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A female voice is speaking in English, with a neutral mood.</p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a neutral tone, discussing a social media post about a stolen tip from an Uber driver.</p><p style="text-align: center;"><audio controls><source src="data/audio/lrMKnLcOHvk_344_3665_354_366.flac" type="audio/flac"></audio></p></td>
        </tr>
    </table>  
</section>

### Speaker language Analysis
This task illustrates the effectiveness of a speaker's language analysis via the following prompt: 
```bash
请描述说话人的语言特性, 包括说话人的语种, 口音等.
```
<section class="hero">
    <table style="text-align: center;">
        <tr>
            <td style="text-align: center;"><p><b>Example 1</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 说话人使用的是英语，带有斯里兰卡的口音。</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括：使用的是标准的英语，口音为印度英语（India English），发音清晰、标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_36758510.mp3" type="audio/mp3"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 2</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 英语，美国口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括: 语种为英语, 口音为美国英语.</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_42452.mp3" type="audio/mp3"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 3</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: Benison is his estranged father's name and Fortune is his mother's maiden name.</p><p style="text-align: left;"><b>xxx</b>: 说话人使用的是英国英语，口音为标准的英国英语。</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_20210516.mp3" type="audio/wav"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center;"><p><b>Example 4</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-南京口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括使用的是普通话，口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_3723.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 5</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-女性口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括他使用的是普通话, 且口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_108.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 6</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-北京口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括：说话人使用的是普通话，口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_3977.wav" type="audio/wav"></audio></p></td>
        </tr>
    </table>  
</section>

## Sound Sphere Insight(SSI)
### Environmental Sound Recognition
This task illustrates the effectiveness of a speaker's language analysis via the following prompt: 
```bash
请描述说话人的语言特性, 包括说话人的语种, 口音等.
```
<section class="hero">
    <table style="text-align: center;">
        <tr>
            <td style="text-align: center;"><p><b>Example 1</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 说话人使用的是英语，带有斯里兰卡的口音。</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括：使用的是标准的英语，口音为印度英语（India English），发音清晰、标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_36758510.mp3" type="audio/mp3"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 2</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 英语，美国口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括: 语种为英语, 口音为美国英语.</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_42452.mp3" type="audio/mp3"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 3</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: Benison is his estranged father's name and Fortune is his mother's maiden name.</p><p style="text-align: left;"><b>xxx</b>: 说话人使用的是英国英语，口音为标准的英国英语。</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_20210516.mp3" type="audio/wav"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center;"><p><b>Example 4</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-南京口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括使用的是普通话，口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_3723.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 5</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-女性口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括他使用的是普通话, 且口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_108.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 6</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-北京口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括：说话人使用的是普通话，口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_3977.wav" type="audio/wav"></audio></p></td>
        </tr>
    </table>  
</section>

### Music Instrument Recognition  
This task illustrates the effectiveness of a speaker's language analysis via the following prompt: 
```bash
请描述说话人的语言特性, 包括说话人的语种, 口音等.
```
<section class="hero">
    <table style="text-align: center;">
        <tr>
            <td style="text-align: center;"><p><b>Example 1</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 说话人使用的是英语，带有斯里兰卡的口音。</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括：使用的是标准的英语，口音为印度英语（India English），发音清晰、标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_36758510.mp3" type="audio/mp3"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 2</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 英语，美国口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括: 语种为英语, 口音为美国英语.</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_42452.mp3" type="audio/mp3"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 3</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: Benison is his estranged father's name and Fortune is his mother's maiden name.</p><p style="text-align: left;"><b>xxx</b>: 说话人使用的是英国英语，口音为标准的英国英语。</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_20210516.mp3" type="audio/wav"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center;"><p><b>Example 4</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-南京口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括使用的是普通话，口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_3723.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 5</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-女性口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括他使用的是普通话, 且口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_108.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center;"><p><b>Example 6</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-北京口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括：说话人使用的是普通话，口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_3977.wav" type="audio/wav"></audio></p></td>
        </tr>
    </table>  
</section>



## Citation

```bib
@article{li2025reinforcement,
  title={Reinforcement Learning Outperforms Supervised Fine-Tuning: A Case Study on Audio Question Answering},
  author={Li, Gang and Liu, Jizhong and Dinkel, Heinrich and Niu, Yadong and Zhang, Junbo and Luan, Jian},
  journal={arXiv preprint arXiv:2503.11197},
  year={2025},
  url={https://github.com/xiaomi-research/r1-aqa; https://huggingface.co/mispeech/r1-aqa}
}
```