# Temperature prediction with Deep Neural Network


## Requirements
* Python 3.7.3
* Pytorch 1.2.0


## Dataset
The dataset is contains daily min and max temperature of Budapest from 2012 to 2018. 
The notebook have 3 kinds of model:
- Forecast for the next day
- Forecast for the 7. day after today
- Forecast for the 28. day after today

But the number of wich day is adjustable in the code after the "Get different type of dataset to different type of training" title

The repository is containing downloded HTML files from the weather website. At the beggining of the code we will make the parsing and the information extracting.

One line of the dataset is the following with the actual informations:
```
#month  max_temp  min_temp
 12     4.2       -1.5
```



## Run
You can run the training and test process from Jupyter Notebook. The training process contains the evaluation and the statistics plotting.

