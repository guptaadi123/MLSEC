# ATTACK DETECTION ON RAW LOG DATA WITH HELP OF ML
* I would like to thanks **VIMAL DAGA SIR and his whole team** for helping and supporting us because of them we can learn this technology so easiy.
* In this article we have developed python scripts that can comapre ur labelled log file with sample data and predict who all are attacker and all that things
* in this label-raw-data.py is used to label raw data into labelled data after onece labelled data is save you can apply  decision-tree-classifier or logistic-regression-classifier to get predicion of logs
* I would also thanks my team mate Rohan  and nikhil who help me in doing this project.
* for label-raw-data.py use the following argument in cmd
# python label-raw-data.py -l ./raw-http-logs-samples/access.log -d ./labeled-data-samples/access.csv 
* for decision-tree-classifier use the following argument in cmd
# python decision-tree-classifier.py -t labeled-data-samples/access.csv -v labeled-data-samples/accessall.csv
* for logistic-regression-classifier use the following argument in cmd
# python logistic-regression-classifier.py -t labeled-data-samples/access.csv -v labeled-data-samples/accessall.csv
