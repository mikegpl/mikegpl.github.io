---
layout: page
title: Introspector
permalink: /introspector/
---

Introspector provides feedback to study participants in organized and safe way.
Introspector flow consists of three parts:

0. Gathering the questionnaire data from given storage - this might be [Google Sheets](https://docs.google.com/spreadsheets/), other publicly available 
spreadsheet service, or other data storage exposing an API, like a SQL or no-SQL database.

0. Calculating the feedback data - you can either provide a data source for `Introspector` to retrieve the feedback, or provide a way of calculating the feedback. 

0. Sending the feedback to the participants - this is done via integration with external SMTP server. You can specify your own message template using [Jinja templates](https://jinja.palletsprojects.com/en/3.1.x/) or use default ones.

`Introspector` can be deployed:

- on your machine,
- in our secure Google-cloud based deployment. 

In accordance to data protection rules, no personal data is stored within the `Introspector`. If you would like to use `Introspector`, contact us via [contact form](https://forms.gle/SUJPRYJ86t3ZDEEK8)