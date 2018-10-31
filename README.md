# Neisseria-meningitidis 84-Nm_S9

```
$ fastqc -o. 84-Nm_S9_L001_R1_001.fastq.gz  84-Nm_S9_L001_R2_001.fastq.gz
Unknown option: o.
Started analysis of 84-Nm_S9_L001_R1_001.fastq.gz
Approx 5% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 10% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 15% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 20% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 25% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 30% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 35% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 40% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 45% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 50% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 55% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 60% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 65% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 70% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 75% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 80% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 85% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 90% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Approx 95% complete for 84-Nm_S9_L001_R1_001.fastq.gz
Analysis complete for 84-Nm_S9_L001_R1_001.fastq.gz
Started analysis of 84-Nm_S9_L001_R2_001.fastq.gz
Approx 5% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 10% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 15% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 20% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 25% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 30% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 35% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 40% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 45% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 50% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 55% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 60% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 65% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 70% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 75% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 80% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 85% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 90% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Approx 95% complete for 84-Nm_S9_L001_R2_001.fastq.gz
Analysis complete for 84-Nm_S9_L001_R2_001.fastq.gz
```

```
$ java -jar /usr/share/java/trimmomatic-0.36.jar PE -phred33 84-Nm_S9_L001_R1_001.fastq.gz 84-Nm_S9_L001_R2_001.fastq.gz output_forward_paired_30.fq.gz output_forward_unpaired_30.fq.gz output_reverse_paired_30.fq.gz output_reverse_unpaired_30.fq.gz ILLUMINACLIP:TruSeq3-PE.fa:2:30:10 LEADING:30 TRAILING:30 SLIDINGWINDOW:10:30 MINLEN:30
 
TrimmomaticPE: Started with arguments:
 -phred33 84-Nm_S9_L001_R1_001.fastq.gz 84-Nm_S9_L001_R2_001.fastq.gz output_forward_paired_30.fq.gz output_forward_unpaired_30.fq.gz output_reverse_paired_30.fq.gz output_reverse_unpaired_30.fq.gz ILLUMINACLIP:TruSeq3-PE.fa:2:30:10 LEADING:30 TRAILING:30 SLIDINGWINDOW:10:30 MINLEN:30
Multiple cores found: Using 4 threads
Using PrefixPair: 'TACACTCTTTCCCTACACGACGCTCTTCCGATCT' and 'GTGACTGGAGTTCAGACGTGTGCTCTTCCGATCT'
ILLUMINACLIP: Using 1 prefix pairs, 0 forward/reverse sequences, 0 forward only sequences, 0 reverse only sequences
Input Read Pairs: 421249 Both Surviving: 397765 (94,43%) Forward Only Surviving: 18842 (4,47%) Reverse Only Surviving: 2319 (0,55%) Dropped: 2323 (0,55%)
TrimmomaticPE: Completed successfully
```

```
$ fastqc -o. output_forward_paired_30.fq.gz output_reverse_paired_30.fq.gz
Unknown option: o.
Started analysis of output_forward_paired_30.fq.gz
Approx 5% complete for output_forward_paired_30.fq.gz
Approx 10% complete for output_forward_paired_30.fq.gz
Approx 15% complete for output_forward_paired_30.fq.gz
Approx 20% complete for output_forward_paired_30.fq.gz
Approx 25% complete for output_forward_paired_30.fq.gz
Approx 30% complete for output_forward_paired_30.fq.gz
Approx 35% complete for output_forward_paired_30.fq.gz
Approx 40% complete for output_forward_paired_30.fq.gz
Approx 45% complete for output_forward_paired_30.fq.gz
Approx 50% complete for output_forward_paired_30.fq.gz
Approx 55% complete for output_forward_paired_30.fq.gz
Approx 60% complete for output_forward_paired_30.fq.gz
Approx 65% complete for output_forward_paired_30.fq.gz
Approx 70% complete for output_forward_paired_30.fq.gz
Approx 75% complete for output_forward_paired_30.fq.gz
Approx 80% complete for output_forward_paired_30.fq.gz
Approx 85% complete for output_forward_paired_30.fq.gz
Approx 90% complete for output_forward_paired_30.fq.gz
Approx 95% complete for output_forward_paired_30.fq.gz
Analysis complete for output_forward_paired_30.fq.gz
Started analysis of output_reverse_paired_30.fq.gz
Approx 5% complete for output_reverse_paired_30.fq.gz
Approx 10% complete for output_reverse_paired_30.fq.gz
Approx 15% complete for output_reverse_paired_30.fq.gz
Approx 20% complete for output_reverse_paired_30.fq.gz
Approx 25% complete for output_reverse_paired_30.fq.gz
Approx 30% complete for output_reverse_paired_30.fq.gz
Approx 35% complete for output_reverse_paired_30.fq.gz
Approx 40% complete for output_reverse_paired_30.fq.gz
Approx 45% complete for output_reverse_paired_30.fq.gz
Approx 50% complete for output_reverse_paired_30.fq.gz
Approx 55% complete for output_reverse_paired_30.fq.gz
Approx 60% complete for output_reverse_paired_30.fq.gz
Approx 65% complete for output_reverse_paired_30.fq.gz
Approx 70% complete for output_reverse_paired_30.fq.gz
Approx 75% complete for output_reverse_paired_30.fq.gz
Approx 80% complete for output_reverse_paired_30.fq.gz
Approx 85% complete for output_reverse_paired_30.fq.gz
Approx 90% complete for output_reverse_paired_30.fq.gz
Approx 95% complete for output_reverse_paired_30.fq.gz
Analysis complete for output_reverse_paired_30.fq.gz
```

