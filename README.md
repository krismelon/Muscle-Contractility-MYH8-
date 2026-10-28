## Muscle-Contractility-MYH8

## A

**assignment number:** 8

**gene:** MYH8

**transcript:** NM_002472.3

**Matching NP_ protein accession:** NP_002463.2

**ClinVar ID:** 14136

## B. Research Questions

**1. What does your assigned gene encode, and how does this protein contribute to muscle function?**

* My assigned gene is MYH8 which encodes myosin heavy chain 8, a protein mainly found in developing skeletal muscle. It helps muscles contract by interacting with actin and using energy from ATP to generate force and movement.

**2. What was the exact protein accession and length retrieved with R?**

* The matching protein accession is NP_002463.2, and the reference protein contains 1,937 amino acids.
   
**3. What did the amino-acid composition chart show? What can it NOT tell you?**

* The amino-acid composition chart showed the number of each of the 20 standard amino acids found in the MYH8 protein. It helped identify which amino acids were most abundant in the protein. However, the chart cannot show the protein's complete three-dimensional structure or prove how the p.Arg674Gln variant affects its function.

**4. What is your fixed ClinVar variant, and what is its current classification and evidence strength?**

* My assigned variant is MYH8 c.2021G>A (p.Arg674Gln), listed under ClinVar Variation ID 14136. It is classified as pathogenic, with 8 out of 10 submissions contributing to the classification in my screenshot. The evidence is supported by multiple submitters with no conflicting classifications, and previous reports have linked this variant to muscle-related conditions, including trismus-pseudocamptodactyly syndrome and Hecht syndrome.

**5. What is the scientifically supported mechanism linking this variant to muscle function, andwhat
remains uncertain?**

* The MYH8 p.Arg674Gln variant changes an amino acid in the myosin head region, near the ATP-binding site and within the actin-binding region. Since myosin uses ATP to generate force through its interaction with actin, this substitution may affect the normal function of the protein and contribute to muscle-related conditions such as trismus-pseudocamptodactyly syndrome. The variant has been reported in affected families, but the exact biochemical effects on ATP binding, actin interaction, and muscle force still need to be established experimentally.

**6. What additional experiment would help test the proposed mechanism?**

* A useful experiment would compare normal myosin with the variant myosin in a laboratory. Researchers could measure how strongly each protein binds to actin and how efficiently it uses ATP. The results would help determine whether the variant affects myosin function and could explain its connection to muscle-related symptoms.

## Steps in R Studio

# Step 1.  Set up your R project

<img width="620" height="186" alt="Screenshot 2026-10-28 084623" src="https://github.com/user-attachments/assets/f81fd4f1-004a-4979-9cef-39c73bdf549f" />

An RStudio project called Muscle_Contractility_MYH8 was created with an R script and folders to store data, results, and figures. The rentrez and ggplot2 packages were used to collect information from NCBI and create graphs.

# Step 2. Retrieve your human NCBI Gene record using R

<img width="538" height="622" alt="Screenshot 2026-10-28 084648" src="https://github.com/user-attachments/assets/59341a77-acba-4c19-beeb-429d10b3091c" />

The MYH8 gene was located in the NCBI database using its gene name and human taxonomy ID, and the gene details were stored in a text file inside the results folder.

# Step 3. Retrieve the matching protein sequence from the assigned transcript

<img width="770" height="557" alt="Screenshot 2026-10-28 084706" src="https://github.com/user-attachments/assets/cd217bea-b8ab-4820-a853-0fd184fc38db" />

The transcript NM_002472.3 was used to find its matching protein record in NCBI, and the protein sequence was downloaded as a FASTA file and stored in the data folder, while its accession number was noted in the results folder.

# Step 4. Analyze protein length and amino-acid composition in R

<img width="1051" height="425" alt="Screenshot 2026-10-28 084748" src="https://github.com/user-attachments/assets/31308d02-4590-4985-a22d-aff4d4ee2cd3" />

The protein sequence was analyzed in R to find its total length and count the amino acids present, then the data were saved in a CSV file and displayed in a bar chart.

# Step 5. Open and document your PREASSIGNED ClinVar record

<img width="732" height="866" alt="Screenshot 2026-10-28 073642" src="https://github.com/user-attachments/assets/365d3617-11c3-40fe-9bff-ec02cf4a3733" />

The information of MYH8 Variation ID 14136 were obtained from ClinVar, including the variant’s classification, related condition, transcript details, and supporting evidence. The available classification and review information were also documented at the time of access.

# Step 6. Produce a second biological visualization

<img width="827" height="481" alt="Screenshot 2026-10-28 084758" src="https://github.com/user-attachments/assets/a87e74cb-b0e8-4f8c-9684-a32c0abddbb3" />

A protein map was made in R using `ggplot2` to illustrate the MYH8 protein’s full length and indicate the variant’s location at amino acid 674. The finished figure was saved in the figures folder for reference.

# Step 7. 

The MYH8 gene provides instructions for making a myosin heavy-chain protein that helps skeletal muscles contract. Myosin interacts with actin and uses energy from ATP to produce muscle movement. The assigned variant, c.2021G>A (p.Arg674Gln), changes the amino acid arginine to glutamine at position 674. ClinVar classifies this variant as pathogenic and reports an association with trismus-pseudocamptodactyly syndrome. However, the exact molecular effect of this amino acid change on myosin activity is still not fully understood. The proposed mechanism is that the variant may affect how myosin interacts with actin, potentially changing muscle function. To test this, an experiment could compare normal myosin with myosin containing the p.Arg674Gln variant by measuring actin binding and ATPase activity. The results could help determine whether the variant affects the interaction between myosin and actin or the use of ATP during muscle contraction.

