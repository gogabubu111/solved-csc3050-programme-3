Download Link: https://assignmentchef.com/product/solved-csc3050-programme-3
<br>
<h1>Overview</h1>

In the class, the teacher introduced the Arithmetic and Logic Unit(ALU) to us. This module is to do math co-processing. In this programme, we will use verilog to complete it.

I will give you examples of verilog module file and testing file. You should add other operations into the code file and analyze the result.

<h1>Block Diagram</h1>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/09/206.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/09/206.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

The ALU must support:

<ul>

 <li>add, sub, mult, div</li>

 <li>addi</li>

 <li>addu, subu, multu, divu</li>

 <li>addiu</li>

 <li>sqrt</li>

 <li>and, or, nor, xor, xnor</li>

 <li>andi, ori</li>

 <li>slt, slti</li>

</ul>

I will give you example of sla and srai.

In the diagram we can see that the reg_C is connected to reg_A. I use a thinner line to show you that it is sometimes not connected. For the instructions like addi, you should rewrite the result to reg_A; For other instructions like add, this relation should be cut.

The flag registers includes zero flag, negative flag and overflow flag. The negative flag will appear when you do subtraction with unsigned values or other arithmetic with signed values. In the addition part, there may be overflow and the overflow detection will better improve our ALU module. The zero flag will be important in the next cpu programme because it decide the jump in a cpu. There are more instructions(bne, beq, etc) in a cpu related to the zero flag.

You should handle two verilog file:

<ul>

 <li>v</li>

 <li>v</li>

</ul>

And your project report.

I will give you example test bench and you should extend the test bench by yourself and analyze the final result in your report.

<h1>Grading</h1>

<strong> </strong>

Support the Arithmetic/Logic operations – 60%

With special handling for flags – 30%

<ul>

 <li>Sign extend – 10% – Zero extend – 10%</li>

 <li>Overflow detection – 10%</li>

</ul>

Project report – 10%