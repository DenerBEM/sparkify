# Sparkify

**Description:** *Predict the customer churn*

### :package: Libraries used:
`from pyspark.sql.functions import isnan, count, when, col, desc, udf, col, sort_array, asc, avg
`<br>
`from pyspark.sql.functions import sum as Fsum, max as Fmax`<br>
`from pyspark.sql.window import Window`<br>
`from pyspark.sql.types import IntegerType`<br>
`from pyspark.ml.classification import LogisticRegression, RandomForestClassifier, LinearSVC, GBTClassifier`<br>
`from pyspark.ml.evaluation import BinaryClassificationEvaluator, MulticlassClassificationEvaluator`<br>
`from pyspark.mllib.evaluation import MulticlassMetrics`<br>
`from pyspark.ml.tuning import CrossValidator, ParamGridBuilder`<br>
`from pyspark.ml.feature import MinMaxScaler, VectorAssembler`<br>
`from pyspark.ml import Pipeline`<br>
`import datetime`<br>
`import pandas as pd`<br>
`import seaborn as sns`<br>
`import matplotlib.pyplot as plt`<br>




### :muscle: Motivation for the project:
My motivation for this project was to learn a new tool (Spark) that nowadays is becoming more and more used due to the big data. 


### :open_file_folder: Files:
* License:<br>
I'm using MIT license

* Jupyter Notebook:<br>
Project-CRISP.ipynb

* README.md:<br>
It's where you are. It contains things about the project.
* Dataset:<br>
The file used in the work.

### :bar_chart: Results:

I had to predict if a user would cancel his service or not.
My final model had approximately 78% of accuracy.

### :boy: Author:
My name is Dener, I'm 25 years old, and I've studied Data Science since 2019, and I've been putting my knowledge in practice by doing some personal projects and publish them on GitHub.
I hope you enjoy reading my codes.

