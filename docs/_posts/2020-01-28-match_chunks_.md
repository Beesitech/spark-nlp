---
layout: model
title: Match Chunk
author: John Snow Labs
name: match_chunks
class: Pipeline
language: 
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
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/public/models/match_chunks_en_2.1.0_2.4_1580246868138.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python
model = PretrainedPipeline.downloadPipeline("match_chunks","","public/models")

model.annotate("The patient had stomach pain and high fever")
```

```scala
val model = PretrainedPipeline.downloadPipeline("match_chunks","","public/models")

model.annotate("The patient had stomach pain and high fever")
```
</div>



{:.model-param}
## Model Information
{:.table-model}
|----------------|--------------|
| Model Name     | match_chunks |
| Model Class    | Pipeline     |
| Dimension      | 2.4          |
| Compatibility  | 2.1.0        |
| License        | open source  |
| Edition        | public       |
| Inputs         |              |
| Output         |              |
| Language       |              |
| Case Sensitive | False        |
| Dpendencies    |              |




{:.h2_title}
## Data Source
  
Visit [this]() link to get more information
