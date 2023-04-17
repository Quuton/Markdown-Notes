<link rel="stylesheet" href="../Resources/styles/base.css">
<!---This is for enabling LaTeX rendering in exports--->
<!---                  Do not remove                --->

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"> 
</script>

<script type="text/x-mathjax-config">
MathJax.Hub.Config({ tex2jax: {inlineMath: [['$','$']]}, messageStyle: "none" });
</script>

# Physics Training Problems

## Mechanical energy problems
### Problem 1: Ball speeding down the runway
A ball starts from a runway at a height of `3.00 m`. It gains speed before being launched directly upwards reaching a height of `4.00 m`. Ignoring friction and air resistance, find the initial speed of the ball $\overrightarrow{v_0}$.

![Alt text](images/problems/7-1/1.png)

> <div class=misc>Solution</div>
> 
> One thing you can note first is that the height of the start of the ramp is different from the height the ball actually reaches.
>
> This means surely **extra energy is applied** at the start of the ramp.
>
> By the law of conservation of energy, the energy of the ball at the start must be equal to when it is at the peak. $W_0$ is the energy of the ball at the start, $W_1$ is the energy of the ball at the peak in the air.
>
> $$ \space W_0 = K_0 + U_0$$
> $$ \space W_1 = U_1$$
> *The reason $W_1$ only has $U_1$ in the equation is because when a particle has reached its peak in the air, all the kinetic energy has been converted to gravitational potential energy.*
>
> With these 2 equations, all we need to do is substitute any $K$ and $U$ where possible.
> $$ \space W_0 = \dfrac{1}{2}mv^2 + mgh$$
> $$ \space W_1 = mgh$$
>
> Using the given variables
> $$ \space W_0 = \dfrac{1}{2}mv^2 + m(9.8)(3)$$
> $$ \space W_1 = m(9.8)(4)$$
>
> Because we can ignore **air resistance** and **friction**. Then due to the conservation of energy, $W_0 = W_1$.
> $$m(9.8)(4) = \dfrac{1}{2}mv^2 + m(9.8)(3)$$
>
> Simply solve for $v$ using algebra and we have our answer.
>
> $$v = 4.427$$
> <div style="page-break-after: always;"></div>

### Problem 2 Staircase Marathon
A person weighing `50.0 kg` decides to climb up the stairs of a temple `443.0 m` tall. In `15 minutes`, what must be the average power output of the person to be able to complete the staircase in time? Express your answer in watts and horsepower.
![Alt text](images/problems/7-2/1.jpg)

> <div class=misc>Solution</div>
> This is simple, first find the potential energy the person would have gained at the top.
> 
> Using $W = mgh$
>
> $$W = 50 \times 9.8 \times 443 = 217070 J$$
>
> After calculating the energy, simply divide it by 15 minutes, or 900 seconds.
>
> $$P = \dfrac{217070}{900}$$
>
> $$P = 241.19 \space W$$
>
> Just like that we have power, one horsepower is 745.7 Watts.
> $$241.19 \space W = 0.323 \space HP$$
>

### Problem 1: Tractor pulling a firewood sled

A farmer is pulling a sled of firewood `20.0 m` along level ground.
The sled weighs `14700.0 N`. The tractor exerts a constant `5000.0 N` force at an angle of `36.9°` above the griybd. A `3500.0 N` friction force opposes the sled’s motion. 
![Alt text](images/problems/7-3/1.png)
Find the overall work done on the sled. 

> <div class=misc>Solution</div>
> First, create a free body diagram to illustrate the forces on the sled.
![Alt text](images/problems/7-3/2.png)
>
> The forcces we can note are the **friction**, **tension** from the tractor, and the **weight**.
> Because work done is calculated using forces parallel to the direction of the displacement, we can effectively ignore **weight**.
> Do note things are different if the sled was inclined.
>
> To calculate the resultant force, we need to sum the resultant forces up:
>
> $$\sum{F} = 5000 \times cos(36.9\degree) - 3500 = 498.42$$
> *Remember that the 5000N force is not perfectly parallel, so some parts of it are acting parallel and some are perpendicular. Use trigonometry to figure out the individual components.*
>
> After getting the total force, simply multiply by distance to get work done
>
> $$W = 498.42 \times 20 = 9968.4 J$$

![Alt text](../Resources/images/Draco%20Centaur.png)
<p style="text-align:center;font-weight:bold;font-size:20px;">You have reached the end</p>