# Delta Platform SDK


## Overview

Delta Platform SDK is a set of configurations, OS patches, BSP, libaries and instructions on how to build and release SDK for Delta platforms. It provides a systematic way to help Delta partners and customers bring up their software on Delta platforms easily and quickly.


## Contents 
The platform SDK repository is grouped by platform. The following five categories of information are required to complete the SDK deliverable for a given platform: documentation, OS, adaption layer, network layer and tutorial.

1. Documentation 

   [ ] hardware specification

   [ ] TBD

2. OS 

   [ ] BSP configuration and code

   [ ] kernel version and package 

   [ ] BSP patch for kernel upgrade 

   [ ] BSP patch instruction 

   [ ] linux distribution package 

   [ ] OS image build instruction (kernel + BSP + linux distribution)

3. Adaption layer  

   [ ] linux distribution agnostic API to control the platform environment 

   [ ] API implementation 

4. Network layer 

   Networking libaries, components and applications including but not limited to 

       [ ] switch SDK (broadcom SDK etc.)

            [ ] instruction for patch, build and install

            [ ] sample app invoking switch SDK

       [ ] OpenNSL 

            [ ] instruction for patch, build and install

            [ ] sample app invoking openNSL 

       [ ] OFDPA 

            [ ] instruction for patch, build and install

            [ ] sample app invoking OFDPA

       [ ] SAI

            [ ] instruction for patch, build and install

            [ ] sample app invoking SAI

5. Tutorial 

   Step by step instruction on how to write, build and run a sample application to invoke Delta's Platform SDK to enable white-box switching.


# Legal

TBD 

# License

TBD
