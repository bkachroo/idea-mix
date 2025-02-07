# idea-mix 
## Overview
The aim is to simulate the process of combining ideas that humans do naturally, and manifests as creativity (see *Where Good Ideas Come From*, and *Creative Thinkering*). We start with a simple computational model of an idea as a Cellular Automata (CA) rule, using Wolfram Language on Mathematica. This process differs from evolutionary programming in that EP exists to find a solution to a specific problem, and remains within a defined solution set. This is an open-ended approach, where we combine algorithms/ideas/rules to find new and interesting and potentially useful behaviour. It also differs from the approach in *New Kind of Science* of enumerating through every rule of a given set, in that effective methods of combination will "jump out" of the set of current rules in unexpected ways. The other appeal of this approach is the possibility of efficiently mining the computational universe; the hope is that "good ideas" will combine to give other good ideas, saving the time of searching through every possible computational rule for interesting behaviour. This approach is very similar to the one used in higher math, where people combine interesting mathematical structures into new ones (ex. groups and commutativity into Abelian groups by taking the intersection/AND-ing the axioms) and then study that new structure's behaviour. 
## File Guide
The code, results and comments are contained in Mixing.nb, which can be opened/edited/run with Mathematica or Wolfram's free [Cloud Programming Lab](https://lab.open.wolframcloud.com/app/). Mixing.html is a compressed print of Mixing.nb with cruddier images.
## Results
View the results at LINK. One important one: combining two nearest-neighbour CA rules in series makes a new CA-rule, not part of the original set but of next-nearest neighbours! This process continues to infinity when you get a CA that uses every input cell to compute every output cell (discrete neural network).
## Next Steps
Build a bunch of functional building blocks of algorithms (ex. select index, cut array) and enumerate through their combinations and examine the resulting behaviours. One problem to solve is making sure no destructive combination occur (infinite loops, type errors), which requires choosing building blocks wisely (make sure they always fit together).
