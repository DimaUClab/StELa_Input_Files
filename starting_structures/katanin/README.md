# README
## Katanin Monomer
The starting structures for running the monomer were adapted from the 6ugd-E14.pdb where we extracted chain A - 6ugd-A-E14.pdb and ATP-A.pdb. The 6ugd-a-e14-atp-topol.top file for the complex set up is provided as an example.

For the COMPLEX setup, the E14 & ATP were incorporated. For the NUC set up we removed the E14 (chain G). For the SUB state we did not incorportate the ATP. For the APO we removed chain G and did not incorporate the ATP.

# Katanin Trimer
The starting structures for running the trimer were adapted 6UGE-ABC-E14.pdb and ATP-BC.pdb. It is important to note that in the ring conformation of katanin by which this trimer was generated for, there is no nucleotide in protomer A. The 6uge-abc-e14-atp-topol.top file for the complex set up is provided as an example. 

As done in the monomer, for the COMPLEX setup, the E14 & ATP were incorporated whereas for the APO set up, neither were included.

The ATP was parameterized with the Automated Topology Builder and Repository (ATB) server. The files used are provided in the atb_param directory. (https://atb.uq.edu.au/)
