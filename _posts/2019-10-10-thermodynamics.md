
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

`dE = dQ - dW` **first law of thermodynamics**

While the (internal) energy `E` is a state function, the quantities `Q` and `W` are not. This means that the path taken to change the state of a system will change the quantities Q and W but their difference will be the same. These are also referred to as non-exact differentials.  

---

A **Process** refers to any change in the system. For example, this can be the change of a system, left on its own, reaching the equilibrium or an agent changing the state of the system in some way. 

- quasi-static : the system is always close to equillibrium. Eg. a very slow moving piston.
- reversible : Heat energy is the only factor for the change in entropy of the system. `dQ = T dS`
- Spontaneous : For these processes, `dQ < T dS`
- Adiabatic : `dQ = 0`. No heat flowing into or out of the system.

Let us look at quasi-static process in further details. First consider the case `dW=0`. Keeping N and V fixed,

`dS = S(E + dE) - S(E) = dE ds/dE = dE/T`

Since, `dW=0, dE = dQ`. Which implies `dQ = T dS` i.e. a quasi-static process is reversible. 

However, in general, `T dS >= dQ` which is **second law of thermodynamics** 

Next let us consider the case of reversible process in which the total energy doesn't change i.e. `dE = 0`. 

`dE = dQ - dW = 0` 

`=> TdS - PdV = 0` (as the process is reversible, `dQ = T dS`)

`dS/dV = P/T` (at constant E and N)

In general, `dE = TdS - PdV + mu dN` **Ist law**

A few examples : 

Consider a closed box with a movable piston in a quasi-static process. As the gas molecules hit the movabale piston, they will push the piston and in-turn return to the box with a slower velocity. This means that the temperature of the system will decrease due to the work done by the piston. As the system is insulated, `dQ =0`.

In the second case, we quickly remove the piston. In this case no work is done by the system as the piston was simply removed. As the system is insulated, dQ=0. However, the entropy change `del S >= 0`. So, in this case, `del S >= del Q /T`.


Next, let us consider two systems that are connected thermally i.e. there is a transfer of heat `del Q` or energy `del E` (since `del W =0`). between the two systems. We are interested in looking at the change in entropy of the system.  The system with the larger slope on S vs E graph, has the lower temperature and vice versa. Heat flows from hot to cold. 

---
### From entropy to energy :


`E(S,X)` has a minimum as a function of X which is reached at equilibrium. Also E is convex. 





