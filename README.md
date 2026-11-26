# upstart-task-02-db-search-annotation
## Search Parameters
* **Program:** `blastn`
* **Database:** Standard databases (`nr/nt`)
* **Query:** `seq1_example` (60 bp)

## Annotation Table

| Query ID | Accession | Scientific Name | Query Cover | Per. Ident | E-value | Biological Annotation |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `seq1_example` | `PX214263.1` | *Homo sapiens* | 100% | 100% | 2.00E-21 | Human hemoglobin subunit beta (*HBB*) / beta-globin related sequence (oxygen transport in erythrocytes) |
| `seq1_example` | `LC507570.1` | *Homo sapiens* | 100% | 100% | 2.00E-21 | Human beta-globin (*HBB*) sequence / variant |
| `seq1_example` | `LC507569.1` | *Homo sapiens* | 100% | 100% | 2.00E-21 | Human beta-globin (*HBB*) sequence / variant |
| `seq1_example` | `MK476504.1` | *Homo sapiens* | 100% | 100% | 2.00E-21 | Longer *Homo sapiens* transcript/sequence containing the matching beta-globin region |
## Biological Interpretation

The query `seq1_example` aligns with **100% query coverage** and **100% sequence identity** (E-value = `2.00E-21`) to *Homo sapiens* sequences corresponding to hemoglobin subunit beta (*HBB* / beta-globin), which encodes the beta chain of adult hemoglobin A responsible for oxygen transport. The very low E-value (`2.00E-21`) and full coverage indicate a strong, non-random match rather than a chance alignment. However, because the query is a short fragment (60 bp), identical 100% matches appear across multiple human accessions, variants, and transcript lengths (such as 656 bp, 699 bp, and 1824 bp records). Full-length sequence comparison and functional context are therefore needed to distinguish specific alleles, isoforms, or genomic/transcript records.
