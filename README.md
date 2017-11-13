<h1 align = "center">
Comment tracer un réseau de neurones en LaTeX ?
</h1>

Le notebook suivant permet la génération du code LaTeX nécessaire au tracé d'une architecture de réseau de neurones. 
<center>
<img src="https://raw.githubusercontent.com/PierreDesmet/Draw_neural_network/master/NN.png" width="600">
</center>

## Paramètres : 
- nb_features (le nombre de features, neurones à gauche du réseau)
- hidden_layers (liste contenant les nombres de neurones cachés, au centre du réseau)

Par exemple, l'image ci-dessus s'obtient avec 
```python
trace_neural_network(nb_features=4, hidden_layers=[6,6])
```

**Remarque** : L'ouput du réseau est unique (classification binaire).