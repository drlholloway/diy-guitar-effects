# Guitar Effects
A second brain for guitar effects information I always look up.

## Table of Contents
1. [Equipment](#equipment)
2. [Components](#components)
3. [Tayda Drill Templates](#tayda-drill-templates)
4. [Building](#building)

## Equipment
Stuff you need or might need when building guitar pedals.

### Soldering Iron
These are pretty personal, I really like MetCal and they can be picked up on eBay for about the cost of a decent new soldering iron if you just watch. I paid a little under $200 shipped for a MetCal MX-500P-II with solder iron and soldering iron stand. I also got a desoldering gun for about $175 which makes desoldering a little bit easier. I wouldn't suggest going this route until you've decided you really want to continue down the path of building guitar pedals.

For starting out, I'd suggest getting a decent soldering gun that has replacable tips, can adjust temperature, and has a stand. I'd also spring for a soldering mat so you can keep your desk or work area from getting burned by a soldering tip. 😄

### Solder
You can't build the pedal without a way to mate the components to the pcb. Broadly, there are two type of solder: Lead-based and lead-free. I tend towards lead free.

## PCBs and Kits
Here are places that sell PCBs and kits that I like to purchase from (alphabetically):
1. [AionFX](https://www.aionfx.com)
2. [DeadEnd FX](https://www.deadendfx.com/)
3. [Effects Layouts](https://www.effectslayouts.com)
4. [FuzzDog](https://shop.pedalparts.co.uk/)
5. [PedalPCB](https://www.pedalpcb.com)
6. [Mas Effects](https://mas-effects.com/)
7. [Small Bear Electronics](https://smallbear-electronics.mybigcommerce.com/)

For the first time builder, I'd suggest the [Ultimmate Beginner Pedal Kit](https://shop.mas-effects.com/products/ultimate-beginner-pedal-kit) from Mas Effects as it has everything (other than soldering iron) to get you from zero to pedal.

## Components
When it comes to purchasing components you can start a holy war. So, I'm just going to go with the places I typically use and what I get from each of them.
1. [Tayda Electronics](https://www.taydaelectronics.com) - passive components (resistors, potentiometers, etc.), enclosures, ocassionally ICs
2. [Mouser](https://wwww.mouser.com) - capacitors, ICs, ocassionally resistors or other passive components, audio jacks, and dc jacs
3. [Love My Switches](https://lovemyswitches.com/) - knobs, enclosures
4. [Stomp Box Parts](https://stompboxparts.com/) - rare diodes, footswitches, ocassionally audio jacks, knobs, enclosures
5. [AionFX](https://www.aionfx.com) - J201 (smd on an adapter for through hole), other specific items related to AionFX builds
6. [Small Bear Electronics](https://smallbear-electronics.mybigcommerce.com/) - wire, pcbs, hard to find ICs or transistors

If you're wondering about quality components, I'll first state that I haven't had an issue with anything I've bought from Tayda or Mouser or anywhere else; but, I generally try to keep to certain brands.

### Resistors
1/4W 1% metal film resistors are what I default to on everything I build (even ones that ask for 1/8W). The Royal Oak ones from Tayda are actually very nice and have thick leads. KAO Speer and Yageo from Mouser are also both good. I'd lean towards buying in bulk as they get cheaper and it lets you build up an inventory. Generally, I buy either 100 or 200 every time I do a purchase of resistors as it strikes a good balance.

### Capacitors
There are a few different types of through-hole capacitors (MLCC, film, tantalum, and electrolytic) that you'll find yourself using in pedal kits and when building them. I'll steal this liberally from [AionFX](https://aionfx.com/resources/parts-sourcing-where-to-buy-what/), as his guide for capacitors is pretty spot on for what to purchase when it comes to them. I generally find that Mouser (in the USA) has really good prices for them -- but you can also find the name brands (WIMA, Panasonic, etc.) at Tayda now as well.

#### MLCC
Use these for the pF values and anything less than 1nF. You want to try and stick to `C0G` and `NP0` as they are the highest quality and the lowest tolerance in capacitance values. `Z5U`, `X5R` and `X7R` drift more with temperature and voltage. You can find these at both Mouser and Tayda. AionFX recommends the TDK FG28 series, so you can't really go wrong with them. I've used all types and haven't noticed much difference, but I do use TDK FG28 if at all possible.

#### Film
Use these for 1nF through until 2.2uF. Again, WIMA and Kemet PHE426 series are the ones you'll want to look for when it comes to high quality. They also are pretty reasonable when you purchase them in bulk. Again, I've used these and generic ones from Mouser and haven't seen much difference but I really do love the bright red WIMA caps.

#### Tantalum
Not too many effects use these, but you'll see them on occassion. Get them from Tayda.

#### Electrolytic
Use these from about 1uF upwards. You can tell when you need to use them on a schematic diagram or PCB because these will be the circular and have a positive and negative terminal clearly marked. You can't go wrong with Panasonic, Nichicon, Rubycon, or Lelon. I typically go with Panasonic or Nichicon but have used ones from Tayda with no issues. Again, if you buy in bulk from Mouser, the pricing is not too bad. Most boards also go with some standardized diameter sizing on electrolytics:

- 1uF–47uF: 5mm
- 100uF–220uF: 6.3mm

### Potentiometers
Tayda and Stomp Box Parts both have wonderful potentiometers. I tend to like Stomp Box Parts' Cusack brand just a shade more than the Alpha or Tayda branded potentiometers but in most my builds I'll just use the Alpha or Tayda ones as the difference is basically imperveciable. If you get the 16mm Tayda potentiometers, make sure you get the 6.35mm diameter shafts. I also generally shy away from splined and d-shafts.

### Diodes (and LEDs)
Tayda for basically everything when it comes to diodes. If you're looking for Germanium or Russian ones, Stomp Box Parts is really good or troll eBay, but be careful, as there are some shady sellers.

### Transistors
Mouser or Tayda for them. I haven't gotten a bad one from either. Mouser is _probably_ a little safer, and, again, the more you buy the cheaper they are. If you're cost concious, check both but I've found good deals on transistors at Mouser compared to Tayda. If you're looking for Germanium or Soviet spec transistors -- eBay has a few trust worthy sellers or you can try Stomp Box Parts

### ICs
For anything in production, Tayda or Mouser, after than take a look at Stomp Box Parts or Small Bear Electronics.

### Enclosures
Tayda has a great selection and very reasonable prices. You can also look at Stomp Box Parts, Love My Switches, Stomp Box Supply, and sometimes Mouser. My standard go to is Tayda for everything personal. For anything I'm going to sell I'd make sure I'm getting a Hammond or Gorva enclosure.

### Knobs
Love My Switches or Tayda are my two go to places for knobs. I really like the smaller aluminum knobs which Love My Switches sell but Tayda has some great choices too.

### Switches & Foot Switches
Tayda has almost all the switches you are going to need from SPST, SPDT, DPDT, etc. They've also got a great selection of rotary switches as well. If Tayda doesn't have them, I look to Love My Switches or Stomp Box Parts. Small Bear Electronics also carries many as well.

### 1/4 Audio Jacks
By now, you can guess, the default is Tayda. From there I'd look at Mouser, Stomp Box Parts and Small Bear. Love My Switches is pretty good too.

### DC Jacks
Tayda, Mouser or Stomp Box Parts for almost all of them. I believe Small Bear Electronics has a nice really slim one great for tight builds. I like to get ones that fix on the outside to give more room on the inside of the box when building for myself. It makes it easier to remove everything and test if there is something wrong.

### Wire
I'm going to totally ape AionFX here and suggest you just use this [wire](https://smallbear-electronics.mybigcommerce.com/22-pre-bond-colors-50-ft-spool/) from Small Bear Electronics.

## Tayda Drill Templates
One of the most annoying things to do is drilling enclosures. Tayda has a drilling service that is cheap and easy to use. I highly suggest using drill templates to save yourself some time and pain when building. Below are links to makers and drill templates associated with the PCB. I'm sure this will grow as I add and build more.

| Company  | Drill Template | PCBs |
|----------|----------------|------|
| PedalPCB | [125B 5 Knob (Type 1)](https://drill.taydakits.com/box-designs/new?public_key=STgrTk5XbCs2b3FIVU5pVmE1M2pvUT09Cg==) | Chalumeau (PCB077) |
| PedalPCB | [125B 2 Knob (Type 1)](https://drill.taydakits.com/box-designs/new?public_key=dlp0K3RxQkFreEFXVGRXZVlIUE1hZz09Cg==) | Panspermia Fuzz (PCB112), Mister Fuzz (PCB401), Friendly Fire Fuzz (PCB246) |
| PedalPCB | [125B 3-Knob (Type 1)](https://drill.taydakits.com/box-designs/new?public_key=NmZuV2JzM1paYkIrUnVHQjJnMGdjQT09Cg==) | Titania2 (PCB081) |

No Known Drill Template: 
1. [Underminer Sub-Octave Synthesizer](https://www.pedalpcb.com/product/pcb360/)
2. [Duo-Phase](https://www.pedalpcb.com/product/duophase/)

## Building
Building a PCB is a very straight-forward process but sometimes there are gotchas. Here are the steps that I take to build one.

### Setup
Clean the area where you are going to work. A clean workspace makes for a much easier time when working. So, take a few minutes to clean up and prepare where you'll be working. Layout everythign you need and make sure it is all in working order.

### Read the Instructions
I know, seems stupid, but, really, we often don't do it and jump in and start soldering stuff right away only to find out that we messed something up. So, take a few minutes and read the instructions all the way through a few times to make sure you know what parts you need, what the pcb (and hopefully schematic) are

### Gather Components

### Build Order
The general idea is to build from the least tall component to the tallest, meaning you'll start with resistors and work your way up to potentiometers and off board wiring.

1. Resistors and diodes
2. Sockets
3. Capacitors
4. Transistors
5. Potentiometers and switches

### Helpful Sites
1. [5-band resistor color code decoder](https://circuitdigest.com/calculators/5-band-resistor-color-code-calculator)
2. [PedalPCB Forums](https://forum.pedalpcb.com)
