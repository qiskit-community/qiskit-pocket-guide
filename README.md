# Welcome to the Qiskit Pocket Guide book site!
	  
[![Qiskit Pocket Guide, by James L. Weaver and Frank J. Harkins](http://covers.oreilly.com/images/9781098112400/cat.gif)](https://www.safaribooksonline.com/library/view/title/9781098112462//)
	  
In general, you may use the code from Qiskit Pocket Guide in your programs and documentation. You do not need to contact the authors for permission unless you're reproducing a significant portion of the code. For example, writing a program that uses several chunks of code from this book does not require permission. Answering a question by citing this book and quoting example code does not require permission. On the other hand, selling or distributing a CD-ROM of examples from Qiskit Pocket Guide does require permission. Incorporating a significant amount of example code from this book into your product's documentation does require permission.
	  
We appreciate, but do not require, attribution. An attribution usually includes the title, author, publisher, and ISBN.
	  
If you think your use of code examples falls outside fair use or the permission given here, feel free to contact O'Reilly at <permissions@oreilly.com>.
	  
Please note that the examples are not production code and have not been carefully tested. They are provided "as-is" and come with no warranty of any kind.

# Quick start for running the code examples

## Installing

You need a way to run Python and Jupyter Notebooks:
```bash
pip install jupyter
```

This is tested on Qiskit Terra 0.20. This and other dependencies can be installed via Pip:
```bash
pip install -r requirements.txt 

```

## Download and run the chapters

```bash
wget http://github.com/qiskit-community/qiskit-pocket-guide/archive/refs/heads/main.zip 
unzip main.zip

```

## You may also run these examples in the cloud
Paste or import an example into the [IBM Quantum Lab](https://quantum-computing.ibm.com/lab) 

# Index

## Chapter 1: Quantum Circuits and Operations
 * [Constructing Quantum Circuits](chapter01_Quantum_Circuits_and_Operations/chapter01-1_Constructing_Quantum_Circuits.ipynb)
 * Instructions and Gates
 * Parameterized Quantum Circuits
## Chapter 2: Running Quantum Circuits
 * [Using the BasicAer Simulators](chapter02_Running_Quantum_Circuits/chapter02-1_Using_the_BasicAer_Simulators.ipynb)
 * [Using the Aer Simulators](chapter02_Running_Quantum_Circuits/chapter02-2_Using_the_Aer_Simulators.ipynb)
 * Monitoring Job Status and Obtaining Results (no code examples)
## Chapter 3: Visualizing Quantum Measurements and States
 * [Visualizing Measurement Counts](chapter03_Visualizing_Quantum_Measurements_and_States/chapter03-1_Visualizing_Measurement_Counts.ipynb)
 * [Visualizing Quantum States](chapter03_Visualizing_Quantum_Measurements_and_States/chapter03-2_Visualizing_Quantum_States.ipynb)
## Chapter 4: Using the Transpiler
 * Quickstart with Transpile
 * Transpiler Passes
## Chapter 5: Quantum Information
 * [Using Quantum Information States](chapter05_Quantum_Information/chapter05-1_Using_Quantum_Information_States.ipynb)
 * [Using Quantum Information Operators](chapter05_Quantum_Information/chapter05-2_Using_Quantum_Information_Operators.ipynb)
 * [Using Quantum Information Channels](chapter05_Quantum_Information/chapter05-3_Using_Quantum_Information_Channels.ipynb)
 * [Using Quantum Information Measures](chapter05_Quantum_Information/chapter05-4_Using_Quantum_Information_Measures.ipynb)
## Chapter 6: Operator Flow
 * [Creating Operator Flow Expressions](chapter06_Operator_Flow/chapter06-1_Creating_Operator_Flow_Expressions.ipynb)
 * [Using the Operator Flow State Function classes](chapter06_Operator_Flow/chapter06-2_Using_the_Operator_Flow_State_Function_classes.ipynb)
 * [Using the Operator Flow Primitive Operators classes](chapter06_Operator_Flow/chapter06-3_Using_the_Operator_Flow_Primitive_Operators_classes.ipynb)
## Chapter 7: Quantum Algorithms
* Background on Quantum Algorithms
* Using the Algorithms Module
* Traditional Quantum Algorithms
* Eigensolvers
## Chapter 8: Qiskit Circuit Library Standard Operations
* Standard Instructions (no code examples)
* Standard Single-Qubit Gates (no code examples)
* Standard Multi-Qubit Gates (no code examples)
## Chapter 9: Working with Providers and Backends
* Graphical Tools
* Text-Based Tools
* Getting System Info Programmatically
* Interacting with Quantum Systems on the Cloud
## Chapter 10: OpenQASM
* Building Quantum Circuits in QASM
* Building Higher-Level Gates
* Classical Types and Instructions
* Building Quantum Programs
