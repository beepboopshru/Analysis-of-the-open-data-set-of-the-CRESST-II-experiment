### Analysis of the open data set of the CRESST-II experiment

This repository contains the analysis code and the publicly available data from the CRESST-II Phase 2 experiment, which operated for about two years from July 2013 to August 2015. CRESST-II is a cryogenic dark-matter search experiment that uses detector modules to measure energy depositions from particle interactions. The published data includes event energies and cut-survival probabilities from two detector modules, TUM40 and Lise, which were used for direct dark-matter searches.

#### Project Structure

* `Files/`: This directory contains all the raw data files in ASCII format. The files include event energies and cut-survival probabilities for the TUM40 and Lise detectors.
* `DataDescription_080217.pdf`: The official document describing the data sets and how to use them.
* `main.ipynb`: A Jupyter Notebook (or Python script) with the code for data analysis and figure reproduction.

#### Analysis and Reproducing Figures

The provided Python code uses the `pandas` library to read the data files and `matplotlib` to plot the results. The analysis successfully reproduces the following figures from the data description document:

* **Figure 3**: Energy spectra of events in the electron-recoil band for TUM40 and Lise.
* **Figure 4**: Cut-survival probabilities for electron and nuclear-recoil events within the electron-recoil band.
* **Figure 5**: Energy spectra of events within the dark-matter acceptance region.
* **Figure 6**: Cut-survival probabilities for different recoil events within the acceptance regions.
* **Figure 7**: Upper 90% exclusion limits for the dark-matter particle cross section.

#### Getting Started

To run the analysis and reproduce the figures, follow these steps:

1.  **Prerequisites**: Ensure you have Python and `pip` installed.
2.  **Clone the repository**:
    ```
    git clone [https://github.com/beepboopshru/Analysis-of-the-open-data-set-of-the-CRESST-II-experiment.git](https://github.com/beepboopshru/Analysis-of-the-open-data-set-of-the-CRESST-II-experiment.git)
    ```
3.  **Install dependencies**: Navigate to the project directory and install the required libraries.
    ```
    cd Analysis-of-the-open-data-set-of-the-CRESST-II-experiment
    pip install pandas matplotlib numpy
    ```
4.  **Run the analysis**: Execute the Python script or run the Jupyter Notebook to generate the plots.

#### Citation

If you base your work on this data, the authors kindly ask that you  this document as well as the relevant papers for the TUM40 and Lise data.

**References:**
* R. Strauss, et al., EPJ C 75, 352 (2015), arXiv:1410.1753 
* G. Angloher, et al., EPJ C 74, 3184 (2014), arXiv: 1407.3146 
* G. Angloher, et al., EPJ C 76, 25 (2016), arXiv:1509.01515 
* R. Strauss, et al., JCAP 1506, 030 (2015), arXiv: 1410.4188 
* G. Angloher, et al., Phys. Rev. Lett. []117, 021303 (2016), arXiv:1601.04447 
* G. Angloher, et al., submitted to EPJ C (2016), arXiv: 1612.07662 
* S. Yellin, Phys. []Rev. D 66, 032005 (2002), arXiv: physics/0203002 
