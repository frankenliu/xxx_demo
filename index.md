# xxx_demo

## Introdction

There two tasks that we will show you some examples.
## Speech Meta Analysis(SMA)
### Speaker Timbre Analysis
This task illustrates the effectiveness of a speaker's timbre analysis via the following prompt:
```text
Qwen2.5-Omni：Listen to the provided audio and produce a caption describing the speaker's timbre.  
xxx: Write an audio caption describing the speaker's timbre.
```
<section class="hero">
    <table style="text-align: center;">
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 1</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A female voice speaking. </p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a clear and confident tone, her voice carrying a sense of authority and determination.</p><p style="text-align: center;"><audio controls><source src="data/audio/lqdBmAaxO78_219_90800000000002_229_908.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 2</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A male in his twenties speaks in Spanish. </p><p style="text-align: left;"><b>xxx</b>: A male speaker with a neutral tone delivers the audio, accompanied by faint background noise resembling a vehicle engine.</p><p style="text-align: center;"><audio controls><source src="data/audio/fiNsI10rlws_213_467_223_467.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 3</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A female is speaking in a neutral mood. </p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a clear and confident tone, her voice resonating in a quiet room.</p><p style="text-align: center;"><audio controls><source src="data/audio/eZNWN8wueV8_21_4264_31_4264.flac" type="audio/flac"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 4</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A female with a Spanish accent is speaking.</p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a car engine running in the background, indicating a conversation inside a moving vehicle.</p><p style="text-align: center;"><audio controls><source src="data/audio/HelMeXcLA9A_34_272549999999995_44_2725.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 5</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A man is speaking and music is playing.</p><p style="text-align: left;"><b>xxx</b>: A male speaker with a clear and articulate voice delivers the audio, exhibiting a neutral emotional tone.</p><p style="text-align: center;"><audio controls><source src="data/audio/UyVwZCyEufY_45_44_55_44.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 6</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A woman is speaking.</p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a clear and confident tone, her voice carrying a sense of authority and expertise.</p><p style="text-align: center;"><audio controls><source src="data/audio/f0C7iAzA0Nc_89_23315_99_2331.wav" type="audio/wav"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 7</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A man is speaking.</p><p style="text-align: left;"><b>xxx</b>: A male speaker with a clear and articulate voice dominates the audio, delivering his message in a neutral tone.</p><p style="text-align: center;"><audio controls><source src="data/audio/eQ0ohbOsZ2Y_252_66000000000003_262_66.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 8</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A male voice is speaking.</p><p style="text-align: left;"><b>xxx</b>: A male speaker with a clear and articulate voice delivers the audio in a neutral tone.</p><p style="text-align: center;"><audio controls><source src="data/audio/HDlbAuqr10A_85_0345_95_0345.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 9</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A male voice speaking in a neutral tone.</p><p style="text-align: left;"><b>xxx</b>: A man speaks with a faint buzzing sound in the background, possibly in a room or an indoor setting.</p><p style="text-align: center;"><audio controls><source src="data/audio/elPijwMmVsY_14_753050000000002_24_7531.flac" type="audio/flac"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 10</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A male voice speaking in English with a neutral mood.</p><p style="text-align: left;"><b>xxx</b>: A male speaker with a clear and articulate voice delivers his speech in an environment with moderate background noise.</p><p style="text-align: center;"><audio controls><source src="data/audio/mqTYKiVuEnU_43_33335_53_3334.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 11</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: The speaker's voice is characterized by a mature, experienced tone, suggesting a mature adult male.</p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a clear and confident tone, her voice resonating in a reverberant space.</p><p style="text-align: center;"><audio controls><source src="data/audio/39oK7RKDMQE_3_5600000000000005_13_56.flac" type="audio/flac"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 12</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: A female voice is speaking in English, with a neutral mood.</p><p style="text-align: left;"><b>xxx</b>: A woman speaks with a neutral tone, discussing a social media post about a stolen tip from an Uber driver.</p><p style="text-align: center;"><audio controls><source src="data/audio/lrMKnLcOHvk_344_3665_354_366.flac" type="audio/flac"></audio></p></td>
        </tr>
    </table>  
</section>

