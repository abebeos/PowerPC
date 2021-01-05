(early draft)

# Speed-up  PowerPC SW-Development.


## Prerequisites

* Win/Lin/Mac Machine
* Docker, git, VSCode
* Usual Package-Manager (chocolateley, apt, etc.)

## Initial Dev-System

You don't need a PowerPC to start development. 

(draft)

## Tasks

(draft)

Follow-up tasks to numba-4026 (timepoint: now, as the domain-knowledge is active)

* - [ ] #1 Refactor llvm RuntimeDyldELF for Clarity
* - [ ] #2 Provide a Near-Zero-Efffort PowerPC Dev-System Setup
    * - [ ] #3 Provide a numba Core-Dev-System Setup
* - [ ] #4 Provide PowerPC llvm JITLink Implementation

### Numba

* Verify necessity to back-port https://reviews.llvm.org/D81126?id=274770
* Drastically simplify numba core-dev-env (for dev-work on numba/llvmlite/llvm itself) setup
* Provide Parallel Testsuite Execution which completes despite timeouts and crashes like segfaults.
* Allow to select reloc-mode via cli/config
* Investigate Test Fork-Issues on High-Core-Count Systems


### General

* Specify a generic add-ppc64-support-process
    * draft: tools, clarity, decoupling
* Drastically Simplify Provisioning of ppc64le VPS Instance
* Provide Method to setup ppc64le-CI, even if main project does not    
* Provide info-streams re llvm/numba ppc development
    * => easily subscribe to ppc-related issues and commits    
  
