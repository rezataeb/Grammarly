# Grammarly
Ping Analysis of Grammarly

In this project, I investigated app/product performance from various aspects such as Daily Active User, Retention Curve, Traffic Source Analysis, etc., during February 2016. 


On this page, I investigated app/product performance from various aspects such as the daily active user(DAU), retention curve, traffic source, and user analysis. The original dataset consists of around 4.8 million rows with 5 columns (date, timestamp, uid, utmSource, isFirst). The only attribute with NaN entires is ‘utmSource’ (1674386 NaN).
Before jumping into the main parts of the analysis, some initial investigations and pre processing were taken.

- Sort Based on Timestamp
- Remove Duplicates
- Remove [date/timestamp/uid] Combination Duplicates
- Handle Entires with More than One ‘isFirst’
- Check the Entries with Delayed First Time Occurrence Recorded
- Source Names Correction and Modification(this will be done at question three)
