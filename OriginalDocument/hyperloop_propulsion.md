
**4.3. Propulsion**
 The propulsion system has these basic requirements:

1.  Accelerate  the  capsule  from  0  to  300  mph  (480  kph)  for  relatively  low
 speed travel in urban areas.
 2.  Maintain the capsule at 300 mph (480 kph) as necessary, including
during
 ascents over
the mountains surrounding Los Angeles and San Francisco.

3.  To accelerate the capsule from 300 to 760 mph (480 to 1,220 kph) at 1g
 at the beginning of the long coasting section along
the I-5 corridor.

4.  To decelerate the capsule back to 300 mph (480 kph) at the end of the I-
 5 corridor.

The Hyperloop as a whole is projected to consume an average of 28,000 hp (21
MW).  This  includes  the  power  needed  to  make  up  for  propulsion  motor
efficiency  (including  elevation  changes),  aerodynamic  drag,  charging  the
batteries to power on-board compressors, and vacuum pumps to keep the tube
evacuated.  A  solar  array  covering  the  entire  Hyperloop  is  large  enough  to

* * * * *

provide  an  annual  average  of  76,000  hp  (57  MW),  significantly  more  than  the
Hyperloop requires.

Since  the  peak  powers  of  accelerating  and  decelerating  capsules  are  up  to  3
times  the  average  power,  the  power  architecture  includes  a  battery  array  at
each  accelerator,  allowing  the  solar  array  to  provide  only  the  average  power
needed  to  run  the  system.  Power  from  the  grid  is  needed  only  when  solar
power is not available.

This section details a large linear accelerator, capable of the 300 to 760 mph
(480  to  1,220  kph)  acceleration  at  1g.  Smaller  accelerators  appropriate  for
urban  areas  and  ascending  mountain  ranges  can  be  scaled  down  from  this
system.

The Hyperloop uses a linear induction motor to accelerate and decelerate the
capsule.  This  provides  several  important  benefits  over  a  permanent  magnet
motor:

* Lower  material  cost  –  the  rotor  can  be  a  simple  aluminum  shape,  and
 does not require rare-earth elements.
* Lighter capsule.
* Smaller capsule dimensions.
* The lateral forces exerted by the stator on the rotor though low at 0.9

lbf/ft (13 N/m) are inherently stabilizing. This simplifies the problem of
 keeping the rotor aligned in the air gap.

* * * * *

![](images/hyperloop_alpha-34_1.jpg)
 Rotor (mounted to capsule)
 Stator (mounted to tube)


**Figure 21. Rotor and stator 3D diagram**

Each  accelerator  has  two  65  MVA  inverters,  one  to  accelerate  the  outgoing
capsule, and one to capture the energy from the incoming capsule. Inverters in
the  10+  MVA  power  range  are  not  unusual  in  mining,  drives  for  large  cargo
ships,  and  railway  traction.  Moreover,  100+  MVA  drives  are  commercially
available.  Inexpensive  semiconductor  switches  allow  the  central  inverters  to
energize only the section of track occupied by a capsule, improving the power
factor seen by the inverters.

The  inverters  are  physically  located  at  the  highest  speed  end  of  the  track  to
minimize conductor cost.

* * * * *

6MW grid
 connection and grid
 tie inverter
 Solar system
 Distributed along length, 285MW peak power total
 Energy storage
 E = 36 MWhr
 PCONT = 37MW
 PPEAK = 52MW
 HVDC bus
 Traction inverters
 65MVA each
 Linear motors for
 Solid-state switches
 arrival track
 M
 M
 M
 M
 M
 M
 M
 M
 Linear motors for
 departure track
 Low speed (300mph) end
 High speed (700mph) end
 Traction power = 20MW
 Traction power = 46MW


**Figure 22. Linear accelerator concept for capsule acceleration and deceleration between 300**

**and 760 mph (480 and 1,220 kph).**

**4.3.1. Capsule Components (Rotor)**

