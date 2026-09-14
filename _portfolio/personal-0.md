---
title: "The New York Times Besteller Lists Historical Viewer"
excerpt: "From a personal project making an automated data pipeline and Streamlit web app"
collection: portfolio
category: "personal"
---

This is a personal project I'm working on that includes both a data pipeline for collecting the regularly-updated NYT "Bestseller Lists" and storing it in a cloud Azure SQL database, and also a Streamlit web app that displays the data going all the way back to 2008. The data pipeline is written in Python under the hood, but uses a combination of Airflow and GitHub Actions for orchestration. It's scheduled to run every Thursday at 2AM PT. On the app side, the Streamlit app lets you view all the rankings sorted by list type and update cadence. I plan to add more features to the web app/dashboard soon.

Sometimes, I enjoy thinking of a particular time in my life and then using the app to see what books were ranked highly during that time period.

See the [webpage](https://nyt-bslists-viewer.streamlit.app/), or have a look at the [source code](https://github.com/canyenheimuli/nytbs_pipeline/tree/main).
