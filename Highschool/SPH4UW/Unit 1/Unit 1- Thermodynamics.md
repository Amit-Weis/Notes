# Reminders

- Always convert to Kelvin
    - In conversion, add 273 when given temp has no decimals, or 273.15 when given temp has decimals

# Lesson 1 - Ideal Gas Law
---
- Relations between heat, work, temperature, and energy
- Isolated systems
- Focus on gases

$$P = \frac{F}{A} \\  
P = Pa = \frac{N}{m^2} \\  
F = N \\  
A = m^2$$

- Pressure can be derived from the force of the gas particles on the surface area on the container
- $psi, mm/Hg, Pa$
- Gas Assumptions:
    - Constant mass
    - Volume & Density can chance
    - Fill their container
- Ideal Gas Law
    
    - Thermodynamics is the study relations between heat, work, temperature and energy
    - All the tiny collisions of gas molecules pushing outward on a container is called pressure
    - Physical processes:
        - Temperature, Pressure, Volume
    - **Isothermal process**: when **temperature** is held constant
        
        $$P\ \alpha\ \frac{1}{V}$$
        
    - **Isobaric process**: when **pressure** is held constant
        
        - As $T \to 0K$, $V \to 0m^3$
        
        $$V\ \alpha\ T$$
        
    - **Isovolumetric** or **Isochoric** process: is when the **volume** is held constant
        
        - As $T \to 0K$, $P \to 0Pa$
        
        $$P\ \alpha\ T$$
        
    - Ideal gas law:
        
        $$PV = nRT \\  
        n = \text{\# of moles} \\  
        R = 8.314 \frac{J}{mol \cdot K} \\  
        \ \\  
        PV = Nk_bT \\  
        N = \text{ \# of molecules} \\  
        k_B = \frac{R}{N_A} = \frac{8.314}{6.022 \cdot 10^{23}} = 1.38 \cdot 10^{-23} \frac{J}{K}\\ \ \\  
        PV = nRT \\  
        \frac{PV}{T} = nR \\  
        nR = nR \\ \ \\\text{ (assuming n is constant)} \\  
        \frac{P_1V_1}{T_1}=\frac{P_2V_2}{T_2}$$
        
    
    ## Examples
    
      
    

# Lesson 2 - Kinetic Theory & Maxwell-Boltzmann Distributions
---
- ideal gas assumptions
    - **random**: particles move in random directions
    - **attraction**: the attraction between particles is negligible
    - **volume**: the volume of an atom is negligible
    - **elastic**: no energy is lost in the collisions of molecules
    - **duration**: time duration of collision is negligible
- there is no energy lost in an ideal gas system undergoing zero external force
- in non ideal gas there is energy lost in the system due to collisions not actually being elastic

- Deriving the relationship between temperature, average kinetic energy, and pressure (NOT ON ASSESMENTS)
    
    - recall:
    
    $$E_k = \frac{1}{2}mv^2 \\ \ \\ Pa = \frac{F}{A} \\ \ \\ p = mv$$
    
    - Using the impulse-momentum change theorem:
    
    $$F = \frac{\Delta p}{\Delta t} \\  
    \text{(where p = momentum, t = time)}$$
    
    - we can find $\Delta p$ by analyzing an ideal gas collision:
        
        ![[image 10.png]]
        
        - The momentum change is limited to $\Delta p_x$
        - since all collisions are elastic:
        
        $$\Delta p_x = p_{x2} - p_{x1} = 2p_x = 2mv_x$$
        
          
        
    - we can find $\Delta t$ by analyzing ideal gas conditions
        
        ![[image 1.png]]
        
        $time = \frac{distance}{speed}$
        
        $distance = L$
        
        $speed = v_x$
        
        $$\therefore\Delta t = \frac{2L}{v_x}$$
        
          
        
    
    - considering what we have gathered so far, the force F that one particle exerts on one wall of the box during $\Delta t$ can be found as:
    
    $$F_x = \frac{\Delta p_x}{\Delta t} \\ \ \\  
    \Delta p_x = 2mv_x \\  
    \Delta t = \frac{2L}{v_x} \\ \ \\  
    \therefore \\  
    F_x = \frac{2mv_x}{(\frac{2l}{v_x})} = \frac{mv_x^2}{L}$$
    
    - but we don't have one particle, we have a lot. therefore we multiply by number of molecules ($N$) and use thier average squared velocity to find the total force
    
    $$F_{x \ (total)} = N\frac{m\bar v_x^2}{L}$$
    
    - but we don't want just the force on one wall, we want the force on all the walls. therefore lets find the total velocity on all axes
    
    $$\overline {v^2} = \overline {v_x^2} + \overline {v_y^2} + \overline {v_z^2}$$
    
    - however, since the average velocity is the same on all axes (see ideal gas law assumptions) we can deduce the following equation:
    
    $$\overline {v^2} = 3\overline {v_x^2} \\  
    \frac{1}{3} \overline {v^2} = \overline {v_x^2}$$
    
    - merging these equations we can find the force exerted by all of the particles in all dimensions
    
    $$F_{x \ (total)} = N\frac{m\overline {v_x^2}}{L} \\  
    F_{x \ (total)} = \frac{1}{3} \cdot \frac{Nm\overline {v^2}}{L}$$
    
    - now we find the total pressure of the container
    
    $$P = \frac{F}{A} \\ \ \\ A = L \cdot L \\ \text{ \ \ (see cube above)} \\ F_{x \ (total)} = \frac{1}{3} \cdot \frac{Nm\overline {v^2}}{L}\\  
    P = \frac{\frac{1}{3} \cdot \frac{Nm\overline {v^2}}{L}}{L ^ 2} \\  
    P = \frac{1}{3} \cdot \frac{Nm\overline {v^2}}{L ^ 3} \\P = \frac{1}{3} \cdot \frac{Nm\overline {v^2}}{V}$$
    
    - Lets rearrange the equation to get PV on the left side
    
    $$PV = \frac{1}{3} \cdot Nm\overline {v^2} \\ PV = nRT = Nk_BT = \frac{1}{3} \cdot Nm\overline {v^2}$$
    
    - now we need to form a relasinship between the average kinetic enegry of its particles and the tempature
    
    $$Nk_BT = \frac{1}{3} \cdot Nm\overline {v^2} \\ k_BT = \frac{1}{3} \cdot m\overline {v^2} \\ \frac{3}{2} \cdot k_BT = \frac{1}{3} \cdot m\overline {v^2} \cdot \frac{3}{2} \\ \overline {E_k} = \frac{1}{2}m\overline {v^2} = \frac{3}{2}k_BT$$
    
    - therefore, the average kinetic energy of molecules in a gas is directly proportional to the temperature because of the following equation:
    
    $$\overline{E_k} = \frac{3}{2}k_BT$$
    
    - note the slides are wrong, if you want to find the total kinetic energy of a system, multiply by $N$. This equation is for the average kinetic energy per particle.
    - using this equation we can find something called the “root-mean-square” velocity
    
    $$\overline{E_k} = \frac{3}{2}k_BT = \frac{1}{2}m\overline{v^2}\\ \ \\ \therefore \\  
    v_{rms} = \sqrt{\overline {v^2}} = \sqrt{\frac{3k_BT}{m}}$$
    
- Summary of derivation
    
    $$v_{rms} = \sqrt{\overline {v^2}} = \sqrt{\frac{3k_BT}{m}}$$
    
    - the average velocity of molecules depends on the temp and mass of the molecule.
    
    $$\overline{E_k} = \frac{3}{2}k_BT$$
    
    - the average kinetic energy of molecules in a gas is directly proportional to the temp
    
    $$P = \frac{1}{3} \cdot \frac{Nm\overline {v^2}}{V}$$
    
      
    
    - the pressure of an ideal gas is directly proportional to the average square of the velocity of the molecules
    

- Maxwell-Boltzmann distributions
    - Probability/velocity is the axes
    - Particles move around with random speeds and directions, but one can model the predicted distributions.
    - The Maxwell-Boltzmann show the probability of finding a molecule traveling at a specific velocity when a gas is at a specific temperature
    - Average velocity may be x, but the most common velocity will be slightly lower then it.
    - As you increase temperature velocity increases, but peak of the probability distribution goes down

# Lesson 3 - PV Diagrams
---
- dude this shit is so easy don't even note: only PV graphs looking at temp vs P vs V

# Lesson 4 - heat and heat transfer
---
- What is Temperature?
    - A measure of the warmth/coldness of an object or substance with reference to some standard value
    - Examples being: Kelvin, Celsius and Fahrenheit
    - A measure of the ability of substance to transfer heat energy to another substance
    - The average kinetic energy of the particles in a sample of matter

  

- Thermometers relate the change in a physical property of a substance to its temperature. Examples include:
    - The change of volume of a gas or liquid
    - The change in length of a metal strip or wire
    - The light or infrared radiation emitted by an object

  

- When substances are in contact with each other, once they settle on a temperature, it is said that the substances have reached Thermal Equilibrium

  

- Most materials expand as they get warmer
    
    - 2 types of expansion, linear and volume. They can be modelled with the following equations:
        
        $$\Delta L = \alpha L_0 \Delta T \\ \ \\ \text{where} \\ \alpha = \text{coeficcient of linear expansion} \\ L = \text{Length of rod}$$
        
        $$\Delta V = \beta V_0 \Delta T \\ \ \\ \text{where} \\ \beta = \text{coeficcient of volume expansion} \\ v = \text{volume of rod}$$
        
    
    - note that $\beta = 3\alpha$, since its linear expansion in 3 dimensions simultaneously
    
    - Water is the one exception we care about to the above rule.
        - water instead follows this graph
            
            ![[image 2.png]]
            
        - this is the reason that ice will float, and that freezing a whole lake is very hard due to ice’s insulating properties
    
      
    

- Energy flows from the higher temperature object to the lower temperature object. this flow of energy is called heat.
    - also known as thermal energy transfer
    - listed in joules

  

- Zeroth Law of Thermodynamics
    - When two objects are placed in thermal contact they will come to thermal equilibrium
    - Holds true for chaining of objects  
          
        
        ![[image 3.png]]
        
        $$\because \\ T_1 = T_3\ \\ T_2 = T_3 \\ \ \\T_1 = T_2$$
        
- Convection is the process where heat is transferred by the friction caused by the movement of molecules in gases and liquids.
    - warm fluids and warm gasses rise, therefore it will make a system of water rising when its hot, then cooling, then falling, etc
        
        ![[image 4.png]]
        

  

- Radiation is energy transferred by electromagnetic waves.
    - can exist in vacuum
    - electromagnetic waves are predominantly photons

- Conduction is the flow of heat due to the transfer of kinetic energy due to molecular collisions.
    - if a cold object is in contact with a hot object, the collisions are going to transfer energy from the hot/fast moving molecule to the cold/slow moving particle. After enough collisions, the kinetic energy on both sides will eventually equalize.
        
        ![[image 5.png]]
        
        - in a situation like this image below:
        
        ![[image 6.png]]
        
        the rate of heat transfer can be expressed as:
        
        $$\frac{Q}{\Delta t} = \frac{kA\Delta T}{L} \\ \ \\ \text{where:} \\ k = \text{conductiviy of heat} \\ A = \text{area of the tube} \\ L = \text{length of the tube}$$
        

# lesson 5 - internal energy and work
---
- in an ideal gas the total kinetic energy of all molecules is called internal energy or $U$

$$U = \sum \overline K = N \overline K = N(\frac{3}{2}k_BT) = \frac{3}{2}nRT$$

- The internal energy of a system can be changed in two differnt ways, either adding heat ($Q$) or doing work ($W$)

- how to calculate the work done on/by a gas in a piston capped container
    
    - Suppose that a cylinder has a cross sectional area $A$ and the pressure exerted by the piston is $P$
    - the force exerted by the piston on the gas is $F = PA$
    - if the piston moves down a distance of $\Delta x$ and the pressure $P$ is constant, the work is
    
    $$W = F \Delta x = (PA)\Delta x = PV$$
    
    - $\therefore$ the work done by the gas is $PV$ and the work done on the gas is $-PV$
    - this also means that the area contained by a process is the same as the work
        
        ![[image 7.png]]
        
    - the reason work is not a vector, is becasue in the case of expansion or contraction it could do so in multiple directions

  

# lesson 6 - First law of thermodynamics
---
$$\Delta U = Q + W \\  
U = \frac32nRT = \frac32NK_BT$$

- conservation of energy
- two ways to increase the internal energy, we can add heat, or we can do work on the system. therefore the change in energy is going to be q + w cuz thats how we change the energy of the system
- adiabatic = no heat added or removed (Q = 0)
- if isothermal internal energy is constant, but U = Q + W, so any work done has to be counteracted by Q (temp ≠ heat)
- isothermal processes are very slow and very shit and very stupid. clues in questions include: [at a constant temperature, the involvement of a hot/cold reservoir, very slowly, etc]
- phase changes are isothermal
- latent heated of fusion: the heat added to change a solid to liquid or the heat removed to change a liquid to a solid is called the
- gas and liquid is called latent heat of vaporization
- if all the heat is going into temp then its a linear relation, otherwise heat can be used to affect volume and pressure and therefore it affecs thte heat temp relation (think heat added but no temp change when work is done on a gas)

  

- isobaric $W = -P\Delta V$
- since t is changed delta u is not 0 and therefore delta u = q + w (it will just say at a constant pressure or isobaric)
- isochoric will be (at a constant volume, rigid container/rigid walls, piston is locked, etc)
- since work is 0 for isochoric, u = q
- adiabatic process, no heat is changing therefore q = 0 therefore u = w
- explosions are adiabatic because its so quick that q has no chance to transfer and therefore q = 0
    
    |   |   |   |
    |---|---|---|
    |process|condition|first law|
    |Isothermal|temp constant, therefore $\Delta U = 0$|$0 = Q + W$|
    |isobaric|$\Delta P = 0$|$U = Q + W$|
    |Isovolumetric||$U = Q$|
    |Adiabatic|$Q= 0$|$U = W$|
    

# Lesson 7 - Second law of thermodynamics
---
- irreversible processes: happen in one direction and not the opposite
- Heat flows naturally from a hot object to a cold object; Heat never flows spontaneously from a cold object to a hot object.
- Entropy
    - Kinetic energy of macroscopic objects (a ball, pendulum...) is associated with organized, coordinated motions of many molecules.
    - heat transfer involves changes in energy of random disordered molecular motion
    - The energy is conserved, its just no longer usable to do work in the system.
    - Entropy provides a quantitative measure of this disorder.
    - Total entropy can do up but doesn't go down in an isolated system
    - entropy will be constant if there is only reversible processes system, entropy will increase if there is any irreversible process in the system
    - energy is only useful when its clumped together, and when u use energy u spread it out. therefore after its spread out it no longer can be used. entropy is frfr a measure of how spread out your energy is. energy is always spreading out, and will never unspread out spontaneously
    - Local decreases of entropy are possible but total entropy (of the universe) don’t go down

$$\text{Entropy or } S = \frac{J}{K}$$

- heat engines
    - thermodynamic system that converts head into mechanicals
    - Hot reservoir transfer heat into engine the engine part of the heat is transeer into wokr doing the expansion of the gas
    - The rest of the $Q_L$ is exhausted to the cold reservoir
    - The efficiency of a heat engine depends on the transfer between the reservoirs and the engine
        
        $$e = \frac{Q_H-Q_C}{Q_H} = \frac{W}{Q_H} = \frac{\text{Usable E}}{\text{Total E}}$$
        
    - Carnot CycleS
        
        ![[image 8.png]]
        
          
        
        - operates between the high tempature reservoir at the $T_H$ and a. low tempture resivoir
        - Engine consists of two reversible iso thermal processes
            
            $$A \Rightarrow B \\  
            C \Rightarrow D$$
            
        - Two reversible adiabatic processes
            
            $$B \Rightarrow C \\  
            D \Rightarrow A$$
            
              
            
        
        - No heat engine operating between two temps can have greater efficiency than a Carnot engine

# Lesson 7b - Calorimetry
---
- blah blah blah
- use SI units, therefore $c = \frac{J}{kg \degree C}$