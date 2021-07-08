<div style="text-align:center"><img src="https://github.com/Darvvvin/GI-VietCong-Ecosystem/blob/main/readme/header.png" height="150px" width="1000px"/></div>

# GI-Viet Ecosystem
 
_After successfully defending Khe Sanh, the Special Operations Group (SOG) and Marines head to Hue City, South Vietnam, after the SOG receives intel on a defector and attempt to hunt him down and acquire his intel [[1](https://callofduty.fandom.com/wiki/Vietnam_War)]._

The world contains three main entities: **GI**, **Việt Cộng**, and **rice**. **GI**s try to hunt down **Việt Cộng** soldiers, with each kill providing them the intel (energy for **GI**) needed to find the defector and therefore extend their stay in the field of operation. **Việt Cộng** soldiers randomly go about the **rice** (energy for **Việt Cộng**) field eating patches, keeping them alive. Both the **GI** and the **Việt Cộng** have a chance to multiply through reinforcements and recruiting impressionable college students, respectively. 

## Agents (Breeds)

<div style="text-align:center"><img src="https://github.com/Darvvvin/GI-VietCong-Ecosystem/blob/main/readme/gi.png" height="150px" width="1000px"/></div>

### GI Operative

_The team travels to Hue City where they are given the objective of extracting a Soviet defector from the MACV compound. Mason and Woods are joined by fellow operative Joseph Bowman. Although the defector was killed, Mason acquires his dossier, and the team fight through the city to extraction by boat [[2](https://callofduty.fandom.com/wiki/Studies_and_Observation_Group)]._

This agent serves as the predator in the model, where they are initially spawned into the world at a random coordinate. Their energy level is set randomly from a range of zero to `2 * <energy gain from intel>`. They remain on the map by eliminating **Việt Cộng** soldiers and gathering intel. Each **GI** has a user-given chance to call for reinforcements in the form of another **GI** agent. 

<div style="text-align:center"><img src="https://github.com/Darvvvin/GI-VietCong-Ecosystem/blob/main/readme/cong.png" height="150px" width="1000px"/></div>

### Việt Cộng

_They do not have formal military uniforms because they are guerrilla fighters. They only tied a piece of red rope on their left arm to distinguish themselves from the others (i.e. civilians). They are commonly seen wearing green pith helmets with leaves for camouflage and head protection, or bandannas, flannel work outfits, or they are shirtless leaving them susceptible to chest shots, and wear sandals, which expose feet and toes to shots and the muddy environment [[3](https://callofduty.fandom.com/wiki/Viet_Cong)]._

Like the predators, they spawn at random locations in the map. Their primary food source are the patches of **rice**, which has a random rate of growth from zero to the user-set upper-bound in the growth slider. There is a also a user-given chance to recruit university students to join in the efforts of upholding Hồ Chí Minh's communist vision.







