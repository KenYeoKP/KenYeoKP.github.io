---
layout: post
title: Data wrangling from video text track (.vtt) format
categories: Data Wrangling
---

### Turning Zoom VTT files into insightful visualisation

#### *A Data Wrangling Project*

I'm excited to share a recent data wrangling project I worked on showcasing the power of integrating Python, SQL, and R for transforming raw data into meaningful visual insights. The project focused on converting Zoom's VTT (video text track) files from a recorded lecture into a visual representation using R to determine how much airtime each student contributed during the class.

The journey began with extracting the data from the VTT file. Using Python, to parse the VTT format and convert the time-stamped text into a SQL table. This involved leveraging libraries like ‘pymysql’ and ‘pandas’ to create and manage the tabular data.

With the data in a table format, it became possible to calculate the length of time (in milliseconds) associated with each entry in the vtt table. Finally, the processed data was imported into R for visualisation. Using R’s powerful ‘ggplot2’ library, I created a horizontal bar chart highlighting the accumulated airtime of each student who spoke up in class.

<a  style="font-weight:bold" href="https://KenYeoKP.github.io/mystuff/3-Data-Wrangling/">Data Wrangling</a>

![Rplot03](https://github.com/KenYeoKP/KenYeoKP.github.io/assets/167163077/e00d5c3c-ef06-4520-beb9-16655e7edf3b)

