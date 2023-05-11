GREP COMMAND

# 1. GREP -R 

## Grep -r is used to search for a pattern in all files within a directory. For example, if we have a large database with many directories, instead of going through each subdirectory separately, we can grep -r to run through the whole thing. 

INPUT : `$ grep -r .txt technical/biomed`

OUTPUT : `technical/biomed/1471-2105-2-1.txt:          Also attached are a users' manual (user.txt - see
technical/biomed/1471-2105-2-9.txt:            of files (e.g., seq or txt files) or from a
technical/biomed/1471-2105-2-9.txt:            fasta_groups.txt output file contains the group name
technical/biomed/1471-2105-2-9.txt:            format. The fasta_groups.txt file is particularly
technical/biomed/1471-2105-2-9.txt:            output 
file, group_seqs.txt, contains the group name
technical/biomed/1471-2105-2-9.txt:            output 
file, group_files.txt, contains the group name,       
technical/biomed/1471-2105-2-9.txt:            file, coverage.txt, shows how many sequences are in
technical/biomed/1471-2105-2-9.txt:            Good [ 
7 ] . Finally, the infile.txt file contains all       
technical/biomed/1471-2105-2-9.txt:          from the 
3' end and looking at the group_seqs.txt output       
technical/biomed/1471-2105-2-9.txt:          to the fasta_groups.txt file, which is ideal for Clustal       
technical/biomed/1471-2105-3-4.txt:          conversions of .chp (.txt) for each individual profile
technical/biomed/1471-2105-3-6.txt:          readme.txt documentation file are also included.
technical/biomed/gb-2001-2-7-research0025.txt:        
Pfam_Annotation.txt
technical/biomed/gb-2001-2-7-research0025.txt:        
Protein_Annotation.txt
technical/biomed/gb-2001-2-9-research0037.txt:        
  hyb2dis.txt in additional data files). More importantly,
technical/biomed/gb-2001-2-9-research0037.txt:        
hyb2dis.txt: patch file that converts White's hybridize
technical/biomed/gb-2001-2-9-research0037.txt:        
Training sets(GlycineMedicago.txt,Rhizobia.txt,       
technical/biomed/gb-2001-2-9-research0037.txt:        
Stramenopiles.txt, ZygoChytrid.txt): FASTA-formatted text
technical/biomed/gb-2001-2-9-research0037.txt:        
Test sets(PsojaeHA.txt, PsojaeMY.txt, PsojaeZO.txt,   
technical/biomed/gb-2001-2-9-research0037.txt:        
MtRHE.txt, DSIR.txt, MHAM.txt, KV0.txt, KV2.txt, KV3.txt):
technical/biomed/gb-2001-2-9-research0037.txt:        
hyb2dis.txt
technical/biomed/gb-2001-2-9-research0037.txt:        
hyb2dis.txt
technical/biomed/gb-2001-2-9-research0037.txt:        
GlycineMedicago.txt
technical/biomed/gb-2001-2-9-research0037.txt:        
Rhizobia.txt
technical/biomed/gb-2001-2-9-research0037.txt:        
Stramenopiles.txt
technical/biomed/gb-2001-2-9-research0037.txt:        
ZygoChytrid.txt
technical/biomed/gb-2001-2-9-research0037.txt:        
PsojaeHA.txt
technical/biomed/gb-2001-2-9-research0037.txt:        PsojaeMY.txt
technical/biomed/gb-2001-2-9-research0037.txt:        PsojaeZO.txt
technical/biomed/gb-2001-2-9-research0037.txt:        MtRHE.txt
technical/biomed/gb-2001-2-9-research0037.txt:        DSIR.txt
technical/biomed/gb-2001-2-9-research0037.txt:        KV0.txt
technical/biomed/gb-2001-2-9-research0037.txt:        KV2.txt
technical/biomed/gb-2001-2-9-research0037.txt:        KV3.txt
technical/biomed/gb-2002-3-12-research0071.txt:        'EtOH.txt', 'SwiSnfMin.txt'and 'SwiSnfRich.txt', and
technical/biomed/gb-2002-3-12-research0071.txt:        'Zinc.txt'.
technical/biomed/gb-2002-3-12-research0078.txt:          .txt extension.     
technical/biomed/gb-2002-3-6-software0001.txt:        as .txt files (tab-delimited text, refer to the user'stechnical/biomed/gb-2002-3-7-research0037.txt:        README.txt contains instructions for installation and
technical/biomed/gb-2003-4-5-r34.txt:            20,000), and repeat the process. The Readme.txt file`

INPUT: `$ grep -r Background technical/biomed`