# Step 8. Publish the full workflow and results on GitHub

The R script, MYH8 gene details, protein sequence, accession number, amino acid composition data, variant information, and figures were saved in their respective folders. A README file was also created to explain the project, procedures, results, and interpretation of the MYH8 variant.

## D. Results/figures

<img width="177" height="500" alt="Screenshot 2026-10-28 092457" src="https://github.com/user-attachments/assets/f5764f72-cced-4b30-a862-a4b62e0e57af" />

**_Table 1_**. Amino acid composition of the gene MYH8

<img width="2400" height="1500" alt="01_amino_acid_composition" src="https://github.com/user-attachments/assets/cf1cdf24-acbf-47c3-b767-efb4558f6ca3" />

**_Figure 1_**. Bar graph showing the amino acid composition of MYH8, where the x-axis shows the amino acid types and the y-axis that shows the number of residues.

<img width="2400" height="750" alt="02_variant_position" src="https://github.com/user-attachments/assets/2220dbe9-e153-4b6a-a365-f23bd33c0878" />

Figure 2. Mapping of the MYH8 protein variant. The diagram illustrates the complete reference protein sequence and identifies the position of the p.Arg674Gln mutation at residue 674. The highlighted site shows where arginine is replaced by glutamine, but the diagram does not establish whether this substitution changes the protein’s activity.

## E. Variant Interpretation

The assigned MYH8 variant, c.2021G>A (p.Arg674Gln), changes the amino acid arginine to glutamine at position 674 of the myosin heavy-chain protein. ClinVar classifies this variant as pathogenic and reports an association with trismus-pseudocamptodactyly syndrome, a condition that can affect jaw opening and finger movement. Studies by Veugelers et al. (2004) and Toydemir et al. (2006) support the association between this variant and the condition. Since myosin interacts with actin and uses ATP to support muscle contraction, the substitution may affect the protein's function. However, the exact molecular effect of this specific variant is not fully established, so changes in actin binding or ATP use should be considered possible explanations rather than confirmed effects.

## F. Limitations and a Possible Validation Experiment

One limitation of this analysis is that it relies mainly on database records and published studies rather than direct laboratory testing of the MYH8 variant. Although the variant has a reported clinical association, the available information does not fully explain how the amino acid substitution affects myosin activity. The protein-position plot identifies where the variant occurs but cannot show whether it changes the protein's structure or function. A possible validation experiment would compare normal myosin with myosin containing the p.Arg674Gln variant. Researchers could measure actin-binding ability and ATPase activity to determine whether the variant affects the interaction between myosin and actin or the use of ATP. The results could provide further evidence about the variant's molecular effects.

## G. Database links, accession versions, access dates, and citations.

| Database/Resource | Accession or Record ID | Link | Access Date |
|---|---|---|---|
| NCBI Gene | MYH8 (Gene ID: 4626) | https://www.ncbi.nlm.nih.gov/gene/4626 | October 28, 2026 |
| NCBI Nucleotide | NM_002472.3 | https://www.ncbi.nlm.nih.gov/nuccore/NM_002472.3 | October 28, 2026 |
| NCBI Protein | NP_002463.2 | https://www.ncbi.nlm.nih.gov/protein/NP_002463.2 | October 28, 2026 |
| ClinVar | Variation ID 14136 | https://www.ncbi.nlm.nih.gov/clinvar/variation/14136/ | October 28, 2026 |
| R Project | R statistical software | [R Project](https://www.r-project.org/) | October 28, 2026 |

## H. Discussion

This project examined the MYH8 gene, which encodes a myosin heavy-chain protein that plays an important role in skeletal muscle contraction. The gene details, reference transcript NM_002472.3, and matching protein accession NP_002463.2 were obtained from NCBI. The protein sequence was downloaded in FASTA format and processed using R to determine its length and amino acid composition. The amino acid counts were organized into a CSV file and visualized in a bar plot to compare the abundance of different amino acids. Another figure was generated to identify the position of the p.Arg674Gln variant at amino acid 674 in the MYH8 protein. This variant replaces arginine with glutamine and is listed in ClinVar as Variation ID 14136. Research by Veugelers et al. (2004) and Toydemir et al. (2006) supports the association of this variant with trismus-pseudocamptodactyly syndrome. However, the precise effect of this substitution on myosin function remains uncertain, as the analysis did not include direct laboratory testing. Further investigation could compare normal and variant myosin by measuring actin binding and ATPase activity to determine whether the substitution affects the protein's role in muscle contraction. Overall, this project demonstrated how NCBI, ClinVar, and R programming can be used to examine protein sequences, visualize variant locations, and interpret genetic findings while recognizing the limitations of database-based analysis.

## References

Veugelers, M., Bressan, M., McDermott, D. A., Weremowicz, S., Morton, C. C., Mabry, C. C., Lefaivre, J., Zunamon, A., Destree, A., Chaudron, J., & Basson, C. T. (2004). Mutation of Perinatal Myosin Heavy Chain Associated with a Carney Complex Variant. New England Journal of Medicine, 351(5), 460–469. https://doi.org/10.1056/nejmoa040584

Toydemir, R. M., Chen, H., Proud, V. K., Martin, R., Van Bokhoven, H., Hamel, B. C. J., Tuerlings, J. H., Stratakis, C. A., Jorde, L. B., & Bamshad, M. J. (2006). Trismus‐pseudocamptodactyly syndrome is caused by recurrent mutation of MYH8. American Journal of Medical Genetics Part A, 140A(22), 2387–2393. https://doi.org/10.1002/ajmg.a.31495
