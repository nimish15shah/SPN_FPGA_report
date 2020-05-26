# Master's thesis - Antoine Gennart

This document aims to describe the general structure of the final master's thesis on implementation of Sum Prodcut network using posit representation on FPGA.

TODO : Find results that I want to compute
TODO : Find figures that I want to show
--> after that, we can write the text

## Abstact

+ describe my contribution

## Introduction

Discuss SPNs and applications of SPNs

Describe the goal of the master thesis:

--> Find an optimal representation of data inside a SPNs for precision, speed, and hardware.

* Precision is computed by bounding the error of SPNs using different representations

* Speed depends on the size of the representation (posit or float), and the size of the SPNs (number of pipelines, ...)

* Hardware size depends on size of the representation also (posit or float)


Everything is hosted on github and available for other people !!

## State of the art

+ some other works from other people (other hardware implementation, limitations, ...)

### Sum product networks - Artithmetic circuit

* Description of SPNs

* SPNs properties

* Training SPNs

### Posit representation

* Description of Posit representation fields

### Floating point representation

* Description of floating point representation fields

## Error bounds

### Error bounds for POSIT

* Encoding error

* Addition error

* Multiplication error

### Error bounds for Float

* Encoding error

* Addition error

* Multiplication error

### Error bound for SPNs

## Hardware implementation

### Posit representation

* Basic building blocks

### Sum Product Networds

* Show methodology (complete workflow)

## Results and experiments

+ describe results and settings for these results

### Error bound

Hypothesis : Double floating point numbers have ultimate precision for AC

Make analysis for multiple SPNs: 1 dummy to show methodology, others not dummy to show real result

1. Show error bound in different cases of SPNs

	* Error bound float vs posit

	* Different SPNs:

		* Different depths

		* Different number of inputs

2. Show that this error bound in valid


### Hardware implementation

* Size of adder / multiplier as a function of posit size

* Maximum number of nodes in a ZedBoard

* Speed

## Conclusion


+ Find experiment to proove that the error bound is correct
-> Scatter of error comparing posit vs float