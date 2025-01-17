October 2015

Global Grid of Probabilities of Urban Expansion to 2030

DESCRIPTION

The Global Grid of Probabilities of Urban Expansion to 2030 presents spatially explicit probabilistic forecasts of global urban land cover change from 2000 to 2030 at a 2.5 arc-minute resolution. For each grid cell that is non-urban in 2000, a Monte-Carlo model assigned a probability of becoming urban by the year 2030. The authors first extracted urban extent circa 2000 from the NASA MODIS Land Cover Type Product Version 5, which provides a conservative estimate of global urban land cover. The authors then used population densities from the Global Rural-Urban Mapping Project, Version 1 (GRUMPv1) to create the population density driver map. They estimated the amount of new urban land in each United Nations region by 2030 in a Monte-Carlo fashion based on present empirical distribution of regional urban population densities and probability density functions of projected regional population and GDP values for 2030. To facilitate integration with other data products, CIESIN reprojected the data from Goode's Homolosine to Geographic WGS84 projection. We recommend using the Goode Homolosine equal area projection for data analysis.

NOTES CONCERNING THE DATA

Although regions were not excluded in the creation of these data some small urban areas, such as Tromso and Norilsk, are missing. This is a result of resampling the input land-cover data from 463 meters to 5 kilometers as described in the documentation.


ACCESSING THE DATA

The data may be downloaded via the World Wide Web at http://sedac.ciesin.columbia.edu/data/set/lulc-global-grid-prob-urban-expansion-2030.

The data are available in a compressed zipfile of GeoTIFF format. The downloaded files need to be uncompressed in a single folder using either WinZip (Windows file compression utility) or a similar application before it can be accessed by your GIS software package.


DATA FORMAT

Two files containing probability of urban expansion grids in GeoTIFF format are available in the download.

The WGS84 archive is in geographic coordinates of decimal degrees based on the World Geodetic System spheroid of 1984.

The Goode Homolosine archive is in projected coordinates based on the pseudocylindrical, equal-area, composite map, Goode Homolosine projection.

File naming convention:

urban-expansion-2000-to-2030-wgs84	WGS 1984, with 0.048125633 decimal degree resolution
urban-expansion-2000-to-2030-goode	Goode Homolosine, with 5 kilometer resolution		


DATA VALUES	

Grid cell values 0 to 100 represent the probability of the area becoming urban by the year 2030. Grid cells with value 101 refer to existing urban areas circa 2000 based on the global urban extent map from MODIS Land Cover Type Product Version 5.


SPATIAL EXTENT

WGS84 grid:		NORTH: 83.978  SOUTH: -55.923  EAST: 180.028 WEST: -180  COLUMNS: 7481 ROWS: 2907
Goode Homolosine grid:	NORTH: 8423784.765  SOUTH: -6131215.235  EAST: 19994658.990  WEST: -17345341.010  COLUMNS: 7468  ROWS: 2911


DISCLAIMER

CIESIN follows procedures designed to ensure that data disseminated by CIESIN are of reasonable quality. If, despite these procedures, users encounter apparent errors or misstatements in the data, they should contact SEDAC User Services at ciesin.info@ciesin.columbia.edu. Neither CIESIN nor NASA verifies or guarantees the accuracy, reliability, or completeness of any data provided. CIESIN provides this data without warranty of any kind whatsoever, either expressed or implied. CIESIN shall not be liable for incidental, consequential, or special damages arising out of the use of any data provided by CIESIN. 


USE CONSTRAINTS

Users are free to use, copy, distribute, transmit, and adapt the work for commercial and non-commercial purposes, without restriction, as long as clear attribution of the source is provided. Users of the data are encouraged to acknowledge CIESIN as the source used in the creation of any reports, publications, new data sets, derived products, or services resulting from their use. CIESIN also requests reprints of any publications acknowledging CIESIN as the source and requests notification of any redistribution efforts.

RECOMMENDED CITATIONS

Data Set:

Seto, K., B. Güneralp, and L.R. Hutyra. 2015. Global Grid of Probabilities of Urban Expansion to 2030. Palisades, NY: NASA Socioeconomic Data and Applications Center (SEDAC). http://dx.doi.org/10.7927/H4Z899CG. Accessed DAY MONTH YEAR.

Scientific Publication:

Seto, K., B. Güneralp, and L.R. Hutyra. 2012. Global Forecasts of Urban Expansion to 2030 and Direct Impacts on Biodiversity and Carbon Pools. Proceedings of the National Academy of Sciences of the United States of America 109 (40): 16083-16088. http://dx.doi.org/10.1073/pnas.1211658109.