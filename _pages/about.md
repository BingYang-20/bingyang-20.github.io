---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a assistant researcher at Westlake University, Hangzhou, China (西湖大学). From 2022 to 2024, I was a Postdoctor with Westlake University, Hangzhou, China, supervised by Prof. Xiaofei Li (李晓飞). 
I received the Ph.D. degree from the School of Electronics Engineering and Computer Science, Peking University, Beijing, China, in 2022, supervised by Prof. Hong Liu (刘宏). I received the B.Eng. degree in automation from the University Of Science and Technology Beijing, Beijing, China, in 2015. 

My research interests include sound source localization and tracking, spatial acoustic parameter estimation, multichannel audio representation learning, and microphone array signal processing. <a href='https://scholar.google.com/citations?user=_rt11bkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>)
 
 
# 🔥 News
- *2025.05*: &nbsp;🎉🎉 one INTERSPEECH paper accepted 
- *2024.11*: &nbsp;🎉🎉 one TASLP paper accepted 
- *2024.09*: &nbsp;🎉🎉 one NeurIPS paper accepted

# 💻 Experience
- *2024.02 - present*, Assistant researcher, Westlake University, Hangzhou, China.
- *2022.02 - 2024.02*, Postdoctor, Westlake University, Hangzhou, China.

# 📖 Educations
- *2015.09 - 2022.01*, Ph.D. in Computer Applied Technology, [School of Electronics Engineering and Computer Science](http://eecs.pku.edu.cn/), [Peking University](https://www.pku.edu.cn/) (PKU), Beijing, China.
- *2011.09 - 2015.06*, B.Eng. in Automation, [School of Automation](http://saee.ustb.edu.cn/), [University of Science and Technology Beijing](https://www.ustb.edu.cn/) (USTB), China

# 📝 Publications 
**Selected Journal**
- **Bing Yang**, Xiaofei Li. [Self-supervised learning of spatial acoustic representation with cross-channel signal reconstruction and multi-channel Conformer](https://ieeexplore.ieee.org/document/10675425). IEEE/ACM Transactions on Audio, Speech, and Language Processing (**TASLP**), vol. 32, pp. 4211-4225, 2024. [[arXiv](https://arxiv.org/abs/2312.00476), [code](https://github.com/Audio-WestlakeU/SAR-SSL)]

- Yabo Wang#, **Bing Yang**# (equal contribution), Xiaofei Li. [IPDnet: A universal direct-path IPD estimation network for sound source localization](https://ieeexplore.ieee.org/document/10771699). IEEE/ACM Transactions on Audio, Speech, and Language Processing (**TASLP**), vol. 32, pp. 5051-5064, 2024. [[arXiv](https://arxiv.org/abs/2405.07021), [code](https://github.com/Audio-WestlakeU/FN-SSL)]

- Yidi Li, Hong Liu, **Bing Yang**. [STNet: Deep audio-visual fusion network for robust speaker tracking](https://ieeexplore.ieee.org/abstract/document/10814658). IEEE Transactions on Multimedia (**TMM**), vol.27, pp.1835-1847, 2024. [[arXiv](https://arxiv.org/abs/2410.05964)]

- **Bing Yang**, Hong Liu, Xiaofei Li. [Learning deep direct-path relative transfer function for binaural sound source localization](https://ieeexplore.ieee.org/document/9582746). IEEE/ACM Transactions on Audio, Speech, and Language Processing (**TASLP**), vol. 29, pp. 3491–3503, 2021. [[arXiv](https://arxiv.org/abs/2202.07841), [code](https://github.com/BingYang-20/DP-RTF-Learning)]

- **Bing Yang**, Runwei Ding, Yutong Ban, Xiaofei Li, Hong Liu. [Enhancing direct-path relative transfer function using  deep neural network for robust sound source localization](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cit2.12024). CAAI Transactions on Intelligence Technology, vol. 7, no. 3, pp. 446-454, 2022.

- **Bing Yang**, Hong Liu, Cheng Pang, Xiaofei Li. [Multiple sound source counting and localization based on TF-wise spatial spectrum clustering](https://ieeexplore.ieee.org/document/8712393). IEEE/ACM Transactions on Audio, Speech, and Language Processing (**TASLP**), vol. 27, no. 8, pp. 1241–1255, 2019. [[code](https://github.com/BingYang-20/TF-Wise-Spatial-Spectrum-Clustering)]

- Hong Liu, Peipei Yuan, **Bing Yang**, Ge Yang, Yang Chen. HRTF-reserved time-frequency masking for robust binaural sound source localization. CAAI Transactions on Intelligence Technology, 2022, 7(1): 26-33.

**Selected Conference**

- Yujie Yang, **Bing Yang**, Xiaofei Li. [Mel-McNet: A Mel-scale framework for online multichannel speech enhancement](https://www.isca-archive.org/interspeech_2025/yang25k_interspeech.html). Annual Conference of the International Speech Communication Association (**INTERSPEECH**), 2025, pp. 1173-1177.

- **Bing Yang**, Changsheng Quang, Yabo Wang, et al. [RealMAN: A recorded and annotated microphone array dataset for dynamic speech enhancement and localization](). International Conference on Neural Information Processing Systems (**NeurIPS**), 2024, pp. 105997-106019. [[arXiv](https://arxiv.org/abs/2406.19959), [dataset](https://github.com/Audio-WestlakeU/RealMAN), [poster](https://neurips.cc/media/PosterPDFs/NeurIPS%202024/97504.png)]

- Yabo Wang#, **Bing Yang**# (equal contribution), Xiaofei Li. [FN-SSL: Full-band and narrow-band fusion for sound source localization](https://www.isca-archive.org/interspeech_2023/wang23j_interspeech.html). Annual Conference of the International Speech Communication Association (**INTERSPEECH**), 2023, pp. 3779-3783. [[arXiv](https://arxiv.org/pdf/2305.19610), [code](https://github.com/Audio-WestlakeU/FN-SSL)]

- **Bing Yang**, Hong Liu, Xiaofei Li. [SRP-DNN: Learning direct-path phase difference for multiple moving sound source localization](https://ieeexplore.ieee.org/document/9746624). IEEE International Conference on Acoustics, Speech and Signal Processing (**ICASSP**), 2022, pp. 721-725. [[arXiv](https://arxiv.org/abs/2202.07859), [code](https://github.com/BingYang-20/SRP-DNN), [poster](https://drive.google.com/file/d/1X7061z7ALr1wCp_6AkBQqBZ-d67CpMp2/view?usp=sharing)]

- **Bing Yang**, Xiaofei Li, Hong Liu. [Supervised direct-path relative transfer function learning for binaural sound source localization](https://ieeexplore.ieee.org/document/9413923). IEEE International Conference on Acoustics, Speech and Signal Processing (**ICASSP**), 2021, pp. 825–829. [[slide](https://drive.google.com/file/d/1gQl0zgZlhDWEntU9GlTFq1Ujdu-5eYlJ/view?usp=sharing), [poster](https://drive.google.com/file/d/1hsmJtT8ZFjXEcufP0W7Uck9YEAIe7_Er/view?usp=sharing)]

- **Bing Yang**, Hong Liu, Cheng Pang. [Multiple sound source counting and localization based on spatial principal eigenvector](https://www.isca-archive.org/interspeech_2017/yang17b_interspeech.html). Annual Conference of the International Speech Communication Association (**INTERSPEECH**), 2017, pp. 1924–1928. [[poster](https://drive.google.com/file/d/18Nhr4qV3W3K7Y4rnAwO6DwHnaO9QZpQ2/view?usp=sharing)]

- Hong Liu, **Bing Yang**, Cheng Pang. [Multiple sound source localization based on TDOA clustering and multi-path matching pursuit](https://ieeexplore.ieee.org/document/7952755/). IEEE International Conference on Acoustics, Speech and Signal Processing (**ICASSP**), 2017, pp. 3241–3245. [[poster](https://drive.google.com/file/d/1-lVYM4nyD9-mq1-FfAUTaEQpZnyKBihl/view?usp=sharing)]

- Hong Liu, Zhan Chen, **Bing Yang**. [Lip graph assisted audio-visual speech recognition using bidirectional synchronous fusion](https://www.isca-archive.org/interspeech_2020/liu20r_interspeech.htmls). Annual Conference of the International Speech Communication Association (**INTERSPEECH**), 2020, pp. 3520-3524. 

- Hong Liu, Yidi Li, **Bing Yang**. 3D audio-visual speaker tracking with a two-layer particle filter. IEEE International Conference on Image Processing (**ICIP**), 2019, pp. 1955-1959. 

- Hong Liu, Haipeng Lan, **Bing Yang**, Cheng Pang. [Multiple concurrent sound source tracking based on observation-guided adaptive particle filter](https://www.isca-archive.org/interspeech_2018/liu18c_interspeech.html). Annual Conference of the International Speech Communication Association (**INTERSPEECH**), 2018, pp. 826-830. 

- Hong Liu, Yongheng Sun, Yidi Li, **Bing Yang**. 3D audio-visual speaker tracking with a novel particle filter. International Conference on Pattern Recognition (**ICPR**), 2021, pp. 7343-7348. 

# 🎖 Honors and Awards
**Awards** 

- Merit Student, Learning Excellence Award, Excellent Scientific Research Award, 	Peking University, Sep. 2015 ~ Jan. 2022 

- Outstanding Graduates, Merit Student, 	Beijing, Sep. 2011 ~ Jun. 2015  

- President Medal, Merit Student, Outstanding Student Leaders, 	University of Science and Technology Beijing, Sep. 2011 ~ Jun. 2015  

**Scholarship**

- Founder Scholarship, 	Peking University, Sep. 2015 ~ Jan. 2022

- National Scholarship, National Encouragement Scholarship,	Ministry of Education of P.R.China, Sep. 2011 ~ Jun. 2015   

- ‘Guanzhi’ Scholarship, 	University of Science and Technology Beijing, Sep. 2011 ~ Jun. 2015   

# 💬 Projects
 

