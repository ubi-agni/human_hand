Human Hand Model
===============

This package is derived from the [pisa_hand_description](https://github.com/WEARHAP/hand-models/tree/master/pisa_hand_description) package

## Usage 

The hand URDF model is loaded and displayed with this launch command

```
roslaunch human_hand_description display.launch tactile_mapping:=<mapping>
```

mandatory arguments:

- tactile_mapping: P3r | P3l | P2 | P1

optional arguments:

- robot_name: human_hand
- use_synergy: true | false
- scale: 1.0 (default)
- calibrated: true | false
- side: '' (read from taxel.yaml)| 'left' |'right' 

## Advanced Usage

Directly upload the human_hand_description with the file `upload.launch`

mandatory arguments:

- tactile_mapping: P3r | P3l | P2 | P1 (see taxel.yaml)

optional arguments:

- use_synergy: true | false
- scale: 1.0 (default)
- calibrated: true | false
- side: '' (=read from taxel.yaml)| 'left' |'right' 
- gui: true | false
- jsp: true | false
- tactile_channel: "tactile glove" (default)
- prefix: "" (default)
- property_file: "" (default= found in human_hand_description package)
- mapping_file: "" (default= found in human_hand_description package)


## Acknowledgment

### authors:
- Guillaume Walck gwalck@techfak.uni-bielefeld.de
- Robert Haschke rhaschke@techfak.uni-bielefeld.de

### original authors (Pisa):
- r.nuti@hotmail.it
- carlos@beta-robots.com
- matteo.bianchi@centropiaggio.unipi.it
- e.battaglia@centropiaggio.unipi.it
