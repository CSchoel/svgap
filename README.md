# SVG action potential (svgap)

This project features a set of SVG images and JavaScript-powered animations that illustrate the formation of the characteristic action potential in pacemaker and non-pacemaker cells in the human heart, including the inner workings of all major ion channels.

This is a byproduct of my PhD thesis, in which I wanted to learn about the electrophysiology of the human heart.
These images reflect my own understanding of the subject and while I was thorough in my research, I have to warn you that I am not a biologist but a computer scientist by training.
All the information about the structure and parameters of individual ion channels and pumps is compiled from scientific references, which I will link here, but there may still be omissions and errors due to misunderstandings on my part.

## General references

Some references (mainly books and web resources) were used for multiple currents, which is why I list them only once here:

* [Klabunde2011](https://isbnsearch.org/isbn/9781451113846) (the starting point of my research)
* [Chandler2009](https://doi.org/10.1161/CIRCULATIONAHA.108.804369) (role and presence of ion currents in SAN)
* [PhysiologyWeb](https://web.archive.org/web/20210611082937/https://www.physiologyweb.com/lecture_notes/neuronal_action_potential/neuronal_action_potential_important_features.html)
* [Gerstner2012](https://doi.org/10.1017/CBO9780511815706)
* [Darnell2000](https://isbnsearch.org/isbn/0716731363)
* [Seeley2006](https://isbnsearch.org/isbn/9780073228051)

## List of images

### Overview

The overview images give a good first impression of which part of cardiac electrophysiology is covered in this project.

* Channels and pumps in the cell membrane
  * Files:
    * [heart_cell_channels.svg](heart_cell_channels.svg) (working copy)
    * [heart_cell_channels_overview.svg](heart_cell_channels_overview.svg)
* Action potential curve of non-pacemaker heart muscle cell
  * File: [action_potential_nonpacemaker.svg](action_potential_nonpacemaker.svg)
* Action potential curve of pacemaker heart muscle cell
  * File: [action_potential_pacemaker.svg](action_potential_pacemaker.svg)
* Comparison between AP curves of pacemaker and non-pacemaker cells
  * Files:
    * [action_potentials_comparison.svg](action_potentials_comparison.svg) (old version)
    * [action_potentials_comparison_half.svg](action_potentials_comparison_half.svg)

### Ion channels

The following images illustrate individual ion channels that sit in the cell membrane.
By convention the top part of the image is the extracellular space and the bottom part represents the intracellular space.

* Fast sodium channel (I<sub>Na</sub>)
  * Files:
    * [ion_channels_fastNa.svg](ion_channels_fastNa.svg)
    * [ion_channels_fastNa_old.svg](ion_channels_fastNa_old.svg) (old version)
* Funny channel (I<sub>f</sub>)
  * Files:
    * [ion_channels_HCN.svg](ion_channels_HCN.svg)
    * [ion_channels_HCN_old.svg](ion_channels_HCN_old.svg) (old version)
* L-type calcium channel (I<sub>Ca,L</sub>)
  * File: [ion_channels_LType.svg](ion_channels_LType.svg)
* T-type calcium channel (I<sub>Ca,T</sub>)
  * File: [ion_channels_TType.svg](ion_channels_TType.svg)
  * Additional references:
    * [Catterall2011](https://doi.org/10.1101/cshperspect.a003947)
    * [Ono2010](https://doi.org/10.1016/j.yjmcc.2009.08.021)
* Inward rectifier potassium channel (I<sub>K1</sub>)
  * Files: 
    * [ion_channels_inward_rectifier.svg](ion_channels_inward_rectifier.svg)
    * [ion_channels_inward_rectifier_old.svg](ion_channels_inward_rectifier_old.svg) (old version)
  * Additional references:
    * [DiFrancesco2010](https://doi.org/10.1161/CIRCRESAHA.109.208041)
* Transient outward channel (I<sub>to</sub>)
  * File: [ion_channels_transient_outward.svg](ion_channels_transient_outward.svg)
* Rapid delayed rectifier channel (I<sub>Kr</sub>)
  * File: [ion_channels_rapid_delayed_rectifier.svg](ion_channels_rapid_delayed_rectifier.svg)
  * Additional references:
    * [hergchannel.com](https://web.archive.org/web/20190806143620/http://hergchannel.com/)
    * [Nattel2008](https://doi.org/10.1113/jphysiol.2008.163089)
* Ultrarapid delayed rectifier channel (I<sub>Kur</sub>)
  * File: [ion_channels_ultrarapid_delayed_rectifier.svg](ion_channels_ultrarapid_delayed_rectifier.svg)
  * Additional references:
    * [Wang1993](https://www.ahajournals.org/doi/abs/10.1161/01.res.73.6.1061)
* Leak channel
  * File: [ion_channels_potassium_leak.svg](ion_channels_potassium_leak.svg)
* Calcium-activated potassium channel (I<sub>K,Ca</sub>)
  * File: [ion_channels_calcium_activated.svg](ion_channels_calcium_activated.svg)
  * Additional references:
    * [Hirschberg1998](https://doi.org/10.1085/jgp.111.4.565)
* ACh-activated potassium channel (I<sub>K,ACh</sub>)
  * File: [ion_channels_calcium_ACh_activated.svg](ion_channels_calcium_ACh_activated.svg)
  * Additional references:
    * [YouTube video](https://www.youtube.com/watch?v=tTY1VNDYtdE)
    * [Grant2009](https://doi.org/10.1161/CIRCEP.108.789081)
* ATP-sensitive potassium channel (I<sub>K,ATP</sub>)
  * File: [ion_channels_atp_sensitive.svg](ion_channels_atp_sensitive.svg)
  * Additional references:
    * [Noma1983](https://doi.org/10.1038/305147a0)

### Ion pumps and exchangers

In addition to ion channels, there are also active transport mechanisms through pumps and exchangers that have to be considered.
These folow the same visual conventions as the ion channels.

* Sodium-calcium exchanger (I<sub>NaCa</sub>)
  * Files:
    * [ion_transport_sodium-calcium-exchanger.svg](ion_transport_sodium-calcium-exchanger.svg)
    * [ion_transport_sodium-calcium-exchanger_base.svg](ion_transport_sodium-calcium-exchanger_base.svg) (working copy)
* Sodium-potassium pump (I<sub>NaK</sub>)
  * Files:
    * [ion_transport_nap-kp-pump.svg](ion_transport_nap-kp-pump.svg)
    * [ion_transport_nap-kp-pump_base.svg](ion_transport_nap-kp-pump_base.svg) (working copy)

### Autonomic nervous system

The membrane potential of heart muscle cells is subject to autonomic control via adrenaline and acetylcholine.
The following images illustrate this phenomenon in the sinoatrial node.

* Base file
  * File: [ans_san_regulation.svg](ans_san_regulation.svg)
* Sympathetic influence via adrenaline
  * File: [ans_san_regulation_sym.svg](ans_san_regulation_sym.svg)
* Parasympathetic influence via acetylcholine
  * File: [ans_san_regulation_para.svg](ans_san_regulation_para.svg)

## Animations

To understand how the interplay between the different channels shapes the action potential curve, I created a set of animations using JavaScript and the above SVG files.
This resulted in two animations, one for pacemaker cells and one for non-pacemaker cells.

* Pacemaker action potential animation
  * File: [animations/pacemaker/pacemaker_action_potential.html](animations/pacemaker/pacemaker_action_potential.html)
* Nonpacemaker action potential animation
  * File: [animations/nonpacemaker/nonpacemaker_action_potential.html](animations/nonpacemaker/nonpacemaker_action_potential.html)

This part of the project contains third party libraries in [animations/lib](animations/lib), which are subject to their respective licenses as indicated in the comments at the top of the JavaScript files.
