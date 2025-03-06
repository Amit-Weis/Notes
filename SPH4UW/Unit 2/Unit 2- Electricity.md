## Electric Charge and Force

friction force is based on electrical force, because friction is actually felt by electric force. Normal force (anti gravity force) is actually the electric force pushing up

- backstory
    - when rubbing stuff, things are attracted to each other. Since stuff is counteracting gravity, a force had to be applied.
    - In ancient Greece, this force is called electric force
    - experimentation showed that certain materials would attract each other after rubbing, while others would repel
    - it was also found that this effect would wear off
    - it was thought that something was being exchanged, so it was named charge. because objects had two states, being repelled or being attracted, it was postulated that this charge came in two types
    - Benjamin Franklin decided to define these as positive and negative charges. like repels like and attracts opposite
    - he also theorized that no new charge is created, meaning that it acts the same as heat or entropy in a closed system.
    - charge gained by one object is exactly equal in magnitude and opposite in sign to the charge lost elsewhere
- summary
    - electric charge is a conserved quantity
    - there is positive and negative charge
    - all materials that are conductive will attempt to equalize charge upon contact.
- charging by friction
    - when two materials come into contact and are quickly rubbed, electrons transfer over due to electronegativity and then get trapped
    - when two dissimilar objects are rubbed together, this is charging by friction
    - the more electronegative object will become negatively charged, while the other object will become more positively charged when rubbing

## atomic structure and source of charge

- electrons are negative, nuclei and protons are positive.
- $3.2 \times10^{-19} \ C$ represents the charge of a single electron, meaning all charges must be multiples of that
- protons are 1800 times more massive than electrons

## Conduction and Induction

- solids are one of three things:
    - conductors - electrons can move freely
    - semiconductors - both
    - and insulators - electrons move only short distances
- since electrons repel each other they will spread out across a conductor (protons also repel but they are much heavier and locked down and so don’t spread)

- polarization in insulators and conductors
    
    - polarization is significantly weaker in insulators then in conductors
    
    ![[image 9.png|image 9.png]]
    
    ![[image 1 2.png|image 1 2.png]]
    

- electrons flow to the ground, the earth is so big and so conductive that all electrons eventually end up there
- most electrical devices are grounded to prevent a charge build jump that could hurt you

- charging by conduction
    - 2 conductors are insulated and transfer charge between them. they should be insulated to prevent charge loss to ground
    - the charge then distributes equally
    - the charge of each one after equalization will be the average ($\frac {x_1 + x_2}{2}$)
- charging by induction
    - charging by induction involves charging objects without having them make contact.
    - ground a conductor and bring a negatively charged rod near (but not touching). Electrons in the sphere are repelled by the rod and then go to the ground, leaving a positive charge on the sphere
    - if you remove the ground, the electrons cannot return, leaving the sphere forever positive

## electroscope

- a thing is charged, then its parts repel cuz they have the same charge.
	- ![[image 2 2.png|image 2 2.png]]
    
- if the electrode is grounded, it can also be done via induction
    
    ![[image 3 2.png|image 3 2.png]]
    

## Electric Force

- when two objects repel or attract, they are applying force on one another.
- the electric force between two charges depends on the inverse square of the distance between them:
    
    ![[image 4 2.png|image 4 2.png]]
	    

	$$\vec F_E \propto \frac{1}{r^2}$$

- the magnitude of electrical force is

	- $$\begin{aligned} | \vec F_E| = \frac{|q_1q_2|}{4\pi\epsilon _0 r^2} \\ \ \\   4 \pi \epsilon_0 = constant \\ q = charge \\ r = distance \end{aligned}$$

- $\epsilon$ represents the electric permittivity
    - which is the measure of resistance to the propagation of an electric field. The electric permittivity of a vacuum has a special value, which is a constant.
    - this value is: $8.85 \times 10^{-12} \frac{C^2}{N\cdot m^2}$
- usually $\frac{1}{4\pi\epsilon _0}$ is replaced with $k$ to make the following expression for electrical force

	- $$|\vec F_E| = \frac{|kQq|}{r^2} \\ \ \\ k = 9.0 \times 10 ^9 \frac{N\cdot m^2}{C^2}$$

## Superimposition of Electrical Forces

- you need to calculate the net initial force on each charge
    - theoretically the charges will react to their initial net forces, but this is beyond scope and therefore don’t care about it

- Assumptions
    - assume all charges are immobile
    - draw a free body diagram for every charge
    - use coulomb's law to find the magnitude of each force, then add the vectors (direction assumed via charge)
    - $F_{12}$ is the force that $Q_1$ exerts on $Q_2$
    - $F_{12} = -F_{21}$

## Super imposition of electrical forces 2D edition

- just do vectors lol
- get gud

## Electric Field