OUTPUT: `technical/biomed/1468-6708-3-7.txt:        Background
technical/biomed/1471-2091-2-10.txt:        Background
technical/biomed/1471-2091-2-12.txt:        Background
technical/biomed/1471-2091-2-13.txt:        Background
technical/biomed/1471-2091-2-16.txt:        Background
technical/biomed/1471-2091-2-5.txt:        Background
technical/biomed/1471-2091-2-7.txt:        Background
technical/biomed/1471-2091-2-9.txt:        Background
technical/biomed/1471-2091-3-13.txt:        Background
technical/biomed/1471-2091-3-14.txt:        Background
technical/biomed/1471-2091-3-15.txt:        Background
technical/biomed/1471-2091-3-16.txt:        Background
technical/biomed/1471-2091-3-17.txt:        Background
technical/biomed/1471-2091-3-18.txt:        Background
technical/biomed/1471-2091-3-22.txt:        Background
technical/biomed/1471-2091-3-23.txt:        Background
technical/biomed/1471-2091-3-30.txt:        Background
technical/biomed/1471-2091-3-31.txt:        Background
technical/biomed/1471-2091-3-4.txt:        Background
technical/biomed/1471-2091-3-8.txt:        Background
technical/biomed/1471-2091-3-8.txt:          determined by scintillation counting. Background binding
technical/biomed/1471-2091-4-1.txt:        Background
technical/biomed/1471-2091-4-5.txt:        Background
technical/biomed/1471-2105-2-1.txt:        Background
technical/biomed/1471-2105-2-9.txt:        Background
technical/biomed/1471-2105-3-12.txt:        Background
technical/biomed/1471-2105-3-14.txt:        Background
technical/biomed/1471-2105-3-16.txt:        Background
technical/biomed/1471-2105-3-17.txt:        Background
technical/biomed/1471-2105-3-18.txt:        Background
technical/biomed/1471-2105-3-2.txt:        Background
technical/biomed/1471-2105-3-22.txt:        Background
technical/biomed/1471-2105-3-22.txt:          from the total element signal. 
Background subtracted
technical/biomed/1471-2105-3-23.txt:        Background
technical/biomed/1471-2105-3-23.txt:          Background for explanation of terms)
technical/biomed/1471-2105-3-26.txt:        Background
technical/biomed/1471-2105-3-28.txt:        Background
technical/biomed/1471-2105-3-3.txt:        Background
technical/biomed/1471-2105-3-3.txt:           for MM. Background intensity,  
technical/biomed/1471-2105-3-30.txt:        Background
technical/biomed/1471-2105-3-34.txt:        Background
technical/biomed/1471-2105-3-37.txt:        Background
technical/biomed/1471-2105-3-38.txt:        Background
technical/biomed/1471-2105-3-4.txt:        Background
technical/biomed/1471-2105-3-6.txt:        Background
technical/biomed/1471-2105-4-13.txt:        Background
technical/biomed/1471-2105-4-24.txt:        Background
technical/biomed/1471-2105-4-25.txt:        Background
technical/biomed/1471-2105-4-26.txt:        Background
technical/biomed/1471-2105-4-27.txt:        Background
technical/biomed/1471-2105-4-28.txt:        Background
technical/biomed/1471-2105-4-31.txt:        Background
technical/biomed/1471-2121-2-1.txt:        Background
technical/biomed/1471-2121-2-10.txt:        Background
technical/biomed/1471-2121-2-11.txt:        Background
technical/biomed/1471-2121-2-12.txt:        Background
technical/biomed/1471-2121-2-15.txt:        Background
technical/biomed/1471-2121-2-18.txt:        Background
technical/biomed/1471-2121-2-21.txt:        Background
technical/biomed/1471-2121-2-22.txt:        Background
technical/biomed/1471-2121-2-3.txt:        Background
technical/biomed/1471-2121-2-6.txt:        Background
technical/biomed/1471-2121-3-10.txt:        Background
technical/biomed/1471-2121-3-11.txt:        Background
technical/biomed/1471-2121-3-12.txt:        Background
technical/biomed/1471-2121-3-13.txt:        Background
technical/biomed/1471-2121-3-15.txt:        Background
technical/biomed/1471-2121-3-16.txt:        Background
technical/biomed/1471-2121-3-18.txt:        Background
technical/biomed/1471-2121-3-19.txt:        Background
technical/biomed/1471-2121-3-2.txt:        Background
technical/biomed/1471-2121-3-21.txt:        Background
technical/biomed/1471-2121-3-21.txt:          Background fluorescence was corrected by images of blank
technical/biomed/1471-2121-3-22.txt:        Background
technical/biomed/1471-2121-3-25.txt:        Background
technical/biomed/1471-2121-3-30.txt:        Background
technical/biomed/1471-2121-3-4.txt:        Background
technical/biomed/1471-2121-3-6.txt:        Background
technical/biomed/1471-2121-3-8.txt:        Background
technical/biomed/1471-2121-4-1.txt:        Background
technical/biomed/1471-2121-4-2.txt:        Background
technical/biomed/1471-2121-4-3.txt:        Background
technical/biomed/1471-2121-4-4.txt:        Background
technical/biomed/1471-2121-4-5.txt:        Background
technical/biomed/1471-2121-4-6.txt:        Background
technical/biomed/1471-213X-1-1.txt:        Background
technical/biomed/1471-213X-1-11.txt:        Background
technical/biomed/1471-213X-1-12.txt:        Background
technical/biomed/1471-213X-1-13.txt:        Background
technical/biomed/1471-213X-1-15.txt:        Background
technical/biomed/1471-213X-1-2.txt:        Background
technical/biomed/1471-213X-1-3.txt:        Background
technical/biomed/1471-213X-1-4.txt:        Background
technical/biomed/1471-213X-1-6.txt:        Background
technical/biomed/1471-213X-2-7.txt:        Background
technical/biomed/1471-213X-2-8.txt:        Background
technical/biomed/1471-213X-3-2.txt:        Background
technical/biomed/1471-213X-3-3.txt:        Background
technical/biomed/1471-213X-3-4.txt:        Background
technical/biomed/1471-213X-3-7.txt:        Background
technical/biomed/1471-2148-1-1.txt:        Background
technical/biomed/1471-2148-1-14.txt:        Background
technical/biomed/1471-2148-1-4.txt:        Background
technical/biomed/1471-2148-1-6.txt:        Background
technical/biomed/1471-2148-1-8.txt:        Background
technical/biomed/1471-2148-2-12.txt:        Background
technical/biomed/1471-2148-2-14.txt:        Background
technical/biomed/1471-2148-2-15.txt:        Background
technical/biomed/1471-2148-2-17.txt:        Background
technical/biomed/1471-2148-2-2.txt:        Background
technical/biomed/1471-2148-2-5.txt:        Background
technical/biomed/1471-2148-2-7.txt:        Background
technical/biomed/1471-2148-2-8.txt:        Background
technical/biomed/1471-2148-3-1.txt:        Background
technical/biomed/1471-2148-3-18.txt:        Background
technical/biomed/1471-2148-3-3.txt:        Background
technical/biomed/1471-2148-3-4.txt:        Background
technical/biomed/1471-2148-3-7.txt:        Background
technical/biomed/1471-2156-2-1.txt:        Background
technical/biomed/1471-2156-2-12.txt:        Background
technical/biomed/1471-2156-2-17.txt:        Background
technical/biomed/1471-2156-2-18.txt:        Background
technical/biomed/1471-2156-2-3.txt:        Background
technical/biomed/1471-2156-2-5.txt:        Background
technical/biomed/1471-2156-2-8.txt:        Background
technical/biomed/1471-2156-3-10.txt:        Background
technical/biomed/1471-2156-3-11.txt:        Background
technical/biomed/1471-2156-3-16.txt:        Background
technical/biomed/1471-2156-3-17.txt:        Background
technical/biomed/1471-2156-3-22.txt:        Background
technical/biomed/1471-2156-3-3.txt:        Background
technical/biomed/1471-2156-3-4.txt:        Background
technical/biomed/1471-2156-4-10.txt:        Background
technical/biomed/1471-2156-4-5.txt:        Background
technical/biomed/1471-2156-4-6.txt:        Background
technical/biomed/1471-2156-4-9.txt:        Background
technical/biomed/1471-2164-2-1.txt:        Background
technical/biomed/1471-2164-2-2.txt:        Background
technical/biomed/1471-2164-2-4.txt:        Background
technical/biomed/1471-2164-2-4.txt:        Background signal is sometimes related to the amount of
technical/biomed/1471-2164-2-6.txt:        Background
technical/biomed/1471-2164-2-7.txt:        Background
technical/biomed/1471-2164-2-8.txt:        Background
technical/biomed/1471-2164-2-9.txt:        Background
technical/biomed/1471-2164-3-1.txt:        Background
technical/biomed/1471-2164-3-10.txt:        Background
technical/biomed/1471-2164-3-13.txt:        Background
technical/biomed/1471-2164-3-15.txt:        Background
technical/biomed/1471-2164-3-16.txt:        Background
technical/biomed/1471-2164-3-16.txt:          Background-corrected intensity 
was computed by
technical/biomed/1471-2164-3-18.txt:        Background
technical/biomed/1471-2164-3-19.txt:        Background
technical/biomed/1471-2164-3-19.txt:          4.0 (Biodiscovery). Background 
subtracted fluorescence
technical/biomed/1471-2164-3-23.txt:        Background
technical/biomed/1471-2164-3-24.txt:        Background
technical/biomed/1471-2164-3-26.txt:        Background
technical/biomed/1471-2164-3-27.txt:        Background
technical/biomed/1471-2164-3-28.txt:        Background
technical/biomed/1471-2164-3-29.txt:        Background
technical/biomed/1471-2164-3-30.txt:        Background
technical/biomed/1471-2164-3-31.txt:        Background
technical/biomed/1471-2164-3-32.txt:        Background
technical/biomed/1471-2164-3-33.txt:        Background
technical/biomed/1471-2164-3-34.txt:        Background
technical/biomed/1471-2164-3-35.txt:        Background
technical/biomed/1471-2164-3-4.txt:        Background
technical/biomed/1471-2164-3-6.txt:        Background
technical/biomed/1471-2164-3-7.txt:        Background
technical/biomed/1471-2164-3-9.txt:        Background
technical/biomed/1471-2164-4-13.txt:        Background
technical/biomed/1471-2164-4-14.txt:        Background
technical/biomed/1471-2164-4-15.txt:        Background
technical/biomed/1471-2164-4-16.txt:        Background
technical/biomed/1471-2164-4-19.txt:        Background
technical/biomed/1471-2164-4-2.txt:        Background
technical/biomed/1471-2164-4-21.txt:        Background
technical/biomed/1471-2164-4-22.txt:        Background
technical/biomed/1471-2164-4-23.txt:        Background
technical/biomed/1471-2164-4-24.txt:        Background
technical/biomed/1471-2164-4-25.txt:        Background
technical/biomed/1471-2164-4-26.txt:        Background
technical/biomed/1471-2164-4-28.txt:        Background
technical/biomed/1471-2164-4-4.txt:        Background
technical/biomed/1471-2164-4-5.txt:        Background
technical/biomed/1471-2164-4-6.txt:        Background
technical/biomed/1471-2172-1-1.txt:        Background
technical/biomed/1471-2172-2-3.txt:        Background
technical/biomed/1471-2172-2-4.txt:        Background
technical/biomed/1471-2172-2-9.txt:        Background
technical/biomed/1471-2172-3-1.txt:        Background
technical/biomed/1471-2172-3-10.txt:        Background
technical/biomed/1471-2172-3-12.txt:        Background
technical/biomed/1471-2172-3-16.txt:        Background
technical/biomed/1471-2172-3-2.txt:        Background
technical/biomed/1471-2172-3-4.txt:        Background
technical/biomed/1471-2172-3-9.txt:        Background
technical/biomed/1471-2172-4-1.txt:        Background
technical/biomed/1471-2172-4-1.txt:          dot plot. Background responses in the presence of 5A6
technical/biomed/1471-2172-4-2.txt:        Background
technical/biomed/1471-2180-1-12.txt:        Background
technical/biomed/1471-2180-1-26.txt:        Background
technical/biomed/1471-2180-1-28.txt:        Background
technical/biomed/1471-2180-1-29.txt:        Background
technical/biomed/1471-2180-1-31.txt:        Background
technical/biomed/1471-2180-1-33.txt:        Background
technical/biomed/1471-2180-1-34.txt:        Background
technical/biomed/1471-2180-1-7.txt:        Background
technical/biomed/1471-2180-1-8.txt:        Background
technical/biomed/1471-2180-2-1.txt:        Background
technical/biomed/1471-2180-2-13.txt:        Background
technical/biomed/1471-2180-2-16.txt:        Background
technical/biomed/1471-2180-2-2.txt:        Background
technical/biomed/1471-2180-2-20.txt:        Background
technical/biomed/1471-2180-2-22.txt:        Background
technical/biomed/1471-2180-2-26.txt:        Background
technical/biomed/1471-2180-2-29.txt:        Background
technical/biomed/1471-2180-2-32.txt:        Background
technical/biomed/1471-2180-2-35.txt:        Background
technical/biomed/1471-2180-2-38.txt:        Background
technical/biomed/1471-2180-2-7.txt:        Background
technical/biomed/1471-2180-3-10.txt:        Background
technical/biomed/1471-2180-3-11.txt:        Background
technical/biomed/1471-2180-3-13.txt:        Background
technical/biomed/1471-2180-3-15.txt:        Background
technical/biomed/1471-2180-3-4.txt:        Background
technical/biomed/1471-2180-3-5.txt:        Background
technical/biomed/1471-2180-3-9.txt:        Background
technical/biomed/1471-2199-2-1.txt:        Background
technical/biomed/1471-2199-2-12.txt:        Background
technical/biomed/1471-2199-2-3.txt:        Background
technical/biomed/1471-2199-2-4.txt:        Background
technical/biomed/1471-2199-3-10.txt:        Background
technical/biomed/1471-2199-3-11.txt:        Background
technical/biomed/1471-2199-3-12.txt:        Background
technical/biomed/1471-2199-3-17.txt:        Background
technical/biomed/1471-2199-3-3.txt:        Background
technical/biomed/1471-2199-3-7.txt:        Background
technical/biomed/1471-2199-4-4.txt:        Background
technical/biomed/1471-2199-4-5.txt:        Background
technical/biomed/1471-2202-1-1.txt:        Background
technical/biomed/1471-2202-2-1.txt:        Background
technical/biomed/1471-2202-2-10.txt:        Background
technical/biomed/1471-2202-2-12.txt:        Background
technical/biomed/1471-2202-2-14.txt:        Background
technical/biomed/1471-2202-2-15.txt:        Background
technical/biomed/1471-2202-2-16.txt:        Background
technical/biomed/1471-2202-2-17.txt:        Background
technical/biomed/1471-2202-2-18.txt:        Background
technical/biomed/1471-2202-2-19.txt:        Background
technical/biomed/1471-2202-2-2.txt:        Background
technical/biomed/1471-2202-2-20.txt:        Background
technical/biomed/1471-2202-2-5.txt:        Background
technical/biomed/1471-2202-2-6.txt:        Background
technical/biomed/1471-2202-2-7.txt:        Background
technical/biomed/1471-2202-2-8.txt:        Background
technical/biomed/1471-2202-2-9.txt:        Background
technical/biomed/1471-2202-3-1.txt:        Background
technical/biomed/1471-2202-3-10.txt:        Background
technical/biomed/1471-2202-3-11.txt:        Background
technical/biomed/1471-2202-3-14.txt:        Background
technical/biomed/1471-2202-3-16.txt:        Background
technical/biomed/1471-2202-3-17.txt:        Background
technical/biomed/1471-2202-3-19.txt:        Background
technical/biomed/1471-2202-3-20.txt:        Background
technical/biomed/1471-2202-3-3.txt:        Background
technical/biomed/1471-2202-3-4.txt:        Background
technical/biomed/1471-2202-3-5.txt:        Background
technical/biomed/1471-2202-3-7.txt:        Background
technical/biomed/1471-2202-3-8.txt:        Background
technical/biomed/1471-2202-4-10.txt:        Background
technical/biomed/1471-2202-4-11.txt:        Background
technical/biomed/1471-2202-4-12.txt:        Background
technical/biomed/1471-2202-4-16.txt:        Background
technical/biomed/1471-2202-4-17.txt:        Background
technical/biomed/1471-2202-4-2.txt:        Background
technical/biomed/1471-2202-4-3.txt:        Background
technical/biomed/1471-2202-4-5.txt:        Background
technical/biomed/1471-2202-4-6.txt:        Background
technical/biomed/1471-2210-1-10.txt:        Background
technical/biomed/1471-2210-1-2.txt:        Background
technical/biomed/1471-2210-1-3.txt:        Background
technical/biomed/1471-2210-1-4.txt:        Background
technical/biomed/1471-2210-1-7.txt:        Background
technical/biomed/1471-2210-1-8.txt:        Background
technical/biomed/1471-2210-2-14.txt:        Background
technical/biomed/1471-2210-2-4.txt:        Background
technical/biomed/1471-2210-2-4.txt:          NADH formed /minute. Background 
activity was determined
technical/biomed/1471-2210-2-5.txt:        Background
technical/biomed/1471-2210-2-6.txt:        Background
technical/biomed/1471-2210-2-8.txt:        Background
technical/biomed/1471-2210-2-9.txt:        Background
technical/biomed/1471-2210-3-1.txt:        Background
technical/biomed/1471-2210-3-3.txt:        Background
technical/biomed/1471-2229-1-2.txt:        Background
technical/biomed/1471-2229-1-3.txt:        Background
technical/biomed/1471-2229-2-11.txt:        Background
technical/biomed/1471-2229-2-3.txt:        Background
technical/biomed/1471-2229-2-4.txt:        Background
technical/biomed/1471-2229-2-8.txt:        Background
technical/biomed/1471-2229-2-9.txt:        Background
technical/biomed/1471-2229-3-3.txt:        Background
technical/biomed/1471-2253-1-1.txt:        Background
technical/biomed/1471-2253-2-4.txt:        Background
technical/biomed/1471-2253-2-5.txt:        Background
technical/biomed/1471-2261-1-6.txt:        Background
technical/biomed/1471-2261-2-11.txt:        Background
technical/biomed/1471-2261-3-4.txt:        Background
technical/biomed/1471-2261-3-5.txt:        Background
technical/biomed/1471-2288-1-9.txt:        Background
technical/biomed/1471-2288-2-10.txt:        Background
technical/biomed/1471-2288-2-11.txt:        Background
technical/biomed/1471-2288-2-4.txt:        Background
technical/biomed/1471-2288-3-4.txt:        Background
technical/biomed/1471-2288-3-8.txt:        Background
technical/biomed/1471-2288-3-9.txt:        Background
technical/biomed/1471-2296-3-18.txt:        Background
technical/biomed/1471-2296-3-19.txt:        Background
technical/biomed/1471-2296-3-3.txt:        Background
technical/biomed/1471-230X-1-5.txt:        Background & Aims
technical/biomed/1471-230X-1-6.txt:        Background
technical/biomed/1471-230X-1-8.txt:        Background
technical/biomed/1471-230X-2-17.txt:        Background
technical/biomed/1471-230X-2-21.txt:        Background
technical/biomed/1471-230X-2-23.txt:        Background
technical/biomed/1471-230X-3-3.txt:        Background
technical/biomed/1471-230X-3-5.txt:        Background
technical/biomed/1471-2318-3-2.txt:        Background
technical/biomed/1471-2326-2-4.txt:        Background
technical/biomed/1471-2334-1-10.txt:        Background
technical/biomed/1471-2334-1-13.txt:        Background
technical/biomed/1471-2334-1-17.txt:        Background
technical/biomed/1471-2334-1-21.txt:        Background
technical/biomed/1471-2334-1-24.txt:        Background
technical/biomed/1471-2334-1-9.txt:        Background
technical/biomed/1471-2334-2-1.txt:        Background
technical/biomed/1471-2334-2-24.txt:        Background
technical/biomed/1471-2334-2-26.txt:        Background
technical/biomed/1471-2334-2-27.txt:        Background
technical/biomed/1471-2334-2-29.txt:        Background
technical/biomed/1471-2334-2-5.txt:        Background
technical/biomed/1471-2334-2-6.txt:        Background
technical/biomed/1471-2334-2-7.txt:        Background
technical/biomed/1471-2334-3-10.txt:        Background
technical/biomed/1471-2334-3-11.txt:        Background
technical/biomed/1471-2334-3-12.txt:        Background
technical/biomed/1471-2334-3-13.txt:        Background
technical/biomed/1471-2334-3-15.txt:        Background
technical/biomed/1471-2350-2-11.txt:        Background
technical/biomed/1471-2350-2-12.txt:        Background
technical/biomed/1471-2350-2-8.txt:        Background
technical/biomed/1471-2350-3-1.txt:        Background
technical/biomed/1471-2350-3-12.txt:        Background
technical/biomed/1471-2350-3-7.txt:        Background
technical/biomed/1471-2350-3-9.txt:        Background
technical/biomed/1471-2350-4-2.txt:        Background
technical/biomed/1471-2350-4-3.txt:        Background
technical/biomed/1471-2350-4-4.txt:        Background
technical/biomed/1471-2350-4-6.txt:        Background
technical/biomed/1471-2369-3-1.txt:        Background
technical/biomed/1471-2369-3-10.txt:        Background
technical/biomed/1471-2369-3-6.txt:        Background
technical/biomed/1471-2369-3-9.txt:        Background
technical/biomed/1471-2369-4-1.txt:        Background
technical/biomed/1471-2369-4-5.txt:        Background
technical/biomed/1471-2377-2-4.txt:        Background
technical/biomed/1471-2377-2-6.txt:        Background
technical/biomed/1471-2377-3-4.txt:        Background
technical/biomed/1471-2407-1-15.txt:        Background
technical/biomed/1471-2407-1-19.txt:        Background
technical/biomed/1471-2407-2-11.txt:        Background
technical/biomed/1471-2407-2-12.txt:        Background
technical/biomed/1471-2407-2-15.txt:        Background
technical/biomed/1471-2407-2-16.txt:        Background
technical/biomed/1471-2407-2-17.txt:        Background
technical/biomed/1471-2407-2-18.txt:        Background
technical/biomed/1471-2407-2-19.txt:        Background
technical/biomed/1471-2407-2-22.txt:        Background
technical/biomed/1471-2407-2-23.txt:        Background
technical/biomed/1471-2407-2-3.txt:        Background
technical/biomed/1471-2407-2-31.txt:        Background
technical/biomed/1471-2407-2-33.txt:        Background
technical/biomed/1471-2407-2-9.txt:        Background
technical/biomed/1471-2407-3-14.txt:        Background
technical/biomed/1471-2407-3-15.txt:        Background
technical/biomed/1471-2407-3-16.txt:        Background
technical/biomed/1471-2407-3-18.txt:        Background
technical/biomed/1471-2407-3-3.txt:        Background
technical/biomed/1471-2407-3-4.txt:        Background
technical/biomed/1471-2407-3-5.txt:        Background
technical/biomed/1471-2415-3-1.txt:        Background
technical/biomed/1471-2415-3-3.txt:        Background
technical/biomed/1471-2415-3-4.txt:        Background
technical/biomed/1471-2415-3-5.txt:        Background
technical/biomed/1471-2431-2-1.txt:        Background
technical/biomed/1471-2431-2-11.txt:        Background
technical/biomed/1471-2431-2-12.txt:        Background
technical/biomed/1471-2431-2-4.txt:        Background
technical/biomed/1471-2431-3-3.txt:        Background
technical/biomed/1471-2431-3-4.txt:        Background
technical/biomed/1471-2431-3-4.txt:          Background data
technical/biomed/1471-2431-3-5.txt:        Background
technical/biomed/1471-2431-3-6.txt:        Background
technical/biomed/1471-244X-2-9.txt:        Background
technical/biomed/1471-244X-3-5.txt:        Background
technical/biomed/1471-2458-2-11.txt:        Background
technical/biomed/1471-2458-2-16.txt:        Background
technical/biomed/1471-2458-2-18.txt:        Background
technical/biomed/1471-2458-2-21.txt:        Background
technical/biomed/1471-2458-2-25.txt:        Background
technical/biomed/1471-2458-2-3.txt:        Background
technical/biomed/1471-2458-2-6.txt:        Background
technical/biomed/1471-2458-3-11.txt:        Background
technical/biomed/1471-2458-3-2.txt:        Background
technical/biomed/1471-2458-3-20.txt:        Background
technical/biomed/1471-2458-3-5.txt:        Background
technical/biomed/1471-2458-3-9.txt:        Background
technical/biomed/1471-2466-1-1.txt:        Background
technical/biomed/1471-2466-2-3.txt:        Background
technical/biomed/1471-2466-2-4.txt:        Background
technical/biomed/1471-2466-3-1.txt:        Background
technical/biomed/1471-2474-2-1.txt:        Background
technical/biomed/1471-2474-2-2.txt:        Background
technical/biomed/1471-2474-3-23.txt:        Background
technical/biomed/1471-2474-3-3.txt:        Background
technical/biomed/1471-2474-4-4.txt:        Background
technical/biomed/1471-2474-4-4.txt:          Background
technical/biomed/1471-2474-4-8.txt:        Background
technical/biomed/1471-2490-3-2.txt:        Background
technical/biomed/1471-5945-2-13.txt:        Background
technical/biomed/1471-5945-3-3.txt:        Background
technical/biomed/1472-6750-1-11.txt:        Background
technical/biomed/1472-6750-1-12.txt:        Background
technical/biomed/1472-6750-1-6.txt:        Background
technical/biomed/1472-6750-1-8.txt:        Background
technical/biomed/1472-6750-2-10.txt:        Background
technical/biomed/1472-6750-2-13.txt:        Background
technical/biomed/1472-6750-2-13.txt:          study. Background breaks at any site in the region
technical/biomed/1472-6750-2-14.txt:        Background
technical/biomed/1472-6750-2-2.txt:        Background
technical/biomed/1472-6750-2-21.txt:        Background
technical/biomed/1472-6750-2-21.txt:          determined. Background counts were subtracted from these
technical/biomed/1472-6750-3-11.txt:        Background
technical/biomed/1472-6750-3-4.txt:        Background
technical/biomed/1472-6750-3-6.txt:        Background
technical/biomed/1472-6769-1-1.txt:        Background
technical/biomed/1472-6769-1-1.txt:          Background, as determined by measuring the intensity and
technical/biomed/1472-6769-1-2.txt:        Background
technical/biomed/1472-6769-1-3.txt:        Background
technical/biomed/1472-6769-1-4.txt:        Background
technical/biomed/1472-6785-1-3.txt:        Background
technical/biomed/1472-6785-1-5.txt:        Background
technical/biomed/1472-6785-2-6.txt:        Background
technical/biomed/1472-6785-2-7.txt:        Background
technical/biomed/1472-6793-1-11.txt:        Background
technical/biomed/1472-6793-1-12.txt:        Background
technical/biomed/1472-6793-1-15.txt:        Background
technical/biomed/1472-6793-1-2.txt:        Background
technical/biomed/1472-6793-1-6.txt:        Background
technical/biomed/1472-6793-1-8.txt:        Background
technical/biomed/1472-6793-2-1.txt:        Background
technical/biomed/1472-6793-2-11.txt:        Background
technical/biomed/1472-6793-2-16.txt:        Background
technical/biomed/1472-6793-2-17.txt:        Background
technical/biomed/1472-6793-2-18.txt:        Background
technical/biomed/1472-6793-2-19.txt:        Background
technical/biomed/1472-6793-2-2.txt:        Background
technical/biomed/1472-6793-2-4.txt:        Background
technical/biomed/1472-6793-2-5.txt:        Background
technical/biomed/1472-6793-2-8.txt:        Background
technical/biomed/1472-6793-3-3.txt:        Background
technical/biomed/1472-6793-3-4.txt:        Background
technical/biomed/1472-6793-3-5.txt:        Background
technical/biomed/1472-6793-3-6.txt:        Background
technical/biomed/1472-6807-1-1.txt:        Background
technical/biomed/1472-6807-2-1.txt:        Background
technical/biomed/1472-6807-2-2.txt:        Background
technical/biomed/1472-6807-2-3.txt:        Background
technical/biomed/1472-6807-2-4.txt:        Background
technical/biomed/1472-6807-2-5.txt:        Background
technical/biomed/1472-6807-2-9.txt:        Background
technical/biomed/1472-6807-3-1.txt:        Background
technical/biomed/1472-6807-3-2.txt:        Background
technical/biomed/1472-6815-2-3.txt:        Background
technical/biomed/1472-6823-2-2.txt:        Background
technical/biomed/1472-6823-3-1.txt:        Background
technical/biomed/1472-6831-2-2.txt:        Background
technical/biomed/1472-6831-3-1.txt:        Background
technical/biomed/1472-684X-1-5.txt:        Background
technical/biomed/1472-684X-2-1.txt:        Background
technical/biomed/1472-684X-2-2.txt:        Background
technical/biomed/1472-6874-2-13.txt:        Background
technical/biomed/1472-6874-2-8.txt:        Background
technical/biomed/1472-6874-3-2.txt:        Background
technical/biomed/1472-6882-1-10.txt:        Background
technical/biomed/1472-6882-1-12.txt:        Background
technical/biomed/1472-6882-1-7.txt:        Background
technical/biomed/1472-6882-2-10.txt:        Background
technical/biomed/1472-6882-3-1.txt:        Background
technical/biomed/1472-6882-3-3.txt:        Background
technical/biomed/1472-6890-1-4.txt:        Background
technical/biomed/1472-6890-3-2.txt:        Background
technical/biomed/1472-6890-3-2.txt:            significantly reduced at pH < 
7.0. Background was
technical/biomed/1472-6890-3-2.txt:            Background-free results were obtained for all
technical/biomed/1472-6890-3-2.txt:          important factor for a clean result. Background tended to
technical/biomed/1472-6890-3-2.txt:            GenPoint kit. Background was found to be present even
technical/biomed/1472-6890-3-2.txt:        biotinylated-tyramide were utilized. Background may also be
technical/biomed/1472-6904-1-2.txt:        Background
technical/biomed/1472-6904-2-4.txt:        Background
technical/biomed/1472-6904-2-5.txt:        Background
technical/biomed/1472-6904-2-7.txt:        Background
technical/biomed/1472-6904-3-1.txt:        Background
technical/biomed/1472-6920-1-3.txt:        Background
technical/biomed/1472-6920-2-1.txt:        Background
technical/biomed/1472-6920-2-3.txt:        Background
technical/biomed/1472-6947-1-2.txt:        Background
technical/biomed/1472-6947-1-5.txt:        Background
technical/biomed/1472-6947-1-6.txt:        Background
technical/biomed/1472-6947-2-4.txt:        Background
technical/biomed/1472-6947-2-7.txt:        Background
technical/biomed/1472-6947-3-5.txt:        Background
technical/biomed/1472-6947-3-8.txt:        Background
technical/biomed/1472-6955-2-1.txt:        Background
technical/biomed/1472-6963-1-11.txt:        Background
technical/biomed/1472-6963-1-8.txt:        Background
technical/biomed/1472-6963-3-1.txt:        Background
technical/biomed/1472-6963-3-11.txt:        Background
technical/biomed/1472-6963-3-12.txt:        Background
technical/biomed/1472-6963-3-13.txt:        Background
technical/biomed/1472-6963-3-14.txt:        Background
technical/biomed/1472-6963-3-14.txt:          In the Background section, we mentioned a number of
technical/biomed/1472-6963-3-6.txt:        Background
technical/biomed/1472-6963-3-7.txt:        Background
technical/biomed/1475-2867-2-10.txt:        Background
technical/biomed/1475-2867-2-15.txt:        Background
technical/biomed/1475-2867-2-7.txt:        Background
technical/biomed/1475-2867-3-12.txt:        Background
technical/biomed/1475-2867-3-2.txt:        Background
technical/biomed/1475-2867-3-3.txt:        Background
technical/biomed/1475-2867-3-4.txt:        Background
technical/biomed/1475-2875-1-14.txt:        Background
technical/biomed/1475-2875-1-5.txt:        Background
technical/biomed/1475-2875-2-14.txt:        Background
technical/biomed/1475-2875-2-4.txt:        Background
technical/biomed/1475-2883-2-11.txt:        Background
technical/biomed/1475-2891-1-2.txt:        Background
technical/biomed/1475-2891-2-1.txt:        Background
technical/biomed/1475-4924-1-10.txt:        Background
technical/biomed/1475-4924-1-5.txt:        Background
technical/biomed/1475-925X-2-10.txt:        Background
technical/biomed/1475-925X-2-11.txt:        Background
technical/biomed/1475-925X-2-12.txt:        Background
technical/biomed/1475-925X-2-3.txt:        Background
technical/biomed/1475-925X-2-6.txt:        Background
technical/biomed/1475-9268-1-1.txt:        Background
technical/biomed/1475-9268-1-2.txt:        Background
technical/biomed/1475-9276-1-3.txt:        Background
technical/biomed/1476-069X-1-3.txt:        Background
technical/biomed/1476-069X-2-2.txt:        Background
technical/biomed/1476-069X-2-4.txt:        Background
technical/biomed/1476-069X-2-7.txt:        Background
technical/biomed/1476-069X-2-9.txt:        Background
technical/biomed/1476-069X-2-9.txt:            Background
technical/biomed/1476-069X-2-9.txt:            Background
technical/biomed/1476-069X-2-9.txt:            Background
technical/biomed/1476-069X-2-9.txt:            Background
technical/biomed/1476-0711-2-3.txt:        Background
technical/biomed/1476-0711-2-7.txt:        Background
technical/biomed/1476-072X-2-3.txt:        Background
technical/biomed/1476-072X-2-4.txt:        Background
technical/biomed/1476-4598-1-3.txt:        Background
technical/biomed/1476-4598-1-5.txt:        Background
technical/biomed/1476-4598-1-6.txt:        Background
technical/biomed/1476-4598-1-8.txt:        Background
technical/biomed/1476-4598-2-1.txt:        Background
technical/biomed/1476-4598-2-2.txt:        Background
technical/biomed/1476-4598-2-20.txt:        Background
technical/biomed/1476-4598-2-22.txt:        Background
technical/biomed/1476-4598-2-24.txt:        Background
technical/biomed/1476-4598-2-25.txt:        Background
technical/biomed/1476-4598-2-28.txt:        Background
technical/biomed/1476-4598-2-3.txt:        Background
technical/biomed/1476-511X-1-2.txt:        Background
technical/biomed/1476-511X-2-3.txt:        Background
technical/biomed/1476-5918-1-2.txt:        Background
technical/biomed/1476-9433-1-2.txt:        Background
technical/biomed/1476-9433-1-3.txt:        Background
technical/biomed/1477-5956-1-1.txt:        Background
technical/biomed/1477-7525-1-10.txt:        Background
technical/biomed/1477-7525-1-12.txt:        Background
technical/biomed/1477-7827-1-13.txt:        Background
technical/biomed/1477-7827-1-17.txt:        Background
technical/biomed/1477-7827-1-21.txt:        Background
technical/biomed/1477-7827-1-23.txt:        Background
technical/biomed/1477-7827-1-27.txt:        Background
technical/biomed/1477-7827-1-31.txt:        Background
technical/biomed/1477-7827-1-36.txt:        Background
technical/biomed/1477-7827-1-43.txt:        Background
technical/biomed/1477-7827-1-46.txt:        Background
technical/biomed/1477-7827-1-48.txt:        Background
technical/biomed/1477-7827-1-6.txt:        Background
technical/biomed/1477-7827-1-9.txt:        Background
technical/biomed/1478-1336-1-2.txt:        Background
technical/biomed/1478-1336-1-4.txt:        Background
technical/biomed/1478-7954-1-3.txt:        Background
technical/biomed/cc303.txt:        Background
technical/biomed/gb-2000-1-1-research002.txt:        Background
technical/biomed/gb-2000-1-2-research0003.txt:        Background
technical/biomed/gb-2001-2-10-research0041.txt:        Background
technical/biomed/gb-2001-2-10-research0042.txt:        Background
technical/biomed/gb-2001-2-11-research0045.txt:        Background
technical/biomed/gb-2001-2-11-research0046.txt:        Background
technical/biomed/gb-2001-2-12-research0051.txt:        Background
technical/biomed/gb-2001-2-12-research0053.txt:        Background
technical/biomed/gb-2001-2-12-research0054.txt:        Background
technical/biomed/gb-2001-2-12-research0055.txt:        Background
technical/biomed/gb-2001-2-12-research0055.txt:          Background
technical/biomed/gb-2001-2-2-research0004.txt:        Background
technical/biomed/gb-2001-2-2-research0004.txt:          Background effects and detection limits
technical/biomed/gb-2001-2-3-research0007.txt:        Background
technical/biomed/gb-2001-2-3-research0008.txt:        Background
technical/biomed/gb-2001-2-4-research0010.txt:        Background
technical/biomed/gb-2001-2-4-research0011.txt:        Background
technical/biomed/gb-2001-2-4-research0012.txt:        Background
technical/biomed/gb-2001-2-4-research0014.txt:        Background
technical/biomed/gb-2001-2-6-research0018.txt:        Background
technical/biomed/gb-2001-2-6-research0020.txt:        Background
technical/biomed/gb-2001-2-6-research0021.txt:        Background
technical/biomed/gb-2001-2-7-research0024.txt:        Background
technical/biomed/gb-2001-2-7-research0025.txt:        Background
technical/biomed/gb-2001-2-8-research0027.txt:        Background
technical/biomed/gb-2001-2-8-research0030.txt:        Background
technical/biomed/gb-2001-2-8-research0031.txt:        Background
technical/biomed/gb-2001-2-8-research0032.txt:        Background
technical/biomed/gb-2001-2-9-research0035.txt:        Background
technical/biomed/gb-2001-2-9-research0037.txt:        Background
technical/biomed/gb-2001-3-1-research0001.txt:        Background
technical/biomed/gb-2001-3-1-research0004.txt:        Background
technical/biomed/gb-2001-3-1-research0005.txt:        Background
technical/biomed/gb-2002-3-10-research0052.txt:        Background
technical/biomed/gb-2002-3-10-research0053.txt:        Background
technical/biomed/gb-2002-3-10-research0054.txt:        Background
technical/biomed/gb-2002-3-10-research0055.txt:        Background
technical/biomed/gb-2002-3-10-research0056.txt:        Background
technical/biomed/gb-2002-3-11-research0059.txt:        Background
technical/biomed/gb-2002-3-11-research0060.txt:        Background
technical/biomed/gb-2002-3-11-research0061.txt:        Background
technical/biomed/gb-2002-3-11-research0062.txt:        Background
technical/biomed/gb-2002-3-11-research0062.txt:          cell is used to calculate local background. Background
technical/biomed/gb-2002-3-11-research0065.txt:        Background
technical/biomed/gb-2002-3-12-research0071.txt:        Background
technical/biomed/gb-2002-3-12-research0072.txt:        Background
technical/biomed/gb-2002-3-12-research0075.txt:        Background
technical/biomed/gb-2002-3-12-research0077.txt:        Background
technical/biomed/gb-2002-3-12-research0078.txt:        Background
technical/biomed/gb-2002-3-12-research0079.txt:        Background
technical/biomed/gb-2002-3-12-research0080.txt:        Background
technical/biomed/gb-2002-3-12-research0083.txt:        Background
technical/biomed/gb-2002-3-12-research0085.txt:        Background
technical/biomed/gb-2002-3-12-research0086.txt:        Background
technical/biomed/gb-2002-3-12-research0087.txt:        Background
technical/biomed/gb-2002-3-12-research0088.txt:        Background
technical/biomed/gb-2002-3-2-research0008.txt:        Background
technical/biomed/gb-2002-3-2-research0009.txt:        Background
technical/biomed/gb-2002-3-3-research0011.txt:        Background
technical/biomed/gb-2002-3-3-research0012.txt:        Background
technical/biomed/gb-2002-3-4-research0018.txt:        Background
technical/biomed/gb-2002-3-4-research0019.txt:        Background
technical/biomed/gb-2002-3-5-research0020.txt:        Background
technical/biomed/gb-2002-3-5-research0021.txt:        Background
technical/biomed/gb-2002-3-5-research0022.txt:        Background
technical/biomed/gb-2002-3-5-research0023.txt:        Background
technical/biomed/gb-2002-3-5-research0024.txt:        Background
technical/biomed/gb-2002-3-5-research0025.txt:        Background
technical/biomed/gb-2002-3-6-research0029.txt:        Background
technical/biomed/gb-2002-3-6-software0001.txt:        sample, array-to-array 
variability). Background-subtracted
technical/biomed/gb-2002-3-7-research0032.txt:        Background
technical/biomed/gb-2002-3-7-research0035.txt:        Background
technical/biomed/gb-2002-3-7-research0036.txt:        Background
technical/biomed/gb-2002-3-7-research0036.txt:          statistics) described in the Background section. The
technical/biomed/gb-2002-3-7-research0036.txt:            the Euclidean distance metric (see Background).
technical/biomed/gb-2002-3-7-research0036.txt:            (see Background).  
technical/biomed/gb-2002-3-7-research0036.txt:            All the external indices described in Background
technical/biomed/gb-2002-3-7-research0036.txt:          methods presented in 
Background using data simulated from
technical/biomed/gb-2002-3-7-research0036.txt:          The six methods described in Background and Clest were
technical/biomed/gb-2002-3-7-research0036.txt:          methods described in 
the Background and Results sections
technical/biomed/gb-2002-3-7-research0037.txt:        Background
technical/biomed/gb-2002-3-8-research0038.txt:        Background
technical/biomed/gb-2002-3-8-research0039.txt:        Background
technical/biomed/gb-2002-3-8-research0040.txt:        Background
technical/biomed/gb-2002-3-9-research0043.txt:        Background
technical/biomed/gb-2002-3-9-research0044.txt:        Background
technical/biomed/gb-2002-3-9-research0045.txt:        Background
technical/biomed/gb-2002-3-9-research0046.txt:        Background
technical/biomed/gb-2002-3-9-research0046.txt:          Background, Channel 2 Foreground and Background, and the
technical/biomed/gb-2002-3-9-research0048.txt:        Background
technical/biomed/gb-2002-3-9-research0049.txt:        Background
technical/biomed/gb-2002-3-9-research0051.txt:        Background
technical/biomed/gb-2002-4-1-r1.txt:        Background
technical/biomed/gb-2002-4-1-r2.txt:        Background
technical/biomed/gb-2003-4-1-r5.txt:        Background
technical/biomed/gb-2003-4-1-r7.txt:        Background
technical/biomed/gb-2003-4-2-r11.txt:        Background
technical/biomed/gb-2003-4-2-r14.txt:        Background
technical/biomed/gb-2003-4-2-r8.txt:        Background
technical/biomed/gb-2003-4-2-r9.txt:        Background
technical/biomed/gb-2003-4-3-r17.txt:        Background
technical/biomed/gb-2003-4-3-r18.txt:        Background
technical/biomed/gb-2003-4-3-r20.txt:        Background
technical/biomed/gb-2003-4-4-r24.txt:        Background
technical/biomed/gb-2003-4-4-r26.txt:        Background
technical/biomed/gb-2003-4-5-r30.txt:        Background
technical/biomed/gb-2003-4-5-r32.txt:        Background
technical/biomed/gb-2003-4-5-r34.txt:        Background
technical/biomed/gb-2003-4-6-r37.txt:        Background
technical/biomed/gb-2003-4-6-r39.txt:        Background
technical/biomed/gb-2003-4-6-r41.txt:        Background
technical/biomed/gb-2003-4-7-r42.txt:        Background
technical/biomed/gb-2003-4-7-r43.txt:        Background
technical/biomed/gb-2003-4-7-r46.txt:        Background
technical/biomed/gb-2003-4-8-r50.txt:        Background
technical/biomed/gb-2003-4-9-r57.txt:        Background
technical/biomed/gb-2003-4-9-r58.txt:        Background
`

