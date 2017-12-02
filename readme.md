## SCS-3250 TTC Project

Clean Up.ipynb contains the script that will generate ttc_delays_cleaned.csv from the `csv_originals/delays.csv` and other csv files in the root folder.

At the time of writing the following columns have been created/cleaned up:

1. *Station* is normalized but there are still ~100 more stations we can try to classify
2. *Line* is normalizd to match the meta data
3. *Bound* is normalized to N/S/E/W
4. *Code Description* has been created with the full code name, when avaibable.

The *Date*, *Time*, and *Station* columns were all fairly sane so no cleaning was done.

No real examination has been done on the Min Gap and Min Bound line yet.

Change here



