#GBP-PR (A Graph-Based Approach for Prioritizing Sets of Related Cancer Genes)
The following libraries and versions were used:
 - Python 3.7.7
 - pandas 1.0.5
 - numpy 1.18.5
 - networkx 2.4
 - matplotlib 3.2.2
 

# Usage
GBP-PR has 2 step for use:

#**Step 2**: Generating input: A input file must be filled with data and the weights for each Variant_Classification. 
- Mutation data on MAF file format
- Mutation score for each gene
-Gene interaction networks in edge lists

#**Step 2**: GBP Gene Proritization with different rating options are 
1. GBP-PR (PageRank with dynamic damping factor)
2. GBP-Keener
3. GBP-Colley 
4. GBP-Massey
5. 
A running example is set on the file python GBP-PR_Agorithm.py 
A set of output files is generated.
