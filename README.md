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

export SPARK_HOME="<sparkhome>"
cd $SPARK_HOME
IPYTHON_OPTS="notebook" ./bin/pyspark

_____________________________________________________________________________________________________________________________

- Extract papers using ADS API
- Verctorize these papers, and generate a term-document matrix
- Run Spark-LDA
- Build JS Matrix
_____________________________________________________________________________________________________________________________

Visualization is [here](https://gist.github.com/rtarun/a2b64b95ba9d4c9fa6aa67a7da9fdbfe).