# 2. AWK 

## awk is very similar to grep but used for more complex text extraction

INPUT : `$ awk /Background/ technical/biomed/1468-6708-3-7.txt`

OUTPUT : `Background`

INPUT : `$ grep ALLHAT technical/biomed/*.txt`

OUTPUT : `technical/biomed/1468-6708-3-10.txt:        Prevent Heart Attack Trial (ALLHAT) is a randomized,
technical/biomed/1468-6708-3-10.txt:          The rationale and design of ALLHAT are described in
technical/biomed/1468-6708-3-10.txt:          1. Did HF cases meet ALLHAT diagnostic criteria?
technical/biomed/1468-6708-3-10.txt:          were reviewed at the ALLHAT Clinical Trials Center (CTC)
technical/biomed/1468-6708-3-10.txt:          ALLHAT Endpoints Subcommittee; 
for these cases additional
technical/biomed/1468-6708-3-10.txt:          The ALLHAT definition of HF, used previously in the
technical/biomed/1468-6708-3-10.txt:        created a dilemma for ALLHAT. Since the trial was not
technical/biomed/1468-6708-3-10.txt:        ALLHAT criteria for HF were equivalently met in the two
technical/biomed/1468-6708-3-10.txt:        HF reports reviewed by the ALLHAT Endpoints Subcommittee
technical/biomed/1468-6708-3-10.txt:        reported in the ALLHAT events that were reviewed, the
technical/biomed/1468-6708-3-10.txt:        smaller and difficult to detect even in a trial of ALLHAT's
technical/biomed/1468-6708-3-10.txt:        as ALLHAT has potential limitations. Built into a structure
technical/biomed/1468-6708-3-10.txt:        number of endpoints, resources available to ALLHAT
technical/biomed/1468-6708-3-10.txt:        according to ALLHAT criteria. Some discharge summaries and
technical/biomed/1468-6708-3-10.txt:        documentation for 2% of ALLHAT event reports.
technical/biomed/1468-6708-3-10.txt:        developed for ALLHAT, specifically for HF events. This
technical/biomed/1468-6708-3-10.txt:        2) The ALLHAT Manual of Operations provides for
technical/biomed/1468-6708-3-10.txt:        3) The ALLHAT follow-up form allows for reporting of
technical/biomed/1468-6708-3-7.txt:        (ALLHAT), the role of peripheral alpha-1 antagonists in the
technical/biomed/1468-6708-3-7.txt:        doxazosin arm of ALLHAT was stopped early, due to a
technical/biomed/1468-6708-3-7.txt:        cause CHF. Because ALLHAT is an active-control trial, no
technical/biomed/1468-6708-3-7.txt:        tolerability. In light of the results of ALLHAT, we
technical/biomed/1468-6708-3-7.txt:          alpha-1 antagonists. Among these, only ALLHAT
technical/biomed/1468-6708-3-7.txt:          ALLHAT demonstrated a highly statistically
technical/biomed/1468-6708-3-7.txt:          (RR 1.19, 95% CI 1.01-1.40). Since ALLHAT is a
technical/biomed/1468-6708-3-7.txt:          comparison, the rates of CHF in 
ALLHAT participants
technical/biomed/1468-6708-3-7.txt:          chlorthalidone has a similar risk reduction in the ALLHAT
technical/biomed/1468-6708-3-7.txt:        The report of the doxazosin arm termination in ALLHAT
technical/biomed/1468-6708-3-7.txt:        the ALLHAT trial were unexpected, 
given the potential
technical/biomed/1468-6708-3-7.txt:        Those treated with doxazosin in ALLHAT had a mean blood
technical/biomed/1468-6708-3-7.txt:        increasing the incidence of CHF in the ALLHAT trial, it
technical/biomed/1468-6708-3-7.txt:        failure findings in ALLHAT, the results support the current`


