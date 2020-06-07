# Quantum-information and -computing related Julia projects

This README is a list of [Julia](https://julialang.org/) projects, packages, and organizations
for quantum information science and technology and related fields,
such as condensed matter physics. It includes links to related lists and other resources.

If you would like to add a project to this list, please feel free to
[make a pull request](https://github.com/jlapeyre/JuliaQuantumInformation).
If you don't have time to make a pull request, please open an issue.

### Notes

* The names of these packages typically end in `.jl`.
  In particular, the suffix is included to distinguish packages from
  similarly-named non-Julia packages.
* The date of the most recent development activity appears just after the name of the package.
* Blurbs taken from the sites should be in italics (asterisks in markdown)
* Packages that support quantum information packages (e.g. tensor packages) are included here.
  Exactly where to cut this off is not clear.
* TODO: How to organize ? By organization for some software seems useful. Within orgs: alphabetically?, popularity? ...

### See Also

* [TutorialForPhysicists.jl](https://rogerluo.me/TutorialForPhysicists.jl/latest/toolchain/index.html) (11 2019) including lists
of packages for physics. The [gihub page](https://github.com/Roger-luo/TutorialForPhysicists.jl). The author says
1) this is out of date and 2) See [this](https://juliaphysics.github.io/latest/index.html).

## Organizations

### [BBN-Q](https://github.com/BBN-Q) ([BBN Technologies](https://www.raytheon.com/capabilities/products/quantum))

* [Cliffords.jl](https://github.com/BBN-Q/Cliffords.jl) (04 2020) - *Efficient calculation of Clifford circuits.*
* [QuantumTomography.jl](https://github.com/BBN-Q/QuantumTomography.jl) (05 2020) - *Quantum state- and process tomography.*
* [QGL.jl](https://github.com/BBN-Q/QGL.jl) (04 2018) - *A performance orientated QGL compiler.*
  This is a Julia reimplemenation of
  [QGL.jl](https://github.com/BBN-Q/QGL) (05 2020) (Quantum Gate Language), a python library.
* [MESolve.jl](https://github.com/BBN-Q/MESolve.jl) (05 2020) - *Master Equation Solver.*
* [QuantumInfo.jl](https://github.com/BBN-Q/QuantumInfo.jl) (04 2020) - *Library for quantum information related calculations.*
* [QSimulator.jl](https://github.com/BBN-Q/QSimulator.jl) (11 2019) - *Unitary and Lindbladian evolution.*
* [RandomQuantum.jl](https://github.com/BBN-Q/RandomQuantum.jl) (12 2019) - *Package for generating
  random quantum states and processes according to a number of natural distributions.*
* [PAPA.jl](https://github.com/BBN-Q/PAPA.jl) (12 2019) - *PAirwise Perturbative Ansatz for Better Estimation And Runtime.*
* [SchattenNorms.jl](https://github.com/BBN-Q/SchattenNorms.jl) (01 2019) - *Schatten norms,
  including completely bounded norms, such as Kitaev's diamond norm (ubiquitous in, e.g., quantum information processing*
* [MathieuFunctions.jl](https://github.com/BBN-Q/MathieuFunctions.jl) (03 2020) - For computing anharmonic quantum oscillator energies.

#### Quantum computing hardware

* [Qlab.jl](https://github.com/BBN-Q/Qlab.jl) (05 2020) - *Generic lab tools.*
* [Instruments.jl](https://github.com/BBN-Q/Instruments.jl) (05 2020) - *Instrument Control.*

### [QuantumBFS](https://github.com/QuantumBFS)
  *A group of quantum developers around Bao Fu Si (Temple).*

The QuantumBFS org maintains a mostly integrated set of about 20 packages for quantum computaion.
They are centered around [Yao.jl](https://github.com/QuantumBFS/Yao.jl).

* [Yao.jl](https://github.com/QuantumBFS/Yao.jl) (03 2020) - *Extensible, Efficient Quantum Algorithm Design for Humans.*
  [yaoquantum.org](http://yaoquantum.org/).

### [Jutho](https://github.com/Jutho) Jutho Haegeman's tensor code

* [TensorOperations.jl](https://github.com/Jutho/TensorOperations.jl) (05 2020) - *tensor contractions and related operations.*
* [WignerSymbols.jl](https://github.com/Jutho/WignerSymbols.jl) (02 2020) - *computing Wigner symbols and related quantities.*
* [LinearMaps.jl](https://github.com/Jutho/LinearMaps.jl) (04 2020) - *defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.*
* [TensorKit.jl](https://github.com/Jutho/TensorKit.jl) (05 2020) - *large-scale tensor computations, with a hint of category theory*

### [ITensor](https://github.com/ITensor)

* [ITensors.jl](https://github.com/ITensor/ITensors.jl) (05 2020) - *efficient tensor computations and tensor network calculations*
* [NDTensors.jl](https://github.com/ITensor/NDTensors.jl) (05 2020) - *n-dimensional sparse tensors.*
* [PEPS.jl](https://github.com/ITensor/PEPS.jl) (05 2020) - Projected entangled pair states.

### Quantum Optics ([QOJulia](https://github.com/qojulia))

* [QuantumOptics.jl](https://github.com/qojulia/QuantumOptics.jl) (05 2020) - *a numerical
  framework written in Julia that makes it easy to simulate various kinds
  of quantum systems. It is inspired by the Quantum Optics Toolbox for MATLAB and the Python framework QuTiP.*
  This is evidently more general than quantum optics.

### [IITiS PAN](https://github.com/iitis) (Institute of Theoretical and Applied Informatics of the Polish Academy of Sciences)

* [QuantumInformation.jl](https://github.com/iitis/QuantumInformation.jl) (08 2019) - *numerical computation in quantum information theory.*
* [QSWalk.jl](https://github.com/iitis/QSWalk.jl) (04 2020) - *simulating the evolution of open quantum systems on graphs.*


### [Rigetti](https://github.com/rigetti)

The following are used to model super-conducting architectures.

* [AdmittanceModels.jl](https://github.com/rigetti/AdmittanceModels.jl) (12 2019)  - *Analysis of linear systems using admittance models*
* [DiscretePDEs.jl](https://github.com/rigetti/DiscretePDEs.jl) (10 2019) - *Partial differential equations using Discrete Exterior Calculus*
* [DiscreteExteriorCalculus.jl](https://github.com/rigetti/DiscreteExteriorCalculus.jl) (10 2019) - *Discrete differential geometry on simplicial complexes*

### [PainterQubits](https://github.com/PainterQubits)

Superconducting qubits and quantum resonators


## Topics

### Tensors

Some tensor packages appear above. Repeat them ? Link them ?

Here is [discussion on tensor packages](https://discourse.julialang.org/t/comparison-of-tensor-packages/11425).

* [SymmetricTensors.jl](https://github.com/iitis/SymmetricTensors.jl) (05 2020) - *Framework for symmetric tensors*
* [Tensors.jl](https://github.com/KristofferC/Tensors.jl) (02 2020) - *Efficient computations with symmetric and non-symmetric tensors with support for automatic differentiation.* The author [says](https://discourse.julialang.org/t/comparison-of-tensor-packages/11425/2?u=jlapeyre) this is
 for real tensors. So quantum applications may be limited. Or the author may say "real" for "genuine".
* [TensorCast.jl](https://github.com/mcabbott/TensorCast.jl) (05 2020) - *It slices, it dices, it splices!*
* [OMEinsum.jl](https://github.com/under-Peter/OMEinsum.jl) (04 2020) - *One More Einsum for Julia! With runtime order-specification and high-level adjoints for AD*
* [TensorNetworkAD.jl](https://github.com/under-Peter/TensorNetworkAD.jl) (08 2019) - *Algorithms that combine tensor network methods with automatic differentiation.*
* [Einsum.jl](https://github.com/ahwillia/Einsum.jl) (02 2019) - *Einstein summation notation*
* [Tullio.jl](https://github.com/mcabbott/Tullio.jl) (05 2020)
* [MERA.jl](https://github.com/mhauru/MERA.jl) (04 2020) - *some basic Multiscale Entaglement Renormalization Ansatz algorithms*


### Simulation of Quantum Computers

* [Schrodinger.jl](https://github.com/jebej/Schrodinger.jl) (04 2020) - *Fast and easy simulation of quantum mechanical systems.*

### Mathematics

* [Grassmann.jl](https://github.com/chakravala/Grassmann.jl) (05 2020) - *⟨Leibniz-Grassmann-Clifford⟩ differential geometric algebra / multivector simplicial complex*


### Quantum Chemistry

* [QuantumLab.jl](https://github.com/vonDonnerstein/QuantumLab.jl) (05 2020) - *A workbench for Quantum Chemistry and Quantum Physics.*
* [DFTK.jl](https://github.com/JuliaMolSim/DFTK.jl/) (06 2020) - *Density-functional toolkit* *is a library of Julia routines for experimentation
   with plane-wave density-functional theory (DFT), as implemented in much larger production codes such as Abinit, Quantum Espresso and VASP.*

### Molecular and protein dynamics, etc.

* [JuliaMolSim](https://github.com/JuliaMolSim) (06 2020) - *Molecular Simulation in Julia*.
  Note that [DFTK.jl](https://github.com/JuliaMolSim/DFTK.jl/), listed above, is in this org.
* [Molly.jl](https://github.com/jgreener64/Molly.jl) (05 2020) - *Molecular dynamics*
* [ProteinEnsembles.jl](https://github.com/jgreener64/ProteinEnsembles.jl) (10 2019) - *Generate and perturb protein structural ensembles using the ExProSE algorithm*

## Unmaintained, deprecated, etc. packages and projects

The date of last activity is shown in parentheses.

* [JuliaQuantum](https://github.com/JuliaQuantum) (12 2016)
* [TensorToolbox.jl](https://github.com/Jutho/TensorToolbox.jl) (09 2017)
   See the author Jutho's [replacement packages]((https://github.com/Jutho)
* [NCon.jl](https://github.com/mhauru/NCon.jl) recommended replacement: [TensorOperations.jl](https://github.com/Jutho/TensorOperations.jl)
