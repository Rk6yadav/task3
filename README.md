#Task3 given by vimal sr

Description:
1. Create contrainer image with install python, keras, numpy, pandas, ternsorflow etc.
2 Container starts the model training with startup of image.
3. Create job chaining of job1, job2, job3, job4, job5 job6with help of piplineing.
4. job1 will pull github repo when developer push repo to git hub.
5. job2 will check the type of program code, and start the regarding ML interpreter inside the container image.
6. job3 will train model and predict accuracy.
7. job4  if accuracy is less than 80% then modifiy the ML architecture.
8. job5 will retrain the model or notify the model trainied sucessfull.
9 job6 will check program running or not. if not it will restart image.