# 3. PERL
## used in complex text processing, works very similarly to the rest but a little more difficult to write as a command. 

INPUT : `$ perl -ne 'print if /Background/' technical/biomed/1468-6708-3-7.txt`

OUTPUT : ` Background`

INPUT : `$  perl -ne 'print if /ALLHAT/' technical/biomed/*.txt`

OUTPUT : ` Prevent Heart Attack Trial (ALLHAT) is a randomized,
          The rationale and design of ALLHAT are described in
          1. Did HF cases meet ALLHAT diagnostic criteria?
          were reviewed at the ALLHAT Clinical Trials Center (CTC)
          ALLHAT Endpoints Subcommittee; for these cases additional
          The ALLHAT definition of HF, used previously in the
        created a dilemma for ALLHAT. Since the trial was not
        ALLHAT criteria for HF were equivalently met in the two
        HF reports reviewed by the ALLHAT Endpoints Subcommittee
        reported in the ALLHAT events that were reviewed, the
        smaller and difficult to detect even in a trial of ALLHAT's
        as ALLHAT has potential limitations. Built into a structure
        number of endpoints, resources available to ALLHAT
        according to ALLHAT criteria. Some discharge summaries and
        documentation for 2% of ALLHAT event reports.
        developed for ALLHAT, specifically for HF events. This
        2) The ALLHAT Manual of Operations provides for
        3) The ALLHAT follow-up form allows for reporting of
        (ALLHAT), the role of peripheral alpha-1 antagonists in the
        doxazosin arm of ALLHAT was stopped early, due to a
        cause CHF. Because ALLHAT is an active-control trial, no
        tolerability. In light of the results of ALLHAT, we
          alpha-1 antagonists. Among these, only ALLHAT
          ALLHAT demonstrated a highly statistically
          (RR 1.19, 95% CI 1.01-1.40). Since ALLHAT is a
          comparison, the rates of CHF in ALLHAT participants
          chlorthalidone has a similar risk reduction in the ALLHAT
        The report of the doxazosin arm termination in ALLHAT
        the ALLHAT trial were unexpected, given the potential
        Those treated with doxazosin in ALLHAT had a mean blood
        increasing the incidence of CHF in the ALLHAT trial, it
        failure findings in ALLHAT, the results support the current`
        
