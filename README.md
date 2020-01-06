*IrisNanolight* 
============
This file is part of *IrisNanolight* a package of Mathematica (C) scripts for the calculation of optical properties in Nanophotonics. 

*IrisNanolight* is licensed under the AGPL and it is free to use. However, if you use *IrisNanolight*  in a work that leads to a scientific or academic publication, we would appreciate it if you would kindly cite *IrisNanolight* in your manuscript.

> S.G. Rodrigo,  
> ["Optical Properties of Nanostructured Metallic Systems",](https://www.springer.com/gp/book/9783642230844)
> Springer-Verlag, Berlin, (2012)

**Important**: This program is free to use. However, if you are using, or plan to use it, specially if it is for research or academic purposes, please send an email with your name, institution and a brief description of your interest for this program. Commercial applications may also acquire a commercial license. Please contact <sergut@unizar.es> for details.      

------------------------------------------------------------------------------------------------------
Copyright (C) 2020 Sergio G Rodrigo <sergut@unizar.es>   

- *IrisNanolight* is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License,or (at your option) any later version.
  
- *IrisNanolight* is distributed in the hope that it will be useful for research or/and academic purpouses, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details. You should have received a copy of the GNU Affero General Public License along with *IrisNanolight* . If not,see <http://www.gnu.org/licenses/>.

- *IrisNanolight* implementation is based on Wolfram Mathematica 11.3 version. It also works with previous versions of Mathematica from 8.0 version.


***

*IrisNanolight*
-------------------------


The scripts can be download from: <https://github.com/IrisFDTD/IrisNanolight>

Scripts:
> **IrisNanolight_1**

+ **IrisNanolight_1** is a Wolfram Mathematica (C) script to characterize the optical properties of Surface Plasmon Polaritons (SPPs) for any metal which dielectric constant has been previously fitted into a Drude-Lorentz model. SPP wavelength, skin-depth and propagation constant is easily obtained. In addition this script allows you to obtain the full band structure of a metal/dielectric interface for rectangular lattices within the 1st Brillouin zone, in the limit of very small scatterers (actually zero size scatters). This version has been checked to work from Mahtematica 8.0 version.  
+ The example included in this version allows you to reproduce several results in Ref. [1]. That work was conducted in context of Extraordinary optical transmission (EOT) research [2]. Roughly speaking, EOT is a family of EM resonances through subwavelength apertures, in either a flat or a corrugated metallic film. These resonances provide high transmission of light, much more that would be expected for such tiny apertures as compared to the wavelength of light [3]. EOT was discovered in 1998 [4] and since then it has been a very active research field, leading both to the discovery of new ways of enhancing the optical transmission and to its application to sensing, color filters, metamaterials, lenses, optical trapping, enhancement of nonlinear effects, among others [5]. <img style="float: right;" width="400" src="./HA_geometry.png">
+ Within a single run of **IrisNanolight_1** you get in C:\ (dir by default):
 + *eps.dat*: gives the dielectric constant used in the script. In the example provided it is done for silver, while other important metals in Nanophotonics can be used using fittings of Table I in Ref.[1]. Check the result with Fig.1 in [1].
 + *SPP_properties.dat*: provides SPP wavelength, its progataion length and skin-depth, as a function of the wavelength. Check the result with Fig.2 in [1]. Spectral dependence for different metals
 + *BS_p=...nm.dat*: provides the SPP band structure in the $\Sigma-X-M$ directions of the first Brillouin zone for the dielectric-silver interface (glass as substrate). The dispersion relation of the SPP is arbitrarly folded for a period $P=500$nm. Check the result with the solid red line shown in Fig.6 in [1].
 + See the script for further details.


 
*References:*

[1] S. G. Rodrigo, F. J. Garc�a-Vidal, and L. Mart�n-Moreno, [*Influence of material properties on extraordinary optical transmission through hole arrays*](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.77.075401), Phys. Rev. B 77, 075401 (2008).

[2] F.J. Garcia-Vidal, L. Martin-Moreno, T.W. Ebbesen, L. Kuipers, [*Light passing through subwavelength apertures*](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.82.729), Rev. Mod. Phys. 82, 729�787 (2010).

[3] H. A. Bethe, [*Theory of difraction by small holes*](https://journals.aps.org/pr/abstract/10.1103/PhysRev.66.163), Phys. Rev. 66, 163�182 (1944).

[4] T. W. Ebbesen, H. L. Lezec, H. F. Ghaemi, T. Thio, and P. A. Wolff, [*Extraordinary optical transmission through subwavelength
hole arrays*](https://www.nature.com/articles/35570), Nature 391, 667�669 (1998).

[5] S.G. Rodrigo, F. de Le�n-P�rez, and L. Mart�n-Moreno, [*Extraordinary Optical Transmission: fundamentals and applications*](https://ieeexplore.ieee.org/document/7592449), Proceedings of the IEEE 104, 2288 (2016). 