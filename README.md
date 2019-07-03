## Fusor Cockcroft-Walton Multiplier
For [Eastside Prep's Fusor project](http://www.eastsideprep.org/fusor-project/), we need a high voltage (~40 kV) and moderate current (~10 mA) power supply. This is my design for a [Cockcroft-Walton Multiplier](https://en.wikipedia.org/wiki/Cockcroft%E2%80%93Walton_generator) to fulfill those requirements.

While we originally bought a Cockcroft-Walton multiplier off Ebay for $100, we found that while it generated very high voltages (~150 kV) it collapsed under virtually any load (~100 µA). This is likely because it used small 22 pF capacitors. Since the circuit design for a CW multiplier is so simple, I opted to simply get new circuit boards made instead of trying to resolder new capacitors onto the exising boards.

The boards were designed using EAGLE and manufactured by JLBPCB. The capacitors and diodes were purchased off Ebay. The boards are designed to be given an input voltage of 15 kV AC (the output of a neon sign transformer), but they should work for any voltage.

This Github repo consists exclusively of the EAGLE files used to design these boards. 

*The manufactured but unsoldered circuit boards*
![](https://raw.githubusercontent.com/guberti/FusorCockcroftWaltonMultiplier/master/cwboards.jpg)

*The layout of the circuit boards in EAGLE*
![](https://raw.githubusercontent.com/guberti/FusorCockcroftWaltonMultiplier/master/boardLayout.png)
