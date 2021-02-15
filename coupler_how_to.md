# How to configure a coupled system
  
Within CLiMA we are building a minimal coupling library that can interface with DG BalanceLaw based models
and potentially with models that do not use the Balance Law machinery.

The Coupler consists of  

1. [A custom timestepper](src/Numerics/ODESolvers/CplSolver.jl)
