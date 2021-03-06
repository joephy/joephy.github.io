---
layout: post
title:  "Bragg Diffraction/布拉格衍射"
date:   2017-06-24
author: "Joephy"
header-img: "img/post-bg-os-metro.jpg"
catalog: true
tag:
- Martensite Phase Transformation/马氏体相变
- Introduction/介绍
comments: true
---
An introduction to Bragg diffraction
------------

Traditionally, because the microstructure of the crystal material is so difficult to observe, even thought TEM and SEM just can tell part of the informations in the material. But when we using XRD (X-ray diffraction) to analyze the material, we can easily know the lattice parameters inside. Bragg diffraction is a theory to characterize the crystal materials. It is using the X-ray diffraction to analyze the structure of a crystal materials and we can know many things inside the materials by this way. And now, I am going to introduce the Bragg diffraction.

## Electron scatter

Firstly, it is important to know what is the electron scatter.It is the basic principle of the X-ray diffraction. Imagine there is an electron in a 3-D space. A radiation, which is the X-ray will hit on the electron, and then, the electron will be accelerated because of the excitation of the X-ray. The accelerated electron will generate a electric field (different from the electric field of the electron itself) in the space.

## Diffraction

When a X-ray shooting on a material, many particles in the material will be excitation. In this situation, every particle will generate electric field in the space. Some of them are weakening by each other, and some of them are strengthening with each other. So at a spectacular point in the space, we can find a very high intensity of the electric field. This is the diffraction.

## Bragg diffraction

Because the atoms in the crystal material are in order, so there are several "planes" which are formed by the atoms will diffract the X-ray in a particular point in the space. Just like a mirror reflect the light, but we should know that this is not the reflection. If the "plane" satisfy the Bragg angle,

$$2d = sin \theta n \lambda,$$

it can "reflect" the X-ray and make it concentrate in a spectacular point. $d$ is the distance between the plane, $\theta$ is the Bragg angle (angle of X-ray incidence), $n$ is an integer and $\lambda$ is the X-ray wavelength. So we can use some other tools to make sure the intensity distribution in the space.

## Intensity

With the Bragg's law, we can find the position of the diffraction. But for the intensity, it is a little complicated. It majority depends on the several factors below:

(1) Structure factor
> It depends on the structure of the crystal. In a crystal, although a plane satisfy the Bragg's law, it may not "reflect" the X-ray and give out the intensity. This structure factor here is to description the phenomena like that. We call it systematic absence.

(2) Lorentz-polarization factor
> Because for a X-ray radiation, the diffraction angle will affect the intensity of the electric field, so we must introduce a factor to describe it.

(3) Multiplicity factor
> For a crystal structure, there are multiplicities structure in a lattice. It is relevant to the structure factor but it describe different atom position will have different contributions to the intensity.

(4) Temperature factor
> It describe the flexibility of the atom in the crystal materials. If the temperature is higher, the atom can move more freely so the electric field it generates will be different. We also call this factor as the B factor.


Here, we can know the position and the intensity of a particular material and do some simulations if you want. And personally, I have already coded a little program to simulation the XRD by Matlab. If you want to go deeper, there are tons of informations on the Internet, and with that, you can enjoy by yourself.

Reference:

1. [Warren, B. E. (1969). X-ray Diffraction. Courier Corporation.](https://books.google.com.hk/books?hl=en&lr=&id=wfLBhAbEYAsC&oi=fnd&pg=PA1&dq=x-ray+diffraction+b.e.+warren&ots=QGTmIG9DlL&sig=11B_L-M293rQ8DdNJ083EfCgvnM&redir_esc=y#v=onepage&q=x-ray%20diffraction%20b.e.%20warren&f=false)
2. [Bragg's Law](https://en.wikipedia.org/wiki/Bragg%27s_law)
3. [Structure factor](https://en.wikipedia.org/wiki/Structure_factor)
4. [Structure factor details](http://pd.chem.ucl.ac.uk/pdnn/diff2/structf.htm)
5. [Lorentz-polarization factor](http://reference.iucr.org/dictionary/Lorentz–polarization_correction)
6. [Multiplicity factor](http://pd.chem.ucl.ac.uk/pdnn/symm2/multj.htm)
7. [Temperature factor](https://en.wikipedia.org/wiki/Debye–Waller_factor)


