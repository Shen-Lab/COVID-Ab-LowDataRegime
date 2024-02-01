# COVID-Ab-LowDataRegime

## Step 1: Predict the structure of antibodies from the sequences. Then predict the docking complex using the [Haddock](https://www.bonvinlab.org/software/haddock2.4/manual/)
### We calculated the ACE2 binding residues (to be protected by the antibodies), as 'ace2_binding_residue'.
### We used [AbodyBuilder](https://opig.stats.ox.ac.uk/webapps/sabdab-sabpred/sabpred/abodybuilder/) to predict the 3D structures of the antibodies from the sequence.
### We used the [ProABC2](https://wenmr.science.uu.nl/proabc2/) to predict the binding residues on the antibodies side.
### We used the [Haddock](https://www.bonvinlab.org/software/haddock2.4/manual/) to predict the antibody-SARS-Cov-2 binding complex.
### We used [Bayesian Activate Learning](https://pubmed.ncbi.nlm.nih.gov/32558561/) to refine the docking complexes and get a 'confidence score' for each conformation of the same antibody.

## Step 2: Predict the neutralization scores and the robustness to variants for all antibodies. All figures used in manuscripts are also generated using this jupyter notebook.
### 
