neuron_play
===========

Thoughts about neural activity

 neurons = []                                                                                                                                                                                                                                                              
>>> for i in range(100):                                                                                                                                                                                                                                                       
...   neurons.append({"id":i}) 


>>> for n in neurons:                                                                                                                                                                                                                                                         
...   for ne in neurons:                                                                                                                                                                                                                                                      
...     connections.append({"from":n, "to":ne, "strength":random.random()})   

>>> layers = []                                                                                                                                                                                                                                                               
>>> for i in range(6):                                                                                                            
...   layers.append({"layer_id":i}) 
