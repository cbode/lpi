# LPI
### Light Penetration Model
LPI is a modernization of the Subcanopy Solar Radiation model's (https://github.com/cbode/ssr) algorithm for calculating the likelyhood of a light ray penetrating vegetation and reaching ground at any location.  This is related to vegetation density and can affect water and soil temperature.     
Source data is point clouds with ground points defined.  These can come from any source (airborne  or ground LiDAR or drone structure from motion).     
Output is a raster map with an index from 0 - 1.0 value for each cell.   

Reference paper:  Bode, C. A., Limm, M. P., Power, M. E., & Finlay, J. C. (2014). Subcanopy Solar Radiation model: Predicting solar radiation across a heavily vegetated landscape using LiDAR and GIS solar radiation models. Remote sensing of environment, 154, 387-397.   
