# Running LightGCN on MovieLens100K and Douban (with modification)

To reproduce these results, follow the instructions below:

1. Set up a virtual environment and install the packages in "requirements.txt"
2. Navigate to the "douban-lightgcn.ipynb" notebook. This script is for running LightGCN architecture on the Douban dataset. To modify hyperparameters/configurations, there is a "config" object in cell 4 of the notebook. There, you can modify the batch size, number of samples per user, epochs, and more. There is also a boolean variable called "use_edge_weights" which determines whether the LightGCN attention modification is made or not. To switch off the modification, set this variable to 'False'.
4. Navigate to the "movielens-lightgcn.ipynb" notebook. This script is for running LightGCN architecture on the MovieLens100K dataset. The same configuration options apply as in the "douban-lightgcn.ipynb" notebook.