### Speaker language Analysis
This task illustrates the effectiveness of a speaker's language analysis via the following prompt: 
```text
请描述说话人的语言特性, 包括说话人的语种, 口音等.
```
<section class="hero">
    <table style="text-align: center;">
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 1</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 说话人使用的是英语，带有斯里兰卡的口音。</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括：使用的是标准的英语，口音为印度英语（India English），发音清晰、标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_36758510.mp3" type="audio/mp3"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 2</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 英语，美国口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括: 语种为英语, 口音为美国英语.</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_42452.mp3" type="audio/mp3"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 3</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: Benison is his estranged father's name and Fortune is his mother's maiden name.</p><p style="text-align: left;"><b>xxx</b>: 说话人使用的是英国英语，口音为标准的英国英语。</p><p style="text-align: center;"><audio controls><source src="data/audio/common_voice_en_20210516.mp3" type="audio/wav"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 4</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-南京口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括使用的是普通话，口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_3723.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 5</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-女性口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括他使用的是普通话, 且口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_108.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 6</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: 普通话-北京口音</p><p style="text-align: left;"><b>xxx</b>: 说话人的语言特性包括：说话人使用的是普通话，口音为标准。</p><p style="text-align: center;"><audio controls><source src="data/audio/test_3977.wav" type="audio/wav"></audio></p></td>
        </tr>
    </table>  
</section>

## Sound Sphere Insight(SSI)
### Environmental Sound Recognition(Multi Label)
This task illustrates the effectiveness of environmental sound recognition via the following prompt: 
```text
Qwen2.5-Omni: Classify the given multi-label audio in English.
xxx: Which labels describe the sound?
```
<section class="hero">
    <table style="text-align: center;">
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 1</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: {'Rattle'}</p><p style="text-align: left;"><b>xxx</b>: {'Coin (dropping)', 'Domestic sounds, home sounds'}</p><p style="text-align: left;"><b>Label</b>: {'Coin (dropping)', 'Domestic sounds and home sounds'}</p><p style="text-align: center;"><audio controls><source src="data/audio/60908.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 2</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: {'Sneeze'}</p><p style="text-align: left;"><b>xxx</b>: {'Car', 'Motorcycle', 'Vehicle horn, car horn, honking', 'Alarm', 'Vehicle'}</p><p style="text-align: left;"><b>Label</b>: {'Car', 'Motorcycle', 'Alarm', 'Vehicle horn and car horn and honking', 'Vehicle'}</p><p style="text-align: center;"><audio controls><source src="data/audio/118807.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 3</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: {'Splash and splatter'}</p><p style="text-align: left;"><b>xxx</b>: {'Water', 'Liquid', 'Splash and splatter'}</p><p style="text-align: left;"><b>Label</b>: {'Water', 'Liquid', 'Splash and splatter'}</p><p style="text-align: center;"><audio controls><source src="data/audio/148317.wav" type="audio/wav"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 4</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: {'Musical instrument', 'Harmonica', 'Music'}</p><p style="text-align: left;"><b>xxx</b>: {'Car', 'Motorcycle', 'Vehicle horn, car horn, honking', 'Alarm', 'Vehicle'}</p><p style="text-align: left;"><b>Label</b>: {'Motorcycle', 'Truck', 'Alarm', 'Boat and Water vehicle', 'Vehicle'}</p><p style="text-align: center;"><audio controls><source src="data/audio/398415.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 5</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: {'speech', 'human voice'}</p><p style="text-align: left;"><b>xxx</b>: {'Speech', 'Human voice', 'Female speech and woman speaking'}</p><p style="text-align: left;"><b>Label</b>: {'Female speech and woman speaking', 'Human voice', 'Speech'}</p><p style="text-align: center;"><audio controls><source src="data/audio/184490.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 6</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: {'Gunshot and gunfire'}</p><p style="text-align: left;"><b>xxx</b>: {'Gunshot and gunfire', 'Explosion'}</p><p style="text-align: left;"><b>Label</b>: {'Explosion', 'Gunshot and gunfire'}</p><p style="text-align: center;"><audio controls><source src="data/audio/192104.wav" type="audio/wav"></audio></p></td>
        </tr>
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 7</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: {'Glass'}</p><p style="text-align: left;"><b>xxx</b>: {'Domestic sounds and home sounds', 'Dishes and pots and pans', 'Glass', 'Chink and clink'}</p><p style="text-align: left;"><b>Label</b>: {'Cutlery and silverware', 'Domestic sounds and home sounds', 'Dishes and pots and pans', 'Human group actions'}</p><p style="text-align: center;"><audio controls><source src="data/audio/185627.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 8</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: {'trumpet', 'brass instrument'}</p><p style="text-align: left;"><b>xxx</b>: {'Brass instrument', 'Music', 'Trumpet', 'Musical instrument'}</p><p style="text-align: left;"><b>Label</b>: {'Brass instrument', 'Music', 'Trumpet', 'Musical instrument'}</p><p style="text-align: center;"><audio controls><source src="data/audio/198874.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 9</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>:{'Train horn'}</p><p style="text-align: left;"><b>xxx</b>: {'Rail transport', 'Train', 'Vehicle'}</p><p style="text-align: left;"><b>Label</b>: {'Rail transport', 'Train', 'Vehicle'}</p><p style="text-align: center;"><audio controls><source src="data/audio/334618.wav" type="audio/wav"></audio></p></td>
        </tr>
    </table>  
