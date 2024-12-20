# Sentinel-2 SR Cloud/Shadow-free Project<br />

Sentinel-2 MSI surface reflectance cloud/shadow-free large imagery generation using JupyterLab and Google Earth Engine. These codes are intended to be executed in the JupyterLab environment installed on the user's computer, not in the Google Coolab cloud environment. If these codes are to be executed in Google Colab, then slight modifications have to be made to the codes.<br />

These codes are a modification of the Sentinel-2 Cloud Masking with s2cloudless (https://developers.google.com/earth-engine/tutorials/community/sentinel-2-s2cloudless).<br />
Original source: https://github.com/google/earthengine-community/blob/master/tutorials/sentinel-2-s2cloudless/index.ipynb<br />
Credit: Justin Braaten (https://github.com/jdbcode)<br />

### Python prerequisites:<br />
Python 3.9 or higher<br />

### Required packages:<br />
earthengine-api (https://anaconda.org/conda-forge/earthengine-api)<br />
geemap (https://anaconda.org/conda-forge/geemap)<br />
geopandas (https://anaconda.org/conda-forge/geopandas)<br />
json (https://anaconda.org/jmcmurray/json)<br />
folium (https://anaconda.org/conda-forge/folium)<br />
geedim (https://anaconda.org/conda-forge/geedim)<br />

### Other requirements:<br />
You must have a Google Earth Engine account to run these codes.<br />

### Notes:<br />
Since the codes will download the image in image tiles format to your local drive. You will need to mosaic the image tiles into a complete image using image processing software. These codes will also usually download the image tiles in Band Interleaved by Pixel (BIP) format and double precision. Of course this will slow down the image display and waste storage space on your disk. If necessary, you can convert the image into Band Sequential (BSQ) format and integer precision to save storage space using your favorite image processing software.<br />
