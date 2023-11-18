---
# the default layout is 'page'
layout: post
tab_name: CV
icon: fas fa-file-lines
order: 5
toc: true
title: Resumé
---

## Work Experience

### Electrical Engineer II at [ENTRUST Corp. DPS](https://www.entrust.com/digital-security/hsm), Cambridge, UK
<hr>
_September 2021 - Present_

<div id="post-list" class="flex-grow-5 px-xl-1">
<article class="card-wrapper card">
      <div class="post-preview row g-0">
      {% assign card_body_col = '12' %}
        <div class="col-md-{{ card_body_col }}">
          <div class="card-body d-flex flex-column">
            <em class = "card-title my-0 mt-md-0">Company Summary</em>
            <p class=" mb-1" style="color:rgb(175,176,177)">
                The Data Protection Solutions sector of Entrust in Cambridge focuses on Hardware Security Modules (HSMs).
                They are hardened, tamper-resistant hardware devices that secure cryptographic processes by generating, protecting, and managing keys used for encrypting and decrypting data and creating digital signatures and certificates.
            </p>
            <!-- .post-meta -->
            </div>
          <!-- .card-body -->
        </div>
        </div>
</article>
</div>
<br>

My current position as an Electrical Engineer II, which amounts to the tasks of a hardware design
engineer within the company.

* **Designed** a PCB, tested, and wrote the firmware for an [RP2040-based](https://thepihut.com/products/tiny-2040) power
monitoring interposer on a PCIe interface.
  * Used in development for data collection.
  * Will be used in production to automate the detection of software updates that increase the power
draw of our hardware, thus improving unit reliability.
* **Developed** two iterations of a controller module for a
[1U rack server](https://www.entrust.com/digital-security/hsm/products/nshield-hsms/nshield-connect) using ARM Cortex M microcontrollers.
  * Used to extend the lifetime of an existing product to include around 3000 more units.
* **Currently tackling** the development of future products alongside the 5-person hardware team,
mainly the next generation of the 1U server appliance:
  * Developed PCBs for the overall chassis,
  * Designed testing to improve performance, with a focus on cooling experiments.
    * Data gathered through the cooling experiments has led to a 33% decrease in temperature with the same power usage.

For 3 months (Jun – Aug 2023), I moved across the organisation to take the role of a software
engineer.

  * **Set up** the infrastructure, compilation, and linking environment for the
Cortex M microcontrollers in the controller module.
  * **Developed** the prototype firmware for the
microcontrollers, allowing validation of the design. This confirmed that I could safely start work on
the second iteration without major blockers or critical design changes.

<br>

### FPGA Software Engineer at [Crystal Vision Ltd.](https://uk.linkedin.com/company/crystal-vision-limited), Whittlesford, UK

<hr>
_July 2020 - August 2020_
{:.h6}

<div id="post-list" class="flex-grow-5 px-xl-1">
<article class="card-wrapper card">
      <div class="post-preview row g-0">
      {% assign card_body_col = '12' %}
        <div class="col-md-{{ card_body_col }}">
          <div class="card-body d-flex flex-column">
            <em class = "card-title my-0 mt-md-0">Company Summary</em>
            <p class=" mb-1" style="color:rgb(175,176,177)">
               Crystal Vision made infrastructure and keying products for professional broadcast engineers in the television industry. It helped people transition through a range of technologies, from SD to HD and from HD to IP. Part of their products included FPGA transceivers for high-speed parallel video streaming solutions.
            </p>
            <!-- .post-meta -->
            </div>
          <!-- .card-body -->
        </div>
        </div>
</article>
</div>
<br>

A two-month internship that involved hands-on experience with custom FPGA transceivers reaching
capabilities of 400Gb/s.

* Tested three different FPGA chips by designing software in VHDL to produce eye-
diagrams.
* Implemented algorithms for optimisation of their low-level VHDL routines.

This work performed manufacturing error checks while pushing the limitations of custom FPGA boards
both in maximum capabilities and reliability of continuous operation.

<br>

### FPGA Software Engineer at [Swindon Silicon Systems](https://www.swindonsilicon.com/custom-ic-design/), Swindon, UK

<hr>
_July 2019 - August 2019_
{:.h6}

<div id="post-list" class="flex-grow-5 px-xl-1">
<article class="card-wrapper card">
      <div class="post-preview row g-0">
      {% assign card_body_col = '12' %}
        <div class="col-md-{{ card_body_col }}">
          <div class="card-body d-flex flex-column">
            <em class = "card-title my-0 mt-md-0">Company Summary</em>
            <p class=" mb-1" style="color:rgb(175,176,177)">
               Swindon Silicon Systems is a global leader in the design and supply of automotive and industrial mixed-signal ASIC solutions.
            </p>
            <!-- .post-meta -->
            </div>
          <!-- .card-body -->
        </div>
        </div>
</article>
</div>
<br>

A two-month internship at the company, in which I was part of a project involving the development of a
custom ASIC solution for a pressure-controlled haptic feedback device.
I used Vivado to program an FPGA to interface with Python via a Jupiter Notebook, to incorporate
simulation tests previously running on a PC to increase the portability of the overall design.

## Education

### Gonville & Caius College, University of Cambridge

_2017 - 2021_
{:.h6}
**MEng Electrical and Electronic Engineering, 2.i, Cambridge MA**

* Sensors and Instrumentation
* Embedded Systems for the Internet of Things
* Radio Frequency and Integrated Digital Electronics
* Data Transmission
* Information Theory and Coding
* Computer Systems
* Software Engineering and Design
* Accounting, Finance, and Modelling Risk

#### [Master’s Thesis](https://github.com/Emc54/CoherentTransceivers)

Optical digital coherent transceivers have the capability of achieving 1 Tbit/s links in the core networks
and 100 Gbit/s links in an access network. I developed algorithms in MATLAB for the simulation of transceivers,
mainly those required for synchronisation and equalisation (both linear and nonlinear), as well as
modulation techniques such as probabilistic shaping.

### Cypriot public education system

_Early Life - 2015_
{:.h6}
Areas of Focus
{:.h5}

* Mathematics
* Physics
* Chemistry
* Greek