- $|\vec F_E| = \frac{|kQq|}{r^2}$ can be understood by assuming the $\vec F_E$ is being applied over a field
- divide the above equation by $q$ and assuming the $Q$ is big enough to make it insignificant
- electric field $\vec E$ gives the magnitude of the force of $Q$ on $q$ at any point

$$\vec E = \frac{\vec F_E}{q} = \frac{\frac{|kQq|}{r^2}}{q} = \frac{|kQ|}{r^2}$$

- $\vec E$ is a mathematical abstraction that lets us visualize the strength of an electric field as you get farther away
- electric field lines
    - will begin on positive and end on negative
    - the density of the lines is proportional to the size of the charges
    - the lines never cross
    - the lines are continuous
        
        ![[image 5 2.png|image 5 2.png]]
        
- based on the surface area of a sphere, we can see that

$$\vec F \propto \vec E \propto \frac{1}{r^2}$$

- excess charge on a conductor resides on the surface, and it has reached electrostatic equilibrium.
- electrostatic equilibrium means that no more charges are moving within the conductor, and therefore there is no net electric force on them
- since there is no net electric force there is no electric field, since $\vec E \propto \vec F$

- for a conductive sphere with radius $R$ the following graph can show the relation between the electric force and the distance from the center of the sphere
    
    ![[image 6 2.png|image 6 2.png]]
    

## Electric and gravitational fields

- there is a similar relationship between the electric field and the gravitational field because they both generate central forces.
- magnitude of the force depends on the distance between the point and the center
- gravitational field is always positive because mass is always positive, but electric field can be negative or positive meaning its attractive or repulsive (unlike gravity)
- gravity is weaker than electrical force

## electric field of multiple charges

- electric field is a vector, therefore if there are multiple charges, you can just add the vectors

- this an example of how it looks with two like charges
    
    ![[image 7 2.png|image 7 2.png]]
    
- this is an example of how it looks with two unlike charges
    
    ![[image 8 2.png|image 8 2.png]]
    

- net electric field can now be calculated by

$$\vec E_{net} = \Sigma \vec E_n \\ \ \\ n = \text{total number of fields}$$

## electric field in multiple dimensions

- more vector addition
- think with thy head

## uniform electric fields

- uniform electric fields is when you have a massive amount of charged particles that create a uniform field
    
    ![[image 9 2.png|image 9 2.png]]
- assumed that the force of gravity is negligible, as electrons and protons fg is so small
- since the electric field in between two plates is constant, all the following electrons are experiencing the same force
	![[Pasted image 20250224100327.png]]

## Electric potential and capacitors
- see [The Secret Calc Part of Physics](The%20Secret%20Calc%20Part%20of%20Physics.md)
# electric potential (voltage)
- $\Delta V = \frac{\Delta U_{E}}{q} = \frac{\frac{kQq}{r}}{q} = \frac{kQ}{r}$
- Our study of electricity began with Coulomb's Law which calculated the electric force between two charges, Q and q. 
-  By assuming q was a small positive charge, and dividing F by q, the electric field E due to the charge Q was defined.
- we can do the same thing with E and V
$$
\Delta V = \frac{\Delta U_{E}}{q} = \frac{\frac{kQq}{r}}{q} = \frac{kQ}{r}
$$
- voltage tells how a charge is bending the space is around it 
- it also tells us how much potential energy is in each charge
- it will also tell us how much work/per charge it can do (since $\Delta U_E= -W_E$)
- Up is representing positive Voltage, and down is representing Negative voltage
	**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUfF9DT4MD7wmhKU1qw5UfQU_2HhIfSE39Alg1aMiJfuXq_LWwpxweHms1ILymEbogjAne02Z2cPyYOBngir06v6hbNe1x1JB1Mw8SgDqR5wnyR58sbfjeEfxJbcw5gZzkWPA1VfBQ=s2048?key=x4nBD2Mcw9wgdoyjCVv3YUHC)**
	- positive charges will fall "down" and negative charges will fall "up"
- The SI units for voltage is $\frac{J}{C}$
- in natural language, it's the amount of joules of energy produced per one coulomb of charge that goes through
- AA batteries and AAA batteries both have $1.5 V$, but AA is siginfinactly bigger
	- all this means is that the AA battery has more chemical reactants and will last longer 
	- a battery being "$1.5 V$" just means that each electron is leaving the battery with the same electric potential
- we can rearrange the equation to find (look at ) $$ W_{ext} = \Delta U_{E} = q\Delta V$$

-  if multiple charges are involved:
$$

\begin{gather}
V_{net} = k \Sigma\frac{ Q}{r}

\\ \\
(V_{net} = V_{1} + V_{2}+ V_{3} \text{ etc...})

\end{gather}

