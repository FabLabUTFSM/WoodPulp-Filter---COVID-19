# Wood Pulp Filter for Covid - 19

<img src="images/biomask.jpg"  width="400" >


This project is been developed by 
[Paloma Gonzalez](http://palomagr.mit.edu/index.html) and 
[José Tomás Domínguez](https://github.com/josetomas) in a collaboration of 
[Arauco ](https://www.arauco.cl)and [UTFSM Fablab](https://www.fablabs.io/labs/fablabutfsm).

COVID-19 has generated a global demand for face masks that our supply chains haven't been able to satisfy. Therefore, there is a huge need to create new materials and manufacturing methods to fabricate face masks and filters.  We are working on a wood pulp filter that protects from Covid - 19, and  could potentially be produced anywhere where there is a wood pulp factory. Wood pulp factories are present in most regions of the world.

Our goal is to physically modify wood pulp sheets to achieve the filtering performance of a N95 filter to produce a functional 
layer for respirators / masks / PPE for the corona viruses. 
[Wood pulp is the raw material for paper towels with the capacity of filtering particles of 0.3 μm.](https://smartairfilters.com/en/blog/paper-towel-effective-against-viruses-diy-mask/)
The corona virus measures approximately 0.1 μm. We can modify the compaction of the layers and/ or the size of the fibers to increase their filtering capacity / breathability. 

## Filter + Half Face Mask
**According to our calculations the half mask will cost $0,12 and the filter will cost $0,1.**  We will make updates to the cost whenever we have new info. We still aim for the cheapest possible option.

We are also developing a face mask which filters can be exchanged, 
completely out of molded wood pulp, taking advantage of our raw material.
[Our design is based on Wasp’s design](https://www.3dwasp.com/en/3d-printed-mask-from-3d-scanning/) but we are looking to work with molding 
and/or 2 mold processes instead of 3D printing. It is crucial to be able to mass produce the half masks. 

The advantage of Wasp design is that shape is ergonomic and the filters are held on the inside side of the mask, decreasing the contamination of the filters when changing them. 
There are also fabric masks in which these filters could work [like this one, the HKMask](https://diymask.site/). [We found carboard masks that also do the trick](http://bumask.ru/eng)

Molded wood pulp is meant to be a disposable material and it is 100% biodegradable as all the additives we are suing are. 
This is a characteristic that we want to take advantage of as after the pandemic we wouldn't want to have 
polluted the environment with more waste. This also means that the half masks will last less than N95 or other masks. We embrace such short temporality, and will 
asses it to notice our users. We expect that these protective equipment lasts 3 to 4 weeks.


## Filter Key Parameters to measure [[2](https://scientificfilters.com/wp-content/uploads/2016/03/BasicFiltrationConcepts.pdf)]
- Scanning Electron Microscope [SEM](https://en.wikipedia.org/wiki/Scanning_electron_microscope): This tests characterize the materials porosity. Target: < 0.1 um. 
        - **Update:** Camron did [SEM](SEM.md) imaging.
- Particle Retention Rate: "In a filtration process, the particle retention efficiency of a depth-type filter is expressed in terms of the particle size (in µm) at which a retention
level of 98% of the total number of particles initially challenging the filter is
obtained". Target: 95%
- Preassure Drop: The higher the pressure drop, the harder it is to breathe. Target: <5.82 [mmH20] at a flow rate of 32 [L/min]. 


We are following [FDA COVID-19 Face Mask Public Health Guidelines ](https://gitlab.cba.mit.edu/palomagr/wood-pulp-filter/-/blob/master/References/COVID19-Face-Masks-Guidance.pdf)

All this tests could be replaced by a DOP ([DOP Guideline](http://www.eacoontario.com/pdf/2013/Revised%20August%2027%202013%20DOP%20PAO%20HEPA%20IntegrityTesting%20Procedure.pdf)). 



## Filter Development
Wood pulp sheets have the following disadvantages:
- Hydrophilic, absorbs any liquid very fast so it could have a lower life expectancy and could absorb contaminated droplets, this can be controlled through design or modifying the material properties. 
- Due to air flow, the user could inhale wood pulp fibers, we are adding wood pulp based fabrics to act as a filter. It’s relevant to point out that wood fibers aren’t toxic, you just can’t digest them. 
- These filters will have a shorter life than plastic filters, we expect them to be replaced every 4 hours.  



### Raw Material for the filter and mask

Celulose comes in letter size sheets, 21.59 cm. X 27.94 cm with a thikness of 1mm.

<img src="images/l2_1.jpg"  width="200" >
<img src="images/l2_0.jpg"  width="200" >

### Fabricating the filter

Due to the density of the cellulose sheets the material is not breathable. We succeeded in testing the feasibility of making it breathable. We pulverized it and compacted it into a breathable filter of 5mm thickness. The filter has three layers, the first and last of fabric to isolate fibers and possibly waterproof the pulp.
The filter needs to be tested to evaluate its filtering capacity and porosity.

<img src="images/l1_2.jpg"  width="200" >
<img src="images/l6.jpg"  width="200" >

### Assembling the mask

We are working with the face mask design by [Wasp](https://www.3dwasp.com/en/3d-printed-mask-from-3d-scanning/)

<img src="images/l3_1.jpg"  width="250" >
<img src="images/l1_1.jpg"  width="250" >
<img src="images/l1_3.jpg"  width="250" >

When everything is already manufactured, assemble the parts, and get a finished face mask with a replaceable wood pulp based filter. 

## Pulp Molding

In order to advance into mass production of the mask, we have been developing a 3D printed wood pulp mold, based on [Startasys](https://www.stratasysdirect.com/technologies/fused-deposition-modeling/fdm-tools-paper-pulp-molding). 

### Wood Pulp Molds

<img src="images/M_1.PNG"  width="400" >

In the image above [[3](https://onlinelibrary.wiley.com/doi/abs/10.1002/pts.2289)] you can see how Wood Pulp Molds work. 
The first part, called the moving half, of the mold is made from a solid material, and is the one that press the second part. 
The second part, called the fixed half, has two different layers, this allows the water to flow through the fiber network, into a porous material, to the drainage channels (as you can see in the image above); this allows the mold to release water and keep its final form. 

### First iteration

#### The Mold for Pulp Molding
You can find the mold .stl files in the following [link](https://github.com/FabLabUTFSM/WoodPulp-Filter---COVID-19/tree/master/3D_Models). 

<img src="images/M_2.jpg"  width="400" >

(Models M_1 correspond to the iteration)

#### Material Formula

We used the following foormula for the first test:

- Pulverized unbleached wood pulp: 11.3 grams

It has to have the following texture:

<img src="images/M_3.jpg"  width="400" >

- Water: 269 grams
- Polyvinyl acetate: 66.3 grams. 

#### Results


In the following pictures you can see the first results we got:

<img src="images/M_4.jpg"  width="200" > <img src="images/M_5.jpg"  width="400" >

#### Conclusions

- After 12 hours of drying, the material was wet. We will improve the geometry and introduce porosity that expells the water out. 
- The porous material layer of the fixed half must have a 1 mm thickness. 
- We must add drain channels to the fixed half. 
- The material is getting a good resolution. 
- The cylinders for the respiration holes must be extended.






