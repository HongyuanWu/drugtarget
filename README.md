
Timeline: 

* [165](extdata/pancancer.drugtarget.pick.rnaseq.dmg.smdos.hr.pick.csv) interesting cancer targets were identified with differential gene expression and survival analyisis

* top [80 most signficant](extdata/tcgaDgeMeta/image/) differential expression genes with code: `subset(rlt,abs(beta)>1 & pval<10^-12)`

* [Drug Gene Interaction database (DGIdb)](http://www.dgidb.org/): drug-gene interactions and the druggable genome, [free download](http://www.dgidb.org/downloads)

* [DrugBank (1572 Drugs)](http://www.drugbank.ca/downloads):includes external identifiers: CAS, UniProt, PhamGKB, TTD

* [TTD (3199 Drugs)](http://bidd.nus.edu.sg/group/cjttd/TTD_Download.asp): Therapeutic Target Database, includes many synonyms!

* [PhamGKB (1885 Drugs)](http://www.pharmgkb.org/resources/downloads_and_web_services.jsp): use genes.tsv, drugs.tsv, relationships.tsv. There is the option to get genotype-SNV linking directly to drug, with requested license.

* [Chembl (1,143,682 compounds)](https://www.ebi.ac.uk/chembldb/index.php/downloads): Usable through .json or xml API ** important to note that the relationship is Compound(drug) to it's bio-activities which in turn are linked to Target(gene) OR Assay(evidence of interaction)


Reference: 

* Mutation hotspots may not be drug targets: https://science.sciencemag.org/content/364/6447/1228
* Targeting transcription factors: https://www.nature.com/articles/nrd.2018.231
