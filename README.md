# Neural Network

## Artificial Neuron

### input signal
x1 + x2 + x3 ... xn {while x = 0 || 1 }

### Weights
w1.x1 + w2.x2 + w3.x3 ... wn.xn

### Alpha
a = &Sigma; wnxn

### Theta 
Hard limit

### Gamma
&gamma; = 1 if &alpha; >= &theta;

&gamma; = 0 if &alpha; < &theta;

### Sigmoid
&gamma; = &sigma;(&alpha;) = 1 / 1+ e <sup>-(&alpha; - &theta;)/p</sup>

where e = 2.7183

### Time
da/dt= - &alpha;a + &beta;s

### Changes
a > 0 then a/dt < 0;
a < 0 then a/dt > 0;

### Equilibrium Value
a <sub>eqm</sub>= (&beta; / &alpha;)s


