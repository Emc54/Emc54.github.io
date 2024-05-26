---
layout: page
title: Internship at Swindon Silicon Systems
img_path: /assets/img/internships/
---

## Who is Swindon Silicon Systems?

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

![Company Info](swindon1.png)

## The problem to be addressed

![The Project](swindon2.png)

## An overview of my proposed solution

The company had a lot of unit tests for VHDL in Vivado that was running on an FPGA.
The tests were issued on a Linux PC with the FPGA plugged in through the PCIe connector.
As they wanted to transition to tests more applicable to their use cases, portability became key.

The task at hand was to use a custom distro of Linux on an MCU to run the VHDL Tests.
The proposed interface between the user and the VHDL tests was Jupyter Notebooks.

![The design of the solution](swindon3.png)

## What I learned

* My biggest takeaway was familiarisation with Linux on a daily basis, which led me to adopt it as an OS in my personal life as well.
* I had faced a project that was much bigger than I could understand or see its completion in my time there, so I realised that I had to focus on the key requirements asked of me for the time being, while absorbing information about the rest of the project organically.
* It was my first role in an organisation larger than 10 people, so I had to learn to interact with the managerial hierarchy and with colleagues working on similar parts of the codebase.
* Introduction to SVN as a repository storage system as opposed to Git.
