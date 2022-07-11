# Quantum Entanglement

Adapted from [Hughes, C., Isaacson, J., Perry, A., Sun, R.F., Turner, J. (2021). Entanglement. In: Quantum Computing for the Quantum Curious.](https://rdcu.be/cRgeZ)    

**Quantum entanglement** is the physical phenomenon that occurs when a group of particles are generated, interact, or share spatial proximity in a way such that the quantum state of each particle of the group cannot be described independently of the state of the others, including when the particles are separated by a large distance.<sup>[1]</sup>   

## Entanglement Fundamentals
To provide one example of the strange behavior of entanglement, suppose we have two fair coins. Classically, if you flipped two fair coins many times, you would measure the outcomes HH, HT, TH, or TT, each occurring with a 25% probability.   

However, **by quantum entangling these two fair coins** (In real life, coins can't be entangled. It is just an anology to understand what entanglement is), it is possible to create a state  

```
( 1/√2 )( |HH⟩ + |TT⟩ ) -> Bell State represented using Bra–ket notation, 
dw will explain what this means
```

They are entangled in such a way that only two measurement outcomes are possible:    
(1) both coins land on heads; or  
(2) both coins land on tails;  
each outcome occurring with 50% probability. You would never see HT or TH! This is what is represented using   
Bra-Ket notation `( 1/√2 )( |HH⟩ + |TT⟩ )` (Bra-Ket is just a notation to represent the quantum states, don't get overwhelmed)

| Flipping entangled coins | Entangled coins communicating with each other  |
|:------------------------:|:----------------------------------------------:|
| <p align = "center"><img src="assets/coin%20entangled.png"></p> | <p align = "center"><img src="assets/coin%20entangled%202.png"></p> |


Furthermore, if the two entangled coins are separated by thousands of miles, one coin can be flipped and measured. In this case, if the measured coin produced the outcome heads, then we automatically know that the other coin must also land on heads. If the measured coin produced the outcome tails, then we automatically know that the other coin must also land of tails! If this isn’t strange enough, this appears to suggest that the two coins can transmit information instantaneously, and possibly even faster than the speed of light (the fastest speed in the Universe).   

Two coins are separated with no means of communication between each other. Classically, the flip of the second coin would be unrelated to the first flip. However, entangled coins would still produce correlated results.  

How does the other coin instantaneously “know” what was measured on the other? Is information somehow being transmitted faster than the speed of light? Einstein called this behavior a **“spooky action at a distance.”** It has since been shown that no information is being transmitted from one place to the other, and so no information is being transmitted faster than the speed of light. Rather, the particles share **non-classical information at the time of entanglement**, which is then observed in the measurement process. The **correlation** between **entangled qubits** is the key that allows quantum computers to perform certain computations much faster than classical computers.  

---

## Hidden Variable Theory

It is tempting to think that there may be some classical explanation for entanglement. **Did the entanglement change the fair coins by adding extra mass to the heads side or the tails side, thereby making them unfair?** Nope.   

To provide a more *realistic example in a classical system*, consider a particle that decays into two lighter particles. The momenta of these three particles are related by the conservation of momentum: `pf = p1 + p2`.   

Given a known total initial momentum, then by measuring the momentum of one of the final state particles, we can determine the momentum of the other final state particle. In summary, by measuring one particle’s momentum, we know the other. **Momentum is the hidden classical variable that is encoded when the two particles are created.** Naturally, the question arises: is there a conceptually similar hidden variable in the quantum mechanical situation?

Hidden Variable Theory tried to explain entanglement using classical physics. It tried to add hidden variables that explained how the bits never transmitted information with each other but instead was just observed to do so. However, Bell’s theorem demonstrated that the correlation between entangled quantum particles is more than what is possible classically, disproving the idea of a hidden variable. **As such, entanglement is a purely quantum phenomenon with no classical explanation.** Bell's Theorem is beyond the scope of this learning, but you are welcomed to give it a read if you are interested.<sup>[2]</sup>

[Additonal Read about Bell's Theorem on brilliant.org](https://brilliant.org/wiki/bells-theorem/) (You can skip this if you want)    
[Watch this video about Quantum Entanglement by Veritasium](https://www.youtube.com/watch?v=ZuvK-od647c)

---

## Entangling Particles irl

There are many different ways of physically entangling particles. One of the common methods called “spontaneous parametric down-conversion” shines a laser at a special nonlinear crystal. The crystal splits the incoming photon into two photons with correlated polarizations.

| A Nonlinear crystal creates two photons with entangled polarizations  | The generated photons can exist in both polarization states (<b>superposition</b> state) before it is measured  |
|:---------------:|:---------------:|
| <p align = "center"><img src="assets/photon%20entangled.webp"></p> | <p align = "center"><img src = "assets/superposition.gif" alt = "superposition in photons" > |

## References
1. https://en.wikipedia.org/wiki/Quantum_entanglement
2. https://brilliant.org/wiki/bells-theorem/
