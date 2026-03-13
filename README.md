# U.S. ZIP Code Drive Time Matrix Data and Toolkit

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

All files related to this project—including the ArcGIS Pro toolkit, the nationwide ZIP code drive time matrix, and the user guide—are available in a single compressed download.

**Download:**  
[Toolkit, Drive Time Matrix, and User Guide (ZIP, 2.1 GB)](https://doi.org/10.6084/m9.figshare.31719763)

The download package contains:

- **ArcGIS Pro Toolkit** – tools for estimating large origin–destination (OD) drive time matrices  
- **Drive Time Matrix Dataset** – the calibrated nationwide drive time matrix between ZIP code areas in the United States  
- **User Guide (PDF)** – documentation explaining how to use the toolkit and dataset

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

- Yujie Hu
- Changzhen Wang
- Ruiyang Li
- Fahui Wang

---

# License

This repository distributes research resources for academic use.  
Please cite the original publication when using the dataset or toolkit.

---

# Contact

Spatial Networks Lab  
University of Florida  
