+++
title = "VSA: Vector Symbolic Architectures for Cognitive Computing in Neural Networks"
date = 2013-06-14T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ross W Gayler"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "Presentation given at The Redwood Center for Theoretical Neuroscience at UC Berkeley, 2013-06-14"
publication_short = "Redwood Center, UC Berkeley"

# Abstract and optional shortened version.
abstract = "This talk is about computing with discrete compositional data structures in analog computers. A core issue for both computer science and cognitive neuroscience is the degree of match between a class of computer designs and a class of computations. In cognitive science, it is manifested in the apparent mismatch between the neural network hardware of the brain (essentially, a massively parallel analog computer) and the computational requirements of higher cognition (statistical constraint processing with compositional discrete data structures to implement facilities such as language and analogical reasoning). Historically, analog computers have been considered ill-suited for implementing computational processes on discrete compositional data structures.\n\nNeural networks can be construed as analog computers -- a class of computer design with a long history, but now relatively unknown. Historically, analog computation had advantages over digital computation in speed and parallelism. Computational problems were cast as dynamical systems and modelled by differential equations, which was relatively straightforward for models of physical problems such as flight dynamics. However, it was far less clear how to translate computations on discrete compositional data structures such as trees and graphs into dynamical systems. This is especially true for problems where the data structures evolve over time, implying the need to rewire the analog computer on the fly. This is particularly relevant to cognitive science because new concepts and relations can be created on the fly, and under the standard conception of neural networks this implies that neurons and connections would be created impossibly rapidly.\n\nIn this talk I describe Vector Symbolic Architectures, a family of mathematical techniques for analog computation in hyperdimensional vector spaces that map naturally onto neural network implementations. VSAs naturally support computation on discrete compositional data structures and a form of virtualisation that breaks the nexus between the items to be represented and the hardware that supports the representation. This means that computations on evolving data structures do not require physical rewiring of the implementing hardware. I illustrate this approach with a VSA system that finds isomorphisms between graphs and where different problems to be solved are represented by different initial states of the fixed hardware rather than by rewiring the hardware. Graph isomorphism is at the heart of the standard model of analogical reasoning and motivates this example, although that aspect is not explored in this talk."
abstract_short = "In this talk I describe Vector Symbolic Architectures, a family of mathematical techniques for analog computation in hyperdimensional vector spaces that map naturally onto neural network implementations. VSAs naturally support computation on discrete compositional data structures and a form of virtualisation that breaks the nexus between the items to be represented and the hardware that supports the representation. This means that computations on evolving data structures do not require physical rewiring of the implementing hardware. I illustrate this approach with a VSA system that finds isomorphisms between graphs and where different problems to be solved are represented by different initial states of the fixed hardware rather than by rewiring the hardware."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project file in `content/project/`.
projects = ["compositional-memory.md"]

# Links (optional).
# url_pdf = "#"
# url_preprint = "#"
# url_code = "#"
# url_dataset = "#"
# url_project = "#"
url_slides = "https://sites.google.com/site/rgayler/home/2013-06-14%20Redwood%20V1.pdf"
url_video = "https://archive.org/details/Redwood_Center_2013_06_14_Ross_Gayler"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

# More detail can easily be written below using *Markdown* and $\rm \LaTeX$ math code.
+++