</section>

### Music Instrument Recognition(Single Label)
This task illustrates the effectiveness of music instrument recognition via the following prompt: 
```text
Qwen2.5-Omni: Recognize the music instrument with keywords in English.
MiDashengLM: What's the music instrument?
```
<section class="hero">
    <table style="text-align: center;">
        <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 1</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: string</p><p style="text-align: left;"><b>xxx</b>: bass</p><p style="text-align: left;"><b>Label</b>: string</p><p style="text-align: center;"><audio controls><source src="data/audio/string_acoustic_014-063-050.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 2</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: keyboard</p><p style="text-align: left;"><b>xxx</b>: guitar</p><p style="text-align: left;"><b>Label</b>: guitar</p><p style="text-align: center;"><audio controls><source src="data/audio/guitar_acoustic_030-102-127.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 3</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: brass</p><p style="text-align: left;"><b>xxx</b>: vocal</p><p style="text-align: left;"><b>Label</b>: vocal</p><p style="text-align: center;"><audio controls><source src="data/audio/vocal_synthetic_003-027-050.wav" type="audio/wav"></audio></p></td>
        </tr>
         <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 4</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: reed</p><p style="text-align: left;"><b>xxx</b>: flute</p><p style="text-align: left;"><b>Label</b>: flute</p><p style="text-align: center;"><audio controls><source src="data/audio/flute_synthetic_000-051-100.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 5</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: guitar</p><p style="text-align: left;"><b>xxx</b>: keyboard</p><p style="text-align: left;"><b>Label</b>: keyboard</p><p style="text-align: center;"><audio controls><source src="data/audio/keyboard_electronic_069-074-075.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 6</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: keyboard</p><p style="text-align: left;"><b>xxx</b>: mallet</p><p style="text-align: left;"><b>Label</b>: mallet</p><p style="text-align: center;"><audio controls><source src="data/audio/mallet_acoustic_047-103-075.wav" type="audio/wav"></audio></p></td>
        </tr>
         <tr>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 7</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: flute</p><p style="text-align: left;"><b>xxx</b>: reed</p><p style="text-align: left;"><b>Label</b>: reed</p><p style="text-align: center;"><audio controls><source src="data/audio/reed_acoustic_018-084-075.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 8</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: guitar</p><p style="text-align: left;"><b>xxx</b>: bass</p><p style="text-align: left;"><b>Label</b>: bass</p><p style="text-align: center;"><audio controls><source src="data/audio/bass_synthetic_135-067-025.wav" type="audio/wav"></audio></p></td>
            <td style="text-align: center; vertical-align: top;"><p><b>Example 9</b></p><p style="text-align: left;"><b>Qwen2.5-Omni</b>: bass</p><p style="text-align: left;"><b>xxx</b>: organ</p><p style="text-align: left;"><b>Label</b>: organ</p><p style="text-align: center;"><audio controls><source src="data/audio/organ_electronic_007-058-025.wav" type="audio/wav"></audio></p></td>
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