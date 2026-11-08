## Hi, I'm Sohrab Kolsoumi

I build scientific software and data tools for climate, drought, hydrology, and
geospatial (LiDAR) data. I am the founder of [AgriMetSoft](https://agrimetsoft.com),
where I design, build, document, and support desktop and web tools used by
researchers, students, and consultants around the world. Based in Ames, Iowa.

I work across the whole process: collecting and cleaning large environmental
datasets, building the analysis, and making it usable through clear software,
charts, and documentation.

### What I work with

- **Languages:** C#, Python, MATLAB, NCL
- **Data:** NetCDF, HDF, GeoTIFF, MODIS, ERA5, NASA POWER; data cleaning,
  validation, and analysis; SQLite and some MS SQL Server
- **Geospatial:** GDAL, coordinate transformation, LiDAR (LAS/LAZ), remote sensing
- **Methods:** drought and climate indices (SPI), statistical downscaling,
  rainfall / IDF analysis, wavelet analysis
- **Apps:** WPF desktop software, web front ends (HTML/JS), MCP servers

### Featured projects

- **[dmap-ai-mcp](https://github.com/sohrab4748/dmap-ai-mcp)** — an MCP server
  that runs drought analysis (SPI, drought events, wavelet) for any location,
  using ERA5 and NASA POWER. *(Python)*
- **[dmap-ai-frontend](https://github.com/sohrab4748/dmap-ai-frontend)** — the
  web app behind [droughtanalysis.com](https://droughtanalysis.com). *(HTML/JS)*
- **[laz-to-text](https://github.com/sohrab4748/laz-to-text)** — read LiDAR
  .laz/.las files and export the points to TXT or CSV. *(C#/WPF)*
- **[laz-to-las](https://github.com/sohrab4748/laz-to-las)** — batch-convert
  compressed LiDAR .laz files to uncompressed .las. *(C#/WPF)*
- **[AgriMetSoft](https://github.com/sohrab4748/AgriMetSoft)** — my suite of
  climate and agricultural data tools.

### AgriMetSoft tools, by area

- **Drought & climate:** DMAP, DMAP-AI, RDIT, MDM
- **Statistical downscaling:** SD-GCM (CMIP5/CMIP6; Delta, Quantile Mapping, EDQM)
- **NetCDF & climate data:** Open NC File, NetCDF Extractor, CORDEX Data Extractor
- **Remote sensing:** MODIS Product Extractor
- **Hydrology:** IDF Curve
- **Data prep & evaluation:** Estimate Missing Climate Data, Model Analyzer, Excel add-in

### Links

- Website: [agrimetsoft.com](https://agrimetsoft.com)
- Google Scholar: [profile](https://scholar.google.com/citations?user=aRK6hE4AAAAJ&hl=en)
- 
# Sohrab Kolsoumi

Founder of **AgriMetSoft LLC**, developing software tools for climate science, drought monitoring, agrometeorology, hydrology, NetCDF data processing, remote sensing, statistical downscaling, and environmental data analysis.

AgriMetSoft provides scientific software tools for researchers, students, consultants, engineers, and environmental data analysts.

- Main website: [AgriMetSoft climate and environmental software](https://agrimetsoft.com/)
- Product list: [AgriMetSoft software products](https://agrimetsoft.com/products/)
- Contact: [AgriMetSoft contact page](https://agrimetsoft.com/contact)

## Featured project: DMAP-AI

**DMAP-AI (Drought Monitoring and Analysis Platform – AI)** is a web-based drought monitoring and analysis platform by AgriMetSoft.

The current Research Version provides free point-based SPI drought analysis using NASA POWER and ERA5-Land/CDS, with charts, drought severity metrics, wavelet diagnostics, copula diagnostics, AI interpretation, JSON output, export tools, and saved runs.

- Platform: [DMAP-AI drought monitoring platform](https://droughtanalysis.com/)
- App: [DMAP-AI Research Version for SPI drought analysis](https://droughtanalysis.com/DMAP_AI_App)
- Tutorial: [DMAP-AI SPI video tutorial](https://droughtanalysis.com/spi_tutorial)
- Methods: [DMAP-AI SPI methods and formulas](https://droughtanalysis.com/formulas)

## AgriMetSoft software tools

### Drought and climate analysis

- [DMAP drought monitoring and prediction software](https://agrimetsoft.com/dmap/) — drought index calculation, drought severity assessment, and prediction workflows.
- [DMAP-AI web-based drought monitoring platform](https://droughtanalysis.com/) — online SPI drought analysis with charts, diagnostics, AI interpretation, JSON output, and export tools.
- [RDIT rain-based drought indices tool](https://agrimetsoft.com/rdit/) — rain-based drought index calculation and severity assessment.
- [MDM meteorological drought monitoring tool](https://agrimetsoft.com/MDM.aspx) — older/free meteorological drought index tool.

### Statistical downscaling and climate projections

- [SD-GCM statistical downscaling software](https://agrimetsoft.com/sd-gcm/) — statistical downscaling for CMIP5 and CMIP6 GCM data using Delta, Quantile Mapping, and Equidistant Quantile Mapping methods.

### NetCDF, CORDEX, and climate data extraction

- [Open NC File NetCDF extraction tool](https://agrimetsoft.com/open-nc-file-for-coordinates/) — extract NetCDF data by station coordinates or rectangular region.
- [NetCDF Extractor for time-series extraction](https://agrimetsoft.com/netcdf-extractor/) — extract time series from NetCDF files.
- [CORDEX Data Extractor](https://agrimetsoft.com/cordex-data-extractor/) — extract regional climate model data from CORDEX NetCDF files.

### Remote sensing and MODIS data

- [MODIS Product Extractor](https://agrimetsoft.com/modis-products-extractor/) — extract MODIS HDF product data for points, regions, or station lists.

### Hydrology and rainfall analysis

- [IDF Curve rainfall intensity-duration-frequency software](https://agrimetsoft.com/idf-curve/) — calculate and draw IDF curves using empirical and theoretical distributions.

### Data preparation and model evaluation

- [Estimate Missing Climate Data software](https://agrimetsoft.com/estimate-missing-climate-data/) — estimate missing climate data using methods such as MLR, ANN, IDW, correlation weighting, interpolation, LOCF, and NOCB.
- [Model Analyzer Tool for model evaluation](https://agrimetsoft.com/model-analyzer-tool/) — analyze model results using QQ plots, residual plots, autocorrelation plots, confidence and prediction bounds, and efficiency criteria.
- [Data-Tool Excel add-in for climate data processing](https://agrimetsoft.com/data-tool/) — reshape climate data and calculate model evaluation statistics.

## Citation for DMAP-AI

Kolsoumi Ayask, S. (2026). **DMAP-AI: Drought Monitoring and Analysis Platform – AI** [Software]. AgriMetSoft LLC. https://droughtanalysis.com/
