# Currrent Mirror using nmos
A current mirror is a circuit created to manage the current flowing through another active device in the circuit, maintaining a consistent output current independent of the load.<br>

The basic circuit for the current mirror using nmos will look like this

![1 1](https://user-images.githubusercontent.com/111113962/190994629-ea6015ce-5755-4aa4-b53b-077cebacc15d.png)
to replicate the current in the adjoining nmos we have to short circuit the drain node and gate node of source nmos.

First we will find out the resistance of the circuit.
We will do AC analysis of the circuit for the frequency sweep of 1 to 1GHz.
It will be found using the Id vs the Frequency plot. Now inverse of magnitude will provide us the resistance. The resistance I got is 165.6 Kohm
the resistance plot will be
![3resistance](https://user-images.githubusercontent.com/111113962/190994761-6a5fb67a-b032-4779-8cd7-d1f2b10f3f28.png)


then we will plot the Id vs Vds to find the mirrored current and it will be done using DC analysis. The Vds will be varied from 0 to 1.8V.
The plot will as follows.
![2](https://user-images.githubusercontent.com/111113962/190994788-731df004-ae91-4a07-a22b-a15451d94a1e.png)

The gate voltages for the both nmos will be as follows
![1](https://user-images.githubusercontent.com/111113962/190994746-ed3d5bee-ed65-441e-973a-b42cd5131020.png)

We can see in the current plot that at gate voltage the current is nearly 100 uA.
Iout=Iref
