# Topoflow Workflow

## Simple Configuration

Only the d8_base component receives data from South Sudan, everything else is set to default

### Configuration files

[Link to configuration files here]

### Executable workflow

[Link to executable workflow]

### Data pre-Processing

#### DEM (Data elevation model) **only**

So far, working on the small Gel-Aliab catchment, which is small enough to be processed on a local machine. The following files are already processed:

* Flow directory (rtg file)
* Slope (rtg file)
* Area (rtg file)

[Bakinam document the manual process]


## More Advanced Configuration

The following components are provided with South Sudan data while the others are set to default:
* Infiltration
* Channel (TBD)
* Meteorology (Precip only)

The components are set in the providers file.

### Configuration files

[Link to configuration files here]

### Executable Workflow

* Example run using [Treynor-Iowa](https://github.com/peckhams/topoflow/tree/master/topoflow/examples/Treynor_Iowa_30m) data is [here]().
* South Sudan [Link to WINGS image here] - Coming Soon

### Data preparation
#### Meteorology

* Precipitation **only** from NOAA FLDAS data. Processing: Working on a WINGS workflow to process the data.

#### DEM (Data elevation model)

So far, working on the small Gel-Aliab catchment, which is small enough to be processed on a local machine. The following files are already processed:

* Flow directory (rtg file)
* Slope (rtg file)
* Area (rtg file)

[Bakinam document the manual process]

#### Channel width and channel roughness
Need to create a rtg file manually. Tried to use River Tools to do so but the demo version doesn't allow to do so.
