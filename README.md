# Music Generation with Deep Learning
This project is part of my Extended Project Qualification, 2024. My formal writeup of this project can be found here as ```FINAL_Music_Generation_with_Deep_Learning_CJIN.pdf```

- An implementation of the backpropagation algorithm, used to train a deep neural network. This was done based on Michael Nielsen's derivation and code in his book "Neural Networks and Deep Learning" Chapters 1-2 (Nielsen, 2015). The network is defined in ```my_mnist_network.py```
- A deep neural network was used to predict the next notes in a Bach Chorale melody, given the previous notes. This is done in the notebook ```V2_JSB_chorales_network.ipynb```. This work is incomplete and may not be fully functional.

## Required Packages
Network: ```NumPy```, ```Matplotlib```
Chorales: ```pretty_midi```, ```music21``` 

## Files
- ```my_mnist_network.py``` defines the network's forward propagation mechanism and its backpropagation training process. 
- ```V2_JSB_chorales_network.ipynb``` loads and parses Chorale data from the ```JSB-Chorales-dataset```. We extract the top line and ignore the bottom 3 parts. We train the network, then test it. We can display the network's output in sheet music form or play the music itself. Finally, we visualise the network's output to explain the poor performance of the network.






