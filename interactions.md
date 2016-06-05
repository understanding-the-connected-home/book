# Interaction layers

*Interactions in the connected home happen at two layers: human-readable and machine-readable. By "readable" we mean a human or machine can easily understand, modify and execute actions. With the rise of more complex computational systems, new layers of interaction may emerge.*

## Introducing interaction layers

Borrowing from the three-tiered Creative Commons licensing structure,[^1] we'd like to explore how interactions in the home can take place at different layers: 

* human-readable
* machine-readable
* new layers, i.e. environment-readable

Each of these layers require ways for humans, or machines respectively, to understand and modify what's going on. There's also a need for interpreting across these layers, so that humans and machines can negotiate preferences and commands as well as resolve conflicts that arise.

## Understanding "readability"

We use the term "readability" as shorthand for the broader ability to read, write and participate fully. That encompasses the ability to view the source of an interaction, to comprehend what's going on, to modify and execute it.

## Human-readable layer

The human-readable layer contains interactions that humans can read and modify.

The purpose of this layer is for humans, regardless of their technical proficiency, to feel confident in understanding what a connected object or service can do, and where desired, modify or opt out of it. 

As much as possible, this layer should convey things in simple iconography or text, or in ways that are intuitive and build on behaviors that humans are already familiar and comfortable with. Accessible control over machines is essential for people to live confidently and with dignity in their home. 

The human-readable layer is how humans can readily tailor digital services and objects to their own needs. Through this power, people can invent new and unanticipated things, inspired by their local contexts and use cases. In this way, readability provides an important path to both user empowerment and grassroots innovation. 

### Designing the human-readble layer

As the home becomes more connected, we have to ensure it remains human-readable. 

Here are some considerations as we design and implement this layer: 

1. How can connected objects or "invisible" digital services communicate what they request users to do, without being intrusive or disempowering?

2. How do connected environments convey their level of connectivity as well as mechanisms for opting out or for better controlling participation?

3. How can humans be guided and advised for their protection, for example against the installation of malicious software or a device violating their tracking preferences? 

4. How can a human's digital preferences, such as preferred temperature or Do Not Track settings, travel with them and be controlled by them depending on the context?

5. How do these interactions change depending on the context, such as being someone's house guest or having a roommate? 
 

![icons](https://raw.githubusercontent.com/understanding-the-connected-home/book/master/img/icons.png)

_A blunt approach to human-readable interactions. A set of icons that indicate what is collecting data, what is transmitting data, what is analyzing data. "Does this thing listen or watch? Does it share data to the cloud?"[^2]_

## Machine-readable layer

As connected devices enter the home, it is beneficial if the machines can talk to each other to some degree. That means there will need to be a layer of interpretation and interaction that is optimized for machines (such as APIs, etc.). 

Typically, this kind of layer is hard for a human to read. Nevertheless, by organizing and structuring data following certain conventions,[^3] machines can read it effectively and that information can then be translated into a more human-readable form. 

There is a lot of technical work to be done designing this layer well. Through decades of developing network technology and international standards, there are established tactics for building interoperability among machines and their data.  

If done correctly, the machine-readable layer can be incredibly powerful. However, since it is hard for most humans to read it directly, we need to ensure that there are ways to trust and verify what is happening at the machine-to-machine level even for non-experts. That way devices can honor what the user wants and cooperates well with other devices, datasets and systems. 

## New layers?

Possibly, given the complexity and ubiquity of connectivity ahead, there will be new readability layers to consider. 

For example, as embedded systems fill a space with sensors, computation and coordination, does the resulting emergent system require the ability to read and modify the environment as a completely different level? 

Or do certain social relationships, such as neighborhoods or cities, gain the ability to read and write collectively? 

We're not sure what those new layers might be, but regardless there remains the need to have human-readable and machine-readable layers so that humans and machines respectively can understand the systems and engage in interaction.  

[^1]: Creative Commons licesening layers: [creativecommons.org/licenses](https://creativecommons.org/licenses)
[^2]: Images from the Noun Project. Eye by Thomas Le Bas ([thenounproject.com/search/?q=eye&amp;i=6186](https://thenounproject.com/search/?q=eye&amp;i=6186)), Ear by Søren Michelsen ([thenounproject.com/search/?q=ear&amp;i=6200](https://thenounproject.com/search/?q=ear&amp;i=6200)), and Cloud by Aaron K. Kim: ([thenounproject.com/search/?q=wifi&amp;i=123908](https://thenounproject.com/search/?q=wifi&amp;i=123908)).
[^3]: [en.wikipedia.org/wiki/Data_model](https://en.wikipedia.org/wiki/Data_model)
