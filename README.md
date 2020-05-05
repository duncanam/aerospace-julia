# References for Aerospace-related Packages
Having come across many neat packages that I have either used or see potential use within the field of aerospace, I thought I'd create a little reference for myself and others I proselytize Julia to. 

## LinearAlgebra
Included with the standard installation, this gives access to eigenvalue `eigvals()` and eigenvector `eigvecs()` as well as factorizations such as `Cholesky()`, `LU()`, and `QR()`. 

## DifferentialEquations.jl
*Multi-language suite for high-performance solvers of differential equations*. Package that gives access to dozens of differential equation solvers, including those specializing in stiff systems. In addition to temporal time-stepping solvers, it also includes boundary value problem (BVP) solvers as well as steady state solvers. This is a very powerful package for solving nearly any kind of differential equation problem. 

**Link:** [DifferentialEquations.jl](https://github.com/SciML/DifferentialEquations.jl)

## JuMP.jl
*JuMP is a domain-specific modeling language for mathematical optimization embedded in Julia.* An optimization toolbox for both linear and nonlinear problems, allowing for efficient optimization finding. Capable of optimizing sytsems of differential equation solving, or basic linear equations. 

**Link:** [JuMP.jl](https://github.com/JuliaOpt/JuMP.jl)

## SatelliteToolbox.jl
*A toolbox for satellite analysis written in the Julia language.* A nice tool for performing satellite analysis. Has orbit propagating, TLE reading and creation, atmospheric models, magnetic field models, and much more. Has generic functions for angular velocity in an orbit, orbit periods, and time-derivatives of RAAN and argument of perigee. 

**Link:** [SatelliteToolbox.jl](https://github.com/JuliaSpace/SatelliteToolbox.jl)

## ControlSystems.jl
*A control systems toolbox for Julia.* A controls toolbox for performing system analysis, PID analysis and design, time and frequency response, plotting, and more. 

**Link:** [ControlSystems.jl](https://github.com/JuliaControl/ControlSystems.jl)

## Plots.jl
*A Powerful plotting API spanning several plotting packages.* Plots allows access to GR, PyPlot, Plotly, PlotlyJS, and more plotting interfaces with a common set of commands. It is capable of two- and three-dimensional plotting as well as animation. Allows for quick changing of plotting backends. 

**Link:** [Plots.jl](https://github.com/JuliaPlots/Plots.jl)

## Makie.jl
*High-level plotting on the GPU, written in Julia.* Makie is an advanced plotting package aimed to eventually replace Plots.jl, with GPU-accelerated 3D plotting. It's capable of both 2D and 3D plotting, as well as animations. Gives access to the useful `volume(data,algorithm=:iso)` command for plotting isosurfaces, which is exceedingly difficult in Python for homogeneous isotropic turbulence (HIT) data, and akin to `isosurface()` in MATLAB. Visualization occurs with OpenGL. 

**Link:** [Makie.jl](https://github.com/JuliaPlots/Makie.jl)
