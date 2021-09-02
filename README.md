# Extracting Alarm Events from the MIMIC-III Clinical Database

The script in the repository are supplementary material for the eponymous publication.

`create_clean_chartevents.ipynb` is a Juypter notebook showing step-by-step how the data set (i.e., the `CHARTEVENTS` table in MIMIC-III) is cleaned.

`generate_alarm_data.py` is the Python script that extracts alarm events from the `CHARTEVENTS` table by crossreferencing vital parameters measurements and alarm thresholds.
