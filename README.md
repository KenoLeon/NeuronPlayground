# NeuronPlayground
### A simple Kivy based interactive/realtime neuron playground.

![Neuron playground](img/neuron_playground.PNG)

# What is this thing ?

I built this neuron playground as a proof of concept for a bigger project back in 2016, the idea is to represent biological neurons and their basic interactions in real time.

# Basics :

You can start by placing some neurons and hitting the play/stop button:

![Place_neurons](img/place_neurons.gif)

These neurons (the circles) have a base neurotransmitter level (the grey color fill) and fill up until they discharge an action potential the rate is fixed for simplicity but in real life can vary.

You can then connect the neurons :

![Connect_neurons](img/connect_neurons.gif)

Connection weights can be changed per connection but are static (once more for simplicity), in real life they change based on the inputs (here we just have a basic oscillation per neuron ). connections propagate when the neurons fire and are indicated in white, the connection weight is also indicated by the thick part of the connecting line.

You can choose excitatory (red) or Inhibitory (blue) connections :

![Inhibit_neurons](img/inhibit_neuron.gif)

Here 3 inhibitory neurons synapse with another neuron that won't fire anymore, you can play with NT levels and conn weights

# Running and packaging :


TK
