+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Compositional Memory"

# Project summary to display on homepage.
summary = "An overview of my approach to compositional memory."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "circular-convolution.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["vector-symbolic-architecture", "compositional-memory"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/compositional-memory-wide.png"
caption = "Compositional memory"

+++

I am attempting to develop a practical connectionist mechanism for compositional and analogical memory.
This is concerned with the ability to recognise and predict situations and objects 
in terms of the pattern of relationships between their component parts 
independently of the precise identity of the component parts.
Current standard connectionist techniques have limited capacity to deal with patterns of relationships 
and consequently have difficulty recognising novel configurations of familiar components 
or recognising familiar patterns of relationship when the components being related are novel.
Human analogical reasoning is the extreme example of the neural functionality I am striving for.
I believe that cognition is based on sensorimotor planning and that analogical retrieval is needed 
to allow the application of sensorimotor schemas to novel and abstract situations.
I argue that high-level perception and all cognition are fundamentally the same process 
and are implemented by this neural mechanism of compositional, analogical memory.

The memory mechanisms I am investigating are based on 
[Vector Symbolic Architectures](https://arxiv.org/abs/cs/0412059) (VSAs), 
Predictive State Representations (PSRs), 
and Map-Seeking Circuits (MSCs). 
**VSAs** are systems of distributed representations and operations on them 
in high-dimensional vector spaces. 
They enable the principled representation, storage, and manipulation of structured data (e.g. trees and graphs) 
in vector spaces of fixed dimension. 
Because VSAs are based on simple vector operations they can be readily mapped to a neural implementation. 
(See [Pentti Kanerva](http://www.rctn.org/vs265/kanerva09-hyperdimensional.pdf), 
and [Tony Plate]
(https://www.researchgate.net/profile/Tony_Plate/publication/2368481_A_Common_Framework_for_Distributed_Representation_Schemes_for_Compositional_Structure/links/0a85e53cad7bab6ee0000000/A-Common-Framework-for-Distributed-Representation-Schemes-for-Compositional-Structure.pdf) 
for related research on VSAs.)

Given VSA as the mechanism for representation and processing of representations, what should be represented? 
**PSRs** represent an agent’s state entirely in terms of observable experience 
(the temporal stream of the agent’s actions and observations), 
e.g. see [Richard Sutton](http://incompleteideas.net/Talks/McGill_2005.pdf) 
or [Michael James](http://ijcai.org/papers/1621.pdf).
A PSR represents the current state of the agent as a set of predictions of future experience 
(observations conditional on the agent’s actions). 
This makes PSRs directly relevant to sensorimotor integration and planning. 
Current PSR research has noted the desirability of composing multiple PSRs 
to allow the agent to exploit its knowledge in novel situations.

David Arathorn has proposed [**MSCs**]
(http://papers.nips.cc/paper/2936-a-cortically-plausible-inverse-problem-solving-method-applied-to-recognizing-static-and-kinematic-3d-objects.pdf) 
as a neurobiologically inspired mechanism for discovering/generating the composition of transformations 
that maximise the similarity between a cue and an item in memory. 
An MSC is a recurrent network that searches simultaneously over a space of transformations to apply to the cue 
and a space of memory items to be recalled in response to the transformed cue. 
The MSC is similar to attentional mechanisms 
that have been proposed for the construction of invariant perceptual representations 
(e.g. [Bruno Olshausen](http://redwood.berkeley.edu/bruno/papers/jneurosci93.pdf)).

The VSAs are the basic processing units, connected in recurrent circuits to form an MSC, 
with PSRs as the information processed by the system. 
My work can be construed as a generalisation of MSCs. 
Whereas Arathorn’s MSCs use localist representations and a fixed palette of geometric transformations, 
my objective is to use distributed connectionist representations 
and arbitrary systematic substitutions as the transformations. 
Using VSAs as the primitives from which the MSC is constructed 
allows the distributed connectionist representation and manipulation of composite structures (such as PSRs). 
One extremely useful feature of VSAs is that the representations can be applied as substitution operators 
to transform other representations. 
This opens the way for transformations to be composed on the fly by the MSC. 
I am also attempting to generalise the MSC by allowing it to recall multiple items simultaneously (rather than only one)
and to find transformations between recalled items 
(rather than only between a cue and a recalled item). 
This would allow the recognition of novel composite objects and situations in terms of familiar components 
and the discovered relationships between them.
