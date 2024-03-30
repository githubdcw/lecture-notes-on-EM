Let A, B, and C be points on $xy$-plane in freespace.  
There is an external charge. This charge produces electric potentials.  
Measured electric potentials at points A, B, and C are 1, 1.5, and 2, respectively.  
```math
\begin{align}V_A &= 1.0 \\V_A &= 1.5 \\V_A &= 2.0 \end{align} 
```  
Placing a 3 by 1 cm. conducting plate at the points A, B, and C as shown in figure below.  
<img src="/contents/asset/numerical-conducting-plate.png" align="center" width=200 alt="" />  

Assume that a constant surface charge density is induced on each 1 by 1 cm plate by the external charge.  
Find electric potentials at points A, B, and C $V_A$, $V_B$, and $V_C$ after the conductor is placed.
## Solution  
Before placing the conductor:
```math
\begin{align}V_A &= 1.0 \\V_B &= 1.5 \\V_C &= 2.0 \end{align} 
```  
After placing the conductor, charge is induced on each conducting square. The charges produces electric potential. 
```math
\begin{align}V_A &= V_{AA}+V_{BA}+V_{CA}+1.0 \\V_B &= V_{AB}+V_{BB}+V_{CB}+1.5 \\V_C &= V_{AC}+V_{BC}+V_{CC}+2.0 \end{align} 
```
Since points A, B, and C are on the conductor, $V_A = V_B = V_C = V$. V is an unknown to be solved for.   
The expression of the electric protential produced by a conducting square of $\Delta \times \Delta$ with a surface charge density of 1 $C/m^2$ can be approximated by  
```math
V(R)=
\begin{cases}
k (4 \text {asinh} (1)) \Delta &; R =0 \\
\frac {k \Delta^2}{ R} &; R> \Delta 
\end{cases}
```
where $k= \frac{1}{4 \pi \varepsilon_o}$.  
To make the problem simpler, instead of using the above equations, let assume that the electric protential produced by a conducting square of 1cm $\times$ 1cm with a surface charge density of 100 $pC/m^2$ can be approximated by  
```math
V(R)=
\begin{cases}
0.035 &; R =0 \\
0.01 &; R = 1 \text {cm} \\
0.005 &; R = 2 \text {cm} 
\end{cases}
```
Assume that the square A has $\rho_{sA} \times 100pC/m^2$, the square B has $\rho_{sB} \times 100pC/m^2$, and the square C has $\rho_{sC} \times 100pC/m^2$.   
```math
\begin{align}
V_{AA} &= 0.035 \rho_{sA}  \\
V_{AB} &= 0.010 \rho_{sA}  \\
V_{AC} &= 0.005 \rho_{sA}  \\
V_{BA} &= 0.010 \rho_{sB}  \\
V_{BB} &= 0.035 \rho_{sB}  \\
V_{BC} &= 0.010 \rho_{sB}  \\
V_{CA} &= 0.005 \rho_{sC}  \\
V_{CB} &= 0.010 \rho_{sC}  \\
V_{CC} &= 0.035 \rho_{sC}  
\end{align}
```
Rewrite these equations  
```math
\begin{align}
V_A &= V_{AA}+V_{BA}+V_{CA}+1.0 \\
V_B &= V_{AB}+V_{BB}+V_{CB}+1.5 \\
V_C &= V_{AC}+V_{BC}+V_{CC}+2.0
\end{align} 
```
as follows  
```math
\begin{align}
V &= 0.035 \rho_{sA}+0.010 \rho_{sB}+0.005 \rho_{sC}+1.0 \\
V &= 0.010 \rho_{sA}+0.035 \rho_{sB}+0.010 \rho_{sC}+1.5 \\
V &= 0.005 \rho_{sA}+0.010 \rho_{sB}+0.035 \rho_{sC}+2.0 \\
\end{align} 
```
There are 4 unknows. One more equation is needed. The net charge on the conductor is Zero.  
$\rho_{sA}+ \rho_{sB}+ \rho_{sC}=0$  


