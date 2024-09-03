# The WUIX index implementation

## Overview

This repository contains a Python script to implement the WUIX (Wildland-Urban Interface Exposure) methodology.

* This work is part of the WUIX index testing campaign and was presented originally in the **[Wildland-Urban Interface Fire Exposure of Rural Settlements: The case of Montesinho Natural Park](https://doi.org/10.1016/j.ijdrr.2024.104790)**

## Usage

### Requirements

- Python 3.x
- Required Python packages listed in `scripts` &#8594; [`requirements.txt`](https://github.com/dener-silv2/WUIX_implementation/blob/main/scripts/requirements.txt) 

### Instructions

1. Clone the repository:

```bash
git clone https://github.com/dener-silv2/WUIX_implementation.git
```

2. Navigate to the repository directory:

```bash
cd .\WUIX_implementation
```

3. Install required packages:

```bash
pip install -r .\scripts\requirements.txt
```

## The main script

> [**wui_implementation.ipynb**](scripts/wui_implementation.ipynb)


## Script Overview

The script performs the following steps:

&#10102;   **Import orthoimage**: Collection of the orthoimage of the defined surrounding region for the study area.

&#10103;   **Try veggetation identification indices**: Apply and compare different indexes for identification of the vegetation and define the most adequate for the next steps.

&#10104;   **Prepare Village**: Prepare the required files for WUIX2 based on the identified vegetation and vectors of existing houses.

&#10105;   **Performe WUIX methodology**: Apply the WUIX methodology through the WUIX2 software.

&#10106;   **Prepare Data Presentation**: Show preliminary results and apply the standardized colour plot.

&#10107;   **Stores Outputs**: Stores the gathered outputs and other data for further analysis.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments and funding

>  This work was financed by National Funds through the Portuguese funding agency, FCT - Fundação para a Ciência e a Tecnologia, within the project INHAVIT, reference MTS/BRB/0086/2020.
