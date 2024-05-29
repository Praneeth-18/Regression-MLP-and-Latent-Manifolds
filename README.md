# Regression-MLP-and-Latent-Manifolds

### Buisness Objective:

We need to update uber's fare prediction model, to account for inflation.

Assumption: We have dataset which includes data from 2009 to 2015 , and we synthetically generated data from 2016 to 2017. Each year the fair increase by certain amount, however based on our data which is only till 2017, we say the algorithm hasn't been updated since 2017, and we want to update the algorithm to account for it, so that uber can run its operations successfully in 2024.

Ourprocess: We have existing fare for trip, for each trip we will increase the fair price by 2.5% per year, this is what we expect the current rides to cost.

# Latent Classification Recommendation

### Business Narration:

Uber is currently just doing cars (back in 2015)
They decide to start doing bikes and compete with citibike(A leading electric bike player)
Based on citibike's data we plan to recommend Uber bikes to our customers when a trip customer is trying to take is very similar to citibike's trips.
