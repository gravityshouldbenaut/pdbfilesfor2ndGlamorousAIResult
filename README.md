# pdbfilesfor2ndGlamorousAIResult
PDB files for the #2 highest binding affinity Mpro Inhibitor from Glamorous AI + Cardiff University's Generative Model

Glamorous AI and Cardiff University created a generative machine learning software (https://chemrxiv.org/articles/A_Generative_Deep_Learning_Approach_for_the_Discovery_of_SARS_CoV2_Protease_Inhibitors/12170337) to come up with potentially brand new pharmaceutical compounds that could be used to inhibit the proteolytic processing of SARS-COV-2 and SARS-COV proteases. The compound with the second highest binding affinity with SARS-COV-2 and highest binding affinity for SARS-COV was provided in SMILES format as: 

CC(O)N1CCN(S(O)(O)C2cC3C(F)CCc(O)C3(F)c4c(O)cc(O)c(O)c24)CC1

Using RPBS's Web Portal, I converted this into PDB format (https://mobyle.rpbs.univ-paris-diderot.fr/cgi-bin/portal.py#welcome) but then had to break it down by model to convert into PDBQT format for Autdock Vina. 

In this Repository, you will find the PDB for the entire SMILES compound, as well as the first 5 models in PDBQT format. If you are working on additonal models, please make a pull request and add them here! It is very tedious work.


