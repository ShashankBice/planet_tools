# planet_tools
Utilities and libraries for working with Planet image data

## Scripts
- `planet_ortho.sh` - orthorectify bands in Level 1B MS image and create RGB, NRG, NDVI
- `planet_udm.py` - simple viewer for DN_udm or MS products

## Example

Screenshot of output from planet_udm.py for Planet image over Mt. Rainier, WA: 20170411_181913_0e0f_1B_AnalyticMS

![Sample output](doc/planet_sample.jpg)

### Requirements 
- [GDAL/OGR](http://www.gdal.org/)
- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [NASA Ames Stereo Pipeline (ASP)](https://ti.arc.nasa.gov/tech/asr/intelligent-robotics/ngt/stereo/)
- [pygeotools](https://github.com/dshean/pygeotools)
