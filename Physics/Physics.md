<link rel="stylesheet" href="../Resources/styles/base.css">
<!---This is for enabling LaTeX rendering in exports--->
<!---                  Do not remove                --->

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"> 
</script>

<script type="text/x-mathjax-config">
MathJax.Hub.Config({ tex2jax: {inlineMath: [['$','$']]}, messageStyle: "none" });
</script>

# College Physics 
- [College Physics](#college-physics)
  - [Basic Kinematics](#basic-kinematics)
    - [Distance, speed and acceleration](#distance-speed-and-acceleration)
    - [Relationship between the measurements](#relationship-between-the-measurements)
      - [Displacement](#displacement)
      - [Velocity](#velocity)
      - [Acceleration](#acceleration)
  - [Uniform acceleration](#uniform-acceleration)
    - [Uniform kinematics](#uniform-kinematics)
    - [Falling in earth's gravity](#falling-in-earths-gravity)
  - [Projectile motion](#projectile-motion)
    - [Motion Equations](#motion-equations)
    - [Trajectory](#trajectory)
    - [Horizontal Range $R$](#horizontal-range-r)
  - [Circular motion](#circular-motion)
    - [Circular velocity](#circular-velocity)
    - [Period](#period)
    - [Centripetal force](#centripetal-force)
  - [Newton's motions](#newtons-motions)
    - [Mass and force](#mass-and-force)
    - [Equilibrium](#equilibrium)
    - [The acting forces](#the-acting-forces)
        - [Object on flat ground](#object-on-flat-ground)
        - [Object on incline](#object-on-incline)
        - [Object suspended by single rope](#object-suspended-by-single-rope)
        - [Object suspended by multiple ropes](#object-suspended-by-multiple-ropes)
      - [Coefficient of Friction](#coefficient-of-friction)
    - [Tension and pulleys](#tension-and-pulleys)
  - [Gravitational force](#gravitational-force)
  - [Energy and Power](#energy-and-power)
    - [Work Done](#work-done)
    - [Mechanical energy](#mechanical-energy)
        - [Instantaneous Kinetic Energy](#instantaneous-kinetic-energy)
        - [Gravitational Potential Energy](#gravitational-potential-energy)
      - [Conservation of energy](#conservation-of-energy)
    - [Work Done Theorem](#work-done-theorem)
        - [Work Done from difference in kinetic energy](#work-done-from-difference-in-kinetic-energy)
        - [Work Done in falling object](#work-done-in-falling-object)
    - [Rate of energy](#rate-of-energy)
      - [Power](#power)
  - [Mass in motion](#mass-in-motion)
    - [Momentum and impulse](#momentum-and-impulse)
      - [Momentum](#momentum)
      - [Impulse](#impulse)
      - [Momentum and impulse theorem](#momentum-and-impulse-theorem)
    - [Conservation of linear momentum](#conservation-of-linear-momentum)
    - [Types of collision](#types-of-collision)
    - [Solving collisions in 2 dimensions](#solving-collisions-in-2-dimensions)
  - [Electric charges](#electric-charges)
    - [Coloumb's Law](#coloumbs-law)
    - [Electric Force](#electric-force)
      - [Electric field from a force](#electric-field-from-a-force)
      - [Electric field from a point charge](#electric-field-from-a-point-charge)
  - [Practical electricity](#practical-electricity)
    - [Ohm's Law](#ohms-law)
      - [Measuring Power Output](#measuring-power-output)
    - [Rules of VIR](#rules-of-vir)
      - [Gimmicks in the series branch](#gimmicks-in-the-series-branch)
      - [Gimmicks in the parallel branches](#gimmicks-in-the-parallel-branches)
      - [Summary](#summary)
    - [Resistivity](#resistivity)
      - [Factor of Material](#factor-of-material)
      - [Factor of Temeprature](#factor-of-temeprature)
    - [Internal resistance](#internal-resistance)
  - [Recommended Units for calculating](#recommended-units-for-calculating)

## Basic Kinematics
### Distance, speed and acceleration

In kinematics, the basic measurements we can know are **distance**, **speed** and **acceleration**. And their vector counterparts **displacement**, **veloocity** and **acceleration**.

**Distance** is simply how much an object has moved in any direction, **displacement** or **position** is how far an object is away from the origin. It is represented as $d$ or alternatively $x - x_0$ or $\Delta{x}$

**Speed** is the rate of change of distance over time, **velocity** is speed with direction (negative means going the other way around). It is represented as $v$

Finally, **acceleration** is the rate of change of **velocity**, if its negative it means the object is either slowing down or speeding up the other way.

### Relationship between the measurements
#### Displacement
**Displacement** from constant velocity:
$$\Delta{x} = d = vt$$

**Instantaneous Displacement** from velocity function:
$$\Delta{x} = d = \int_{t_0}^{t} v dt$$

#### Velocity
**Velocity** from constant acceleration:
$$v = v_0 + at$$

**Average Velocity**:
$$v_{avg} = \dfrac{\Delta{x}}{\Delta{t}}$$ 

**Average Velocity** from 2 velocities:
$$v_{avg} = \dfrac{v_0 + v}{2}$$

**Instantaneous velocity** from given displacement function:
$$v = \dfrac{dx}{dt}$$

**Instantaneous velocity** from given acceleration function:
$$v = \int_{t_0}^{t}a dt$$

#### Acceleration
**Instantaneous Acceleration** from given displacement equation:
$$a = \dfrac{d^2x}{dt^2}$$
**Instantaneous Acceleration** from given velocity equation:
$$a = \dfrac{dv}{dt}$$
**Average acceleration** from velocities:
$$a_{avg} = \dfrac{dv}{dt}$$



## Uniform acceleration
### Uniform kinematics
The equations below only apply if we know the acceleration does not change.

Likely, you will find yourself missing 2 variables, one which you need to find. To find that, select the equation with a missing quantity you do not need to find yet.

**Velocity accelerating constantly**. *Missing quantity: $\Delta{x}$*
$$v = v_0 + at$$

**Displacement between 2 instant velocities**. *Missing quantity: $a$*
$$x - x_0 = \dfrac{v_0 + v}{2}t$$

**Displacement of the initial velocity accelerating**. *Missing quantity: $v$*

$$x - x_0 = v_{0}t + \dfrac{1}{2}at^2$$

**Displacement using a final accelerated velocity**. *Missing quantity: $v_0$*

$$x - x_0 = vt - \dfrac{1}{2}at^2$$

**Square of final velocity from initial squared velocity and acceleration and distance**. *Missing quantity: $t$*
$$v^2 = v_{0}^{2} + 2a(\Delta{x})$$



### Falling in earth's gravity
As an object falls on earth, there is an accelration caused by gravity:
$$ a = -g = -9.8 m/s$$

When an object is air with a given velocity, we can assume its velocity to be -9.8 m/s.

Additionally, the typical turning point where the object starts to fall after having been launched up into the air can be found when the velocity is 0.


## Projectile motion  

In projectile kinematics, we need to assume the horizontal and vertical motion of the particle seperately.

Here, $\theta_0$ represents the launch angle or the landing angle

![Alt text](images/w0015_ch4.jpg)

### Motion Equations
**Horizontal displacement due to velocity**
$$\Delta{x} = (v_0cos{\theta_0})t$$
**Vertical displacement due to velocity and gravity**
$$y_1 - y_0 = \Delta{y} = (v_0sin{\theta_0})t - \dfrac{1}{2}gt^2$$

**Vertical velocity influenced by gravity**
$$v_y = v_0 sin{\theta_0} - gt$$
**Vertical velocity calculated from vertical displacement**
$$v_y^2 = (v_0 sin{\theta_0})^2 - 2g(\Delta{y - y_0})$$

### Trajectory
$$y = (tan{\theta_0})x - \dfrac{gx^2}{2(v_0 cos{\theta_0})^2}$$

### Horizontal Range $R$

$R$ is the horizontal distance from the launch point to the point at which the particle returns to the launch height
$$R = \dfrac{v_0^2}{g}sin{2\theta_0}$$

## Circular motion
### Circular velocity
If a particle travels along a circular path of radius $r$, 
it is said to be at **uniform circular motion** if the velocity $v$ is constant,
and it has an acceleration $a$ of constant magnitude $\overrightarrow{a}$.

$$a = \dfrac{v^2}{r}$$

$$a = \dfrac{2 \pi v}{T} \space or \space a=\dfrac{4\pi^2r}{T^2} $$

### Period
This acceleration $\overrightarrow{a}$ is directed towards the center, it is **centripetal**, the time needed for the particle to complete the circle is:

$$T = \dfrac{2 \pi r}{v}$$

### Centripetal force
$$F = \dfrac{mv^2}{r    }$$
## Newton's motions
### Mass and force
$$F = m \times a$$

### Equilibrium
A body is set to be in translational equilibrium if all the vectors summed up equals zero.

$$\Sigma{F_x} = 0, \Sigma{F_y} = 0$$
$$\therefore \sum{F = 0} $$

In relation to the formula $F = ma$, when the force is 0, that also means acceleration is 0, or when velocity wont change. Mass can also be 0, but that would be pointless to study.

### The acting forces
Generally every object has a bunch of forces acting on it. A few examples nad their free body diagrams below illustrate the forces and how they act on a box.

![Alt text](images/feffeef.drawio.png)

##### Object on flat ground
For diagram 1, or an object on a flat ground. The object has an opposite force acting upwards. This is the normal force resulting from the surface pushing against the object as the object pushes against the surface. Thats why when you drop an egg, it breaks.

##### Object on incline
For diagram 2, or an object on an incline. Gravity is always a directly downward vertical force, no matter the incline. This gravity influences 2 other forces, the angle of the incline determines the proportion at which gravity affects these forces.

##### Object suspended by single rope
For diagram 3, or an object suspended in air. The upward force is instead tension on the rope suspending it. *Note the arrow for upward tension is shifted so you can see the rope, it is still vertically up and centered.*

##### Object suspended by multiple ropes
For diagram 4, or an object suspended my multiple ropes, the multiple rope that suspend the object contribute to a collective upward force.

When any object is in equilibrium, the opposite forces on one axis always cancel each other out, for example in diagram 1. The normal force and gravity is equal in magnitude and will cancel each other out. 

#### Coefficient of Friction

For an object on ground, the friction force can be found by using the coefficient of friction $\mu$ multiplied by the upward normal force $F_N$.

$$f = \mu F_N$$

However it should be known that there are generally 2 types of friction. **Static friction $\mu_s$** and **Kinetic friction $\mu_k$**.

As the names may imply, static friction applies to objects in rest. Kinetic friction applies when the object is moving.
### Tension and pulleys
$$T = mg+ma$$
## Gravitational force
$$F = G\dfrac{m_1 m_2}{r^2}$$

$r$ is the seperated distance between 2 objects, $G$ is the gravitational constant $6.67 × 10^{−11} N  \dfrac{m^2}{kg^2}$

## Energy and Power

### Work Done
To calculate for the amount of work done, you can find the resultant force at which the objects is moving at and multiply by the distance it moved.

$\overrightarrow{F}$ is the force acting parallel to the direction of the displacement.

$$W = \overrightarrow{F} \times D$$

Alternatively, instantaneous work done can be found by finding the difference in distance.

$$W = \int^i_y{F_x \space dx}$$


### Mechanical energy

##### Instantaneous Kinetic Energy
$$KE = \dfrac{1}{2}mv^3$$

##### Gravitational Potential Energy
$$U = mgh$$
> Note: $h$ is the vertical height. And another popular symbol for gravitational energy is $GPE$

#### Conservation of energy
In a scenario where friction and air resistance does not exist. For a free falling an object, the sum of the kinetic energy and gravitational energy stays the same.
![Alt text](images/conservationofenergy.png)

So when an object is launched upwards, it is converting its kinetic energy into Gravitational potential energy.

Likewise when it is falling instead, the Gravitational potential energy is converted into kinetic energy.

And when the object is at rest, there is no kinetic energy, only Gravitational potential energy.

In short,

$$K_0 + GPE_0 = K_1 + GPE_1$$
### Work Done Theorem
##### Work Done from difference in kinetic energy
$$W = \Delta{K}$$

##### Work Done in falling object
$$W = \Delta{U} = mg(h_1 - h_0)$$

### Rate of energy
#### Power
$$P = \dfrac{W}{t}$$

## Mass in motion
### Momentum and impulse
#### Momentum
$$\overrightarrow{P} = M \times \overrightarrow{v}$$

#### Impulse
It is said to be the change in an object's momentum.
$$\overrightarrow{T} = \overrightarrow{F} \times \Delta{t}$$

#### Momentum and impulse theorem
It can be said that:
$$\overrightarrow{P} = \overrightarrow{T}$$

or

$$M \times \overrightarrow{v} = \overrightarrow{F} \times \Delta{t}$$

### Conservation of linear momentum
Where there is no acting external force, liek air resistance, friction, etc.
$$m_0 \times u_0 + m_1 \times u_1 = m_0 \times v_0 + m_1 \times v_1$$

Where $u$ = initial velocity pre-collision, and $v$ = final velocity post collision

### Types of collision
Generally collision fall between 2 types, elastic or inelastic or somewhere between the both. The "elasticity" refers to how momentum is transfered when objects collide.

### Solving collisions in 2 dimensions
Its really just solving 1D collisions twice, once for each axis.

## Electric charges
### Coloumb's Law
This law describes the electrostatic force (or electric force) between two charged particles.

$$F = k \dfrac{|q_1| |q_2|}{r^2}$$

Where $k$ is the Coulomb Constant, $8.99 × 10^9 \space Nm^2/C^2$

> The equation above can be applied similarly to the way you apply [gravity](#gravitational-force).

Similar to magnets, like charges will repel each other, exerting forces in opposite directions. And unlike charges will want to attract, having forces that go to each other.

![Alt text](images/electroforce.jpg)

And if particles are in a 2D scenario instead of 1D. Calculate for each axis seperately.

### Electric Force
#### Electric field from a force
A charged particle sets up an electric field (a vector quantity) in the surrounding space. If a second charged particle is located in that space, an electrostatic force acts on it due to the magnitude and direction of the field at its location.

The electric field $\overrightarrow{E}$ at any point can be found with
$$\overrightarrow{E} = \dfrac{\overrightarrow{F}}{q_0}$$
Where $\overrightarrow{F}$ is the force exerted on the particle, and $q_0$ is the charge of the particle affected.

> It is not relevant to know the $q$ of the particle setting up the electric field.

#### Electric field from a point charge
The difference is, we have another charged particle or a definite point instead of some uniform field.

So the effective elctric field at some point can be found using the distance to the exerting point $r$ and the exerting charged particle's field $q$.

$$E = k \dfrac{q}{r^2}$$

## Practical electricity
### Ohm's Law
Generally, every object can actually conduct electricity. Things like plastic, glass, paper, etc can conduct electricity if the volatage is high enough.

We categorize their ability to conduct electricity through  measuring their **resistance**. So plastic and glass can be safely used as insulators because their resistance is whoppingly high.

The relationship of electricity is usually tied together by this equation:
$$V = I \times R$$

Where $V$ is the voltage or potential difference, it is the energy to drive electrons in a medium.

$I$ is the current, it is the measurement of how many electrons are actually moving.

$R$ is the resistance, how much it tries to stop the electrons from moving freely.

![Alt text](images/vir.jpg)


#### Measuring Power Output
Power can be derived if you know the voltage and the current
$$P = V I$$

### Rules of VIR
Electricity behaves differently the moment it can branch.
Circuits with said branches are called "**parallel**" circuits. Because they usually have components that dont connect to each other directly, but share a branch.

Circuits that dont do this and connect every component in chains is called a "**series**" circuit.

#### Gimmicks in the series branch
In a **series** circuit or some continous branch, the **voltage** may be different across different devices, but its sum will stay the same.

**Current** however stays the same wherever in the series branch, wherever you measure next to any device, the current stays the same.

**Resistance** is summed up as normal addition. If they are next to each other, add their resistances and you can consider them 1 resistor.
#### Gimmicks in the parallel branches
Regardless of branching, the **voltage** stays the same across every parallel branch, but still in a given branch, the **voltage** will differ across devices on that branch, but it sums up to be the same voltage as other branches.

Current here is divided in branches, it is not shared equally. But just like its older gimmick, in a given branch, current is the same anywhere within.

**Resistance** behaves weirdly in branches, instead of summing up, you need to find the reciprocal.

$$\dfrac{1}{R_0} + \dfrac{1}{R_1} + ... = \dfrac{1}{R_t}$$

> Do not keep the whole $\dfrac {1}{R_t}$, the resistance value you are looking for is simply $R_t$.

#### Summary
![Alt text](images/gimmick.png)




### Resistivity
#### Factor of Material
The wires you use are also not perfect and has resistance on the electricity.

The resistivity can be calculated using:
$$R = \rho \dfrac{L}{A}$$

Where $L$ is the length of the wire in meters, $A$ is the cross-sectional area in meters squared, and $\rho$ is the resistivity factor, which is different for each material.

#### Factor of Temeprature
Material isnt the only thing that defines resistance.
So is the temperature.

**Generally the hotter an object is, the more resistant it is**

$$\rho = \rho_0 [1 + a(T - T_0)]$$

$T$ is the final temperature and $T_0$ is the initial temperature. $a$ is a temperature coefficient for resistivity, different for every material.

As the equation suggests. the hotter the object becomes, the resistivity factor $\rho$ also increases. Since $\rho$ and $R$ are directly proportional, the equation also works with resistance straight away.

$$R = R_0 [1 + a(T - T_0)]$$


### Internal resistance
So the batteries you use for a power source arent exactly free from resistance either.

Batteries have an internal resistance, just pretend its another resistor connected.

Now you have 2 new equations:

The typical Ohm's Law
$$V = \epsilon - Ir$$

$$IR = \epsilon - Ir$$

$V$ here is still voltage of the circuit, **having taking account of the internal resistance already**. $\epsilon$ is the supposed voltage if the battery was perfect.

$R$ is the efffective resistance, and $r$ is the internal resistance of the battery.

> This also means if a voltage source is not connected to anything, it can be said that $V = \epsilon$

## Recommended Units for calculating
The table below shows the recommended metrics when calculating. It is advised to convert values into the form below.
> Eg: If you are given a distance in centimeters $cm$, convert it to meters $m$. Convert mass in grams $g$ to kilograms $kg$, and so on.

|     Unit     |             Symbol              |              Unit Metric              |
| :----------: | :-----------------------------: | :------------------------------: |
|   Distance   | $d, h, \Delta{x}, \Delta{Y}, R$ |            Meter $m$             |
|   Velocity   |               $v$               |      Meter per second $m/s$      |
| Acceleration |               $a$               | Meter per second squared $m/s^2$ |
|     time     |               $t$               |           Seconds $s$            |
|    Force     |               $F$               |           Newtons $N$            |
|     Mass     |               $m$               |          Kilograms $kg$          |
|    Energy    |       $E$, $W$, $KE$, $U$       |            Joules $J$            |
|    Power     |               $P$               |            Watts $W$             |


<div style="page-break-after: always;"></div>

![Alt text](../Resources/images/Draco%20Centaur.png)
<p style="text-align:center;font-weight:bold;font-size:20px;">You have reached the end</p>