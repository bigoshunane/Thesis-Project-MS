

# Project Title
## The Study of the Anisotropic Microstructure of Uniaxially Cold Compacted Metal Powder
## Background
Most theoretical studies neglect the plastic deformation of metal powder particles during uniaxial cold compaction. However, particle deformation gives rise to two important phenomena. First, structural activity which occurs in the form of deformation-induced defects within the powder particles, it significantly influences mass-transport mechanisms and contributes to anisotropic shrinkage during sintering. Second, geometrical activity which results from plastic deformation at interparticle contacts, leading to contact extension and altered particle morphology. This geometrical modification changes the relationship between neck growth and particle shrinkage, further promoting anisotropic dimensional changes. In addition, the increased dislocation density introduced by plastic deformation produces an inhomogeneous microstructure in the green body and enhances the extension of interparticle contacts, as plastic flow substantially modifies contact morphology.

 ![anisotropic](https://user-images.githubusercontent.com/84547558/224463187-c3cc9a14-fafd-405b-90de-b12b18b4c54d.png)
 
 
 ![coldcompaction](https://user-images.githubusercontent.com/84547558/225505944-65618106-701f-4be8-8a4c-7858b4bbee7e.png)
 
    Fig.1 Micrograph showing morphological change of particles during cold compaction.
## Objective: What?
1. Experimental Verification of Microstructural Anisotropy

To verify the anisotropy of dimensional change in green compacts of austenitic stainless steel powder (AISI 316L) through:

               - Metallographic preparation of green parts

               - Measurement of interparticle contact lengths

               - Quantification of contact geometry along:

                              - Longitudinal (pressing) direction
                              - Transversal direction

The measured contact lengths will be used to evaluate directional differences in contact growth resulting from uniaxial compaction.

2. Verification of the Sintering Shrinkage Equation

To validate the previously developed shrinkage kinetics equation by:

    - Introducing experimentally measured contact lengths into the shrinkage model

    - Incorporating a time-dependent effective bulk diffusion coefficient 𝐷𝑒𝑓𝑓(𝑡)Deff (t)

    - Comparing predicted directional shrinkage with experimentally measured dimensional change

This objective aims to confirm that anisotropic contact geometry directly influences anisotropic sintering shrinkage.

3. Verification of the FEM Deformation Model

To verify the finite element model developed for predicting particle deformation during cold compaction by:

    - Measuring mean particle diameters from metallographic images

    - Computing equivalent particle diameter

    - Introducing experimentally determined stress–strain data and material properties

    - Comparing FEM-predicted contact lengths with experimentally measured values

Evaluating directional deformation behavior along:

              - Longitudinal direction

              - Transversal direction

The agreement between predicted and measured contact ratios will assess the reliability of the mechanical deformation model.
## Approach: How?
-  EXPERIMENTAL APPROACH
   -  Metal powder cold compaction and Metallographic analysis:
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

![ansys-2](https://user-images.githubusercontent.com/84547558/225506401-7b5ed0e1-d950-470b-836c-d0f2f1865c20.png)

![ansys-3](https://user-images.githubusercontent.com/84547558/225506425-d45d6b09-51ff-4165-a90a-d12b38d4328a.png)

## Summary
  - The present study investigates the anisotropic microstructural evolution and sintering behavior of uniaxially cold-compacted AISI 316L metal powder. Quantitative measurements of interparticle contact lengths revealed pronounced anisotropy in dimensional change, with distinct values observed along the transversal and longitudinal directions.
  -  Analysis of contact number and effective contact number further confirmed directional dependence, demonstrating slightly increased anisotropy with increasing green density and particle size.
increasing on increasing green density & particle size.
  - Measured contact lengths were incorporated into a theoretically developed shrinkage kinetics model to estimate directional sintering shrinkage. The results verified the anisotropic nature of shrinkage, yielding different magnitudes along the two principal directions. 
  - To address shrinkage overestimation, effective diffusivity during the sintering cycle was calculated, showing an increase with both green density and particle size, with a more pronounced effect in the longitudinal direction.

  - A finite element model (FEM) was developed to simulate particle deformation during cold compaction using experimentally measured equivalent particle diameters and stress–strain data. The simulation demonstrated excellent agreement with experimental measurements, with approximately 1% deviation in predicted ratios.

  - Although absolute contact lengths were not accurately predicted due to the use of simplified material parameters, particularly the absence of the true stress–strain curve of AISI 316L, the predicted directional ratios closely matched experimental results.

  - These findings confirm that anisotropy in green microstructure significantly influences sintering shrinkage behavior and highlight the importance of incorporating accurate material constitutive data in theoretical and numerical modeling of powder compaction and sintering processes.

## Authors

- [Workineh Shunane](https://www.linkedin.com/in/workineh-shunane/)
- [Prof. Alberto Molinari](https://webapps.unitn.it/du/en/Persona/PER0004157/Pubblicazioni)
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

