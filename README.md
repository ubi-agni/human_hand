Human Hand Model
===============

This package is derived from the [pisa_hand_description](https://github.com/WEARHAP/hand-models/tree/master/pisa_hand_description) package

The hand URDF model is loaded and displayed with this launch command

```
roslaunch human_hand_description display.launch tactile_mapping:=<mapping>
```

mandatory arguments:
- tactile_mapping: P3r | P3l | P2 | P1

optional arguments:
- robot_name: human_hand
- use_synergy: true | false

authors:
- Guillaume Walck gwalck@techfak.uni-bielefeld.de
- Robert Haschke rhaschke@techfak.uni-bielefeld.de

original authors (Pisa):
- r.nuti@hotmail.it
- carlos@beta-robots.com
- matteo.bianchi@centropiaggio.unipi.it
- e.battaglia@centropiaggio.unipi.it
