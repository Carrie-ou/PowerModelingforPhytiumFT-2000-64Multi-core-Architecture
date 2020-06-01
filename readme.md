# Power Modeling for Phytium FT-2000+/64 Multi-core Architecture



## Motivation

In an era where computing hardware hits the power wall, increasing the energy efficiency of our computing systems is of paramount importance. Indeed, power and energy consumption has become the first-class design constraint of computing architectures. Although performance optimization is a familiar topic for developers, few are aware of the application power profiles of the underlying hardware. Therefore, developers require tools that analyze the power and energy consumption.



## Datasets

| Benchmarks   | Description                                                  |
| ------------ | ------------------------------------------------------------ |
| RandomAccess | This benchmark is designed to measure the random update frequency of the memory subsystem. |
| PTRANS       | This benchmark tests the network communication capability of parallel metrics transpose. |
| DGEMM        | This benchmark measures the floating-point arithmetic performance by performing double-precision metrics multiplication. |
| STREAM       | This benchmark measures the memory bandwidth of computing nodes. |
| FFT          | This measures the floating-point arithmetic capability by performing one-dimensional discrete Fourier Transform using double-precision operations. |



## How to reproduce the baseline results?

> Step 1. Download the data material above.

> Step 2. Use both real power and  indicators to train a linear power model. The detailed method is described in the paper *Power Modeling for Phytium FT-2000+/64 Multi-core Architecture*.

> Step 3. Input indicators and use power model to estimate power.

The paper mainly use data *FT_4w_8core.xls* to build power estimation model. Data *FT_8w_XXcore.xls* are used to explore the scalability of our model.


**TODO**

-  Provide estimation power model through machine learning method.



## Acknowledgements

This work is supported in part by the Advanced Research Project of China under grant number 31511010203 and the Research Program of NUDT grant number ZK18-03-10.

