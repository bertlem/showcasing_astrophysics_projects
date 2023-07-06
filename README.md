# showcasing_astrophysics_projects
This repository is meant to present a few astrophysical results of mine, with a focus on data-driven/machine-learning methods


### PL-relation

PL-relations are used to determine the distance of pulsating stars, hence the systems (star clusters, galaxies) that contain them.
The tasks include the determination of the coefficients of a linear relation using student's T robust regression (with pymc3)

### MilkyWay_warp

The Milky Way disk is not flat but slightly warped. To derive the exact shape of the warp, we fitted a multi-parameters warp model to the data thanks to student's T robust regression (with pymc3). Investigating the impact of the warp on the distance of stars in the outer disk of the Milky Way was done by solving an equation numerically with scipy.

### MilkyWay_spiral_arms

TBD: Locating the spiral arms of the Milky Way using t-sne + HDBSCAN as a clustering algorithm.


### MilkyWay_warp_spiral_arms_test

Testing the t-sne + HDBSCAN combination on mock data
