
# Chromothripsis

## Background

A new phenomenon called chromothripsis was discovered by [Stephens et al. in 2011](www.ncbi.nlm.nih.gov/pubmed/21215367), in which chromosomes shatter and are poorly rearranged in a single catastrophic event. Chromothripsis appears to lead to cancer in many cases (88.9% in Acute lymphoblastic leukemia with iAMP21, 100% in ISHH medulloblastoma with mutant TP53, etc.) and challenges the previous theories of slow accumulation of genetic mutations leading to cancer. There are various stimuli that are proposed to cause it, including the formation of micronuclei and radiation. One particular stimulus I explored was telomere instability ([Rode, et al. 2015](onlinelibrary.wiley.com/doi/full/10.1002/ijc.29888)), which has been linked to chromothripsis ([Ernst, et al. 2016](onlinelibrary.wiley.com/doi/full/10.1002/%20ijc.30033)). I created a protocol that leads to telomere crisis and finally, chromothripsis.
## Experimental Process
### Overview
The protocol to shorten telomeres involved modifying the TREX1 gene, which leads to telomere bridges and further to telomere shortening and ultimately to chromothripsis. The TREX1 modification validation involved Sanger sequencing of the TREX1 gene. The telomere shortening is validated by a method involving the use of restriction enzymes known as Telomere Restriction Fragment (TRF) method. Occurrence of chromothripsis is validated using a low-cost DNA fingerprinting method (Amplified Fragment Length Polymorphism/AFLP) instead of whole genome sequencing.
### Cell Culturing 

Experiments were carried out on A549 cells (human lung carcinoma) which had to be cultured first. 

