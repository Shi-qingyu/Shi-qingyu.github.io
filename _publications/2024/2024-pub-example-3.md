---
title:          "DreamRelation: Bridging Customization and Relation Generation"
date:           2024-11-20 00:01:00 +0800
selected:       true
pub:            "CVPR"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Oral</span>'
pub_date:       "2025"
abstract: >-
  Customized image generation is essential for creating personalized content based on user prompts, allowing large-scale text-to-image diffusion models to more effectively meet individual needs. However, existing models often neglect the relationships between customized objects in generated images. In contrast, this work addresses this gap by focusing on relation-aware customized image generation, which seeks to preserve the identities from image prompts while maintaining the relationship specified in text prompts. Specifically, we introduce DreamRelation, a framework that disentangles identity and relation learning using a carefully curated dataset. Our training data consists of relation-specific images, independent object images containing identity information, and text prompts to guide relation generation. Then, we propose two key modules to tackle the two main challenges: generating accurate and natural relationships, especially when significant pose adjustments are required, and avoiding object confusion in cases of overlap. First, we introduce a keypoint matching loss that effectively guides the model in adjusting object poses closely tied to their relationships. Second, we incorporate local features of the image prompts to better distinguish between objects, preventing confusion in overlapping cases. Extensive results on our proposed benchmarks demonstrate the superiority of DreamRelation in generating precise relations while preserving object identities across a diverse set of objects and relationships.
cover:   ./assets/images/covers/dreamrelation.jpeg
authors:
  - Qingyu Shi
  - Lu Qi
  - Jianzong Wu
  - Jinbin Bai
  - Jingbo Wang
  - Yunhai Tong
  - Xiangtai Li
links:
  Page: https://shi-qingyu.github.io/DreamRelation.github.io/
  Code: https://github.com/Shi-qingyu/DreamRelation
---
