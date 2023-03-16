

# Project Title
THE STUDY OF THE ANISOTROPIC MICROSTRUCTURE OF THE UNIAXIALLY COLD COMPACTED METAL POWDERS (GREEN PARTS)
## Background
Most theoretical works do not consider plastic deformation of metal powder particles when uniaxially cold compacted. 
Due to deformation of particles two phenomena can happen; structural defects of powder particles (structural activity) which influences mass transport phenomenon responsible for anisotropy of shrinkage and extension on contact regions (geometrical activity) which modifies the relationship between the neck size growth and shrinkage of particles resulting in anisotropy of dimensional change.
Moreover, dislocation density introduced by plastic deformation of the particles attributes to the inhomogeneous microstructure of the green body, inducing 
extension of interparticle contacts since plastic deformation modifies significantly the morphology of the contacts.


 ![anisotropic](https://user-images.githubusercontent.com/84547558/224463187-c3cc9a14-fafd-405b-90de-b12b18b4c54d.png)
 
 
 ![coldcompaction](https://user-images.githubusercontent.com/84547558/225505944-65618106-701f-4be8-8a4c-7858b4bbee7e.png)
 
    Fig.1 Micrograph showing morphological change of particles during cold compaction.
## Objective (What?)
-  Verification of the anisotropy of dimensional change of the microstructures of uniaxially cold compacted green parts/austenitic steel powder AISI-316L; by experimantal approach; i.e by measuring interparticles contact length of metallographic images.
    
-  Verify sintering shrinkage equation developed in previous work considering time depending bulk diffusion coefficient (Deff).

-  Verify FEM Model developed for prediction of particles deformation during cold compaction along traversal and longitudinal directions by measuring particles mean diameters and introducing computed equivalent diameter into the FEM model.

## Approach (How?
-  EXPERIMENTAL APPROACH
   -  Metal powder cold compaction and Metallographic analsis:
      -  A. Measuring interparticles contact length.
      -  B. Measuring particles mean diameter and computing equivalent diameter.

-  Contact length measurement

![contactlengthmeasurement](https://user-images.githubusercontent.com/84547558/224465971-fa1b1994-f17d-4d85-a448-c4b3373fb8bd.png)

-  Mean diameter measurement and equivalent diameter computation and how parameters selected for FEM model

![equivalant diameter](https://user-images.githubusercontent.com/84547558/225505992-9a3a0f9d-211c-4ab8-9bc5-27064c5435cb.png)
![load applied caculation](https://user-images.githubusercontent.com/84547558/225506011-10700d33-b786-41c5-8aa6-a49720dd745e.png)


## Results

-  Contact length in transversal and longitudinal directions

![contact_length](https://user-images.githubusercontent.com/84547558/224477884-3d3b6d42-c1fe-4843-af72-b1613a96243b.png)

-  Prediction of shrinkage

![shrinkage](https://user-images.githubusercontent.com/84547558/224478208-c4edbbf0-c95c-41f2-8f44-33e839eb5c9f.png)

-  Effective diffusivity

![Deff](https://user-images.githubusercontent.com/84547558/224478837-abd5fa61-d71a-40fe-a908-49c85f66c57f.png)


-  Verification of FEM model for particle deformation

![ansys-1](https://user-images.githubusercontent.com/84547558/224478853-39778df7-8ec7-4cfb-8074-2cf759cda529.png)

![asys-2](https://user-images.githubusercontent.com/84547558/224478860-ea2ca3d8-3a7b-4c9c-b573-d153f9e3a09e.png)

![ansys-3](https://user-images.githubusercontent.com/84547558/224478863-96692563-a113-4746-87de-241f1ffcd105.png)

## Summary
  -  The measurement of length of interparticle contact regions verified the anisotropy of dimensional
change `resulting in differet values` along both traversal and longitudinal directions.
  -  The contact number & effective contact number along transversal & longitudinal directions also
verified the `anisotropy of shrinkge showing different values along the two directions` and slightly
increasing on increasing green density & particle size.
  -  The `values of shrinkage estimated` by introducing measured contact lengths in a theoretically
developed shrinkage kinetics equation `verified the anisotropy of sintering shrinkage` by resulting
in different values along both directions.
  -  The `effective diffusivity` suitable during `sintering cycle` for the green part has been calculated to
account for overestimation made during shrinkage estimation & it increases on increasing density
and particle size, but more pronounced along longitudinal direction.

  -  `FEM model developed for deformation of a particle during cold compaction has been verified` by
introducing measured equivalent diameter of the particles, stress-strain curve data points & other
material properties. The resut showed very close with `1% deviation in ratio` with the measured
values.

  -  The `theoretical calculation does not predict properly the contact length due to deformation`,
because `the actual stress-strain curve of AISI 316L was not used`; the differences in yield strength &
strain hardening coefficiend modifiy the results.

  -  Neverthless, the ratio between contact lengths is very close to the measured one; hence, it will be
expected to have the `actual values when the true stress-strain curve of AISI 316L will be used`.

## Authors

- [Workineh Shunane](https://www.linkedin.com/in/workineh-shunane/)
- [Prof. Alberto Molinari](https://www.aitem.org/Materialiadditive/en/2018/05/12/prof-alberto-molinari/)
- [Sasan Amir](https://www.linkedin.com/in/sasanamir/)
- [Marco Zago](https://www.linkedin.com/in/marco-zago-440724a9/)


### References

  -  I. Cristofolini, G. Pederzini, A. Rambelli, A. Molinari: Study of the uniaxially cold compaction of AISI 316L stainless steel powders through single action tests', Powder Technology, 2016, 295, 284-295.
  -  E. Torresani, I. Cristofolini, A. Molinari: 'Study of the anisotropic microstructure of the uniaxially cold compacted green parts'
  -  A. Molinari, E. Torresani, C. Menapace, M. Larsson: ''The anisotropy of dimensional change on sintering of iron'', The Americam Ceramic Society, 2015, 98:11, 3431-3437.
  -  E. Klar, P.K. Samal, Powder Metallurgy Stainless Steels: Processing, Microstructures, and Properties, 2007, 1- 4.
  -  A. Salak, Ferrous Powder Metallurgy, Ed. Cambridge, International Science Publishing, (1995), 68 -78.
  -  I. M. Sas-Boca, T. canta, D. Frunza: 'Cold pressing powder with assisted friction compaction with high speed tools', Proceedings of Powder Metallurgy, RoPM 2005, Cluj-Napoca, Romania.
  -  [H. Hofman,P. Bowen:'Powder technology', (2016 December 07)](http://ltp.epfl.ch/files/content/sites/ltp/files/shared/Teaching/Master/06PowderTechnology/Compacton.pdf)
  -  F. George,V. Voort, Metallography principles and practice, New York, McGraw-Hill, (1984), 99 – 24360.
  -  I. Cristofolini, G. Pederzini, A. Rambelli, A. Molinari: 'Densification and deformation during uiaxial cold compaction of stainless steel powder with different particle size', Powder Metallurgy, 2016, 59:1, 73 – 84.
  -  A. Molinari, E. Torresani: 'Preliminary study to determine the sintering stress from microstructural analysis of green parts', Powder Metallurgy, 2015, 58:5, 323 – 327.
  -  A. Molinari, E. Torresani, C. Menapace, M. Larsson: ''The anisotropy of dimensional change on sintering of iron'', The Americam Ceramic Society, 2015, 98:11, 3431-3437.
  -  A. Molinari et.al: 'Effect of carbon and nitrogen content on deformation and fracture of AISI 304 stainless steel', Frattura ed integrita strutturale, 4(2008), 12 – 19.

