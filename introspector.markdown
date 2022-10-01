---
layout: page
title: Introspector
permalink: /introspector/
---

Introspector is an app that can be used for providing feedback to study participants in organized and safe way.
Introspector flow consists of three parts:

0. Scraping the questionnaire data from given data storage - this might be [Google Sheets](https://docs.google.com/spreadsheets/), other publicly available 
spreadsheet service, or other data storage exposing an API, like a SQL or no-SQL database. This can be configured using main `Introspector` config file.

0. Calculating the feedback data - you can either provide a data source for `Introspector` to retrieve the feedback, or provide a way of calculating the feedback. This can be configured using main `Introspector` config file.

0. Sending the feedback to the participants - this is done via integration with external SMTP server. You can specify your own message template using [Jinja templates](https://jinja.palletsprojects.com/en/3.1.x/) or use existing, default ones.

`Introspector` can be deployed on your own VM (requires Docker engine) as well as in our secure cloud environment. In accordance to data protection rules, no personal data is stored within the `Introspector`.