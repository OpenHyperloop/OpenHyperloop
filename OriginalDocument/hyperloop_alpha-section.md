Note: This was translated from PDF by [@pooyak](https://github.com/pooyak/hyperloop)

# Hyperloop Alpha

![](images/hyperloop_alpha-1_1.jpg)

**Intro**

The  first  several  pages  will  attempt  to  describe  the  design  in  everyday
language, keeping numbers to a minimum and avoiding formulas and jargon. I
apologize in advance for my loose use of
language and imperfect analogies.

The  second  section  is  for  those  with  a  technical  background.  There  are  no
doubt  errors  of  various  kinds  and  superior  optimizations  for  elements  of  the
system.  Feedback  would  be  most  welcome  –  please  send  to
[hyperloop@spacex.com  ](mailto:hyperloop@spacex.com)o[r  hyperloop@teslamotors.com.  ](mailto:hyperloop@teslamotors.com)
I  would  like  to  thank
my  excellent  compadres  at  both  companies  for  their  help  in  putting  this
together.

**Background**

When the California “high speed” rail was approved, I was quite disappointed,
as  I  know  many  others  were  too.  How  could  it  be  that  the  home  of  Silicon
Valley and JPL – doing incredible things like indexing all the world’s knowledge
and putting rovers on Mars – would build a bullet train that is both one of the
most  expensive  per  mile  and  one  of  the  slowest  in  the  world?  Note,  I  am

* * * * *

hedging  my  statement  slightly  by  saying  “one  of”.  The  head  of  the  California
high speed rail project called me to complain that it wasn’t the very slowest
bullet train nor the very most expensive per mile.

The  underlying  motive  for  a  statewide  mass  transit  system  is  a  good  one.  It
would be great to have an alternative to flying or driving, but obviously only if
it is actually *better* than flying or driving. The train in question would be both
slower, more expensive to operate (if unsubsidized) and less safe by two orders
of magnitude than flying, so why would anyone use it?

If we are to make a massive investment in a new transportation system, then
the return should by rights be equally massive. Compared to the alternatives,
it
should ideally be:

* Safer
* Faster
* Lower cost
* More convenient
* Immune to weather
* Sustainably self-powering
* Resistant to Earthquakes
* Not disruptive to those along the route

Is there truly a new mode of transport – a fifth mode after planes, trains, cars
and boats – that meets those criteria and is practical to implement?
Many ideas
for a system with most of those properties have been proposed and should be
acknowledged, reaching as far back as Robert Goddard’s to proposals in recent
decades by the Rand Corporation and ET3.

Unfortunately, none of these have panned out. As things stand today, there is
not  even  a  short  distance  demonstration  system  operating  in  test  pilot  mode
anywhere  in  the  world,  let  alone  something  that  is  robust  enough  for  public
transit. They all possess, it would seem, one or more fatal flaws that prevent
them from coming to fruition.

**Constraining the Problem**

The  Hyperloop  (or  something  similar)  is,  in  my  opinion,  the  right  solution  for
the specific case of high traffic city pairs that are less than about 1500 km or
900  miles  apart.  Around  that  inflection  point,  I  suspect  that  supersonic  air
travel ends up being faster and cheaper. With a high enough altitude and the
right geometry, the sonic boom noise on the ground would be no louder than
current  airliners,  so  that  isn’t  a  showstopper.  Also,  a  quiet  supersonic  plane
immediately  solves  *every*  long  distance  city  pair  without  the  need  for  a  vast
new worldwide infrastructure.

* * * * *

However, for a sub several hundred mile journey, having a supersonic plane is
rather pointless, as you would spend almost all your time slowly ascending and
descending and very little time at cruise speed. In order to go fast, you need to
be at high altitude where the air
density drops exponentially, as air at sea level
becomes  as  thick  as  molasses  (not  literally,  but  you  get  the  picture)  as  you
approach sonic velocity.

**So What is Hyperloop Anyway?**

Short  of  figuring  out  real  teleportation,  which  would  of  course  be  awesome
(someone please do this), the only option for super fast travel is to build a tube
over  or  under  the  ground  that  contains  a  special  environment.  This  is  where
things get tricky.

At one extreme of the potential solutions is some enlarged version of the old
pneumatic tubes used to send mail and packages within and between buildings.
You  could,  in  principle,  use  very  powerful  fans  to  push  air  at  high  speed
through  a  tube  and  propel  people-sized  pods  all  the  way  from  LA  to  San
Francisco.  However,  the  friction  of  a  350  mile  long  column  of  air  moving  at
anywhere near sonic velocity against the inside of the tube is so stupendously
high that this is impossible for all practical purposes.

Another  extreme  is  the  approach,  advocated  by  Rand  and  ET3,  of  drawing  a
hard  or  near  hard  vacuum  in  the  tube  and  then  using  an  electromagnetic
suspension.  The  problem  with  this  approach  is  that  it  is  incredibly  hard  to
maintain  a  near  vacuum  in  a  room,  let  alone  700  miles  (round  trip)  of  large
tube  with  dozens  of  station  gateways  and  thousands  of  pods  entering  and
exiting every day. All it takes is one leaky seal or a small crack somewhere in
the hundreds of miles of tube and the whole system stops working.

However, a low pressure (vs. almost no pressure) system set to a level where
standard  commercial  pumps  could  easily  overcome  an  air  leak  and  the
transport  pods  could  handle  variable  air  density  would  be  inherently  robust.
Unfortunately, this means that there is a non-trivial amount of air in the tube
and leads us straight into another problem.

**Overcoming the Kantrowitz Limit**

Whenever  you  have  a  capsule  or  pod  (I  am  using  the  words  interchangeably)
moving at high speed through a tube containing air, there is a minimum tube to
pod area ratio below which you will choke the flow. What this means is that if
the walls of the tube and the capsule are too close together, the capsule will
behave like a syringe and eventually be forced to push the entire column of air
in the system. Not good.

Nature’s  top  speed  law  for  a  given  tube  to  pod  area  ratio  is  known  as  the
Kantrowitz limit. This is highly problematic, as it forces you to either go slowly

* * * * *

or  have  a  super  huge  diameter  tube.  Interestingly,  there  are  usually  two
solutions to the Kantrowitz limit – one where you go slowly and one where you
go really, really fast.
 The latter solution sounds mighty appealing
at first, until you realize that going
several thousand miles per hour means that you can’t tolerate even wide turns
without painful g loads. For a journey from San Francisco to LA, you will also
experience a rather intense speed up and slow down. And, when you get right
down  to  it,  going  through  transonic  buffet  in  a  tube  is  just  fundamentally  a
dodgy prospect.

Both  for  trip  comfort  and  safety,  it  would  be  best  to  travel  at  high  subsonic
speeds for a 350 mile journey. For much longer journeys, such as LA to NY, it
would  be  worth  exploring  super  high  speeds  and  this  is  probably  technically
feasible,  but,  as  mentioned  above,  I  believe  the  economics  would  probably
favor a supersonic plane.

The approach that I believe would overcome the Kantrowitz limit is to mount
an electric compressor fan on the nose of the pod that actively transfers high
pressure air from the front to the rear of the vessel. This is like having a pump
in the head of the syringe actively relieving pressure.

It would also simultaneously solve another problem, which is how to create a
low friction suspension system  when traveling at over 700 mph.  Wheels don’t
work  very  well  at  that  sort  of  speed,  but  a  cushion  of  air  does. Air  bearings,
which  use  the  same  basic  principle  as  an  air  hockey  table,  have  been
demonstrated  to  work  at  speeds  of  Mach  1.1  with  very  low  friction.  In  this
case, however, it is the pod that is producing the air cushion, rather than the
tube,
as it is important to make the tube as low cost and simple as possible.

That then begs the next question of whether a battery can store enough energy
to power a fan for the length of the journey with room to spare. Based on our
calculations, this is no problem, so long as the energy used to accelerate the
pod is not drawn from the battery pack.

This  is  where  the  external  linear  electric  motor  comes  in,  which  is  simply  a
round  induction  motor  (like  the  one  in  the  Tesla  Model  S)  rolled  flat.  This
would  accelerate  the  pod  to  high  subsonic  velocity  and  provide  a  periodic
reboost roughly every 70 miles. The linear electric motor is needed for as little
as \~1% of the tube length, so is not particularly costly.

**Making the Economics Work**

The pods and linear motors are relatively minor expenses compared to the tube
itself – several hundred million dollars at most, compared with several billion
dollars for the tube. Even several billion is a low number when compared with
several tens of billion proposed for the track of
the California rail project.

* * * * *

The key advantages of a tube vs. a railway track are that it can be built above
the  ground  on  pylons  and  it  can  be  built  in  prefabricated  sections  that  are
dropped  in  place  and  joined  with  an  orbital  seam  welder.  By  building  it  on
pylons,  you  can  almost  entirely  avoid  the  need  to  buy  land  by  following
alongside  the  mostly  very  straight  California  Interstate  5  highway,  with  only
minor deviations when the highway makes a sharp turn.
 Even when the Hyperloop path deviates from the highway,
it will cause minimal
disruption to farmland roughly comparable to a tree or telephone pole, which
farmers  deal  with  all  the  time.  A  ground  based  high  speed  rail  system  by
comparison  needs  up  to  a  100  ft  wide  swath  of  dedicated  land  to  build  up
foundations for both directions, forcing people to travel for several miles just
to  get  to  the  other  side  of  their  property.  It  is  also  noisy,  with  nothing  to
contain the sound, and needs unsightly protective fencing to prevent animals,
people or vehicles from getting on to the track. Risk of derailment is also not
to be taken lightly, as demonstrated by
several recent fatal train accidents.

**Earthquakes and Expansion Joints**

A ground based high speed rail system is susceptible to Earthquakes and needs
frequent  expansion  joints  to  deal  with  thermal  expansion/contraction  and
subtle, large scale land movement.

By building a system on pylons, where the tube is not rigidly fixed at any point,
you can dramatically mitigate Earthquake risk and avoid the need for expansion
joints. Tucked away inside each pylon, you could place two adjustable lateral
(XY) dampers and one vertical (Z) damper.

These  would  absorb  the  small  length  changes  between  pylons  due  to  thermal
changes, as well as long form subtle height changes.  As land slowly settles to a
new  position  over  time,  the  damper  neutral  position  can  be  adjusted
accordingly.  A  telescoping  tube,  similar  to  the  boxy  ones  used  to  access
airplanes  at  airports  would  be  needed  at  the  end  stations  to  address  the
cumulative length change of the tube.

**Can it Really be Self-Powering?**

For the full explanation, please see the technical section, but the short answer
is that by placing solar panels on top of the tube, the Hyperloop can generate
far in excess of the energy needed to operate. This takes into account storing
enough energy in battery packs to operate at night and for periods of extended
cloudy weather. The energy could also be stored in the form of compressed air
that then runs an electric fan in reverse to generate energy, as demonstrated
by LightSail.

****


* * * * *

**Hyperloop Preliminary Design Study**

**Technical Section**

****

**1. Abstract**

Existing conventional modes of transportation of people consists of four unique
types:  rail,  road,  water,  and  air.  These  modes  of  transport  tend  to  be  either
relatively slow (i.e., road and water), expensive (i.e., air), or a combination of
relatively slow and expensive (i.e., rail). Hyperloop is a new mode of transport
that  seeks  to  change  this  paradigm  by  being  both  fast  and  inexpensive  for
people and goods. Hyperloop is also unique in that it is an open design concept,
similar  to  Linux.  Feedback  is  desired  from  the  community  that  can  help
advance the Hyperloop design and bring it from concept to reality.

Hyperloop consists of a low pressure tube with capsules that are transported at
both low and high speeds throughout the length of the tube. The capsules are
supported on a  cushion  of air,  featuring pressurized  air and  aerodynamic  lift.
The  capsules  are  accelerated  via  a  magnetic  linear  accelerator  affixed  at
various stations on the low pressure tube with rotors contained in each capsule.
Passengers may enter and exit Hyperloop at stations located either at the ends
of the tube, or branches along the tube length.

In  this  study,  the  initial  route,  preliminary  design,  and  logistics  of  the
Hyperloop  transportation  system  have  been  derived.  The  system  consists  of
capsules  that  travel  between  Los  Angeles,  California  and  San  Francisco,
California.  The  total  trip  time  is  approximately  half  an  hour,  with  capsules
departing  as  often  as  every  30  seconds  from  each  terminal  and  carrying  28
people  each.  This  gives  a  total  of  7.4  million  people  each  way  that  can  be
transported  each  year  on  Hyperloop.  The  total  cost  of  Hyperloop  in  this
analysis is under \$6 billion USD. Amortizing this capital cost over 20 years and
adding daily operational costs gives a total of  about \$20 USD (in current year
dollars) plus operating costs per
one-way ticket on the passenger Hyperloop.

Useful  feedback  is  welcomed  on  aspects  of  the  Hyperloop  design.  E-mail
feedback to[ hyperloop@spacex.com ](mailto:hyperloop@spacex.com)o[r hyperloop@teslamotors.com.](mailto:hyperloop@teslamotors.com)

**2. Table of Contents**

* [Background](hyperloop_background.md)

* [Hyperloop Transportation System](hyperloop_transportation.md)

* [Capsule](hyperloop_capsule.md)

* [Tube](hyperloop_tube.md)

* [Propulsion](hyperloop_propulsion.md) 

* [Route](hyperloop_route.md)
 
* [Safety and Reliability](hyperloop_safety.md)
 
* [Cost](hyperloop_cost.md)
 
* [Conclusions](hyperloop_conclusions.md)

* [Future Work](hyperloop_future.md)