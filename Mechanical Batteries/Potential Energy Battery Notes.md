## Household Energy Usage
- Average kWh usage for a 500-square-foot home: 400 kWh.
- Average kWh usage for a 1,000 square foot home: 880 kWh.
- Average kWh usage for a 2,000 square foot home: 1,325 kWh.
- Average kWh usage for a 3,000 square foot home: 1,840 kWh.
- Average kWh usage for a 4,000 square foot home: 2,200 kWh.
- 
- 
-  
## GPE Storage
![[Pasted image 20231115180152.png]]
1 cubic meter, 998 kg, 275 gallons


### Gravitation Potential Energy and Power
Power available = 60.11 kg/s * 9.81 * 10 = 5896.791 watts

The power available in water at height is given by equation:
	 **P = Q x g x h**
- P = power in watts
- Q = discharge of water in kg/s (this is also mass per unit time)
- g = acceleration due to gravity (m/s2)
- h = head (m)
* power = net head x flow /10
- power = electric power in W
- net head = the gross head in ft including the head loss in the penstock
- flow = flow of water in gal/min
- 10 = conversion factor (this can range from 8 - 12, with 10 being about average)
### Flow Rate
Liquid volume flow = Cc Cv_ A (2 g H)1/2  
Calculated for 3 inch diameter pipe
0.97 * 0.97 * 0.004561281 m2 (2 * 9.81 * 10 m)^1/2 = 0.06011 m3/s
System is empty in 1m/0.06011m/s = 16.6 s
Or 275gal/952.762924gal/min (60s/min) = 17.3 seconds

A typical modern system has an efficiency of about 53%
**power = net head x flow / 10**
32.8084 ft * 952.762924 / 10 = 3125.862 watts
Efficiencies coefficients of 1 to 0.7 expected: range of 3125.862 to 2188.10

### Appendix and Equations
The liquid **outlet velocity** when draining a tank or a container can be calculated

_v = Cv (2 g H )1/2                                (1a)_

_where_
_v = outlet velocity (m/s)_
_Cv = velocity coefficient (water 0.97)_
_g = [acceleration of gravity](https://www.engineeringtoolbox.com/accelaration-gravity-d_340.html "acceleration of gravity") (9.81 m/s2)_
_H = height (m)_

The liquid **volume flow** can be calculated

_V = Cd A (2 g H)1/2                        (1b)_

_where_
_V = volume flow (m3/s)_
_A = area of aperture - flow outlet (m2)_
_Cd = discharge coefficient_

_where_
_Cd = Cc Cv_ 

_where_
_Cc = contraction coefficient (sharp edge aperture 0.62, well rounded aperture 0.97)_
_A = area aperture (m2)_

Figure 1, Tank Nomenclature
![[Pasted image 20231021161644.png]]


![[Pasted image 20231021170158.png]]
![[Pasted image 20231021170352.png]]

![[Pasted image 20231021171227.png]]

Rim-driven flow turbine

![[Pasted image 20231021164359.png]]
## Spiral Spring Energy Storage
spiral spring coil storing elastic potential energy
![[Pasted image 20231115180223.png]]


### Potential Energy Stored in Spiral Spring
Assume peak loads of 0.8 kw
p = I V
800 watts / 120v = 6.66 amps
Assume 12 hours continuous use: 2592000 seconds
800 watts * 2592000 seconds = 2 073 600 000 j
100 watts * 2592000 s = 259 200 000 j

![[Pasted image 20231023131533.png]]
![[Pasted image 20231023131547.png]]
![[Pasted image 20231023131606.png]]

By integrating torque we find the equation for potential energy of a spiral spring.
![[Pasted image 20231023133635.png]]
360 degrees = 6.28319 radians
Calculation for 0.5 thickness spring steel that is 12 inches long
![[Pasted image 20231023134116.png]]

To hold 259 200 000 j of energy, find the optimized spring parameters
259 200 000 = 0.5 * 178.70 * (theta)^2
or rotational angle = sqrt(energy stored/(0.5 * spring coefficient))

E = elastic modulus, material dependent, constant
b = material width, variable
t = plate thickness, variable
l = total length, variable

Commercial material specifications range:
0.003” to 0.250” thickness, and 0.125” x 3.50” wide.
0.0762 mm to 6.35 mm thickness, and 3.175 mm to 88.9 mm wide.

![[Pasted image 20231025154924.png]]


