# FedAvg_implementation
Simple implementation of the FedAvg algorithm and experiments

## How to Use
Change the experiment arguments (dictionaries) in the experiments section. It's easy to add other datasets or tasks to the code as well. The global section is to show that the FedAvg algorithm works as well as regular centralized training. I have not tested this code on larger models.

The main part is the training loops. In the local training loop function, a client trains their local model. In the federated training function, the overall training scheme is coordinated. Aggregation is done through the federated aggregation function, which is called at the end of every round in the federated training function.
