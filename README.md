# Caravel User Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

| :exclamation: Important Note            |
|-----------------------------------------|

## Please fill in your project documentation in this README.md file 

Refer to [README](docs/source/index.rst#section-quickstart) for a quickstart of how to use caravel_user_project

Refer to [README](docs/source/index.rst) for this sample project documentation. 

Refer to the following [readthedocs](https://caravel-sim-infrastructure.readthedocs.io/en/latest/index.html) for how to add cocotb tests to your project. 

# Cloning and Setup
Use the below commands to clone and setup
```
git clone https://github.com/Pavan2280/pes_binary_to_gray_tapeout.git
mkdir ~/asic
export OPENLANE_ROOT=~/asic/openlane
export PDK_ROOT=~/asic/pdk
cd pes_binary_to_gray_tapeout/
make setup

ls $PDK_ROOT
ls $OPENLANE_ROOT
ls openlane/
make user_proj_example
ls gds/
klayout gds/user_proj_example.gds
```



# Creating SSH key


# MPW Precheck
