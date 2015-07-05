## global-bd-conf
* Code and datasets for the Spark workshop http://globalbigdataconference.com/52/santa-clara/big-data-developer-conference/schedule.html
* Big Data Track II, July 16 8AM-5:00PM

## Setup
1. Install Spark 1.4.x
2. Make sure you have a working Python setup. anaconda distribution is recommended
3. Make sure iPython is running fine (on it's own)
4. Download this repository to ../global-bd-conf.

    >I will keep this updated, as more materials are developed. Will definitely be current by cob 15th ;o)
5. cd ../global-bd-conf
6. Run iPython and pyspark

    >IPYTHON=1 IPYTHON_OPTS="notebook" ~/Downloads/spark-1.4.0/bin/pyspark --packages com.databricks:spark-csv_2.11:1.0.3
7. Use the right spark path. I have spark installed in ~/Downloads/spark-1.4.0/
8. Run the two initial notebooks 000-PreFlightCheck and the 001-TestSparkCSV
9. Now you are ready for the workshop !

>It could take sometime to get there - don't worry. _That is part of the learning._

## Workshop Outline
* The workshop will start with some Spark basics, move into DataFrames and then to wrangling with datasets
* The focus is on Data Science and data wrangling using Python
* Will try to have more discussions.
* If you have completed the edX/Berkeley CS100.1x and/or CS190.1x and have questions, come on over. But then some of the materials would be basic for you.
* A rough agenda
  1. Intro To Spark
    * Spark Yesterday-Today-Tomorrow
    * Spark Architecture
  2. Setup and PreFlight Check notebooks
  3. Spark DataFrames - An in-depth look
    * APIs, hands-on code
  4. Data Science Folk Knowledge - http://www.slideshare.net/ksankar/data-science-folk-knowledge
  5. Data Wrangling with DataFrames & MLlib
    * SQL Data
    * Titanic Kaggle competition
    * ...

### Preparation
* To prepare for the workshop, it would be good to go through the Spark Summit 2015 West Training materials [spark-summit-W2015-1] and [spark-summit-W2015-2]
* Brian and Sameer have done an excellent job
* The reference below has more materials - Tons of good materials from Paco Nathan

## Reference
### Intro
* [spark-summit-W2015-1] http://www.slideshare.net/SparkSummit/intro-to-spark-development
* [spark-summit-E2015-1] http://training.databricks.com/workshop/intro_spark.pdf
* [spark-intro] http://training.databricks.com/workshop/itas_workshop.pdf

### Intro++ (or Intro#)
* [spark-camp-01] http://training.databricks.com/workshop/sparkcamp.pdf
* [spark-summit-W2015-2] http://www.slideshare.net/SparkSummit/dev-ops-training
* [spark-visual-api] http://training.databricks.com/visualapi.pdf
* [spark-summit-E2015-2] http://training.databricks.com/workshop/datasci.pdf



