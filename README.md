# KAOS

based on:

* 40106 hex inverting schmitt trigger
* 4040 binary counter/divider
* 4051 8 channel analog multiplexer/demultiplexer

* the 40106 provides control oscilators for the 4040. the 4051 generates custom waveforms with the 4040 as its controller
* the other 4 oscilators on the 40106 are audio LFOs
* 2 2N3904s doing the loose connection electron cascade thing(?) to produce white noise

everything is summed together with individual volume controls and a master volume control.

![kaos](kaos.jpg)

**PROVISIONAL DESIGN**  

based on the [Heterodyne Peyote Space Explorer](http://beavisaudio.com/projects/cmossynthesizers)  

**TO CONSIDER:**
- [ ] how many cut-up buttons and where? (everything? each type of everything?)
- [ ] mixing: volume for everything vs. combining some volume controls
- [ ] voltage starving JUST FOR THE HEX INVERTER

see [circuit](circuit) for design.  

_need to figure out how many cut-up switches to use and where_  

_possibly add a LM741 amplifier and a distortion circuit_  