# 4. SED 

## short for stream editor and can substitute text with new text, quick transformations of text

INPUT: `$ sed -n '/ALLHAT/p' technical/biomed/*.txt`

OUTPUT: ` Prevent Heart Attack Trial (ALLHAT) is a randomized,
          The rationale and design of ALLHAT are described in
          1. Did HF cases meet ALLHAT diagnostic criteria?
          were reviewed at the ALLHAT Clinical Trials Center (CTC)
          ALLHAT Endpoints Subcommittee; for these cases additional
          The ALLHAT definition of HF, used previously in the
        created a dilemma for ALLHAT. Since the trial was not
        ALLHAT criteria for HF were equivalently met in the two
        HF reports reviewed by the ALLHAT Endpoints Subcommittee
        reported in the ALLHAT events that were reviewed, the
        smaller and difficult to detect even in a trial of ALLHAT's
        as ALLHAT has potential limitations. Built into a structure
        number of endpoints, resources available to ALLHAT
        according to ALLHAT criteria. Some discharge summaries and
        documentation for 2% of ALLHAT event reports.
        developed for ALLHAT, specifically for HF events. This
        2) The ALLHAT Manual of Operations provides for
        3) The ALLHAT follow-up form allows for reporting of
        (ALLHAT), the role of peripheral alpha-1 antagonists in the
        doxazosin arm of ALLHAT was stopped early, due to a
        cause CHF. Because ALLHAT is an active-control trial, no
        tolerability. In light of the results of ALLHAT, we
          alpha-1 antagonists. Among these, only ALLHAT
          ALLHAT demonstrated a highly statistically
          (RR 1.19, 95% CI 1.01-1.40). Since ALLHAT is a
          comparison, the rates of CHF in ALLHAT participants
          chlorthalidone has a similar risk reduction in the ALLHAT
        The report of the doxazosin arm termination in ALLHAT
        the ALLHAT trial were unexpected, given the potential
        Those treated with doxazosin in ALLHAT had a mean blood
        increasing the incidence of CHF in the ALLHAT trial, it
        failure findings in ALLHAT, the results support the current`
        
