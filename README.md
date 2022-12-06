# Bagging
Bagging is the term from "Bootstrap Aggregation Algorithm", That is for Low Bias &amp; Low Variance

# Introduction
The statistical method known as Bootstrap Aggregating, or "bagging," is a type of ensemble techniques. ensemble learning techniques are commonly used to reduce variance within a noisy dataset. This approach is used to improve classification by combining classifications of randomly generated dataset.

# History
Bootstrap Aggregating was proposed by Leo Breiman in 1994, who was statistician and had done many research on statistics. It was derived from the concept of bootstrapping which was developed by Bradley Efron

# Algorithm
    =>Input the Dataset D.

    =>Let k be the number of bootstrap samples.

    =>for i = 1 to k do

       =>Create a bootstrap sample of size n , 𝐷_𝑖 (n < D).

       =>Train the Base Classifier 𝐶_𝑖 on the bootstrap sample 𝐷_𝑖.

    =>end for

    =>𝐶^∗(x) = argmax Σ_𝑖 𝛿(𝐶_𝑖(x = y)). {𝛿(.) = 1, if its argument is True and 0 otherwise}



# Flowchart
![image](https://user-images.githubusercontent.com/109208035/205918502-40f9cb7b-b9bd-42f9-9ffc-4cd0252b18e0.png)

# Mathematical Model!
![image](https://user-images.githubusercontent.com/109208035/205919451-0a8598d0-d264-4ab6-bc6d-6c6d02846e29.png)

# Program Results in term of graph
BY increasing NO of Trees
![image](https://user-images.githubusercontent.com/109208035/205919961-432f093e-6e9a-49bc-9c9b-a2b99004fd62.png)


Final Output after Bagging Procedures
![image](https://user-images.githubusercontent.com/109208035/205920200-4bb0b717-79d1-4bfd-be70-a83995d48469.png)


