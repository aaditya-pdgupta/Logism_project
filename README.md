# Introduction

A logics gate is an electronic circuit which makes logic decision. It accepts two state input and gives two state output only. The two state input-output '0' and '1', or 'low' and 'high' etc. A logic gate has only one output terminal and can have one or more than one input terminals. To get a right logical output, a logical input (i.e, either '0' or '1') is to be given to each input terminal. Hence, every input variable to a logic gate is either '0' or '1'.

There are different types of logic gates:
* OR gate
* AND gate
* NOT gate
* XOR gate
* NAND gate
* NOR gate

Among above gates, NAND & NOR gates are the most commonly encountered universal gate in logics gate. A universal gate is such a gate that we can implement any Boolean function, no matter how complex, using a circuit that consists of only that particular gate. 

# NAND gate

NAND gate is also called as universal gate whose output is high when any or all of the inputs are low. It is, in fact, a NOT AND gate. That is, a combination of an AND gate and a NOT gate. Mathematically, the operation is represented as

$$\overline{A \cdot B} = Y$$

The electronic symbol symbol for a NAND gate is shown in figure below.

<p align="center">
  <img src="../main/Figures/NAND_gate.jpg" width="250" height="100"/>
</p>



## Operation
* When A is low and B is low, Y is high.
* When A is low and B is high, Y is high.
* When A is high and B is low, Y is high.
* When A is high, and B is also high, Y is low. 

The truth table for two input is shown below in table.

<p align="center">
  <img src="../main/Table/Logism_table_NAND.jpg" width="250" height="100"/>
</p>

Using the NAND gate we can make other logics gate such as OR gate, AND gate, NOT gate, XOR gate etc which are discussed below.

# AND Using NAND

AND gate is a logic gate whose output is high if all of its inputs are high and output is low if all of its inputs are low. Mathematically, the operation for it is represented as

$$A \cdot B = Y$$

The electronic symbol of AND Using NAND gate is shown figure below.

<p align="center">
  <img src="../main/Figures/AND_Gate.jpg" width="250" height="100"/>
</p>

The figure above is quite straightforward. Here, we first compliment the inputs A and B. Then we perform the NAND operation on these complemented inputs we get:

$$\overline{A \cdot B}$$

And if we compliment the same output as input given by NAND operation for NOT opertion we get:

$$\overline{\overline{A \cdot B}} = Y$$

Using De-Morgans's law we can say that

$$\overline{\overline{A \cdot B}} = A \cdot B = Y$$ 

which is required mathematical expression for AND gate.

## Operation
* When A is low and B is also is low, Y is low.
* When A is low and B is high, Y is low.
* When A is high and B is low, Y is low.
* When A is high, and B is also high, Y is high. 

The truth table for two input is shown below in table.

<p align="center">
  <img src="../main/Table/Logism_table_AND.jpg" width="250" height="100"/>
</p>

# OR Using NAND

OR gate is a logic gate whose output is '1' state or high if any or all the inputs are '1' state or high. Mathematically, the operation for it is represented as

$$A + B = Y$$ 

The electronic symbol of OR Using NAND gate is shown figure below.

<p align="center">
  <img src="../main/Figures/OR_Gate.jpg" width="250" height="100"/>
</p>

