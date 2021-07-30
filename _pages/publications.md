---
layout: page
permalink: /publications/
title: publications
description: Publications by categories in reversed  chronological order. (last update July 2021)
---

#### Submitted/pipelined journal papers
{% bibliography --query @preprint %}


#### International journal papers
{% bibliography --query @article %}


#### International conference papers
{% bibliography --query @inproceedings[language!=French] %}

#### National conference papers
{% bibliography --query @inproceedings[language=French] %}

#### Thesis
{% bibliography --query @phdthesis %}