```
$ bwa index sequence.fasta
[bwa_index] Pack FASTA... 0.02 sec
[bwa_index] Construct BWT for the packed sequence...
[bwa_index] 0.57 seconds elapse.
[bwa_index] Update BWT... 0.01 sec
[bwa_index] Pack forward-only FASTA... 0.01 sec
[bwa_index] Construct SA from BWT and Occ... 0.21 sec
[main] Version: 0.7.17-r1188
[main] CMD: bwa index sequence.fasta
[main] Real time: 1.234 sec; CPU: 0.816 sec
```

```
$ bwa mem sequence.fasta ~/Neisseria_meningitidis/NM_102018/84-Nm_S9/output_forward_paired_30.fq.gz ~/Neisseria_meningitidis/NM_102018/84-Nm_S9/output_reverse_paired_30.fq.gz > alignment_84-Nm_S9.sam
[M::bwa_idx_load_from_disk] read 0 ALT contigs
[M::process] read 43814 sequences (10000221 bp)...
[M::process] read 43434 sequences (10000120 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (3, 20073, 0, 3)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (261, 367, 476)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 906)
[M::mem_pestat] mean and std.dev: (373.92, 158.98)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1121)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 43814 reads in 3.265 CPU sec, 3.129 real sec
[M::process] read 42814 sequences (10000075 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (4, 19911, 0, 4)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (259, 364, 473)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 901)
[M::mem_pestat] mean and std.dev: (371.58, 159.35)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1115)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 43434 reads in 3.835 CPU sec, 3.690 real sec
[M::process] read 42912 sequences (10000481 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (5, 19616, 0, 4)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (259, 365, 476)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 910)
[M::mem_pestat] mean and std.dev: (372.75, 159.75)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1127)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 42814 reads in 3.774 CPU sec, 3.627 real sec
[M::process] read 42934 sequences (10000411 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (2, 19628, 1, 6)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (259, 365, 474)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 904)
[M::mem_pestat] mean and std.dev: (372.40, 159.12)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1119)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 42912 reads in 3.527 CPU sec, 3.343 real sec
[M::process] read 43360 sequences (10000255 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (8, 19671, 0, 8)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (259, 366, 474)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 904)
[M::mem_pestat] mean and std.dev: (373.10, 159.84)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1119)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 42934 reads in 3.336 CPU sec, 3.185 real sec
[M::process] read 43586 sequences (10000258 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (3, 19912, 1, 2)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (258, 364, 476)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 912)
[M::mem_pestat] mean and std.dev: (372.48, 160.09)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1130)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 43360 reads in 3.494 CPU sec, 3.331 real sec
[M::process] read 43696 sequences (10000258 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (5, 19984, 0, 5)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (257, 365, 474)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 908)
[M::mem_pestat] mean and std.dev: (372.62, 160.06)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1125)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 43586 reads in 3.765 CPU sec, 3.609 real sec
[M::process] read 43598 sequences (10000018 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (7, 19912, 0, 10)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (259, 367, 476)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 910)
[M::mem_pestat] mean and std.dev: (373.92, 159.33)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1127)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation RR...
[M::mem_pestat] (25, 50, 75) percentile: (182, 271, 349)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 683)
[M::mem_pestat] mean and std.dev: (223.38, 82.82)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 850)
[M::mem_pestat] skip orientation RR
[M::mem_process_seqs] Processed 43696 reads in 4.268 CPU sec, 4.054 real sec
[M::process] read 43882 sequences (10000483 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (9, 20015, 0, 7)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (260, 368, 475)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 905)
[M::mem_pestat] mean and std.dev: (373.85, 158.79)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1120)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 43598 reads in 4.558 CPU sec, 4.382 real sec
[M::process] read 46650 sequences (10000400 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (7, 20187, 0, 4)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (259, 367, 475)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 907)
[M::mem_pestat] mean and std.dev: (372.53, 158.89)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1123)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 43882 reads in 4.339 CPU sec, 4.162 real sec
[M::process] read 46394 sequences (10000325 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (3, 21395, 1, 7)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (261, 369, 479)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 915)
[M::mem_pestat] mean and std.dev: (376.40, 160.72)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1133)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 46650 reads in 4.434 CPU sec, 4.253 real sec
[M::process] read 44604 sequences (10000099 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (7, 21234, 0, 4)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (260, 365, 476)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 908)
[M::mem_pestat] mean and std.dev: (373.48, 160.45)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1124)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 46394 reads in 4.909 CPU sec, 4.748 real sec
[M::process] read 42910 sequences (10000512 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (9, 20389, 0, 4)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (259, 366, 479)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 919)
[M::mem_pestat] mean and std.dev: (374.78, 161.49)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1139)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 44604 reads in 5.082 CPU sec, 4.931 real sec
[M::process] read 42698 sequences (10000171 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (4, 19687, 0, 2)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (262, 367, 477)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 907)
[M::mem_pestat] mean and std.dev: (375.44, 159.12)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1122)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 42910 reads in 5.325 CPU sec, 5.180 real sec
[M::process] read 42688 sequences (10000335 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (5, 19602, 0, 5)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (261, 367, 477)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 909)
[M::mem_pestat] mean and std.dev: (374.91, 159.80)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1125)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 42698 reads in 5.503 CPU sec, 5.328 real sec
[M::process] read 42752 sequences (10000457 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (5, 19602, 0, 3)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (263, 367, 477)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 905)
[M::mem_pestat] mean and std.dev: (375.38, 158.66)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1119)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 42688 reads in 4.621 CPU sec, 4.463 real sec
[M::process] read 42752 sequences (10000487 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (6, 19631, 1, 5)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (263, 368, 479)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 911)
[M::mem_pestat] mean and std.dev: (376.48, 159.60)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1127)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 42752 reads in 4.110 CPU sec, 3.877 real sec
[M::process] read 10052 sequences (2383676 bp)...
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (3, 19651, 0, 6)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (263, 369, 480)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 914)
[M::mem_pestat] mean and std.dev: (378.31, 159.94)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1131)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 42752 reads in 3.746 CPU sec, 3.635 real sec
[M::mem_pestat] # candidate unique pairs for (FF, FR, RF, RR): (3, 4619, 0, 1)
[M::mem_pestat] skip orientation FF as there are not enough pairs
[M::mem_pestat] analyzing insert size distribution for orientation FR...
[M::mem_pestat] (25, 50, 75) percentile: (269, 376, 485)
[M::mem_pestat] low and high boundaries for computing mean and std.dev: (1, 917)
[M::mem_pestat] mean and std.dev: (382.59, 160.06)
[M::mem_pestat] low and high boundaries for proper pairs: (1, 1133)
[M::mem_pestat] skip orientation RF as there are not enough pairs
[M::mem_pestat] skip orientation RR as there are not enough pairs
[M::mem_process_seqs] Processed 10052 reads in 0.781 CPU sec, 0.741 real sec
[main] Version: 0.7.17-r1188
[main] CMD: bwa mem sequence.fasta /home/anton/Neisseria_meningitidis/NM_102018/84-Nm_S9/output_forward_paired_30.fq.gz /home/anton/Neisseria_meningitidis/NM_102018/84-Nm_S9/output_reverse_paired_30.fq.gz
[main] Real time: 74.233 sec; CPU: 76.817 sec
```

