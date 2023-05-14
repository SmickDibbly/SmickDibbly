I'm a hobbyist programmer interested in C and software renderers. I am fascinated by Binary Space Partitions and Constructive Solid Geometry, and hope to some day contribute to the theory or applications thereof.

# Self-imposed constraints
A lot of my code has restrictions that are self-imposed, for no reason other than to facilitate deep understanding. These include:
- Minimal use of compiler-specific extensions. I try to write pedantically C99-conforming code.
- Minimal use of floating point types. I rather prefer fixed-point integer arithmetic because it forces me to very carefully understand complicated computations.
- No math.h from the C standard library (nor any external math library whatsoever).
- For graphics, I prefer software rendering just like ye olden days of yore.

See [LMP88959](https://github.com/LMP88959) for another programmer who works under similar constraints.

All of these constraints are rooted in the desire to *deeply* understand *every* piece of code I write. For example, by forbidding the use of any math library I am forced to learn about many approximation techniques that I would otherwise just take for granted.

I'm not *too* strict about always adhering to all of the above constraints. Often I start with whatever can be written quickest, and then later go back and make it conform to my constraints. 

<!---
SmickDibbly/SmickDibbly is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
