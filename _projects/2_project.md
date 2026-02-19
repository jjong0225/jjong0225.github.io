---
layout: page
title: 다중 View 적대 학습 기반 변형 정합 
description: 복부 CT 정합 시 큰 변형으로 인한 영상 왜곡을 줄이기 위해, Transformer 기반 Coarse-to-Fine 정합과 Multi-view Adversarial Learning을 결합하여 사실적이고 신뢰할 수 있는 변형 정합 구현
img: assets/img/publication_preview/AD_DIR.png
importance: 2
category: Medical Imaging
related_publications: true
giscus_comments: true
---

복부 CT 간 변형 정합(Deformable Image Registration) 과정에서 큰 변형으로 인해 발생하는 영상 왜곡이 정합 품질과 신뢰성을 저하시키는 문제가 있다. 본 연구에서는 이를 해결하기 위해 **큰 변형에 강건한 Transformer 기반의 Coarse-to-Fine 정합 모델**과 **큰 변형 시 발생하는 오변형을 규제하는 Multi-view Adversarial Learning**을 제안하였다. 이를 통해 보다 사실적이고 임상적으로 신뢰할 수 있는 정합 결과를 달성하였다.

{% cite dir2025 %}

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ad_poster.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    다중 View 적대 학습 기반 변형 정합.
</div>