```
$ samtools view -S -b alignment_84-Nm_S9.sam > alignment_84-Nm_S9.bam
```

```
$ samtools flagstat alignment_84-Nm_S9.bam
796714 + 0 in total (QC-passed reads + QC-failed reads)
0 + 0 secondary
1184 + 0 supplementary
0 + 0 duplicates
796209 + 0 mapped (99.94% : N/A)
795530 + 0 paired in sequencing
397765 + 0 read1
397765 + 0 read2
793922 + 0 properly paired (99.80% : N/A)
794744 + 0 with itself and mate mapped
281 + 0 singletons (0.04% : N/A)
0 + 0 with mate mapped to a different chr
0 + 0 with mate mapped to a different chr (mapQ>=5)
```

```
$ samtools sort alignment_84-Nm_S9.bam -o alignment_84-Nm_S9_sorted.bam
```

```
$ samtools index alignment_84-Nm_S9_sorted.bam
```

```
$ samtools mpileup -f sequence.
sequence.fasta      sequence.fasta.bwt  sequence.fasta.sa
sequence.fasta.amb  sequence.fasta.fai  sequence.gff3
sequence.fasta.ann  sequence.fasta.pac  
```

```
$ samtools mpileup -f sequence.fasta alignment_84-Nm_S9_sorted.bam > 84-Nm_S9.mpileup
[mpileup] 1 samples in 1 input files
<mpileup> Set max per-file depth to 8000
```

```
$ java -jar VarScan.v2.4.0.jar  mpileup2snp ~/Neisseria_meningitidis/NM_102018/84-Nm_S9.mpileup --min-var-freq 0.95 --variants --output-vcf 1 > VarScan_84-Nm_S9.vcf
Only SNPs will be reported
Warning: No p-value threshold provided, so p-values will not be calculated
Min coverage:	8
Min reads2:	2
Min var freq:	0.95
Min avg qual:	15
P-value thresh:	0.01
Reading input from /home/anton/Neisseria_meningitidis/NM_102018/84-Nm_S9.mpileup
2167649 bases in pileup file
1016 variant positions (1002 SNP, 14 indel)
76 were failed by the strand-filter
928 variant positions reported (928 SNP, 0 indel)
```





