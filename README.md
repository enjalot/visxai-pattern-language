# Towards a pattern language for visualizing AI

This is an attempt to start cataloging design patterns for visualizing AI. These patterns are introduced in [these talk slides](https://docs.google.com/presentation/d/1h8pubQ4v8cZelU72wvAjvg4566rxa0p93U6eQ9x_OmU/edit#slide=id.p) with screenshots and GIFs. The goal of this document is to add to the language and enrich the patterns with more detailed information and examples. 

Pull requests welcome! 

## Why a pattern language?
TBD (summarize introduction from talk on design & development challenges)

## Content
These patterns are concerned with representing concepts that show up repeatedly in AI.

### Parameter spaces
**Show how parameters change together.**  
We rarely are interested in a single parameter in isolation. When possible allow exploration of the possibility space created by multiple parameters.

Examples: 
* https://distill.pub/2017/momentum/
* https://jgoertler.com/visual-exploration-gaussian-processes/




## Context
These patterns are concerned with clarifying our communication. Keep in mind that all of the patterns in this category work just as well in static media like PDFs. It is still important to call them out explicitly because when they are combined with the patterns in the Choice categories it opens up a whole new world of possibilities.

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


## Choice
The differentiating patterns of dynamic media are about giving readers a choice. 

### Linked views
**Setup interactions with one figure to change the contents of another figure.**  
A powerful way of demonstrating the impacts of certain choices is by linking them to 
Linked views are often used with small multiples, dimensionality reduction and aggregations.

Examples: 
* https://distill.pub/2018/building-blocks/
* https://theo-jaunet.github.io/MemoryReduction/
* https://www.ruthfong.com/projects/interactive_overlay/


## Environment
These patterns help us organize our thoughts across different programming and computing environments.

### Package management
**Know how to download code other people wrote.**  
Leveraging community code is a huge factor in building any software. Python has pip and anaconda, JavaScript has npm and yarn. 
Knowing where packages get installed and how to resolve version conflicts can save hours of your life.

