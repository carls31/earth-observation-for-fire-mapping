# EO Fire Mapping
**Assessing Burn Severity Indexes for Fire Mapping using Multispectral Satellite Imagery**

Project Assignment of the [Earth Observation](https://www11.ceda.polimi.it/schedaincarico/schedaincarico/controller/scheda_pubblica/SchedaPublic.do?&evn_default=evento&c_classe=789438&polij_device_category=DESKTOP&__pj0=0&__pj1=196a64c2792be22b7b598fedd1518680) course at [Politecnico di Milano](https://www.polimi.it/).

The main Google Earth Engine source code is avaiable at this [link](https://code.earthengine.google.com/65bc6c647f8e190d937a00684d3d32ad)

### Abstract
The complete paper can be found in the [report](https://github.com/carls31/eo-fire-mapping/blob/main/EO_report_10601118.pdf) file.

Accurate burn severity assessment is crucial for understanding fire behavior, ecology, and post-fire management. While NASA
Landsat satellites are commonly used, the newer European Space Agency Sentinel-2 satellites provide higher temporal and spatial
resolution globally and free data access. Burn severity estimates was compared from Landsat and Sentinel in four different regions
in western North America and South Europe affected by wildfires. Sentinel often outperforming Landsat, utilizing Sentinel’s 20
m resolution reduced high-severity patch interior mapping compared to Landsat (30 m), indicating improved fine-scale fire effect
detection. However, caution is advised when comparing severity patterns at different resolutions. Integrating Sentinel imagery
enhances burn severity mapping by increasing availability and enabling finer-scale fire effect analysis. In the end, the accuracy
assessment of the estimated burned area from Sentinel 2 was performed using the newly integrated QGIS plugin BAD (Burn Area
Detector) as the ground truth.
