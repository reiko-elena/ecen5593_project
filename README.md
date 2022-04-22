# DOLMA+SAT



This source code is modified based on the USENIX Security paper "DOLMA:
Securing Speculation with the Principle of Transient Non-Observability". The goal of this code is trying to reduce the DOLMA overhead by adding a safe address(SAT) look up table. 

Ref: 
[DOLMA Paper](https://www.kevinloughlin.org/dolma.pdf)
[DOLMA Github](https://github.com/efeslab/dolma.git)
[gem5 simulator](https://github.com/gem5/gem5)


# Instrution:
To install the necessary dependencies on Ubuntu 20.04, run `./install_dependencies_ubuntu20.sh` from the repo's top level directory (requires sudo)

To compile DOLMA, run `python2 $(which scons) -j$(nproc) build/X86_MESI_Two_Level/gem5.opt` from the repo's top level directory

Please go to `attacks` folder to for running attacks instructions

# Change to DOLMA
Please use `git grep -il IDOLMA` to see the all main changes