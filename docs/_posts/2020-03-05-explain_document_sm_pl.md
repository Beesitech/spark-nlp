---
layout: model
title: Explain Document Small
author: John Snow Labs
name: explain_document_sm
class: PipelineModel
language: pl
repository: public/models
date: 2020-03-05
tags: [pipeline]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 




{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/public/models/explain_document_sm_pl_2.5.0_2.4_1588531081173.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = PretrainedPipeline("explain_document_sm","pl","public/models")

model.annotate("The patient had stomach pain and high fever")
```

```scala
val model = PretrainedPipeline("explain_document_sm","pl","public/models")

model.annotate("The patient had stomach pain and high fever")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|---------------------|
| Model Name     | explain_document_sm |
| Model Class    | PipelineModel       |
| Dimension      | 2.4                 |
| Compatibility  | 2.5.0               |
| License        | open source         |
| Edition        | public              |
| Inputs         |                     |
| Output         |                     |
| Language       | pl                  |
| Case Sensitive | True                |
| Dependencies   |                     |




{:.h2_title}
## Data Source
  
Visit [this]() link to get more information
