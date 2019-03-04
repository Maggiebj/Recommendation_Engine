# Recommendation_Engine
This project is to built  a recommendation system from [IBM Watson Community](https://dataplatform.cloud.ibm.com/community?context=wdp) user-articles interactions data .

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


# Installation<a name="installation"></a>
The jupyter notebook file should be run with python 3.X . 

# Project Motivation<a name="motivation"></a>
Built a recommendation system with rank based recommendations, user-user based collaborative filtering, and matrix factorization perdiction from IBM Watson Community user-articles interactions data for users.


# File Descriptions<a name="files"></a>
There are 1 python files implement the product.

Recommendations_with_IBM.html--The implementation of rank based recommendations, user-user based collaborative filtering, and matrix factorization perdiction


# Results<a name="results"></a>
Built the recommendation system making recommendation by rank based for new users(cold start), while making recommendations by user-user based collaborative filtering for old users(who had interactions of articles). We can also use SVD matrix factorization model prediction making recommendaions for old users. 

Further more we can evaluate the performance of the recommendation system by AB test or compare the SVD matrix factorization model prediction with the actually user-articles interactions according to recommendations.

# Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to [IBM Watson Community](https://dataplatform.cloud.ibm.com/community?context=wdp) for the data.And.[Udacity](http://www.udacity.com) for project design and instructions.
