<h1> Batch Learning / offline learning </h1>

Batch learning represents the training of machine learning models in a batch manner. The data get accumulated over a period of time. The models then get trained with the accumulated data from time to time in a batch manner.  In other words, the system is incapable of learning incrementally from the stream of data. The fact that the model is  with a lot of accumulated data takes a lot of time and resources (CPU, memory space, disk space, disk I/O, network I/O, etc.). Batch learning is also called offline learning. The models trained using batch learning are moved into production only at regular intervals based on the performance of models trained with new data.  

If the models trained using batch learning needs to learn about new data, the models need to be retrained using the new data set and replaced appropriately with the model already in production based on different criteria such as model performance. The whole process of batch learning can be automated as well.

The disadvantage of batch learning is it takes lot of time and resources for re-training the model.

<h3>case</h3>
Here, each data set row is considered as a batch, that is, if you have a data set containing 1000 images, then each image is a batch (total 1000 batches), so the hyper parameters like weights and bias are updated after each row of the data set. 2. Batch gradient descent algorithm

<h3>Lazy learning</h3>
Batch learning is also called offline learning. The models trained using batch learning are moved into production only at regular intervals based on the performance of models trained with new data.

<h3>Disavantage</h3>

 - lots of data
 - hardware limitation
 - availability

<h3>Process of batch learning </h3>
 - 1-Train and Test model 
 - 2-test and deploy on server

when we neeed to update training we need to working model to stop and again train and then deploy.
