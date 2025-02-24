## Electric Charge and Force

- backstory
    - when rubbing stuff, things are attracted to each other. Since stuff is counteracting gravity, a force had to be applied.
    - In ancient Greece, this force is called electric force
    - experimentation showed that certain materials would attract each other after rubbing, while others would repel
    - it was also found that this effect would wear off
    - it was thought that something was being exchanged, so it was named charge. because objects had two states, being repelled or being attracted, it was postulated that this charge came in two types
    - benjamin franklin decided to define these as positive and negative charge. like repels like and attracts opposite
    - he also theorized that no new charge is created, meaning that it acts that same as heat or entropy in a closed system.
    - charge gained by one object is exactly equal in magnitude and opposite in sign to the charge lost elsewhere
- summary
    - electric charge is a conserved quantity
    - there is positive and negative charge
    - all materials that are conductive will attempt to equalize charge upon contact.
- charging by friction
    - when two materials come into contact and are quickly rubbed, electrons transfer over due to electronegativity and then get trapped
    - when two dissimilar objects are rubbed together, this is charging by friction
    - the more electronegative object will become negatively charged, while the other object will become more positively charged when rubbing

## atomic strucutre and source of charge

- electrons are negative, nucleas and protons are positve.
- $3.2 \times10^{-19} \ C$ represents the charge of a single electron, meaing all charges must be multiples of that
- protons are 1800 times more massive then electrons

## Conduction and Induction

- solids are one of three things:
    - conducters - electrons can move freely
    - semi conductors - both
    - and insulators - electrons move only short distances
- since electrons repel each other they will spread out across a conductor (protons also repel but they are much heavier and locked down and so don’t spread)

- polarization in insulators and conductors
    
    - polarization is signifncatly weaker in insulators then in conducctors
    
    ![[image 9.png|image 9.png]]
    
    ![[image 1 2.png|image 1 2.png]]
    

- electrons flow to the ground, the earth is so big and so conductive that all electrons eventually end up there
- most electrical devices are grounded to prevent a charge build jump that could hurt you

- charging by conduction
    - 2 conductors are insulated and transferring charge between them. they should be insulated to prevent charge loss to ground
    - the charge then distributes equally
    - the charge of each one after equalization will be the average ($\frac {x_1 + x_2}{2}$)
- charging by induction
    - charging by induction involves charging objects without having them make contact.
    - ground a conductor and bring a negatively charged rod near (but not touching). Electrons in the sphere are repelled by the rod and then go to the ground, leaving a positive charge on the sphere
    - if you remove the ground, the electrons cannot return, leaving the sphere forever positive

## electroscope

- a thing is charged, then its parts repel cuz they have same charge.
- ![[image 2 2.png|image 2 2.png]]
    
- if the electrode is grounded, it can also be done via induction
    
    ![[image 3 2.png|image 3 2.png]]
    

## Electric Force

- when two objects repel or attract, they are applying force on one another.
- the electric force between two charges depends on the inverse square of the distance between them:
    
    ![[image 4 2.png|image 4 2.png]]
    

$$\vec F_E \propto \frac{1}{r^2}$$

- the magnitude of electrical force is

$$\begin{aligned}
| \vec F_E| = \frac{|q_1q_2|}{4\pi\epsilon _0 r^2} \\ \ \\  
4 \pi \epsilon_0 = constant  
\\ q = charge \\ r = distance
\end{aligned}$$

- $\epsilon$ represents the electric permittivity
    - which is the measure of matters resistance to the propagation of an electric field. the electric permittivity of a vacuum has a special value, which is a constant.
    - this value is: $8.85 \times 10^{-12} \frac{C^2}{N\cdot m^2}$
- usually $\frac{1}{4\pi\epsilon _0}$ is replaced with $k$ to make the following expression for electrical force

$$|\vec F_E| = \frac{|kQq|}{r^2} \\ \ \\ k = 9.0 \times 10 ^9 \frac{N\cdot m^2}{C^2}$$

## Superimposition of Electrical Forces

- you need to calculate the net initial force on each charge
    - theoretically the charges will react to their initial net forces, but this is beyond scope and therefore don’t care about it

- Assumptions
    - assume all charges are immobile
    - draw a free body diagram for every charge
    - use coulombs law to find the magnitude of each force, then add the vectors (direction assumed via charge)
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

- for a conducive sphere with radius $R$ the following graph can show the relation between the electric force and the distance from the center of the sphere
    
    ![[image 6 2.png|image 6 2.png]]
    

## Electric and gravitational fields

- there is a similar relationship between the electric field and the gravitational field because they both generate central forces.
- magnitude of the force depends on the distance between the point and the center
- gravitational field is always positive because mass is always positive, but electric field can be negative or positive meaning its attractive or repulsive (unlike gravity)
- gravity is weaker then electrical force

## electric field of multiple charges

- electric field is a vector, therefore if there are multiple charges, you can just add the vectors

- this an example of how it looks with two like charges
    
    ![[image 7 2.png|image 7 2.png]]
    
- this is an example of how it looks with two unlike charges
    
    ![[image 8 2.png|image 8 2.png]]
    

- net eletric field can now be calcaulted by

$$\vec E_{net} = \Sigma \vec E_n \\ \ \\ n = \text{total number of fields}$$

## eletric feild in multiple dimensions

- more vector addition
- think with thy head

## uniform eletric fields

- uniform electric fields is when you have a massive amount of charged particles that create a uniform field
    
    ![[image 9 2.png|image 9 2.png]]
- assumed that the force of gravity is negligble, as electronsd and protons fg is so small
- since the eletric filed inbetween two plates is consant, all the following eletrcons are experincing the same force
	![[Pasted image 20250224100327.png]]

## Electric potential and capacitors
- Start with two postive charges initially at rest, with $Q$ and origin and $q$ at rest. 
	- let $Q >> q$ so the field of $q$ is negligable
	- the field that $Q$ creates has to be counteracted by an external force $F_{ext}$ 
	- if q is moved at a constant $v$  $|\vec{F_{ext}}| =  |\vec{F_{E}}|$ 
	- when a **conservative** force exerts a force on an object, the work done is via displacment, not distance. 
	- eletric field is a conservative force, meaning its not used up when exerting force
	- if the object is being pushed against the field, the work of the field is negative, if it is being pushed towords the field, the work of the field is positve
	- this means the internal energy is represented by the following relation:
	$$ \Delta U_{E} = -W_{E}$$
	- where $\Delta U_{E}$ represents the change in energy in the system
		- if you have to push against the field ($W_E$ is negative) energy must be added
	- if we are pushing the objject towrods origin, assuming that both have the same charge $$ \begin{gather}
	 \Delta U_{E} = -W_{E} \\ 
	 \Delta U_{E} = \int_{\infty}^r F_{E} \cdot dr \\
	 	 \Delta U_{E} = \int_{\infty}^r \frac{k|Qq|}{r^2} \cdot dr \\
∫ \frac{1}{r^2} dr=- \frac{1}{r}​ \\
\text{integral of } \Delta U = U \\
U = k|Qq|\left[ - \frac{1}{r} + \frac{1}{\infty}\right]
\\
W = k|Qq|\left[ - \frac{1}{r} \right]
\\ W = -  \frac{k|Qq|}{r}


\end{gather}$$
testing


friction force is based on electrical force, because friction is actually felt by electric force. Normal force (anti gravity force) is actually the electric force pushing up
