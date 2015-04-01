# Amplitude of the anomalous magnetic field 

[Vanderlei C. Oliveira Jr.](http://fatiando.org/people/oliveira-jr/)<sup>1</sup>

<sup>1</sup>[*Observatório Nacional*](http://www.on.br/)

## Description

Magnetic sources produce a magnetic induction that disturbs the
local-geomagnetic field on the Earth's surface. The amplitude of 
this disturbing magnetic induction has been called **amplitude of
the anomalous magnetic field**. According to recent published works
(Shearer and Li, 2004; Li et al., 2010; Li and Li, 2014; 
Leão-Santos et al., 2015), the
amplitude of the anomalous magnetic field is weakly dependent on the
magnetization direction of the sources and, because of that, this is
useful to characterize magnetic sources presenting strong remanent 
magnetization. Here, I present some numerical tests to verify the 
dependence of the amplitude of the anomalous magnetic field on
the magnetization direction of the sources.

### References

* Sarah E. Shearer and Yaoguo Li (2004) 3D Inversion of magnetic total 
    gradient data in the presence of remanent magnetization. SEG Technical
    Program Expanded Abstracts 2004: pp. 774-777.
    doi: [10.1190/1.1851318](http://dx.doi.org/10.1190/1.1851318)

* Yaoguo Li, Sarah E. Shearer, Matthew M. Haney, and Neal Dannemiller (2010). 
    Comprehensive approaches to 3D inversion of magnetic data affected by remanent 
    magnetization. 
    Geophysics, 75(1), L1-L11.
    doi: [10.1190/1.3294766](http://dx.doi.org/10.1190/1.3294766)
    
* Shu-Ling Li and Yaoguo Li (2014). Inversion of magnetic anomaly on rugged 
    observation surface in the presence of strong remanent magnetization. 
    Geophysics, 79(2), J11-J19. 
    doi: [10.1190/geo2013-0126.1](http://dx.doi.org/10.1190/geo2013-0126.1)

* Marcelo Leão-Santos, Yaoguo Li, and Roberto Moraes (2015). 
    Application of 3D magnetic amplitude inversion to iron oxide-copper-gold 
    deposits at low magnetic latitudes: A case study from Carajás Mineral 
    Province, Brazil. 
    Geophysics, 80(2), B13-B22.
    doi: [10.1190/geo2014-0082.1](http://dx.doi.org/10.1190/geo2014-0082.1)

## Reproducing the results

The [IPython notebooks](http://ipython.org/notebook.html) located in the
`notebooks` directory of this repository
reproduce all synthetic data, results, and figures presented here.
They use the [Fatiando a Terra](http://fatiando.org) library
and libraries from the [Scipy ecosystem](http://scipy.org/)
to perform the calculations and generate figures.

You can view a static version of the notebooks without having to download or
install anything in the
[nbviewer](http://nbviewer.ipython.org/) web service:

http://nbviewer.ipython.org/github/birocoles/Magnetic-amplitude/tree/master/notebooks/

Navigate to the folder containing the notebook you want to view and click on
the `.ipynb` file. You won't be able to run the code in this online version.

The method proposed in this paper is implemented in Fatiando a Terra version
0.3. You can
[view the code online](https://github.com/fatiando/fatiando/blob/v0.3/fatiando/gravmag/magdir.py#L29)
or download a copy from the official website.


