---
# the default layout is 'page'
tab_name: Example
icon: fas fa-file-lines
order: 2
---

# Work Experience
<hr>
_September 2021 - Present_
{:.h6}
**Electrical Engineer II** at **[ENTRUST Corp. DPS](https://www.entrust.com/digital-security/hsm), Cambridge, UK**
{:.h5}

<div id="post-list" class="flex-grow-5 px-xl-1">
<article class="card-wrapper card">
      <div class="post-preview row g-0">
      {% assign card_body_col = '12' %}
        <div class="col-md-{{ card_body_col }}">
          <div class="card-body d-flex flex-column">
            <em class = "card-title my-0 mt-md-0">Summary</em>
            <p class=" mb-1" style="color:rgb(175,176,177)">
                The Data Protection Solutions sector of Entrust in Cambridge, focuses on Hardware security modules (HSMs). 
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
* Designed a PCB, tested, and have written the firmware for a [RP2040-based](https://thepihut.com/products/tiny-2040) power
monitoring interposer on a PCIe interface. 
  * Used in development for data collection.
  * Will be used in production to automate the detection of software updates that increase the power
draw of our hardware, thus improving unit reliability.
* Developed two iterations of a controller module for a
1U rack server using ARM Cortex M microcontrollers. 
  * Used to extent the lifetime of an existing product to include around 3000 more units.
* Currently tackling the development of future products alongside the 5-person hardware team,
mainly the upgrade to the 1U server appliance: 
  * Developed PCBs for the overall chassis,
  * Designed testing to improve performance, with a focus on cooling experiments. 
    * Data gathered through the cooling experiments has lead to 33% decrease in temperature with the same power usage.
* For 3 months (Jun – Aug 2023), I moved across the organisation to take the role of a software
engineer. 
  * I set up the infrastructure, compilation, and linking environment for the
Cortex M microcontrollers in the controller module.
  * Developed the prototype firmware for the
microcontrollers, allowing validation of the design. This confirmed that I could safely start work on
the second iteration without major blockers or critical design changes.

<br>
_July 2020 - August 2020_
{:.h6}
**FPGA Software Engineer** at **[Crystal Vision Ltd.](https://uk.linkedin.com/company/crystal-vision-limited), Whittlesford, UK**
{:.h5}

<div id="post-list" class="flex-grow-5 px-xl-1">
<article class="card-wrapper card">
      <div class="post-preview row g-0">
      {% assign card_body_col = '12' %}
        <div class="col-md-{{ card_body_col }}">
          <div class="card-body d-flex flex-column">
            <em class = "card-title my-0 mt-md-0">Summary</em>
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
* Tested three different FPGA chips by designing testing software in VHDL to produce eye-
diagrams. 
* Wrote software for optimisation of their low-level VHDL routines.

This work performed manufacturing error checks while pushing the limitations of custom FPGA boards
both in maximum capabilities and reliability of continuous operation.