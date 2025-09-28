# 臺灣大學李宏毅教授「機器學習 2021 Spring」課程筆記

此筆記內容為臺灣大學李宏毅教授 2021 Spring 的[機器學習 (Machine Learning) 課程](https://www.youtube.com/playlist?list=PLJV_el3uVTsMhtt7_Y6sgTHGHp1Vb2P2J) (YouTube)  
筆記中的圖片皆擷取自老師的上課簡報，來自於老師的[課程網站](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.php)  

* Dcard [研究所版 分享文](https://www.dcard.tw/f/graduate_school/p/241639442)
* Dcard [軟體工程師版 分享文](https://www.dcard.tw/f/softwareengineer/p/241639712)  

行有餘力的話，可以幫我點個星星 ⭐，非常感謝 🙂  

---

## 💡 Reminds

**1.** 提供 [Notion](https://chsiang.notion.site/ntuml2021notes)、[Website](https://chsiang426.github.io/ML-2021-notes/) 兩種線上筆記資源，以及 [PDF](https://github.com/chsiang426/ML-2021-notes/tree/main/PDF) 可供下載。

**2.** 筆記內容皆照著老師的上課內容消化理解製作，若有理解錯誤，請不吝指正。

**3.** 筆記有幾個小部分不完整（老師有講但我沒有寫下來），還請見諒。

---

## 📖 Notes

<table>
  <thead>
    <tr>
      <th colspan="4" align="center">以章節劃分</th>
    </tr>
    <tr>
      <th align="center">#</th>
      <th align="center">Topic</th>
      <th align="center">Note Link</th>
      <th align="center">Video</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td align="center">01</td>
      <td align="center">機器學習基本概念簡介</td>
      <td align="center"><a href="https://chsiang.notion.site/01-b6979cc5ba9b4e2887d2b5e86c174897">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/01-機器學習基本概念簡介/01-機器學習基本概念簡介.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/01-%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5%E7%B0%A1%E4%BB%8B.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/Ye018rCVvOo">video 1</a>, <a href="https://youtu.be/bHcJCp2Fyxs">video 2</a></td>
    </tr>
    <tr>
      <td align="center">02</td>
      <td align="center">DeepLearning<br/>1. General Guidance<br/>2. 類神經網路優化技巧<br/>3. Loss of Classification</td>
      <td align="center">
        1. <a href="https://chsiang.notion.site/02-1-DeepLearning-General-Guidance-8a5b0e746c03406eba3921c51734629c">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/02.1-DeepLearning-General%20Guidance/02.1-DeepLearning-General%20Guidance.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/02.1-deeplearning-general_guidance.pdf">PDF</a><br/>
        2. <a href="https://chsiang.notion.site/02-2-DeepLearning-002585231c2f413bbc626e00e464694d">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/02.2-DeepLearning-%E9%A1%9E%E7%A5%9E%E7%B6%93%E7%B6%B2%E8%B7%AF%E5%84%AA%E5%8C%96%E6%8A%80%E5%B7%A7/02.2-DeepLearning-%E9%A1%9E%E7%A5%9E%E7%B6%93%E7%B6%B2%E8%B7%AF%E5%84%AA%E5%8C%96%E6%8A%80%E5%B7%A7.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/02.2-deeplearning-%E9%A1%9E%E7%A5%9E%E7%B6%93%E7%B6%B2%E8%B7%AF%E5%84%AA%E5%8C%96%E6%8A%80%E5%B7%A7.pdf">PDF</a><br/>
        3. <a href="https://chsiang.notion.site/02-3-DeepLearning-Loss-of-Classification-f492fe29ad284cc7bc3837600dc2f5d6">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/02.3-DeepLearning-Loss%20of%20Classification/02.3-DeepLearning-Loss%20of%20Classification.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/02.3-deeplearning-loss_of_classification.pdf">PDF</a>
      </td>
      <td align="center"><a href="https://youtu.be/WeHM2xpYQpw">video 1</a>, <a href="https://youtu.be/QW6uINn7uGk">video 2</a>, <a href="https://youtu.be/zzbr1h9sF54">video 3</a>, <a href="https://youtu.be/HYUXEeh3kwY">video 4</a>, <a href="https://youtu.be/O2VkP8dJ5FE">video 5</a>, <a href="https://youtu.be/BABPWOkSbLE">video 6</a></td>
    </tr>
    <tr>
      <td align="center">03</td>
      <td align="center">CNN（卷積神經網路）</td>
      <td align="center"><a href="https://chsiang.notion.site/03-CNN-86e7f137fdd0494fb08f236d34c67b6e">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/03-CNN（卷積神經網路）/03-CNN（卷積神經網路）.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/03-CNN%EF%BC%88%E5%8D%B7%E7%A9%8D%E7%A5%9E%E7%B6%93%E7%B6%B2%E8%B7%AF%EF%BC%89.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/OP5HcXJg2Aw">video</a></td>
    </tr>
    <tr>
      <td align="center">04</td>
      <td align="center">Self-attention</td>
      <td align="center"><a href="https://chsiang.notion.site/04-Self-attention-30e8a76bd1b146c690fe39faee260757">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/04-Self-attention/04-Self-attention.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/04-Self-attention.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/hYdO9CscNes">video 1</a>, <a href="https://youtu.be/gmsMY5kc-zw">video 2</a></td>
    </tr>
    <tr>
      <td align="center">05</td>
      <td align="center">Transformer</td>
      <td align="center"><a href="https://chsiang.notion.site/05-Transformer-b6d1aa6cf7944806b0581ae5b667f66c">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/05-Transformer/05-Transformer.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/05-Transformer.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/n9TlOhRjYoc">video 1</a>, <a href="https://youtu.be/N6aRv06iv2g">video 2</a></td>
    </tr>
    <tr>
      <td align="center">06</td>
      <td align="center">Generative Adversarial Network（GAN）</td>
      <td align="center"><a href="https://chsiang.notion.site/06-Generative-Adversarial-Network-GAN-3eef1d4d34384ea596d6be37eb429a25">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/06-Generative%20Adversarial%20Network（GAN）/06-Generative%20Adversarial%20Network（GAN）.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/06-Generative_Adversarial_Network%EF%BC%88GAN%EF%BC%89.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/4OWp0wDu6Xw">video 1</a>, <a href="https://youtu.be/jNY1WBb8l4U">video 2</a>, <a href="https://youtu.be/MP0BnVH2yOo">video 3</a>, <a href="https://youtu.be/wulqhgnDr7E">video 4</a></td>
    </tr>
    <tr>
      <td align="center">07</td>
      <td align="center">Self-Supervised Learning（BERT）</td>
      <td align="center"><a href="https://chsiang.notion.site/07-Self-Supervised-Learning-BERT-2cb6d4c62aa44f9386708f3be787fba5">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/07-Self-Supervised%20Learning（BERT）/07-Self-Supervised%20Learning（BERT）.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/07-Self-Supervised_Learning%EF%BC%88BERT%EF%BC%89.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/e422eloJ0W4">video 1</a>, <a href="https://youtu.be/gh0hewYkjgo">video 2</a>, <a href="https://youtu.be/ExXA05i8DEQ">video 3</a>, <a href="https://youtu.be/WY_E0Sd4K80">video 4</a></td>
    </tr>
    <tr>
      <td align="center">08</td>
      <td align="center">Auto-encoder</td>
      <td align="center"><a href="https://chsiang.notion.site/08-Auto-encoder-df28a523e1274b8db44489440685dd97">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/08-Auto-encoder/08-Auto-encoder.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/08-Auto-encoder.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/3oHlf8-J3Nc">video 1</a>, <a href="https://youtu.be/JZvEzb5PV3U">video 2</a></td>
    </tr>
    <tr>
      <td align="center">09</td>
      <td align="center">Adversarial Attack</td>
      <td align="center"><a href="https://chsiang.notion.site/09-Adversarial-Attack-b2cea886ebd94672872127b4db066b4d">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/09-Adversarial%20Attack/09-Adversarial%20Attack.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/09-Adversarial_Attack.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/xGQKhbjrFRk">video 1</a>, <a href="https://youtu.be/z-Q9ia5H2Ig">video 2</a></td>
    </tr>
    <tr>
      <td align="center">10</td>
      <td align="center">Explainable ML</td>
      <td align="center"><a href="https://chsiang.notion.site/10-Explainable-ML-d9b555b0dddd4ac5be62dacc0e42c39a">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/10-Explainable%20ML/10-Explainable%20ML.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/10-Explainable_ML.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/WQY85vaQfTI">video 1</a>, <a href="https://youtu.be/0ayIPqbdHYQ">video 2</a></td>
    </tr>
    <tr>
      <td align="center">11</td>
      <td align="center">Domain Adaptation</td>
      <td align="center"><a href="https://chsiang.notion.site/11-Domain-Adaptation-3517a984643f46069ff838bb2f630523">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/11-Domain%20Adaptation/11-Domain%20Adaptation.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/11-Domain_Adaptation.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/Mnk_oUrgppM">video</a></td>
    </tr>
    <tr>
      <td align="center">12</td>
      <td align="center">Reinforcement Learning（強化學習）</td>
      <td align="center"><a href="https://chsiang.notion.site/12-Reinforcement-Learning-b136944b862d43c68341c0dfa8cc9c4a">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/12-Reinforcement%20Learning%EF%BC%88%E5%BC%B7%E5%8C%96%E5%AD%B8%E7%BF%92%EF%BC%89/12-Reinforcement%20Learning%EF%BC%88%E5%BC%B7%E5%8C%96%E5%AD%B8%E7%BF%92%EF%BC%89.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/12-Reinforcement_Learning%EF%BC%88%E5%BC%B7%E5%8C%96%E5%AD%B8%E7%BF%92%EF%BC%89.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/XWukX-ayIrs">video 1</a>, <a href="https://youtu.be/US8DFaAZcp4">video 2</a>, <a href="https://youtu.be/kk6DqWreLeU">video 3</a>, <a href="https://youtu.be/73YyF1gmIus">video 4</a>, <a href="https://youtu.be/75rZwxKBAf0">video 5</a></td>
    </tr>
    <tr>
      <td align="center">13</td>
      <td align="center">Life Long Learning（終身學習）</td>
      <td align="center"><a href="https://chsiang.notion.site/13-Life-Long-Learning-51582d9bb84f430fb8ebe5b3dae7c7b2">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/13-Life%20Long%20Learning%EF%BC%88%E7%B5%82%E8%BA%AB%E5%AD%B8%E7%BF%92%EF%BC%89/13-Life%20Long%20Learning%EF%BC%88%E7%B5%82%E8%BA%AB%E5%AD%B8%E7%BF%92%EF%BC%89.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/13-Life_Long_Learning%EF%BC%88%E7%B5%82%E8%BA%AB%E5%AD%B8%E7%BF%92%EF%BC%89.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/rWF9sg5w6Zk">video 1</a>, <a href="https://youtu.be/Y9Jay_vxOsM">video 2</a></td>
    </tr>
    <tr>
      <td align="center">14</td>
      <td align="center">Nerwork Compression</td>
      <td align="center"><a href="https://chsiang.notion.site/14-Nerwork-Compression-4bae9dc82e1c4e06938d3637e6e966f9">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/14-Nerwork%20Compression/14-Nerwork%20Compression.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/14-Nerwork_Compression.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/utk3EnAUh-g">video 1</a>, <a href="https://youtu.be/xrlbLPaq_Og">video 2</a></td>
    </tr>
    <tr>
      <td align="center">15</td>
      <td align="center">Meta Learning（元學習）</td>
      <td align="center"><a href="https://chsiang.notion.site/15-Meta-Learning-d31c228801f648a88ced9d064b347d1a">Notion</a> / <a href="https://chsiang426.github.io/ML-2021-notes/15-Meta%20Learning%EF%BC%88%E5%85%83%E5%AD%B8%E7%BF%92%EF%BC%89/15-Meta%20Learning%EF%BC%88%E5%85%83%E5%AD%B8%E7%BF%92%EF%BC%89.html">Website</a> / <a href="https://github.com/chsiang426/ML-2021-notes/blob/main/PDF/15-Meta_Learning%EF%BC%88%E5%85%83%E5%AD%B8%E7%BF%92%EF%BC%89.pdf">PDF</a></td>
      <td align="center"><a href="https://youtu.be/xoastiYx9JU">video 1</a>, <a href="https://youtu.be/Q68Eh-wm1Ts">video 2</a></td>
    </tr>
  </tbody>
</table>
