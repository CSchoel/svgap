# SVG action potential (svgap)

This project features a set of SVG images that illustrate the formation of the characteristic action potential in pacemaker and non-pacemaker cells in the human heart, including the inner workings of all major ion channels.

This is a byproduct of my PhD thesis, in which I wanted to learn about the electrophysiology of the human heart.
These images reflect my own understanding of the subject and while I was thorough in my research, I have to warn you that I am not a biologist but a computer scientist by training.
All the information about the structure and parameters of individual ion channels and pumps is compiled from scientific references, which I will link here, but there may still be omissions and errors due to misunderstandings on my part.

## List of images

### Overview

#### Channels and pumps in the cell membrane

Files:

* [heart_cell_channels.svg](heart_cell_channels.svg) (working copy)
* [heart_cell_channels_overview.svg](heart_cell_channels_overview.svg)

#### Action potential curve of non-pacemaker heart muscle cell

File: [action_potential_nonpacemaker.svg](action_potential_nonpacemaker.svg)

#### Action potential curve of pacemaker heart muscle cell

File: [action_potential_pacemaker.svg](action_potential_pacemaker.svg)

#### Comparison between AP curves of pacemaker and non-pacemaker cells

Files:

* [action_potentials_comparison.svg](action_potentials_comparison.svg) (old version)
* [action_potentials_comparison_half.svg](action_potentials_comparison_half.svg)

### Ion channels

#### Fast sodium channel (I<sub>Na</sub>)

Files:

* [ion_channels_fastNa.svg](ion_channels_fastNa.svg)
* [ion_channels_fastNa_old.svg](ion_channels_fastNa_old.svg) (old version)

#### Funny channel (I<sub>f</sub>)

Files:

* [ion_channels_HCN.svg](ion_channels_HCN.svg)
* [ion_channels_HCN_old.svg](ion_channels_HCN_old.svg) (old version)

#### L-type calcium channel (I<sub>Ca,L</sub>)

File: [ion_channels_LType.svg](ion_channels_LType.svg)

#### T-type calcium channel (I<sub>Ca,T</sub>)

File: [ion_channels_TType.svg](ion_channels_TType.svg)

#### Inward rectifier potassium channel (I<sub>K1</sub>)

Files: 

* [ion_channels_inward_rectifier.svg](ion_channels_inward_rectifier.svg)
* [ion_channels_inward_rectifier_old.svg](ion_channels_inward_rectifier_old.svg) (old version)

#### Transient outward channel (I<sub>to</sub>)

File: [ion_channels_transient_outward.svg](ion_channels_transient_outward.svg)

#### Rapid delayed rectifier channel (I<sub>Kr</sub>)

File: [ion_channels_rapid_delayed_rectifier.svg](ion_channels_rapid_delayed_rectifier.svg)


#### Ultrarapid delayed rectifier channel (I<sub>Kur</sub>)

File: [ion_channels_ultrarapid_delayed_rectifier.svg](ion_channels_ultrarapid_delayed_rectifier.svg)

#### Leak channel

File: [ion_channels_potassium_leak.svg](ion_channels_potassium_leak.svg)

#### Calcium-activated potassium channel (I<sub>K,Ca</sub>)

File: [ion_channels_calcium_activated.svg](ion_channels_calcium_activated.svg)

#### ACh-activated potassium channel (I<sub>K,ACh</sub>)

File: [ion_channels_calcium_ACh_activated.svg](ion_channels_calcium_ACh_activated.svg)

#### ATP-sensitive potassium channel (I<sub>K,ATP</sub>)

File: [ion_channels_atp_sensitive.svg](ion_channels_atp_sensitive.svg)

### Ion pumps and exchangers

#### Sodium-calcium exchanger (I<sub>NaCa</sub>)

Files:

* [ion_transport_sodium-calcium-exchanger.svg](ion_transport_sodium-calcium-exchanger.svg)
* [ion_transport_sodium-calcium-exchanger_base.svg](ion_transport_sodium-calcium-exchanger_base.svg) (working copy)

#### Sodium-potassium pump (I<sub>NaK</sub>)

Files:

* [ion_transport_nap-kp-pump.svg](ion_transport_nap-kp-pump.svg)
* [ion_transport_nap-kp-pump_base.svg](ion_transport_nap-kp-pump_base.svg) (working copy)

### Autonomic nervous system

#### Base file

File: [ans_san_regulation.svg](ans_san_regulation.svg)

#### Sympathetic influence via adrenaline

Files: [ans_san_regulation_sym.svg](ans_san_regulation_sym.svg)

#### Parasympathetic influence via acetylcholine

File: [ans_san_regulation_para.svg](ans_san_regulation_para.svg)

## Animations

To understand how the interplay between the different channels shapes the action potential curve, I created a set of animations using JavaScript and the above SVG files.
This resulted in two animations, one for pacemaker cells and one for non-pacemaker cells.

Files:

* [animations/pacemaker/pacemaker_action_potential.html](animations/pacemaker/pacemaker_action_potential.html)
* [animations/nonpacemaker/nonpacemaker_action_potential.html](animations/nonpacemaker/nonpacemaker_action_potential.html)

This part of the project contains third party libraries in [animations/lib](animations/lib), which are subject to their respective licenses as indicated in the comments at the top of the JavaScript files.