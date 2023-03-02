# hw_sim
Relatively simple hardware simulator

Here I want to create a gate-level simulator which can handle time-based circuit simulation.

It should, eventually, support a text-file description of said circuit. It should also allow scripted input settings and check that outputs are as expected. This is a work-in-progress and I fully expect it will morph as it ages, matures hopefully.

Initially, it needs to map gates to a class (or classes) and have a class for an event list which manages the above input script, output checks, as well as scheduled gate output changes after an appropriate propagation delay. With a little jittering of the delays, we can largely avoid the potential infinite loop where a given gate output is connected to it's input. I'm sure this will need to be revisited to avoid pitfalls encountered along the way.

Well, have fun watching me struggle through. :-)