$$
## Electric Potential Energy due to a uniform Electric Field
- recall
	- a uniform electric field is created by two infinite plates of charge 
	- the planes have equal charge, thus creating a uniform field
	- the field outside of the plates is zero
	- the typical photo of two plates is an idealized/expanded picture of a capacitor
	 ![](../../images/Pasted%20image%2020250226163336.png)
	- real capacitors will have a much smaller distance between their plates
	- the electric field is generated by the separation of the charge, and its reason is the difference in electric potential (volts) 
	- if a charge is being pushed against the field by an external force, the field is doing negative work, and the external force is doing positive work
	- movement in a uniform electric field is directly analogous to movement of a mass within our intuitive grasp of gravity
## Electric potential due to a uniform electric field
- since its uniform $V \neq \frac{kQ}{r}$ as its no longer depended on the distance between the charges since the field is constant
- instead a new formula has to be derived
$$
\begin{gather}
F_{E} = qE \text{ in a uniform electric field} \\

U_{E} = -W_{E} = -F_{E}d = -(qE)d  \\
\frac{U_{E}}{q} = -Ed \\
\frac{q\Delta V}{q} = -Ed \\
\Delta V = -Ed
\end{gather}
$$
- the formula sheet shows this formula as $|\vec{E}| =|\frac{\Delta V }{\Delta r}|$
- thinking about a conductor, since there is no field inside the conductor, that means that the electric on the surface is the same as anywhere within the conductor (since $\Delta V=-Ed$)
- summary of formulas:
$$
\begin{gather}
\text{point charges only:} \\
|\vec{F_{E}}| = \frac{k|Qq|}{r^{2}}  \\
|\vec{E}| = \frac{k|q|}{r^{2}} \\
U_{E} = \frac{kQq}{r} \\
V = \frac{kQ}{r}
\\  \\
\text{any situation:} \\
\vec{E} = \frac{\vec{F_{E}}}{q} \\
\Delta U_{E} = q\Delta V \\
 \\
 \\
\text{only uniform electric fields:} \\
\vec{E} = |\frac{\Delta V}{\Delta r}| \\
\Delta U_{E} = -qEd

\end{gather}
$$
## Capacitance and Capacitors 
- "arcing" means there is enough energy to make air a conductor 
- simplest version of a capacitor is the parallel plate capacitor 
- diagrams make the plates look far apart,  but it's very close
- when a battery is connected the charge moves between them, every electron that moves to the negative plate leaves a positive ion behind 
- the plates have equal magnitudes of charge. but one is positive and the other is negative
- this generates a uniform electric field (sorta)
- the reason it's basically uniform, is because the distance between the plates is so small compared to the surface area 
- a capacitor can store a certain amount of charge for a given voltage, this is called capacitance, $C$
- by definition 
- $\Delta V=\frac{Q}{C}$
- $C = \frac{Q}{\Delta V}$
- SI unit is Farad $F$, or $C/V$
- $C \propto \text{ Area of Plate}$ and $C \propto \text{Distance Between Plates}$
- to calculate $C$ based on the area of plate and the distance between plates we need a constant
- the constant is the permittivity of free space
$$
\begin{gather} \\
\epsilon =
8.85 \times 10^{-12} \frac{C^{2}}{Nm^{2}}\\
\therefore \\
C = \frac{\epsilon A}{d}
\end{gather}
$$
- the charge will forever hold charge
- $V$ will linearly decrease/increase (because it's a quasi uniform electric field )
	-![](../../images/Pasted%20image%2020250227101454.png)
- the first time you move  a charge, there is zero work, since there is no diff in voltage
- however, every subsequent electron will be doing a little bit more work each time
- since its a linear relation, the average will be $\frac{1}{2}e\Delta V$
- to find the amount of work required to charge a capacitor a charge of $Q$ 
$$
W = \frac{1}{2}Q\Delta V
$$
- since the work done is that, the potential to do work in the future is also
$$
U_{E} = \frac{1}{2}Q\Delta V
$$
- you can also find
$$
U_{E} = \frac{1}{2} \frac{{Q^{2}}}{C}
$$
- and 
$$
U_{E} = \frac{1}{2} C(\Delta V)^{2}
$$
## Dielectrics
- capacitance can be increased by inserting a dielectric an insulator into the gap
	- ![](../../images/Pasted%20image%2020250227103628.png)
- the additional electric field generated by the additional increases the efficiency of the capacitor 
- the dielectric is originally neutral, but becomes polarized when charged 
- the reason the dielectric is useful is because you can make the distance between the plates really small, and not have to worry about arcing 
- every material has a dielectric constant $\kappa$ 
- therefore the capacitance becomes 
$$
\begin{gather} \\

C = \frac{\kappa\epsilon A}{d}

\end{gather}
$$
q = point charge
Q = uniform electric fields

