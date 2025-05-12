# verilog-lab-0-switches-leds-and-multiplexers-solved
**TO GET THIS SOLUTION VISIT:** [Verilog Lab 0-Switches, LEDs, and Multiplexers Solved](https://www.ankitcodinghub.com/product/verilog-lab-0-switches-leds-and-multiplexers-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91435&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Verilog Lab 0-Switches, LEDs, and Multiplexers Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Lab 0

Switches, LEDs, and Multiplexers

The purpose of this lab is to learn how to utilize some I/O devices (i.e., switches and LEDs) on an FPGA development board and implement simple Multiplexer circuits utilizing these I/O devices.

Part 1 (Building a 3-bit 2×1 MUX)

For this part, you will design the circuit in Figure 1 and implement it on the Nexys board. The circuit implements a 2×1 MUX with 3-bit inputs and outputs. In other words, the inputs X, Y and output M are all 3-bit signals.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Write Verilog code to describe a 2×1 MUX with 1-bit inputs and outputs (you can use dataflow or behavioral modeling for this item). Call the file `mux_2x1_simple`</li>
<li>Use the `mux_2x1_simple` to implement a 3-bit input/output 2×1 MUX as shown in Figure 1. In other words, instantiate several instances of the `mux_2x1_simple` module to create the 3-bit version. Call the file `mux_2x1_3bit`</li>
<li>Verify the functionality of your code by implementing it on the Nexys board using the following IO specifications:
a. SW2ßSW0 for the input X

b. SW5 ß SW3 for the input Y

c. SW15 for the select signal

d. LED2 ß LED0 for the output M

e. LED15 to reflect the status of the select signal
</li>
</ol>
Part 2 (Building a 3-bit 4×1 MUX)

For this part, you will use several instances of the `mux_2x1_3bit`, that was developed in Part 1, to design and implement a 3-bit 4×1 MUX as shown in Figure 2. The circuit implements a 4×1 MUX with 3-bit inputs and outputs. The MUX will route X, Y, Z, or W to M depending on the value placed on S0 and S1.

1. Write Verilog code to describe the 4×1 MUX, you should instantiate as many `mux_2x1_3bit` as necessary. Call the file `mux_4x1_3bit`

</div>
<div class="column">
Figure 1: 2×1 MUX

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2: 4×1 MUX

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2. Verify the functionality of your code by implementing it on the Nexys board using the following IO specifications:

a. SW2ßSW0 for the input X

b. SW5 ß SW3 for the input Y

c. SW8 ß SW6 for the input Z

d. SW11 ß SW9 for the input W

e. SW15 ß SW14 for the select signal f. LED2 ß LED0 for the output M

g. LED15 ß LED14 to reflect the status of the select signal

</div>
</div>
</div>
