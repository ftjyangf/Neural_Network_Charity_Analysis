# Neural_Network_Charity_Analysis
# Project Overview
## Alphabet Soup has funded 34,000 organizations over years, Alphabet Soup wants to invest those money in a more efficient and selective way, so they are wondering if the Neural_Network can be used to predict is the money would be used efficiently by histocal funding data. 
## Data Processing 
### At first we want to clean all data which can be used by machine learning process. fortunately, the data is intact and ready for process. after checking all the features, we need to drop identitication number and names of the project, which provide little infomation for our analysis, then drop feature status, which has only 5 instance of inactive and 34000 active. using density plot to decide the threshold to group the small group of feature, we used those method on organization code,which is grouped by government and on application type. 
## Machine Learning
### Machine Learning we impoved a little on the model by drop features and re-grouping the features. for example droping status feature and regrouping the application type, we impoved the accuracy 0.4. intially we have 1 input layer, 1 hyden layer and 1 output layer. the number of neutrons for hyden layer is set to be the number of feature in our model,we tried different combination of activation function, such as 'relu','relu','tah', 'relu','relu','sigmoid', and 'tanh','relu','sigmoid'. 'sigmoid' is the best acitivation function for the out layer. 



