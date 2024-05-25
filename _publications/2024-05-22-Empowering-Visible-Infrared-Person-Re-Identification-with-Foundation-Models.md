---
title: "Empowering Visible-Infrared Person Re-Identification
with Foundation Models"
collection: publications
permalink: /publications/2024-05-22-Empowering-Visible-Infrared-Person-Re-Identification-with-Foundation-Models
excerpt: 'We propose a novel text-enhanced VI-ReID framework driven by Foundation Models (TVI-FM).'
date: '2024-05-22'
venue: ':  Submitted to NeurIPS'
paperurl: 'https://whu-hzy.github.io/files/2024_NIPS_HZY_TVI_FM.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<!-- <object data="../files/overview-framework.pdf" type="application/pdf" weight="700px">
    <embed src="../files/overview-framework.pdf">
        <p>This browser does not support PDFs. Please <a href="../files/overview-framework.pdf">download the PDF</a> to view.</p>
    </embed>
</object> -->
<!-- 插入图片-->
<img src="../files/overview-framework.png" alt="overview-framework"/>


Visible-Infrared Person Re-identification (VI-ReID) often underperforms compared to RGB-based ReID due to significant modality differences, primarily caused by the absence of detailed information in the infrared modality. With the development of Large Language Models (LLMs) and Language Vision Models (LVMs), this motivates us to investigate a feasible solution to empower VI-ReID performance with off-the-shelf foundation models. To this end, we propose a novel text-enhanced VI-ReID framework driven by Foundation Models (TVI-FM). The basic idea is to enrich the representation of the infrared modality with automatically generated textual descriptions. Specifically, we incorporate a pretrained multimodal language vision model (LVM) to extract textual features from descriptions augmented by LLM and incrementally fine-tune the text encoder to minimize the domain gap between generated texts and original visual images. Meanwhile, to enhance the infrared modality with robust textual representations, we leverage modality alignment capabilities of LVMs and LVM-generated feature-level filters. This allows the text model to learn complementary features from the infrared modality, ensuring semantic structural consistency between the fusion modality and the visible modality. Furthermore, we introduce modality joint learning to align features of all modalities, ensuring that textual features maintain stable semantic representation of overall pedestrian appearance during complementary information learning. Additionally, a modality ensemble retrieving strategy is proposed to consider each query modality for leveraging their complementary strengths to improve retrieval effectiveness and robustness. Extensive experiments demonstrate that our method significantly improves retrieval performance on three expanded cross-modal re-identification datasets, paving the way for utilizing foundation models in downstream data-demanding tasks. The code will be released.

<p class="wordwrap">Download <a href="https://whu-hzy.github.io/files/2024_NIPS_HZY_TVI_FM.pdf">here</a></p>