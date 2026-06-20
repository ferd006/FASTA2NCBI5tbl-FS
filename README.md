# FASTA2NCBI5tbl-FS
FASTA2NCBI5tbl-FS is a specialized bioinformatics command-line utility. It simplifies the preparation of genetic sequence data for submission to the NCBI GenBank repository.  Specifically, the tool takes query nucleotide sequences (in standard FASTA) and cross-references them against an official NCBI database entry via a GenBank reference ID. . It dynamically aligns the two, extracts exon boundaries, checks for translational anomalies, and outputs an NCBI-compliant five-column feature table (.tbl).

Before running the install sequence provided in your script, ensure your system meets the following software prerequisites:

Python Version: Python 3.7 or higher (Python 3.8 to 3.11 is recommended for stability with the specified external dependencies).
Network Connectivity: Active internet connection is mandatory during runtime execution so Biopython can retrieve structural gene components via NCBI Entrez servers.

chmod +x FASTA2NCBI5tbl-FS

./dist/FASTA2NCBI5tbl-FS --input filename.fas --ref JQ711180.1 --email your@email.com --output result.tbl


