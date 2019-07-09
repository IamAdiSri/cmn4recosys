# Collaborative Memory Network for Recommendation Systems

**_Ebesu, Shen, Fang - The 41st International ACM SIGIR Conference on Research & Development in Information Retrieval - SIGIR '18_**

[Link to paper.](https://arxiv.org/pdf/1804.10862.pdf)

[This](https://github.com/IamAdiSri/cmn4recosys) repository by [**Aditya Srivastava**](https://github.com/IamAdiSri/) is a PyTorch port to the original TensorFlow [project](https://github.com/tebesu/CollaborativeMemoryNetwork).

### Running the Collaborative Memory Network

1. Start a Jupyter server and open the notebook. 
2. Run the cells starting at the top and moving downwards.
3. **Pretraining the network is optional**; pretrained embeddings have been provided already in `pretrain/`.

### Requirements
* Python 3.6
* Jupyter
* PyTorch
* Matplotlib


### Data Format

The structure of the data in the npz file is as follows:

```
train_data = [[user id, item id], ...]
test_data = {userid: (pos_id, [neg_id1, neg_id2, ...]), ...}
```

### Acknowledgements

My, thanks to Travis Ebesu, author of the paper linked above, for helping debug the project and clear up any questions I had about the Tensorflow implementation.

### Issues

Please feel free to contact me/raise an issue in case of any quesations/bugs.