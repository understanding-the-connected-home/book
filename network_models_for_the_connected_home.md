# Network models for the connected home 

How do we handle connectivity in the connected home? This is not just a question of networking standards and protocols but also one of architecture: Which network model - or more concretely, which logical network topology - is the best fit?

## Network models are models of control

This is as much a philosophical question as one of maintenance and business models, and each model comes with its own strengths and weaknesses.

They also represent control in the literal sense, and hence power: Depending on the model, different actors (hardware manufacturers, software developers, standards) are allowed to have more or less power over the network - and hence our homes. Which makes this a key question.

## Master/slave

In a master/slave scenario, there's a centralized control unit (the master) that coordinates what's going on in the network. This could be built into the router or be a smart phone app. It's clearly top-down.

Apple tends to build this kind of architecture because it's easier to deliver a seamless experience if the whole system is integrated and hence under control. It's also a system that fosters lock-in: If nine devices are integrated into one system, it's harder to get a tenth from a different system into play.

## Hub and spokes

The hub and spokes model is a variant of the master/slave model in that it also has a central unit. It differs in that it theoretically allows for instructions to flow "upstream" towards the central unit. It's not _as inherently_ top down as the master/slave model.

Google's architecture tends to be also relatively centralized, but not quite as integrated as Apple's. So if we go by corporate stereotypes, this would most likely inform Google's approach.

## Mesh network

Then there's the mesh, the counterpoint to master/slave architecture in that is fully decentralized. Every node in the network helps distribute and coordinate the flow of data. This is what traditionally the open source community would favor. 

It is the most open in that new nodes can be added at any time, that every node has to strictly adhere to standards to play along but there is no central integrator at play. A mesh or peer-to-peer style architecture is both the messiest, and the most resilient.

Of course all of these are just theoretical models, so they can be implemented more or less "pure". Hybrids are possible and likely to happen.

## Key takeaways

- Network models are models of control and power, so choose wisely.
- Each model has its own strengths and weaknesses.

## Further reading

For a quick overview, see [Wikipedia's article on network topology](https://en.wikipedia.org/wiki/Network_topology#Topology)


