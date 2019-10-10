
One of the main aims of statistical mechanics is to explain the macroscopic behavior, which is described by the laws of 
thermodynamics, in terms of the interactions among the particles at the microscopic level. 

Suppose we take a box of volumne V with N identical particles and total energy E. If we now join the
two together, such that there is no sepration between them, we will have a box of size 2V, with 2N particles and energy 2E. 
Properties such as these, which scale with system size, are called **extensive quantities**.

One of the most important statements made in statistical mechanics is that there exists a quantity, called entropy, which is both extensive (as mentioned earlier) and concave(over any of its dependent quantities). It is denoted as :
`S (E,N,V)`

The other two properties of entropy are that it is a monotonically increasing function and that in a closed system, left on its own, entropy will only increase and never decrease. In equillibrium, entropy reaches its maximum value.

---

Let us now look at the derivatives of entropy with respect to the three dependent variables. Let us take a thermally insulated box that has a partition in the middle which allows only the exchange of energy (heat) between the two compartments. At equillibrium : 

(The following are partial derivatives keeping N and V constant)
`E = E1 + E2 = constant`

`=> d/dE1 = - d/dE2`

`dS/dE1 = 0 = d(S1+S2)/dE1 = dS1/dE1 + dS2/dE1 = dS1/dE1 - dS2/dE2`

`=> dS1/dE1 = dS2/dE2`

The qunatity `dS/dE` at constant N and V is defined as `1/T`. This means that `T1 = T2`. This is what we would expect from a system in equillibrium, i.e. temperatures of the two compartments are the same.

Let us now look at the other partial derivatives.  Suppose we have a thermally conducting wall which can also move which means that not only the energy can vary but the volumes can change as well. 

Using similar argumnets as earlier, `dS1/dV1 = dS2/dV2`. The quantity `dS/dV` is defined as `P/T`. Since in equillibrium, we already know that `T1 = T2`, we can also see that `P1 = P2` for the box with a moving wall.

Lastly, lets look at the system where the partition wall is fixed but can allow energy and particles to exchnage between the two compartments. Similar to the previous case, we have a new quantity called chemical potential `mu` such `dS/dN = mu/T`. In the case of equillibrium, since the temperatures are same in the two compartments, the chemical potentials are the same as well `mu1 = mu2`

`T  =   dS/dE`
`P  = T dS/dV`
`mu = T dS/dN`



What we had seen earlier was that the quantities 'E, V, N' were **extensive variables**. The corresponding "derivative-related" qunatities that we saw `T, P and mu`, do not scale with the system size. These qunatities are called **intensive variables**. If we double the size of the box, the temperature of the box will not double.

---

Now we focus on the energy of the system. Energy of the system can be increased by heating the system or by doing work on the system. 

`dE = dQ - dW` first law of thermodynamics

While the (internal) energy `E` is a state function, the quantities `Q` and `W` are not. This means that the path taken to change the state of a system will change the quantities Q and W but their difference will be the same. These are also referred to as non-exact differentials.  

---

A **Process** refers to any change in the system. For example, this can be the change of a system left on its own, reaching the equilibrium or an agent changing the state of the system in some way. 

- quasi-static : the system is always close to equillibrium. Eg. a very slow moving piston.
- reversible : Heat energy is the only factor for the change in entropy of the system. `dQ = T dS`
- Spontaneous : For these processes, `dQ < T dS`
- Adiabatic : `dQ = 0`. No heat flowing into or out of the system.

