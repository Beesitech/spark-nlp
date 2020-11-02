---
layout: model
title: Clean Slang
author: John Snow Labs
name: clean_slang
class: PipelineModel
language: en
repository: public/models
date: 2020-01-28
tags: [pipeline]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 




{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/public/models/clean_slang_en_2.0.0_2.4_1580255816146.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = PretrainedPipeline("clean_slang","en","public/models")

model.annotate("The patient had stomach pain and high fever")
```

```scala
val model = PretrainedPipeline("clean_slang","en","public/models")

model.annotate("The patient had stomach pain and high fever")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|---------------|
| Model Name     | clean_slang   |
| Model Class    | PipelineModel |
| Dimension      | 2.4           |
| Compatibility  | 2.0.0         |
| License        | open source   |
| Edition        | public        |
| Inputs         |               |
| Output         |               |
| Language       | en            |
| Case Sensitive | True          |
| Dependencies   |               |




{:.h2_title}
## Data Source
  
Visit [this]() link to get more information