![Splitting a Flask](https://lh3.googleusercontent.com/gPolDUIFY2_V2asGlNlR-ae6dgiVF7fXvuBD0iEEu4RcpemfRw7ALC8RpHKVp9HZjxGT_5ArD4s "Cultures, cultures, cultures")
##### Splitting a flask
![Culture Flasks](https://lh3.googleusercontent.com/Nh3DXarFFMHyfGFzUbcgAdJN5SWmS5CgA-FL0l6gFXKQmL6D5h_1-SbTNgOuccynEPUUJyUHGeg "Culture Flasks")
##### Culture flasks
![Cells after 1 Day of Growth](https://lh3.googleusercontent.com/U3dOEb3IK2BlPiBcfC1PMCQQA0WsnqLX6OE1rF2PL9_hciR-NZYebRBFrI-8bx5Yx0bEFoIthlU "Cells after 1 Day of Growth")
##### Cells after 1 day of growth
![After 4 Days of Growth](https://lh3.googleusercontent.com/12XjqlSrMMIPbXwFtLLDTRV3M5yfHh-6Q6r06ghRZ7Ka_v7T5DShXsya2UdOwMAmCYnNFgFq7ws "After 4 Days of Growth")
##### Cells after 4 days of growth

### CRISPR/Cas9 Edit

I used CRISPR/Cas9 to edit the TREX1 gene and render it useless ( [Maciejowski, et al. 2016](www.ncbi.nlm.nih.gov/pmc/articles/PMC4687025/)).

Once the cultures had grown enough, I plated them into 6-well plates. 

![Cells in 6-well plates.](https://lh3.googleusercontent.com/oLmTeNCuizqjgpLoGHCvAst1rGg2cdF0FWUGWcH1snI6msIXDKVayZkDw_7aJJ8W_WiPs0cIwdql "Plating!")

#### Making RNP Complex

![RNP Formation](./svgs/RNPformation.svg)


#### Transfecting

![Transfection](./svgs/transfection.svg)

After I left the cells to grow, they looked like this 4 days later:

![enter image description here](https://lh3.googleusercontent.com/9h2LJ-pbWhpvcELoV5fr_GJfQGtHwv4oqOXqU090DsscH8ZyBWPccVOYPcQCzOFx4vSmn3Zk9Y_R)
![enter image description here](https://lh3.googleusercontent.com/hT-NYq251ckUiFHQad1hKIJeNp6vThJJrPf_B8SlbLfu1n8Jkpcs6PDD_QKb88HQMaJy1bVUUA1w)


I then tried a plate using only Lipofectamine and no Cas9 to check to see if there was a difference in visuals. 
![enter image description here](https://lh3.googleusercontent.com/Q7cDeOqa2WVUcxpb6H11DFihLp6SSlpCuBhZhEVOO6NHVIPFWtsshpbJrGsJjOaXAYLrV0fmB2AI)
![enter image description here](https://lh3.googleusercontent.com/E_w6A0Ikj3UWIpiPdUfHC9bCYnvuA8yWhoOcs6waU6gF8rMzlTDAf07JeG8V3GgkczpFjDlhvlSJ)
I could then conclude that the visual difference was due to the Cas9, and not the Lipofectamine.

### DNA Extraction  

I extracted the DNA from both the gene edited cells and the regular cells so I could run a series of tests to see if the gene edit actually happened and if chromothripsis occurred.

![enter image description here](https://lh3.googleusercontent.com/uf-SLD-d0lq-TiWCXLrQJgFG2l3o-lqMwvfScQ2yv6Q8pnCNLwxCubQ7MSVTv0xgEHThAr09gE8o)
##### DNA extractions of the samples
![enter image description here](https://lh3.googleusercontent.com/RLgs6zc4jMOtN-xIMFxnx859b-j-a1PdKIBKXbXa6Lb99cazuALY7JB4J_8gtyFRuhLWawc4aq6C)
##### DNA

![enter image description here](https://lh3.googleusercontent.com/4o2JxjiXYkITjqI1HMyLMfEI4eqVCTz0gdoTK50wbDhpDct8RRHkTCeKQGkAnE2sniEUlrleAWbj)
##### DNA Concentration of a Sample

### Gene Modification Validation

I performed PCR to amplify the TREX1 gene in a DNA sample. However, sequence data for the amplified sample showed the PCR ended up amplifying the regular cells (confirmed with sequence data for the regular cells). The sequence data for the non-PCR sample of unedited cells had noise indicating that there was genome rearrangements, however with the mix of different edits and no edits, it was hard to tell where exactly edits occurred. 
![enter image description here](https://lh3.googleusercontent.com/o2A1bC9q0W04O6_yZto0qVcn3rsoNltHqkvSJx2bW23liwFqEj0ZLYWAnyYtn9P3hC45CUACd7UM)
Regular TREX1 (top) compared to the mix of edited and unedited chromothripsis-ridden cells (bottom)

### Telomere Fusion Validation

Explained by the breakage-fusion-bridge (BFB) cycle, a dicentric chromosome is formed by the fusion of the two unprotected telomeres and the centromeres of the chromosomes. When the chromosomes are pulled to the opposite sides of the cell, an anaphase bridge forms.

-   Telomere bridges are very volatile and lead to telomere shortening, as found by [Capper et al. (2007)](www.ncbi.nlm.nih.gov/pmc/articles/PMC1993879/) 
-   TREX1 deletion leads to telomere fusion, as given by [Maciejowski et al. (2015)](www.ncbi.nlm.nih.gov/pmc/articles/PMC4687025/)
-   Used subtelomeric primers to amplify the telomere fusions during PCR, and ran the PCR products on a 0.7% agarose gel (gel electrophoresis)

![enter image description here](https://lh3.googleusercontent.com/wLotPrIEbp4l-rf6Eayqp9dVImg2T_5PzbNlXBp03fhXmQ1G20WpMKkvWH4JS-MVyw3LK5QmdaeI)
##### Gel results
The bands on the 2 control samples are both identical (which is expected). The 12 edited samples have varying bands (some shorter and some the same length as the control) showing the samples which still have DNA in the telomere bridge phase (shorter bands) and the samples which are out of the phase (same length as control).

### Telomere Shortening Validation
I used the Telomere Restriction Fragment method for analysis 

### DNA Fingerprinting Analysis
