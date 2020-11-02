---
layout: model
title: Explain Document Medium
author: John Snow Labs
name: explain_document_md
class: PipelineModel
language: da
repository: public/models
date: 2020-08-30
tags: [pipeline]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 




{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/public/models/explain_document_md_da_2.6.0_2.4_1598817214832.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = PretrainedPipeline("explain_document_md","da","public/models")

model.annotate("The patient had stomach pain and high fever")
```

```scala
val model = PretrainedPipeline("explain_document_md","da","public/models")

model.annotate("The patient had stomach pain and high fever")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|---------------------|
| Model Name     | explain_document_md |
| Model Class    | PipelineModel       |
| Dimension      | 2.4                 |
| Compatibility  | 2.6.0               |
| License        | open source         |
| Edition        | public              |
| Inputs         |                     |
| Output         |                     |
| Language       | da                  |
| Case Sensitive | True                |
| Dependencies   |                     |




{:.h2_title}
## Data Source
  
Visit [this]() link to get more information
