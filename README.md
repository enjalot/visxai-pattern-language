# Towards a pattern language for visualizing AI

This is an attempt to start cataloging design patterns for visualizing AI. These patterns are introduced in [these talk slides](https://docs.google.com/presentation/d/1h8pubQ4v8cZelU72wvAjvg4566rxa0p93U6eQ9x_OmU/edit#slide=id.p) with screenshots and GIFs. The goal of this document is to add to the language and enrich the patterns with more detailed information and examples. 

Help us collect good examples of these patterns and sharpen their definitions. Feel free to open an issue or pull request!

## Why a pattern language?
TODO summarize introduction from talk on design & development challenges

## Content
These patterns are concerned with representing concepts that show up repeatedly in AI.

### Architecture
TODO

### Activations
**The outputs of the activation function for each neuron.**  
TODO further describe & add more examples

Examples: 
* https://distill.pub/2018/building-blocks/

### Weights
**The strength of connections between neurons.**  
TODO further describe & add more examples 

Examples: 
* https://distill.pub/2020/circuits/visualizing-weights/

### Attention
**It's all you need.**  
TODO further describe & add more examples

Examples: 
* https://distill.pub/2016/augmented-rnns/


### Parameter spaces
**Show how parameters change together.**  
We rarely are interested in a single parameter in isolation. When possible allow exploration of the possibility space created by multiple parameters.

Examples: 
* https://distill.pub/2017/momentum/
* https://jgoertler.com/visual-exploration-gaussian-processes/

### Graphs
**Nodes and links, objects and connections, entities and relationships.** 
Examples:  
* https://distill.pub/2021/gnn-intro/
* http://www.shawnfarris.io/research/graphicalDataRepresentations/


## Context
These patterns are concerned with clarifying our communication. Keep in mind that all of the patterns in this category work just as well in static media like PDFs. It is still important to call them out explicitly because when they are combined with the patterns in the Choice categories it opens up a whole new world of possibilities.

### Annotation

### Text integration
**Connect written words with figures directly via color, location and hyperlinks.**  
When describing concepts in text, link their representations visually via thoughtful layout and consistent use of color. When describing interactions, hyperlink the text to the figure, making a linked view.

Examples:  
* https://distill.pub/2017/momentum/
* https://introduction-to-autoencoders.vercel.app/
* https://nipunbatra.github.io/hmm/
* https://observablehq.com/@clpuc/analyzing-the-design-space-for-visualizing-neural-attenti
* https://observablehq.com/@observablehq/text-color-annotations-in-markdown
* https://theo-jaunet.github.io/MemoryReduction/

### Aggregation
**Aggregate sparingly.**  
The nature of AI work involves large quantities of data and high dimensions. The most practiced method of reducing complexity is via aggregation. Aggregation destroys context quickly by hiding actual data behind invisible computation.  
When possible, link views between aggregations and underlying data points.

Examples:
* https://distill.pub/2020/circuits/visualizing-weights/
* https://distill.pub/2018/building-blocks/

### Dimensionality reduction
**Reduce dimensions carefully and consistently.**  
Dimensionality reduction can be a powerful way to make high dimensional data accessible.  
Use with caution, combining with other patterns can help with clarity.

Examples: 
* https://distill.pub/2016/misread-tsne/
* https://tiga1231.github.io/umap-tour/
* https://distill.pub/2020/grand-tour/

### Small multiples
**Show many facets of the same data with small multiples.**  
A common technique in static figures, small multiples can be even more powerful with linked views.

Examples:  
* https://distill.pub/2020/grand-tour/

### Slow build
**Build up context slowly, introducing concepts and interactions piece by piece.**  
Complex games, simulations and interactive visualizations can be overwhelming without proper orientation.

Examples: 
* https://distill.pub/2021/gnn-intro/
* https://aatishb.com/entropy/
* https://theo-jaunet.github.io/theo-guesser/
* https://ncase.me/polygons/



## Choice
The differentiating patterns of dynamic media are about giving readers a choice. 

### Examples
**Allow readers to choose from examples.**
Letting the reader compare and contrast the differences between examples allows them to build their own intuition for how those differences come about.
Use representations and affordances to give a preview of what the user can expect when choosing on an example.

Examples:
* https://theo-jaunet.github.io/theo-guesser/
* https://distill.pub/2018/building-blocks/

### Games
**Build intuition by framing choices as a game.**  
Games can be a powerful way to form intuition of a system.  
By encouraging readers to step into the shoes of the algorithm they can better understand the power and the challenges behind it.

Examples: 
* https://www.pewresearch.org/interactives/how-does-a-computer-see-gender/
* https://interactive-maml.github.io/

### Playback

### Affordances

### Linked views
**Setup interactions with one figure to change the contents of another figure.**  
A powerful way of demonstrating the impacts of certain choices is by linking them to 
Linked views are often used with small multiples, dimensionality reduction and aggregations.

Examples: 
* https://distill.pub/2018/building-blocks/
* https://theo-jaunet.github.io/MemoryReduction/
* https://www.ruthfong.com/projects/interactive_overlay/

### Inputs

### Object constancy


## Environment
These patterns help us organize our thoughts across different programming and computing environments.

### Kernel

### Browser

### Package management
**Know how to download code other people wrote.**  
Leveraging community code is a huge factor in building any software. Python has pip and anaconda, JavaScript has npm and yarn. 
Knowing where packages get installed and how to resolve version conflicts can save hours of your life.

### Data serialization

### File management

### APIs
---
TODO: replace URLs with their article titles
