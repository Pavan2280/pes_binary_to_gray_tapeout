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

![WhatsApp Image 2023-11-24 at 20 59 05_217a5c9d](https://github.com/Pavan2280/pes_binary_to_gray_tapeout/assets/131603225/0bdba397-ef37-4e28-83fe-65861bffd11b)
![WhatsApp Image 2023-11-24 at 20 59 05_e214ed7d](https://github.com/Pavan2280/pes_binary_to_gray_tapeout/assets/131603225/f5d5774d-894f-454b-aa0e-21f6f4d516a8)
![WhatsApp Image 2023-11-24 at 20 59 05_b4e720e9](https://github.com/Pavan2280/pes_binary_to_gray_tapeout/assets/131603225/bc1d8d72-f9e6-4b99-8988-72810e83b705)


# Creating SSH key

![WhatsApp Image 2023-11-24 at 21 02 01_e714d53d](https://github.com/Pavan2280/pes_binary_to_gray_tapeout/assets/131603225/c06d68a9-881b-461c-ac1f-3384ba55daff)

# MPW Precheck
![WhatsApp Image 2023-11-24 at 20 59 05_42d473f8](https://github.com/Pavan2280/pes_binary_to_gray_tapeout/assets/131603225/3a61c240-cc9f-46b5-ab59-1e4966210bb7)
![WhatsApp Image 2023-11-24 at 20 59 05_fc01cc36](https://github.com/Pavan2280/pes_binary_to_gray_tapeout/assets/131603225/dcbb3e66-e8b8-475d-b9da-9909bba06181)
