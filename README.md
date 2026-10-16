# Sen2Fire-Wildfire-Detection
Sen2Fire Multispectral Wildfire is a research-oriented project that investigates the application of multispectral satellite imagery and deep learning for wildfire analysis. Using the Sen2Fire dataset as the initial benchmark, the project explores how spectral information can support wildfire-related segmentation, how models generalize across geographical regions, and how satellite-derived spectral indices can support post-fire burn severity assessment.

## Core Components

### Multispectral Segmentation
Investigates the use of multiple Sentinel-2 spectral bands to segment wildfire-related regions. Experiments compare RGB and multispectral inputs to evaluate the contribution of spectral information to segmentation performance.

### Cross-Region Generalization
Evaluates model robustness on geographically distinct scenes that are excluded from training. The objective is to understand how geographical distribution shifts affect prediction quality and whether learned spectral representations generalize beyond the training data.

### Burn Severity Analytics
Explores post-fire land damage assessment using spectral indicators such as the Normalized Burn Ratio (NBR) and differenced Normalized Burn Ratio (dNBR). Suitable pre-fire and post-fire satellite imagery will be required to analyze changes in vegetation and burned landscapes.

## Dataset
Primary dataset: Sen2Fire
Sen2Fire serves as the initial benchmark for multispectral wildfire-related segmentation experiments.
Dataset source: https://zenodo.org/records/10881058
Additional satellite imagery may be incorporated for cross-region evaluation and burn severity analysis, subject to data availability and compatibility with the research objectives.
