# HCR Probe Designer
<img width="2064" height="1145" alt="hcr_probe_designer" src="https://github.com/user-attachments/assets/01df0259-e35a-4fe6-84c7-221105b097ac" />

**Live App Link:** [HCR Probe Designer](https://tirthadasbanerjee.com/hcrprobedesigner/hcr_22.1.html)

## Overview
The HCR Probe Designer is a fast, web-based utility designed to streamline the creation of HCR3.0 style probes for spatial mRNA profiling. It automatically processes target gene sequences to generate appropriate probe pairs based on user-defined parameters, accelerating the probe design workflow.

## Features
* **Customizable Parameters:** Define your gene name, sequence, amplifier type, GC content threshold, and the gap between probe sets.
* **Amplifier Selection:** Fully supports 20 different HCR amplifiers (B1 through B20).
* **Dynamic Validation:** Automatically reverse-complements sequences and filters out probe pairs that do not meet the chosen GC content threshold.
* **Visual Sequence Highlighting:** Visually maps and highlights the successful probe regions directly on the input sequence in the browser.
* **Streamlined Export:** Generates an `.xlsx` file containing the generated probe sets. The output is specifically formatted for seamless ordering from Integrated DNA Technologies (IDT) as either individual oligos (100 µM) or as Pools (oPool at 50 pmol/oligo).

## How to Use
1. **Enter Gene Name:** Input an identifier for your target gene.
2. **Enter Gene Sequence:** Paste your target sequence. *Note: The sequence must be a minimum of 102 base pairs.*
3. **Select Amplifier:** Choose your desired HCR amplifier sequence (B1 to B20) from the dropdown.
4. **Set GC Content Threshold (%):** Select the minimum allowable GC concentration (ranging from 30% to 70% in 5% increments).
5. **Define Probe Gap:** Enter the spacing between distinct probe sets in base pairs (defaults to 30).
6. **Design Probes:** Click **"Design Probes"** to generate your pairs. The app will display your sequence with the selected probe binding regions highlighted.
7. **Download Excel File:** Click **"Download Excel File"** to export your formatted `hcr_probes.xlsx` file.

## Developer
Developed by [Tirtha Das Banerjee](https://scholar.google.com/citations?user=H2S5ROQAAAAJ&hl=en).

## References & Citations
If you utilize this tool in your research workflow, please consider citing the following literature:

* Banerjee, T. D., Raine, J., Mathuru, A. S., Chen, K. H., and Monteiro, A. (2024). A spatial mRNA profiling workflow using Rapid Amplified Multiplex FISH (RAMFISH). *bioRxiv*. [Link](https://www.biorxiv.org/content/10.1101/2024.12.06.627193v4)
* Choi, H. M. T., Schwarzkopf, M., Fornace, M. E., Acharya, A., Artavanis, G., Stegmaier, J., Cunha, A. and Pierce, N. A. (2018). Third-generation in situ hybridization chain reaction: multiplexed, quantitative, sensitive, versatile, robust. *Development*. [Link](https://journals.biologists.com/dev/article/145/12/dev165753/48466/Third-generation-in-situ-hybridization-chain)
* Wang, Y., Liu, X., Zeng, Y., Saka, S. K., Xie, W., Goldaracena, I., Kohman, R. E., Yin, P. and Church, G. M. (2024). Multiplexed in situ protein imaging using DNA-barcoded antibodies with extended hybridization chain reactions. *Nucleic Acids Research 52*, e71. [Link](https://academic.oup.com/nar/article/52/15/e71/7706473)
