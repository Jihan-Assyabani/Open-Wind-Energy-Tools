# Open Wind Energy Tools and Data Sources

Lists of open source softwares and publicly available datasets in wind energy. 

## Wind Farm and Wake Modelling
| Toolkit | Repo Owner | Language | Description|
|---|---|---|---|
| [PyWake](https://gitlab.windenergy.dtu.dk/TOPFARM/PyWake) | DTU | Python | an AEP calculator for wind farms implemented in Python including a collection of wake models |
| [FOXES](https://github.com/FraunhoferIWES/foxes) | Fraunhofer IWES | Python |  Wind farm optimization, e.g. layout optimization or wake steering; Wind farm post-construction analysis; Wake model studies, comparison and validation; Wind farm simulations invoking complex model chains |
| [FLORIS](https://github.com/NatLabRockies/floris) | NRL| Python | Wind farm wake and control modelling |
| [Velantis Wind](https://plugins.qgis.org/plugins/VelantisWind/#plugin-details) | Velantis Wind | Python (QGIS) | QGIS plugin for wind farm planning. [Velantis Wind page](https://www.velantiswind.com/qgis); [GitHub repository](https://github.com/Velantis-Wind/VelantisWind/tree/main/VelantisWind)|

## Wind Turbine Aeroelastic Simulation
| Toolkit | Repo Owner | Language | Description|
|---|---|---|---|
| [OpenFAST](https://github.com/OpenFAST/openfast) | NRL| FORTRAN | physics-based engineering tool for simulating the coupled dynamic response of wind turbines |

## CFD/RANS/LES
| Toolkit | Repo Owner | Language | Description|
|---|---|---|---|
| [PALM](https://palm.muk.uni-hannover.de/trac)|Leibniz Universität Hannover| FORTRAN | meteorological modeling system for atmospheric and oceanic boundary layer flows
| [PyFuga](https://gitlab.windenergy.dtu.dk/TOPFARM/PyFuga) | DTU | Python | a linearised RANS / CFD model for wind farm flows | 

## Reanalysis Data Source
| Reanalysis Data | Dataset Period | Source |
|---|---|---|
| [BARRA2](https://opus.nci.org.au/spaces/NDP/pages/264241166/BOM+BARRA2+ob53) | 1979-2024 | Bureau of Meteorology’s atmospheric high-resolution regional reanalysis for Australia |
| ERA6 (upcoming) | - | Copernicus Climate Change Service (C3S) Climate Data Store (CDS) |
| [ERA5](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=overview) | 1940 - onwards | Copernicus Climate Change Service (C3S) Climate Data Store (CDS) |
| [MERRA2](https://disc.gsfc.nasa.gov/datasets?project=MERRA-2) | 1980 - onwards | Goddard Space Flight Center Distributed Active Archive Center (GSFC DAAC) |

## Visualization & Other Tools
| Toolkit | Repo Owner | Language | Description|
|---|---|---|---|
| [WISDEM](https://github.com/NLRWindSystems/WISDEM) | NLR | Python | Wind plant cost of energy (COE) assessment and optimization | 
| [ROSCO](https://github.com/NatLabRockies/ROSCO) | NLR | Python, Fortran | Reference wind turbine controller |
|[IEA22 Blade Viewer](https://github.com/BasemRajjoub/iea22mw-blade-viewer) | Basem Rajjoub | html | Interactive blade components viewer |

## Reference Wind Turbines & Wind Farms
| Turbine | Capacity | Rotor Diameter | Type | Author | Description |
|---|---|---|---|---|---|
| [Commercial Turbines v2](https://zenodo.org/records/19879819) | Varies | Varies | Offshore | Fraunhofer IWES | Open European offshore wind turbine database |
| [Commercial Turbines v1](https://zenodo.org/records/17311571) | Varies | Varies | Offshore | Fraunhofer IWES | Open European offshore wind turbine database |
| [IEA-740-10-MW-ROWPs](https://github.com/IEAWindSystems/IEA-Wind-740-10-ROWP) | 740.MW (Wind Farm) | - | Offshore | IEA Wind | 74 x IEA-10MW WTs. [Report](https://www.osti.gov/servlets/purl/2333634/).|
| [IFE-UPSCALE-25MW-RWT](https://github.com/IFE-FOU/IFE-UPSCALE-25MW-RWT/tree/main) | 25.0 MW | 308 m | Offshore (Floating) | IFE | Upscale of IEA 15 MW RWT | 
| [IEA-22-280-RWT](https://github.com/IEAWindSystems/IEA-22-280-RWT) | 22.0 MW | 280 m | Offshore (Monopile) | IEA Wind | |
| [IEA-15-240-RWT](https://github.com/IEAWindSystems/IEA-15-240-RWT) | 15.0 MW | 240 m | Offshore (Monopile) | IEA Wind | |
| [Hybrid-Lambda](https://zenodo.org/records/10406460) | 15.0 MW | 326 m | Offshore (Monopile) | D. Ribnitzky/ForWind | IEA 15MW Upscale with 2 TSR | 
| [IEA-10-198-RWT](https://github.com/IEAWindSystems/IEA-10.0-198-RWT) | 10.0 MW | 199 m | Offshore (Monopile) | IEA | | 
| [NREL-5MW](https://github.com/ricklupton/OpenFAST-NREL-5MW) | 5.0 MW | 126 m | Offshore (Monopile) | NREL | [Report](https://docs.nlr.gov/docs/fy09osti/38060.pdf) | 
| [IEA-3.4-130-RWT](https://github.com/IEAWindSystems/IEA-3.4-130-RWT) | 3.4 MW | 130 m | Onshore | IEA Wind | |

## Common Airfoils for Wind Turbines
| Family | Origin | Technical Report | Coordinates |
|---|---|---|---|
| FFA-series | The Aeronautical Research Institute of Sweden | [Tech. Report](https://skippy.org.uk/wp-content/uploads/2018/11/FFA-TN-1990-15-v.1-2-c.1.pdf) | [In this repository](https://github.com/Jihan-Assyabani/Open-Wind-Energy-Tools/tree/main/airfoils/FFA%20series)|
