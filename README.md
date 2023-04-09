# Introduction
This project focus on binary classification and multiclassification

# Software Requirmemts
Runing binary_full and multiclass has certain software versioning requirements.
* R 4.2.0 or greater

# Running binary_full
binary_full just uses the glm function with binomial family to fit the data to predict the values.
its performance based on the training data is showed as follow:

![Screenshot 2023-04-08 194956](https://user-images.githubusercontent.com/117102360/230747209-e7e4eab9-2698-4b88-84b0-699dc463c35c.png)

and the accuracy is 1.(don't need to improve the performance)

![Screenshot 2023-04-08 201842](https://user-images.githubusercontent.com/117102360/230747912-35893e3e-971b-4621-aee6-80d2eab810d7.png)


# Running multiclass
## baseline algorithm
the baseline algorithm of multiclassication just uses the svm function with cost = 10 to fit the data to predict the values.
its performance based on the training data is showed as follow:

![Screenshot 2023-04-08 201328](https://user-images.githubusercontent.com/117102360/230747789-9f375064-ed1e-4a7e-a97f-2cb5e6d3420b.png)

and the accuracy is 0.998455.

![Screenshot 2023-04-08 201409](https://user-images.githubusercontent.com/117102360/230747803-d55767b3-6847-46d7-8f22-25ea82d56f07.png)


## improvement
we can tune the cost parameter and this figure shows the relationship between the cost and the number of support vectors:

![Screenshot 2023-04-08 201655](https://user-images.githubusercontent.com/117102360/230747870-727faffe-435b-4289-86f9-e0f894cd78c5.png)
and then we choose the best model which is svm function with cost = 100. And the performance based on the training data is showed as follow:

![Screenshot 2023-04-08 200955](https://user-images.githubusercontent.com/117102360/230747702-9996e5d0-8905-41cf-9326-fef1925380f9.png)

and the accuracy is 1.

![Screenshot 2023-04-08 201842](https://user-images.githubusercontent.com/117102360/230747908-81c158df-bbaf-4793-8c28-fd7f68aef901.png)

# leaderboard performance
## task 1

## task 2

# further improvement
according to the results below, we can see that many variables are highly correlated. Thus, we can delete or merge some highly correlated variables into one new variable.

![Screenshot 2023-04-08 202507](https://user-images.githubusercontent.com/117102360/230748044-9b332eb9-0558-4a5e-8340-b29f65e7a941.png)

![Screenshot 2023-04-08 202525](https://user-images.githubusercontent.com/117102360/230748050-fbd8357d-9ad1-4f74-ac80-82c5600917ff.png)



