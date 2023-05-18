# Project Scope

Chemical Langevin Equation, Stochastic Differential Equations, Parametric Identifiability, Systems Biology Case Studies.


# For Graders
Relevant Code is in NeuralCLEmodel.jl


# Generating Project.toml and Manifest.toml

If you have no Project.toml and Manifest.toml files in your active directory for this project (which are used for package environments separate from the base environment), then running `generate-project-toml.ipynb` will generate them for you. Take the files and copy them over to your active directory.

To modify list of packages used for this project and all jupyter notebooks, add the packages to `generate-project-toml.ipynb` where indicated and run the file.

If you have Project.toml and Manifest.toml files in your active directory, run `import Pkg; Pkg.activate("."); Pkg.instantiate(verbose=true)` at top of Julia scripts or jupyter notebooks in the active directory in order to start using the isolated package environment for this project.

You should only have to run `generate-project-toml.ipynb` once if you do not modify it.
