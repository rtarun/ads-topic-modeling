# topic-modeling

Topic Modeling using Spark LDA on NASA ADS

Testing on Reuters dataset for smaller tests
_____________________________________________________________________________________________________________________________

ADS API developer key from SAO/NASA ADS is requested here: https://docs.google.com/spreadsheet/viewform?formkey=dFJZbHp1WERWU3hQVVJnZFJjbE05SGc6MQ#gid=0
_____________________________________________________________________________________________________________________________

Running PySpark on Jupyter:

1. Set the paths from
[here](https://gist.github.com/tommycarpi/f5a67c66a8f2170e263c)

2. And then run IPYTHON_OPTS="notebook" pyspark
inside $SPARK_HOME 

Alternative:

export SPARK_HOME="/Users/tarunruchandani/Desktop/HarvardSummer2016/spark-1.6.1"
cd $SPARK_HOME
IPYTHON_OPTS="notebook" ./bin/pyspark

_____________________________________________________________________________________________________________________________

- Extract papers using ADS API
- Verctorize these papers, and generate a term-document matrix
- Run Spark-LDA
- Build JS Matrix
