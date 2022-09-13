---
title: JiaotongUniv
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2022-09-13'
author-meta:
- Mulin Wan
- Jingwen Yao
- Yunze Guo
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="JiaotongUniv" />
  <meta name="citation_title" content="JiaotongUniv" />
  <meta property="og:title" content="JiaotongUniv" />
  <meta property="twitter:title" content="JiaotongUniv" />
  <meta name="dc.date" content="2022-09-13" />
  <meta name="citation_publication_date" content="2022-09-13" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Mulin Wan" />
  <meta name="citation_author_institution" content="CEE, University of Illinois Urbana-Champaign" />
  <meta name="citation_author" content="Jingwen Yao" />
  <meta name="citation_author_institution" content="CEE, University of Illinois Urbana-Champaign" />
  <meta name="twitter:creator" content="@Yaojune" />
  <meta name="citation_author" content="Yunze Guo" />
  <meta name="citation_author_institution" content="CEE, University of Illinois Urbana-Champaign" />
  <link rel="canonical" href="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/" />
  <meta property="og:url" content="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/" />
  <meta property="twitter:url" content="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/" />
  <meta name="citation_fulltext_html_url" content="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/" />
  <meta name="citation_pdf_url" content="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/v/1598ab0d8703cb03353a3c70da4ddb4ec75325bf/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/v/1598ab0d8703cb03353a3c70da4ddb4ec75325bf/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/v/1598ab0d8703cb03353a3c70da4ddb4ec75325bf/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://uiceds.github.io/cee-492-term-project-fall-2022-jiaotonguniv/v/1598ab0d8703cb03353a3c70da4ddb4ec75325bf/))
was automatically generated
from [uiceds/cee-492-term-project-fall-2022-jiaotonguniv@1598ab0](https://github.com/uiceds/cee-492-term-project-fall-2022-jiaotonguniv/tree/1598ab0d8703cb03353a3c70da4ddb4ec75325bf)
on September 13, 2022.
</em></small>

## Authors



+ **Mulin Wan**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [mulin-wan](https://github.com/mulin-wan)<br>
  <small>
     CEE, University of Illinois Urbana-Champaign
  </small>

+ **Jingwen Yao**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [jingwenyaooo](https://github.com/jingwenyaooo)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [Yaojune](https://twitter.com/Yaojune)<br>
  <small>
     CEE, University of Illinois Urbana-Champaign
  </small>

+ **Yunze Guo**<br>
    · ![GitHub icon](images/github.svg){.inline_icon}
    [cyfcx2](https://github.com/cyfcx2)<br>
  <small>
     CEE, University of Illinois Urbana-Champaign
  </small>



# Abstract

## Introduction

### Title of the project

#### Bike-Share Usage in London Network Analysis

### Description

#### Dataset:

For this project, we are going to combine the data from two datasets. The first one is 'London and Taipei Bike-Share Data', and the second one is London bike sharing dataset. 

#### London and Taipei Bike-Share Data

The raw data is collected from the respective cities open data sites. 

[London](https://cycling.data.tfl.gov.uk/) 

[Taipei](https://data.taipei/#/dataset?topic=topic-transportation)

The data has been reformatted into CSV in order to be easier to use and compare. The content is unchanged. This gives the columns in the data comprise:

##### 1.rental_id - id of people who rent the bike

##### 2.duration - duration of rental

##### 3.bike_id - id of bike

##### 4.end_rental_date_time - date and time of end rental

##### 5.end_station_id - id of end station

##### 6.end_station_name - name of end station

##### 7.start_rental_date_time - date and time of start rental

##### 8.start_station_id - id of start station

##### 9.start_station_name - name of start station

#### London bike sharing dataset

This dataset runs from 4th January 2015 to 3rd January 2017 and reports total bike hire numbers for a bike rental scheme in London, England, alongside some weather info.

The data has been formatted into CSV in order to be easier to use and compare. This gives The columns in the data comprise:

##### 1.mestamp - timestamp field for grouping the data

##### 2.cnt- the count of a new bike shares

##### 3.t1 real temperature in C

##### 4.t2 - temperature in C "feels like"

##### 5.hum - humidity in percentage

##### 6.windspeed - wind speed in km/h

##### 7.weathercode - category of the weather

###### 1 = Clear ; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity

###### 2 = scattered clouds / few clouds

###### 3 = Broken clouds

###### 4 = Cloudy

###### 7 = Rain/ light Rain shower/ Light rain

###### 10 = rain with thunderstorm

###### 26 = snowfall

##### 8.isholiday - boolean field - 1 holiday / 0 non holiday - refers to bank holidays

##### 9.isweekend - boolean field - 1 if the day is weekend / 0 if a working day

##### 10.season - category (0-spring; 1-summer; 2-autumn; 3-winter)

In addition to season and isweekend, from the timestamp feature we can extract many separate time features - day of the week (as one scaled column or as seven columns of ismonday, istuesday etc.), month number, day of the month, week number, hour, minute. In combination with external data, we could add islight for after dawn times and is_schoolholiday to match London school holiday times.

#### Link of dataset:

[London and Taipei bikeshare](https://www.kaggle.com/datasets/ajohrn/bikeshare-usage-in-london-and-taipei-network)

[London bikeshare](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/discussion?resource=download)

### Proposal

Recently, bike-sharing in big cities has become an important part of residents' daily life, which plays a significant role in urban transportation system. The data is spatiotemporal, in other words, it varies over space and time. That variation can be explored, described, and modeled in many different ways. The overlap of two datasets shows many factors affecting residents' bike-renting behavior.

Previous work has shown that weather is a key driver for variation in usage. By utilizing those datasets to analyze how extreme weather events like winter rains in London will affect bike-sharing system, it is safe to draw some conclusions to guide the process of making contingency plans. The locations of start-trip and end-trip is also considered to have the potential of revealing hot spots of bike-renting usage.

The result will be able to offer some suggestions for the decision maker of bike-sharing companies about the arrangement of bike density in different blocks, distribution between urban and rural areas and methods to tackle extreme weather conditions.


## This is an introduction

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
