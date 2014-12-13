Test files for reproducing vsearch error
===============

- AVSdb.fasta is the full database that is used for the reference checking
- test_query_first_1000.fastq is the first 1000 lines of my fastq file. 
- test_query_first_1000_derep.fasta result of `vsearch -derep_fulllength test_query_first_1000.fastq -output test_query_first_1000_derep.fasta -sizeout`

