---
title: "A New Ensemble Method for Concessively Targeted Multi-model Attack"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ziwen He
- Wei Wang
- Xinsheng Xuan
- admin
- Tieniu Tan

date: "2019-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: arXiv preprint arXiv:1912.10833
#publication_short: In *ICW*

abstract: It is well known that deep learning models are vulnerable to adversarial examples crafted by maliciously adding perturbations to original inputs. There are two types of attacks:targeted attack and non-targeted attack, and most researchers often pay more attention to the targeted adversarial examples. However, targeted attack has a low success rate, especially when aiming at a robust model or under a black-box attack protocol. In this case, non-targeted attack is the last chance to disable AI systems. Thus, in this paper, we propose a new attack mechanism which performs the non-targeted attack when the targeted attack fails. Besides, we aim to generate a single adversarial sample for different deployed models of the same task, e.g. image classification models. Hence, for this practical application, we focus on attacking ensemble models by dividing them into two groups:easy-to-attack and robust models. We alternately attack these two groups of models in the non-targeted or targeted manner. We name it a bagging and stacking ensemble (BAST) attack. The BAST attack can generate an adversarial sample that fails multiple models simultaneously. Some of the models classify the adversarial sample as a target label, and other models which are not attacked successfully may give wrong labels at least. The experimental results show that the proposed BAST attack outperforms the state-of-the-art attack methods on the new defined criterion that considers both targeted and non-targeted attack performance.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: http://arxiv.org/abs/1912.10833
