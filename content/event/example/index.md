---
abstract: "The new crown epidemic (Covid-19) is a major event in the world that
  can involve all human lives since World War II. Since the outbreak of the new
  crown epidemic in Wuhan, China in 2019, the global economy and politics have
  been affected to a certain extent. In order to respond to the epidemic, health
  organizations in many countries have used machine learning and other methods
  to carry out relevant forecasting studies to predict the number of future
  diagnoses based on historical data, and use this as a basis to improve the
  accuracy of the deployment of medical resource plans. However, most of the
  existing new crown prediction models are based only on the single feature of
  historical confirmed number data, and do not incorporate some richer regional
  characteristics: the intensity of epidemic prevention measures, regional
  population economic data, and such constructions. The effect of the model
  method is often not good enough. In order to solve the above problems, we
  proposed a multi-feature hybrid coding model for predicting the number of
  confirmed diagnoses of the new crown to integrate regional features to improve
  the model's ability to predict future diagnoses. In order to achieve this
  goal, we have carried out hierarchical and classified feature coding on the
  characteristics of prevention and control measures. By dividing the prevention
  and control measures into ten categories and four intensity levels, we can
  quantify the time sequence of prevention and control measures taken in each
  region. In the prediction fitting, we adopted the huber regression model to
  reduce the sensitivity of the model to data outliers. We tested our method on
  the data set of CHIP2020 Evaluation 4, and the average MAPE index in three
  typical regions is 0.2061, reaching the best result of the evaluation, showing
  the effectiveness of our method. Furthermore, we conducted an explanatory
  analysis of the model and found that among the ten types of measures, two
  types of measures, restrictions on private gatherings and restrictions on
  public places, have a significant effect on controlling the epidemic. In this
  study, we constructed a new crown diagnosis prediction model that combines
  time series and regional features. The superior results on real data from
  CHIP2020 prove the effectiveness and practicality of our model. At the same
  time, we also obtained two types of important prevention and control measures
  through explanatory analysis of the model, and this conclusion can assist
  relevant health organizations in making decisions. "
slides: ""
url_pdf: ""
summary: An example talk using Wowchemy's Markdown slides feature.
title: "2020chip Conference Oral Report: COVID-19 predicting based on Huber
  Regression and Hierarchical Encoding"
location: Online
date: 2020-11-01T13:00:00.000Z
date_end: 2020-11-02T15:00:00.000Z
all_day: false
event: "2020 chip Conference Oral Report "
event_url: https://www.bilibili.com/video/BV185411574p?p=52
featured: false
authors: []
url_video: ""
url_slides: ""
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: "94305"
  country: United States
links:
  - name: Result
    url: http://www.cips-chip.org.cn/2020/eval_result
  - url: files/ppt_chip.pptx
    name: PPT
publishDate: 2021-04-16T06:11:59.997Z
tags: []
projects:
  - CHIP2020
image:
  caption: ""
  focal_point: CENTER
  filename: featured.jpg
url_code: ""
---
{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}