INPUT: `$   perl -ne 'print if /the role of peripheral alpha-1/p' technical/biomed/*.txt`

OUTPUT : ` (ALLHAT), the role of peripheral alpha-1 antagonists in the`

# How I found these commands: I used ChatGPT to find these commands; here are the prompts I gave it and its responses:

## `what are 4 other commands equivalent to grep that i can use in bash?`

`In Bash, there are several commands you can use as alternatives to `grep` for searching and filtering text. Here are four commonly used commands:

1. **sed**: Sed (stream editor) is a powerful command-line tool for text manipulation. While its primary purpose is not searching, it can be used with regular expressions to perform pattern matching and filtering. Example: `sed -n '/pattern/p' file.txt`.

2. **awk**: Awk is a versatile programming language designed for text processing. It can handle complex text manipulation tasks and provides pattern matching capabilities. Example: `awk '/pattern/' file.txt`.

3. **perl**: Perl is a robust scripting language that excels at text processing and pattern matching. It has built-in regular expression support and provides powerful text manipulation capabilities. Example: `perl -ne 'print if /pattern/' file.txt`.

4. **rgrep**: Rgrep (recursive grep) is another variant of `grep` that supports recursive searching in directories. It is not available by default in all systems, but if installed, it can be used similarly to `grep`. Example: `rgrep "pattern" directory`.

Remember to replace "pattern" with the search pattern you want to use, and "file.txt" or "directory" with the appropriate file or directory name.` 
