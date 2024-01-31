# Lab 2: 

# Overview and Motivation
Welcome to the Lab 02 of CS281: Introduction to Computer Systems! 
This lab will help you get more familiar with mux and logic circuits. The lab will take you through the intricacies of the 74150 mux chip and different gates (And, Or, Not). By the end of this lab, you'll be adept at working with essential circuit components.


# Objectives of the Lab
1. Familiarize yourself with the mux chip and learn to control it.
2. Understand and construct an Adder by using circuit chips.
3. Develop the ability to read and interpret IC data sheets.
4. Gain hands-on experience in controlling circuits with the Arduino.
 
# Materials
- PB-503 breadbofard prototyping station (integrated device with a number of electrical components like switches)
- Arduino kit
- 7404 NOT gate IC
- 7408 AND gate IC
- OR gate IC
- 74150 mux chip
- Wires
- LED
- Arduino controller and USB cable


# A 2 to 1 Mux
## 0 About

## 1. Project Step


## 2. Testing




# A 4 to 1 Mux
## 0 About

## 1. Project Step


## 2. Testing




# A 4 to 1 Mux with Arduino
## 0 About

## 1. Project Step


## 2. Testing



# Adder Circuit
## 0 About
We will generate a binary adder in this section! 
The adder has a couple of inputs: namely bits Ai + Bi of the two operands.
The outputs are the carry-over from the previous sum and sum bit. 
We will use cin be the carry-in bit from a previous column. Let cout be the carry-out bit which may go through to the next column.
This will be very important in building complex arithmetic circuits later.
Now let's start!
 
## 1. Project Step
- Design a circuit that takes two 1-bit numbers as inputs, plus a carry-in and outputs (first - a bit representing the 1-bit sum of the numbers and second - a bit representing the 1-bit carry)
  1. Build a truth table (tree inputs and two output columns)
  2. Create SOP design for two outputs (try to reduce the complexity if you can)
  3. Design a circuit for the adder
- Check the circuit is working by using a computer program
- Build the circuit on the breadboard!
- Start testing!

## 2. Testing
- Use three switches for the inputs that you connected
- Try to implement the truth table and check the outputs match



# Conclusion



