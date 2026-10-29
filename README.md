# PCR Master Mix Calculator

This is a lightweight, browser-based calculator for setting up PCR master mixes and overlapping PCRs.

(https://pvalissery.github.io/pcr-calculators/) 

This tool takes the core math from my personal lab spreadsheets and ports it into a clean web UI. 

* **Taq PCR Calculator:** Standard master mix math based on reaction volume, target template concentration, and number of tubes. 
* **Phusion PCR (Standard):** Calculates mix for standalone Phusion polymerase, dNTPs, and 5x Buffer.
* **Phusion Hot Start Flex (2x Master Mix):** Quick calculations for the premixed 2x version, including extension time estimates based on amplicon size.
* **Overlapping PCR Calculator:** Figuring out equimolar concentrations for two different fragments is always annoying. You just punch in the concentration (ng/ul) and size (bp) of both fragments, and this spits out exactly how many microliters of each to pool together.

## How to use it
Since it's built entirely with HTML, CSS (Tailwind), and vanilla JavaScript, you have two options:
1. **The easy way:** Just bookmark the live GitHub Pages link at the top of this readme and pull it up on your phone or lab tablet. 
2. **The offline way:** Clone this repo or just download the `index.html` file, double-click it, and it will run locally in your browser **without an internet connection**.

## Caveats
* The Overlapping PCR calculator assumes standard base pair molecular weights. 
* Always double-check your pipetting volumes if you have weirdly concentrated primer stocks. The default calculators assume standard working concentrations (e.g., 10 uM primers). 

Feel free to fork this and tweak the default concentrations to match whatever your lab keeps in the freezer.
