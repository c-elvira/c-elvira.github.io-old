---
layout: page
permalink: /publications/
title: publications
description: Publications by categories in reversed  chronological order. (last update march 2022)
---

#### Preprint(s)
{% bibliography --query @preprint %}

#### International journal papers
{% bibliography --query @article %}

#### International conference papers
{% bibliography --query @inproceedings[language!=French] %}

#### National conference papers
{% bibliography --query @inproceedings[language=French] %}

#### Technical reports
{% bibliography --query @techreport %}

#### Thesis
{% bibliography --query @phdthesis %}