The  rotor  of  the  linear  accelerators  is  very simple  –  an  aluminum  blade  49  ft
(15 m) long, 1.5 ft (0.45 m) tall, and 2 in. (50 mm) thick. Current flows mainly
in the outer 0.4 in. (10 mm) of this blade, allowing it to be hollow to decrease
weight and cost.

The  gap  between the  rotor  and the  stator is  0.8  in. (20  mm)  on  each  side. A
combination  of  the  capsule  control  system  and  electromagnetic  centering
forces allows the capsule to safely enter, stay within, and exit such a precise
gap.

* * * * *

![](images/hyperloop_alpha-36_1.png)
 Copper coils
 Air gap

 Rotor aluminum (mounted to capsule)

****
 Stator iron (mounted to tube)

**Figure 23. Magnetic field strength inside linear induction motor**

**4.3.2. Tube Components (Stator)
**
The stator is mounted to the bottom of the tube over the entire 2.5 miles (4.0
km) it takes to accelerate and decelerate between 300 and 760 mph (480 and
1,220 km). It is approximately  1.6 ft (0.5 m) wide (including the air gap) and
4.0 in. (10 cm) tall, and weighs 530 lb/ft (800 kg/m).

Laid out symmetrically on each side of the rotor, its electrical configuration is
3-phase, 1 slot per pole per phase, with a variable linear pitch (1.3 ft or 0.4 m
maximum).  The  number  of  turns  per  slot  also  varies  along  the  length  of  the
stator, allowing the inverter
to operate at nearly constant phase voltage, which
simplifies  the  power  electronics  design.  The  two  halves  of  the  stator  require
bracing  to  resist  the  magnetic  forces  of  20  lbf/ft  (300N/m)  that  try  to  bring
 them together.

* * * * *

![](images/hyperloop_alpha-37_1.jpg)
 Rotor
 Stator windings
 Stator iron


**Figure 24. Cross section of rotor inside stator**

**4.3.3. Energy Storage Components**

Energy storage allows this linear accelerator to only draw its average power of
8,000 hp (6 MW) (rather than the peak power of 70,000 hp or 52 MW) from its
solar array.

Building the energy storage element out of the same lithium ion cells available
in  the  Tesla  Model  S  is  economical.  A  battery  array  with  enough  power
capability  to  provide  the  worst-case  smoothing  power  has  a  lot  of  energy  –
launching 1 capsule only uses 0.5% of the total energy – so degradation due to
cycling is not an issue. With proper construction and controls,
the battery could
be directly connected to the HVDC bus, eliminating the need for an additional
DC/DC converter to connect it to the propulsion system.

**4.3.4. Cost**

As described above, the propulsion elements on the capsule are limited to the
rotor  and  not  expected  to  cost  any  more  than  \$3  million  USD  for  the  overall
system. The bulk of the propulsion cost is for the stator elements connected to
the  track  and  for  the  inverters  to  drive  the  stator.  All  tube-side  propulsion
costs together for linear accelerators add up to \$140 million USD.
 This cost is roughly divided as followed:
 -  Stator and structure materials = 54%

* * * * *

-  Power electronics (traction inverters, grid tie inverters) = 33%
-  Energy storage = 13%

The solar array and associated electronics provide an average power of 28,000
hp (21 MW) and are expected to cost approximately \$210 million USD.

**4.3.5. Propulsion for Passenger Plus Vehicle System**

Compared  to  the  passenger-only  capsule,  the  passenger  plus  vehicle  capsule
weighs more, requires a more powerful compressor, and has 50% higher total
drag. This increases both the peak and continuous power requirements on the
propulsion system, so that the Hyperloop now consumes an average of 66,000
hp (49 MW). However, there is still more than enough solar power available on
the wider tubes (122,000 hp or 91 MW, on average) to provide this.

The expected total cost for this larger propulsion system is \$691 million USD,
divided as follows:
 -  66,000 hp (49 MW) (yearly average) solar array: \$490 million USD

 -  Propulsion system total: \$200 million USD
 o  Stator and structure materials = 47%
o  Power electronics = 37%
o  Energy storage = 16%

