---
layout: page
title: SYCL Practitioners Hackathon
subtitle: >
    Monday 17 April 2023 | University of Cambridge
cover-img: 'assets/img/cms-blurred.jpg'
---


## Summary

This event will follow on from the [SYCL practitioners
hackathon](https://scicomp.webspace.durham.ac.uk/events/code_performance_series/sycl-practitioners-hackathon-2022-user-group-meeting/)
hosted in Durham In November 2022. We are hosting in Cambridge so that it is
convenient for those attending [IWOCL/SYCLcon 2023](https://www.iwocl.org/)
which takes place over the following three days.

This will be a one-day hands-on hackathon. Given the limited time, we will focus
on working with an open source benchmarks project that will help both learning
for attendees and also benefit the overall SYCL community. Teams will work on
adding to and enhancing the project. There will be also be the opportunity to
chat with SYCL experts and other members of the community to discuss code,
issues, SYCL features and general queries.

Participants are not required to bring along their own SYCL code but some basic
familiarity with SYCL will be assumed (e.g. at the level of the material covered
in the [Intel Essentials of SYCL
modules](https://www.intel.com/content/www/us/en/developer/tools/oneapi/training/dpc-essentials.html)
or the material covered in the [Codeplay SYCL
Academy](https://github.com/codeplaysoftware/syclacademy)).  Furthermore,
participants will be expected to live-code throughout the hackathon and will
therefore need to bring along a laptop with which they can access the remote
system and program on.
## SYCL benchmark codes

In this hackathon there will be three themes related to the
[HeCBench](https://github.com/zjin-lcf/HeCBench) project:

### Performance and optimization

Do you want to learn how to profile and optimize SYCL code? Or do you have
profiling and optimization experience you would like to share?

The HeCBench project brings an extensive set of benchmarks together covering a
broad set of different algorithms. These benchmarks are written with SYCL, CUDA
and HIP and provide a unique opportunity to compare these programming models.
There are however some benchmarks with significant performance variations and
some of these listed in the accompanying spreadsheet. We have identified some
benchmarks to focus on understanding why performance variation occurs. Perhaps
this is because the CUDA and SYCL kernels are not equivalent, or there is a
difference in the problem size, or there it exposes a performance gap. Let's
work together to make the HeCBench benchmarks show an accurate picture of
performance of CUDA and SYCL code running on CSD3.

### Updates to support the latest SYCL 2020 features
Do you want to learn how to use the latest SYCL 2020 features and syntax?

The SYCL specification continues changing every year. Therefore, users observe
that certain language features and programming interfaces are deprecating or
deprecated when compiling these benchmarks with a recent compiler. Upgrading the
SYCL benchmarks will minimize the number of compiler warnings about deprecation
and help to gather feedback on the latest SYCL features. A list of the
benchmarks that need to be updated is available.

### Improving benchmark occupancy and consistency of run time

Do you want to understand more about how to run benchmarks in a fair, useful and
consistent way?

Running benchmarks can be tricky. There are different considerations that need
to be taken into account when writing and also running benchmarks. Is the
benchmark running with high occupancy on the target processor? Does the
benchmark run for long enough for the recorded timing to be a useful measure? Do
the benchmarks provide consistent results?

The HeCBench project has a large set of benchmarks, and some have been
identified as needing work to address these questions. Work on this theme to
improve the overall execution of the benchmarks in this project.



## Registration

Please complete the [registration form](register) by 

<p align=center style="color:red"><strong> midnight on Thursday 6 April. </strong></p>

Note that there is limited capacity and that priority will be given to
participants from Intel oneAPI Centers of Excellence, ExCALIBUR and local
participants.

## Logistical details

* Timings: 09:00 - 18:00 UTC, Mon 17 Apr 2023
* Location: Centre for Mathematical Sciences, University of Cambridge, Wilberforce Road, Cambridge, CB3 0WA, UK 

<div style="width 100%;">
    <iframe scrolling="no" marginheight="10" marginwidth="10" src="https://maps.google.com/maps?width=720&amp;height=600&amp;hl=en&amp;q=Centre%20for%20Mathematical%20Sciences,%20Wilberforce%20Road,%20Cambridge,%20CB3%200WA+(Centre%20for%20Mathematical%20Sciences)&amp;t=&amp;z=15&amp;ie=UTF8&amp;iwloc=B&amp;output=embed" width="100%" height="400" frameborder="0">
    </iframe>
</div>

## Agenda

The following is preliminary.

| Time | Activity | Lead |
| --- | --- | --- |
| 09:00-09:30 | Arrival | - |
| 09:30-09:45 | Introduction to hackathon | Jay Mahalingham (Intel, remote) |
| 09:45-10:00 | Introduction to HeCBench project and hackathon themes | Rod Burns (Codeplay), Hugh Delaney (Codeplay) |
| 10:00-10:15 | Introduction to CSD3 | Kacper Kornet (Cambridge) |
| 10:15-10:30 | Introduction to Ponte Vecchio on the Intel DevCloud | Hugh Delaney (Codeplay) |
| 10:45-11:30 | Hands-on | - |
| 11:30-11:45 | Coffee break | - |
| 11:45-13:00 | Hands-on | - |
| 13:00-14:00 | Lunch | - |
| 14:00-15:45 | Hands-on/own SYCL code discussion | - |
| 15:45-16:00 | Coffee break | - |
| 16:00-17:45 | Hands-on/own SYCL code discussion | - |
| 17:45-18:00 | Wrap-up and close | Rod Burns (Codeplay), Miren Radia (Cambridge) |

## Travel and accommodation

If you are arriving by rail, there is a direct bus link from Cambridge [central]
station to a stop that is very close to the Centre for Mathematical Sciences
(CMS) which runs approximately every 15 minutes. For more details see
[here](https://www.environment.admin.cam.ac.uk/travel/travel-bus).

If you are booking accommodation for both this hackathon and IWOCL/SYCLcon, the
CMS is approximately a 20-minute walk from Sidney Sussex College (where
IWOCL/SYCLcon is taking place)/the town centre.


## HPC system

In order to streamline setup, we would prefer participants to use the [Cambridge
Service for Data Driven Discovery
(CSD3)](https://www.hpc.cam.ac.uk/high-performance-computing) system for this
hackathon. 

In particular we will be using the
[Wilkes3](https://www.hpc.cam.ac.uk/systems/wilkes-2) part of this system which
features 80 nodes each with

* 2x AMD EPYC 7763 64-Core Processor 1.8GHz (128 cores in total)
* 1000 GiB RAM
* 4x NVIDIA A100-SXM-80GB GPUs
* Dual-rail Mellanox HDR200 InfiniBand interconnect

If you do not have an account on CSD3, please indicate on the registration form.
If you do have an account, please provide your username so that it can be added
to the reservation.

In addition to CSD3, attendees will have the opportunity to use a system with
the new Intel Data Center GPU Max 1100 (aka Ponte Vecchio) on the Intel DevCloud 
during the hackathon.

<p align=center>
    <img src="assets/img/pvc.png" height=160>
</p>

## Support

This event is being organised in collaboration between the two [oneAPI Centers
of
Excellence](https://www.intel.com/content/www/us/en/developer/tools/oneapi/training/academic-program/centers-of-excellence.html)
at the University of Cambridge: 
* [The Stephen Hawking Centre for Theoretical Cosmology](https://www.ctc.cam.ac.uk/)
* [The Cambridge Open Zettascale Lab](https://www.zettascale.hpc.cam.ac.uk/)

<p align=center>
    <img src="assets/img/oneapi.png" height=160>
</p>

We are grateful to the support provided by Intel and Codeplay for this event.

<p align=center>
    <img style="padding-left: 30px; padding-bottom: 10px; padding-right: 30px; padding-top: 10px;" src="assets/img/intel-logo.webp" height="80">
    <img style="padding-left: 30px; padding-bottom: 10px; padding-right: 30px; padding-top: 10px;" src="assets/img/codeplay-logo-black.svg" height="80">
</p>