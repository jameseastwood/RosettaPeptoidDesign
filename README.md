The Rosetta macromolecular modeling suite [rosettacommons](https://www.rosettacommons.org/) has incorporated the ability to model synthetic oligomers, including peptoids (N-substituted glycine oligomers) [1-3]. The resources in this repository constitute effort to develop design protocols making use of these capabilities. The protocols are implemented as xml files to be passed to the rosetta_scripts program. Some of these scripts may be useful, with minor adaptation, to design peptides and peptidomimetics.

To use these scripts, you will first need to 
1) obtain a valid license for Rosetta, download and install it (https://www.rosettacommons.org/software/license-and-download)
2) Download the NCAA rotamer libraries and place them in Rosetta/main/database/rotamer/ncaa_rotlibs
3) Uncomment the peptoid entries from the database file Rosetta/main/database/chemical/residue_types_sets/fa_standard/residue_types.txt

References:
(1) Renfrew, P. D.; Choi, E. J.; Bonneau, R.; Kuhlman, B. Incorporation of Noncanonical Amino Acids into Rosetta and Use in Computational Protein-Peptide Interface Design. PLoS ONE 2012, 7 (3). https://doi.org/10.1371/journal.pone.0032637.
(2) Drew, K.; Renfrew, P. D.; Craven, T. W.; Butterfoss, G. L.; Chou, F. C.; Lyskov, S.; Bullock, B. N.; Watkins, A.; Labonte, J. W.; Pacella, M.; Kilambi, K. P.; Leaver-Fay, A.; Kuhlman, B.; Gray, J. J.; Bradley, P.; Kirshenbaum, K.; Arora, P. S.; Das, R.; Bonneau, R. Adding Diverse Noncanonical Backbones to Rosetta: Enabling Peptidomimetic Design. PLoS ONE 2013, 8 (7). https://doi.org/10.1371/journal.pone.0067051.
(3) Renfrew, P. D.; Craven, T. W.; Butterfoss, G. L.; Kirshenbaum, K.; Bonneau, R. A Rotamer Library to Enable Modeling and Design of Peptoid Foldamers. Journal of the American Chemical Society 2014, 136 (24), 8772–8782. https://doi.org/10.1021/ja503776z.
