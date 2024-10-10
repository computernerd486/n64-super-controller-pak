# Preformance Memory Card

Commonly found 3rd party memory card, longer than the OEM controller pak

![memory_card.jpg](..%2Fimages%2Foriginal%2Fpreformance%2Fmemory_card.jpg){ width=290 }{border-effect=line}

### Board
Similar to the OEM pack, utilizes a `32K X 8 CMOS STATIC RAM`, backed up by a battery to keep memory while
it is not inserted into a powered on system. 

Unlike the OEM pack which uses a battery management IC, it utilizes a transistor, two diodes, and a couple resistors to manage the power.

#### Hardware Specs

    Ram chip: Winbond W24258-70LE 
    32K X 8 CMOS Static RAM


| ![board_front.png](..%2Fimages%2Foriginal%2Fpreformance%2Fboard_front.png){ width=400 } | ![board_back.png](..%2Fimages%2Foriginal%2Fpreformance%2Fboard_back.png){ width=400} |
|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|

### Timings
THe write address access time, and write cycle time is longer than the OEM pak at 100nS

![Timing Chart](../images/original/preformance/timing.png)