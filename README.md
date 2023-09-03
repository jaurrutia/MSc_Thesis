# Optical Properties of Partially Embeddeed Nanospheres
#### by Jonathan Alexis Urrutia Anguiano
#### Directed by Dr. Alejandro Reyes Coronado (http://sistemas.fciencias.unam.mx/~coronado/)




Master thesis for obtaining the title of *Master in Science (Physics)*

Dissertation at the **Posgrado en Ciencias Físicas**, National Autonomous University of Mexico (PCF-UNAM)

## Abstract:

Plasmonic metasurfaces, metallic nanostructures supported on a substrate, have been used as alternatives for biosensing due to their low-cost and easy-to-use features, and due to their light enhancement and confinement capacity. In common biosensing techniques, a liquid flows over the substrate, where the nanostructure is located, so there is a  detachment risk. Therefore, a partial embedding of the nanostructure in the substrate is desirable, which modifies its optical response under ideal conditions. In this thesis, it is studied the optical response of a single spherical gold nanoparticle of radius 12.5 nm, suited for biosensing-aimed-metasurfaces, when the nanosphere is partially embedded in between an air matrix and glass substrate, both which form a flat interface, and illuminated by an electromagnetic plane wave with wavelengths in the optical range, considering two states of polarization as well as different angles of incidence. The optical properties of the partially embedded nanosphere, that is, the scattering, absorption and extinction cross sections and the induced electric field in the near and far-field regimes, are calculated by means of the Finite Element Method and compared with the analytical solutions of two limiting cases: a nanosphere embedded in an infinite matrix of air, and in an infinite matrix of glass. Based on the obtained numerical results, it was determined optimal configurations for  biosensing with a disordered metasurface of partially embedded nanosphere of radius 12.5 nm in the diluted regime.

![normal](normal.png?raw=true "a] Absorption and b] scattering efficiencies of a 12.5 nm AuNP partially embedded in a glass substrate (ns = 1.5) with an air matrix (nm = 1) as a function of the wavelength λ of the incident electromagnetic plane wave with a wave vector ki perpendicular to the glass-air interface. The partial embedding of the AuNP is determined by the ratio h/a with a the AuNP’s radius and h the distance between the interface and the center of the AuNP. The green shaded region shows the two Mie-limiting cases of a AuNP embedded either in air or in glass; the magenta (partially embedded AuNP) and cyan (Mie-limiting) markers correspond to the efficiencies evaluated at the wavelength of resonance for each case; the gray dashed line is a guide to the eye.")

---
## What is contained in this repository?

 - Codes and inkscape files for each graph and diagram shown in the thesis and the presentation.
   - Aside form the Finite Element calculations performed in Comsol Multiphysics, all codes for the Mie Theory results, as well as for any graph shown in the Thesis can be found in here.
   - The codes for the graphs are in both Mathematica  (.nb) and in Jupyter (.ipynb) Notebooks.
   - To run the Mie Theory related codes and employ the size-correctred dielectric function for gold nanospheres you need to use the (soon to have a proper documentation) **Mie Theory for Mathematica** packege found in [here](https://github.com/jaurrutia/Mie-Theory-Mathematica).
 - The complete thesis tex-files, whose main file is [tesis.tex](./Tex%Files/tesis.tex)
 - The complete presentation tex-files, whose main file is [presentation    |.tex](./Tex%Files/tesis.tex)
