# ChipJabber-BasicBBI

What the heck is Body Biasing Injection? This is a method of injecting faults into the backside of an IC, which results in an injection somewhere between EMFI & Laser-FI. This work has been presented since 2012, yet there is little follow on work.

You can see the following papers for the origins of this:

	Philippe Maurine, Karim Tobich, Thomas Ordas, Pierre Yvan Liardet. Yet Another Fault Injection
	Technique : by Forward Body Biasing Injection. YACC’2012: Yet Another Conference on Cryptography, Sep 2012, Porquerolles Island, France. fflirmm-00762035f


## BBI Made Simple

BBI uses a simple idea - use a physical probe on the IC die *backside*. While it turns out that WLCSP devices expose the backside (or have some flimsy film over it you can remove easily), allowing you to perform BBI without becoming [John McMaster](https://twitter.com/johndmcmaster).

The idea of this repo is to perform BBI using a simple probe, which uses a transformer to generate the required pulses. This looks something like this:

![](img/bbi.png)

## CARDIS 2020 Paper

This work was presented at CARDIS 2020, see an extended version of the paper in the [CARDIS](cardis2020/ChipJabber_BBI.pdf) directory of this repository.