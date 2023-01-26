# ShigaToxin_Toxoid_Sequences
Sequences of Shiga toxin subtypes modified to encode a non-toxic (toxoid) mutant of Stx. These mutant sequences can be placed in a cloning plasmid and be used as a non-toxic control for PCR directly as a plasmid or as an E. coli transformant. This will allow for an easier and more accessible way to assess Shiga toxin PCRs for the inclusivity of all known shiga toxin subtypes.

The Shiga Toxin Toxoid (stxoid) sequences are altered from the wild type stx sequence that would produce an enzymatically inactive A subunit protein by modifying glutamate 167 to glutamine (Hovde et al., 1988) and arginine 170 to leucine (Yamasaki et al., 1991). The protein produced by these modifications have been demonstrated to have no toxicity compared to controls in studies with cell cultures, mice, pigs, and calves (Makino et al., 2001; Ishikawa et la., 2003; Ohmura-Hoshino et al., 2004; Wen et al., 2006; Kerner et al., 2015).


NCBI accession numbers and other information used to generate the databases of gene fragments are in: Accession_Numbers_and_info.txt

Sequences of Shiga toxin Toxoids are in: Shiga_Toxin_Toxoid_Sequences.txt

Note: for stx2m sequences, single-end iontorrent reads from strain E75_19 (BioSample # SAMEA7019263) were assembled and stx2m sequences identified as follows:

  1. Strain E75_19 assembly (performed by Julie Shay): Ion torrent reads (SRA ERX4245790) were assembled de novo using SPAdes v3.15.4 (--isolate and --iontorrent flags) after adapter removal with Sickle v1.33 (default SE parameters except for setting "qual-type" to "sanger") and quality trimming with Trimmomatic v0.39 (LEADING:25 TRAILING:25 MINLEN:50). The resulting draft genome was deposited into NCBI (GCA_025984515.1) and annotated with PGAP.

  2. stxm sequences: stx2m nt sequence was identified by BLAST of the stx2a gene region (X07865.1) to the draft genome from stx2m strain E75_19 (performed by Julie Shay); stx2a subunit A and B sequences (CAA30714.1, CAA30715.1) were used to confirm the stx2m the start/stop and spacer region and derive stx2m nt and translated aa sequences (performed by Kelly Weedmark). Sequences were verified by Torsten Seeman.


Provide github link (https://github.com/bmh-vteclab/ShigaToxin_Toxoid_Sequences) along with the current commit number (e.g. c2b6677).


Authors:

Alex Gill1, Tanis McMahon1, Kelly Weedmark1, Julie Shay2

  1Bureau of Microbial Hazards, 251 Sir Frederick Banting Driveway, PL2204E, Health Canada, Ottawa, Ontario, K1A 0K9
  
  2Bureau of Food Surveillance and Science Integration, 251 Sir Frederick Banting Driveway, PL2204E, Health Canada, Ottawa, Ontario, K1A 0K9


References

Hovde, C.J., Calderwood, S.B., Mekalanos, J.J., and Collier, R.J. 1988. Evidence that glutamic acid 167 is an active-site residue of Shiga-like toxin I. Proc Natl Acad Sci U S A. 85:2568–2572. DOI: 10.1073/pnas.85.8.2568

Ishikawa, S., Kawahara, K., Kagami, Y., Isshiki, Y., Kaneko, A., Matsui, H., Okada, N., and Danbara, H. (2003). Protection against Shiga toxin 1 challenge by immunization of mice with purified mutant Shiga toxin 1. Infection and Immunity. 71(6): 3235–3239. DOI:10.1128/IAI.71.6.3235-3239.2003

Kerner, K., Bridger, P.S., Köpf, G., Fröhlich, J., Barth, S., Willems, H., Bauerfeind, R., Baljer, G., and Menge, C. 2015. Evaluation of biological safety in vitro and immunogenicity in vivo of recombinant Escherichia coli Shiga toxoids as candidate vaccines in cattle. Veterinary Research. 46(1):38. DOI: 10.1186/s13567-015-0175-2.

Makino, S., Watarai, M., Tabuchi, H., Shirahata, T., Furuoka, H., Kobayashi, Y., and Takeda, Y. (2001). Genetically modified Shiga toxin 2e (Stx2e) producing Escherichia coli is a vaccine candidate for porcine edema disease. Microbial pathogenesis, 31(1), 1–8. DOI: 10.1006/mpat.2001.0440

Ohmura-Hoshino, M., Yamamoto, M., Yuki, Y., Takeda, Y., and Kiyono, H. (2004). Non-toxic Stx derivatives from Escherichia coli possess adjuvant activity for mucosal immunity. Vaccine, 22(27-28), 3751–3761. DOI: 10.1016/j.vaccine.2004.03.034

Wen, S. X., Teel, L. D., Judge, N. A., and O'Brien, A. D. 2006. Genetic toxoids of Shiga toxin types 1 and 2 protect mice against homologous but not heterologous toxin challenge. Vaccine, 24(8), 1142–1148. DOI: 10.1016/j.vaccine.2005.08.094

Yamasaki, S., Furutani, M., Ito, K., Igarashi, K., Nishibuchi, M., and Takeda, Y. 1991. Importance of arginine at position 170 of the A subunit of Vero toxin 1 produced by enterohemorrhagic Escherichia coli for toxin activity. Microb Pathog 11:1–9. DOI: 10.1016/0882-4010(91)90088-r
