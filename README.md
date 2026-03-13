# U.S. ZIP Code Drive Time Matrix Toolkit

This repository provides a toolkit and dataset for estimating a large origin–destination (OD) drive time matrix between ZIP code areas in the United States.

The toolkit implements the **differential sampling approach** described in the following publication:

Hu, Y., Wang, C., Li, R., & Wang, F. (2020).  
*Estimating a large drive time matrix between ZIP codes in the United States: A differential sampling approach.*  
Journal of Transport Geography, 86, 102770.  
https://doi.org/10.1016/j.jtrangeo.2020.102770

---

## Overview

Estimating a nationwide drive time matrix between locations is a challenging task due to:

- limited access to reliable road network and traffic data
- high computational cost
- complex data preparation procedures

This toolkit provides a practical solution for estimating drive times between **all ZIP code pairs in the United States**.

The approach:

1. Uses algorithms of varying complexity to estimate drive times for trips of different lengths
2. Samples ZIP code pairs with varying intensities according to trip distance
3. Retrieves travel times from the Google Maps API
4. Uses these travel times to calibrate computationally inexpensive estimates
5. Accounts for both **interzonal** and **intrazonal** travel times

The result is a **nationwide drive time matrix that can be used for transportation, accessibility, and spatial interaction research**.

---

# Contents

## ArcGIS Pro Toolkit

Download the ArcGIS Pro toolkit:

**Download:**  
[ArcGIS Pro Toolkit](LINK_TO_TOOLKIT)

The toolkit allows users to generate or extend large OD drive time matrices.

---

## Drive Time Matrix Dataset

The calibrated nationwide ZIP code drive time matrix is available here:

**Download:**  
[ZIP Code Drive Time Matrix (2.1 GB)](LINK_TO_MATRIX)

The matrix contains estimated drive times between ZIP code areas across the United States.

---

## User Guide

Detailed instructions for using the toolkit are provided in the user guide.

**Download:**  
[User Guide (PDF)](LINK_TO_USER_GUIDE)

---

# Citation

If you use this dataset or toolkit, please cite:

Hu, Y., Wang, C., Li, R., & Wang, F. (2020).  
Estimating a large drive time matrix between ZIP codes in the United States: A differential sampling approach.  
*Journal of Transport Geography*, 86, 102770.

---

# Applications

The dataset can support research in:

- transportation accessibility
- healthcare access
- spatial interaction modeling
- regional science
- mobility and infrastructure analysis

---

# Authors

Original research by:

- Yu Hu
- Chao Wang
- Rui Li
- Fahui Wang

---

# License

This repository distributes research resources for academic use.  
Please cite the original publication when using the dataset or toolkit.

---

# Contact

Spatial Networks Lab  
University of Florida  
