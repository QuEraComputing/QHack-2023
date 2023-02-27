# QHack 2023 QuEra Challenge

This repository and README contain some resources that individuals participating in the [Hybrid Quantum-Classical Computing Challenge](https://github.com/XanaduAI/QHack2023#hybrid-quantum-classical-computing-challenge) in [QHack 2023](https://qhack.ai/).

## Pointers
 
Before diving into the resources below it's helpful to keep the following in mind:

* There is no expectation for hackers to submit to the hardware, everything can be developed through local simulators
* The simulators are constrained by the memory and processing power your computer has. Remember that linear growth in the number of atoms means exponential growth in memory!
  * To that end, in the __Literature__ section of this `README` there are system sizes that go beyond what simulators on your laptop/PC can handle. The papers are provided more as "food for thought" as well as a potential avenue hackers can investigate.

## Resources

### Tools

* [Bloqade.jl](https://github.com/QuEraComputing/Bloqade.jl) is QuEra's SDK for simulating neutral atom simulation/computation.
  * Bloqade is written in the [Julia](https://julialang.org/) Programming Language. If you come from a Python background you'll find the Julia syntax to be very familiar although there are some [differences worth being aware of](https://docs.julialang.org/en/v1/manual/noteworthy-differences/#Noteworthy-differences-from-Python). 
* [AWS Braket](https://github.com/aws/amazon-braket-sdk-python) is AWS's Python SDK that allows you to design and simulate quantum algorithms (including those for neutral atoms!) as well as access a broad range of hardware.
  * [Hello AHS: Run your first Analog Hamiltonian Simulation](https://docs.aws.amazon.com/braket/latest/developerguide/braket-get-started-hello-ahs.html#braket-get-started-analyzing-simulator-results) is a gentle introduction to using the Python SDK for neutral atom simulation
  * [AWS AHS Examples](https://github.com/aws/amazon-braket-examples/tree/main/examples/analog_hamiltonian_simulation) provide a greater variety of examples of what you can do with neutral atoms and the AWS SDK

### Literature

* The [Bloqade Documentation](https://queracomputing.github.io/Bloqade.jl/dev/) not only serves as a reference manual but also comes with a number of tutorials ranging from the basics ([the Rydberg Blockade](https://queracomputing.github.io/Bloqade.jl/dev/tutorials/1.blockade/main/])) to more advanced applications such as [the Maximum Independent Set Problem](https://queracomputing.github.io/Bloqade.jl/dev/tutorials/1.blockade/main/)
* The `state-preparation.md` file contains some helpful background, approaches, and literature on Quantum State Preparation
* The `Intro to QC with Neutral Atoms.pdf` file is a copy of the slides Pedro Lopes used for his QHack talk
* [Quantum optimization of maximum independent set using Rydberg atom arrays (S. Ebadi et al.)](https://www.science.org/doi/10.1126/science.abo6587)
* [Realizing quantum spin liquid phase on an analog Hamiltonian Rydberg simulator - AWS Quantum Technologies Blog](https://aws.amazon.com/blogs/quantum-computing/realizing-quantum-spin-liquid-phase-on-an-analog-hamiltonian-rydberg-simulator/)
  * A nice higher-level read that focuses on [this paper by G. Semeghini et al.](https://www.science.org/doi/10.1126/science.abi8794)
* [Probing quantum critical dynamics on a programmable Rydberg Simulator (A. Keesling et al.)](https://authors.library.caltech.edu/92399/11/1809.05540.pdf)
* [Probing many-body dynamics on a 51-atom quantum simulator (H. Bernien et al.)](https://www.nature.com/articles/nature24622)
* [Quantum Kibble-Zurek mechanism and critical dynamics on a programmable Rydberg Simulator (A. Keesling)](https://www.nature.com/articles/s41586-019-1070-1)