# AI-Synthesized-Speech-Detection-A-Comprehensive-Survey

### Table II: THE CHALLENGE COMPETITIONS PROPOSED FOR DEEPFAKE SPEECH DETECTION
| Challenge Competitions  | Years  | Data | Languages | Public Label (train&dev/test) | Audio | Visual | Team No. |   Top 1 System |
| :---------------------: |:------:| :---:| :--------:| :----------------------------:| :----:| :----:| :--------:| :-------------:|
| ASVspoof 2015 [[11](https://www.asvspoof.org/is2015_asvspoof.pdf)]| 2015 | Speech | English | Yes/Yes | Yes | No | 16 | Ensemble |
| ASVspoof 2019 (LA Task) [[12](https://arxiv.org/pdf/1911.01601)]  | 2019 | Speech | English | Yes/Yes | Yes | No | 48 | Ensemble |
| DFDC [[13](https://arxiv.org/pdf/1910.08854)], [[14](https://arxiv.org/pdf/2006.07397)]  | 2020 | Speech | English | Yes/Yes | Yes | Yes | 2114 | Ensemble |
| FTC [[15](https://www.ftc.gov/news-events/contests/ftc-voice-cloning-challenge)] | 2020 | Speech | English | No/No | Yes | No | - | - |
| ASVspoof 2021 (LA Task) [16](https://arxiv.org/pdf/2109.00537)]   | 2021 | Speech | English | Yes/Yes | Yes | No | 54 | Ensemble |
| ASVspoof 2021 (DF Task) [[16](https://arxiv.org/pdf/2109.00537)]  | 2021 | Speech | English | Yes/Yes | Yes | No | -  | Ensemble |
| ADD 2022 Track 1 [[17](http://addchallenge.cn/add2022)]  | 2022 | Speech | Chinese | Yes/Yes | Yes | No | 42  | - |
| ADD 2022 Track 2 [[17](http://addchallenge.cn/add2022)]  | 2022 | Speech | Chinese | Yes/Yes | Yes | No | 27  | - |
| ADD 2022 Track 3.2 [[17](http://addchallenge.cn/add2022)]  | 2022 | Speech | Chinese | Yes/Yes | Yes | No | 33  | - |
| ADD 2023 Track 1.2 [[18](http://addchallenge.cn/add2023)]  | 2023 | Speech | Chinese | No/No | Yes | No | 49  | - |
| ADD 2023 Track 2 [[18](http://addchallenge.cn/add2023)]  | 2023 | Speech | Chinese | No/No | Yes | No | 16 | - |
| AV-Deepfake1M [[19](https://arxiv.org/pdf/2311.15308)], [[20](https://deepfakes1m.github.io/)]  | 2024 | Speech | English | Yes/No | Yes | Yes | - | - |
| ASVspoof 2024 [[21](https://www.asvspoof.org/)]  | 2024 | Speech | English | Yes/No | Yes | No | 53 | - |
| SVDD 2024 [[22](https://challenge.singfake.org/)]  | 2024 | Singing | - | Yes/No | Yes | No | - | - |

### Table III: PUBLIC AND BENCHMARK DATASETS PROPOSED FOR AI-SYNTHESIZED SPEECH DETECTION
| Dataset | Year  | Language | Speakers (Male/Female) | Utt. No. (Real/Fake) | AI-Synthesized Speech Systems | Speech Condition | Real Speech Resources | Utt. length | Evaluation Metrics |
| :-----: |:-----:| :-------:| :---------------------:| :-------------------:| :----------:| :----:| :--------:| :-------------:|:-------------:|
| ASVspoof 2015 [[11](https://www.asvspoof.org/is2015_asvspoof.pdf)](audio)| 2015 | English | 45/61 | 16,651/246,500 | 10 | Clean | Speaker Volunteers | 1 to 2 |EER|
| FoR [[25](https://bil.eecs.yorku.ca/wp-content/uploads/2020/01/FoR-Dataset_RR_VT_final.pdf)](audio)| 2019 | English | 33 | 198,000+ | 7 | Clean | Kaggle [[26](https://www.kaggle.com/datasets/percevalw/englishfrench-translations)] | 2.35 | Acc. |
| ASVspoof 2019 (LA task) [[12](https://arxiv.org/pdf/1911.01601)](audio)| 2019 | English | 46/61 | 121,461 | 19 | Clean & Noisy | Speaker Volunteers | - |EER|
| DFDC [[27](https://arxiv.org/pdf/2006.07397)](video)| 2020 | English | 3426 | 12,8154/104,500 | 1 | - | Speaker Volunteers | 68.8 | Precision/ Recall |
| ASVspoof 2021 (LA task) [[16](https://arxiv.org/pdf/2109.00537)](audio)| 2021 | English | 21/27 | 18,452/163,114 | 13 | Clean & Noisy | Speaker Volunteers | - | EER |
| ASVspoof 2021 (DF task) [[16](https://arxiv.org/pdf/2109.00537)](audio)| 2021 | English | 21/27 | 22,617/589,212 | 100+ | Clean & Noisy | Speaker Volunteers | - | EER |
| WaveFake [[28](https://arxiv.org/pdf/2111.02813)](audio)| 2021 | English, Japanese | 0/2 | 117,985 | 6 | Clean | LJSPEECH [[29](https://arxiv.org/pdf/1802.08435)] & JSUT [[30](https://arxiv.org/pdf/1711.00354)] | 6s/4.8s | EER |
| KoDF [[31](https://arxiv.org/pdf/2103.10094)](video)| 2021 | Korean | 198/205 | 62,116/175,776 | 2 | Clean | Speaker Volunteers | 90/15 (real/fake) | Acc & AuC |
| ADD 2022 [[17](http://addchallenge.cn/add2022)]| 2022 | Chinese |  |  |  |  |  |  | EER |
| FakeAVCeleb [[32](https://arxiv.org/pdf/2108.05080)](video) | 2022 | English | 250/250 | 600/- | 2 | Clean & Noise | Vox-Celeb2 [[33](https://arxiv.org/pdf/1806.05622)] | 7s | AuC |
| In-the-Wild [[34](https://arxiv.org/pdf/2203.16263)](audio) | 2022 | English | 58 | 31779 | - | - | Self-collected | 4.3s | EER |
| LAV-DF [[35](https://arxiv.org/pdf/2204.06228)](video) | 2022 | English | 153 | 36,431/99,873 | 1 | Clean & Noise | Vox-Celeb2 [[33](https://arxiv.org/pdf/1806.0562)] | - | AP |
| Voc.v [[36](https://arxiv.org/pdf/2210.10570)](audio) | 2023 | English | 46/61 | 82,048 | 5 | Clean & Noisy | ASVspoofing 2019 LA | - | EER |
| PartialSpoof [[37](https://arxiv.org/pdf/2204.05177)](audio) | 2023 | English | 46/61 | 12,483/108,87 | 19 | Clean & Noisy | ASVspoofing 2019 | 0.2-6.4 | EER |
| LibriSeVoc [[38](https://arxiv.org/pdf/2304.13085)](audio) | 2023 | English | - | 13,201/79,06 | 6 | Clean & Noisy | Librispeech  | - | EER |
| AV-Deepfake1M [[19](https://arxiv.org/pdf/2311.15308)], [[20](https://deepfakes1m.github.io/)](video) | 2023 | English | 2,068 | 286,721/860,039 | 2 | Clean & Noisy | Vox-Celeb2 [[33](https://arxiv.org/pdf/1806.0562)] | - | Acc & AuC |
