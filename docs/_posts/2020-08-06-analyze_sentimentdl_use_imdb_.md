---
layout: model
title: Analyze Sentiment DL
author: John Snow Labs
name: analyze_sentimentdl_use_imdb
class: Pipeline
language: 
repository: public/models
date: 2020-08-06
tags: [pipeline]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 




{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/public/models/analyze_sentimentdl_use_imdb_en_2.5.0_2.4_1591608106144.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = PretrainedPipeline.downloadPipeline("analyze_sentimentdl_use_imdb","","public/models")

model.annotate("The patient had stomach pain and high fever")
```

```scala
val model = PretrainedPipeline.downloadPipeline("analyze_sentimentdl_use_imdb","","public/models")

model.annotate("The patient had stomach pain and high fever")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|------------------------------|
| Model Name     | analyze_sentimentdl_use_imdb |
| Model Class    | Pipeline                     |
| Dimension      | 2.4                          |
| Compatibility  | 2.5.0                        |
| License        | open source                  |
| Edition        | public                       |
| Inputs         |                              |
| Output         |                              |
| Language       |                              |
| Case Sensitive | False                        |
| Dpendencies    |                              |




{:.h2_title}
## Data Source
  
Visit [this]() link to get more information
