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

## Zhengqiang ZHANG (郑强 张)

I am currently a fourth-year PhD student in the Department of COMP at Hong Kong Polytechnic University (PolyU), supervised by [Prof. Lei ZHANG](https://www4.comp.polyu.edu.hk/~cslzhang/). Prior to that, I worked as Multimedia AI Algorithm Engineer at HUYA Company for about one and a half years. I received my Master's (supervised by [Prof. Xinge You](https://bmal.hust.edu.cn/EN.htm)) and Bachelor's degree at Huazhong University of Science and Technology (HUST).
My research interests lie in image generation and image reconstruction. Recently, I focus on diffusion generative models and LLM-based agent frameworks, especially their native integration into image/video generation pipelines.

# 🔥 News
- *2026.09*: &nbsp;🎉🎉 2 papers accepted by NeurIPS 2026, including 1 first-author paper and 1 co-first-author paper.
- *2026.07*: &nbsp;🎉 1 paper accepted by ECCV 2026.
- *2026.02*: &nbsp;🎉 1 paper accepted by CVPR 2026.
- *2025.09*: &nbsp;🎉🎉 3 papers accepted by NeurIPS 2025, including 1 first-author paper.
  
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/logo.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LDM-is-AE: Latent Diffusion Model is an Auto-Encoder for End-to-End Image Generation](https://github.com/PolyU-VCLab/LDMisAE)

**Zhengqiang ZHANG**, Lingchen Sun, Rongyuan Wu, Qiaosi Yi, Xiangtao Kong, Chaodong Xiao, Lei Zhang+

*NeurIPS 2026*

+: Corresponding author
- A single-stage, end-to-end image generation framework that makes the DiT backbone itself an explicit auto-encoder, removing the external VAE and its inherited bias.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/gpstoken.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GPSToken: Gaussian Parameterized Spatially-adaptive Tokenization for Image Representation and Generation](https://github.com/xtudbxk/GPSToken)

**Zhengqiang ZHANG**, Rongyuan Wu, Lingchen Sun, Lei Zhang+

*NeurIPS 2025*

+: Corresponding author
- A non-uniform, spatially-adaptive image tokenizer using 2D Gaussians, which allocates more tokens for complex regions while less tokens for simple regions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/gsasr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized and Efficient 2D Gaussian Splatting for Arbitrary-scale Super-Resolution](https://github.com/ChrisDud0257/GSASR)

Du Chen*, Liyi Chen*, **Zhengqiang ZHANG**, Lei Zhang+

*ICCV 2025*

*: Equal contribution, +: Corresponding author
- Arbitrary-scale SR via 2D Gaussian Splatting.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/frecas.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FreCaS: Efficient Higher-Resolution Image Generation via Frequency-aware Cascaded Sampling](https://github.com/xtudbxk/FreCaS)

**Zhengqiang ZHANG**, Ruihuang Li, Lei Zhang+

*ICLR 2025*

+: Corresponding author
- A training-free sampling strategy which generates higher-resolution images with pretrained diffusion models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/ssl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SSL: A Self-similarity Loss for Improving Generative Image Super-resolution](https://github.com/ChrisDud0257/SSL)

Du Chen*, **Zhengqiang ZHANG***, Jie Liang, Lei Zhang+

*ACM MM 2024*

*: Equal contribution, +: Corresponding author
- A self-similarity loss for generative ISR task.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2024</div><img src='images/tmp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TMP: Temporal Motion Propagation for Online Video Super-Resolution](https://github.com/xtudbxk/TMP)

**Zhengqiang ZHANG**, Ruihuang Li, Shi Guo, Yang Cao, Lei Zhang+

*IEEE TIP 2024*

+: Corresponding author
- A fast motion estimation method for online VSR.
</div>
</div>

More papers can be seen in [Google Scholar](https://scholar.google.com/citations?user=UX26wSMAAAAJ).


# 📖 Educations
- *2022.09 - Now*, PhD, Hong Kong Polytechnic University, COMP Department.
- *2017.09 - 2020.06*, Master, Huazhong University of Science and Technology, School of Electronic Information and Communications.
- *2013.09 - 2017.06*, Bachelor, Huazhong University of Science and Technology, School of Electronic Information and Communications.

# 💻 Internships
- *2022.09 - Now*, OPPO, China.

# 💼 Occupation
- *2020.09 - 2022.03*, Huya, China.

