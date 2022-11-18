##########################################################################################################
#############################                                               #############################
#############################    README file for General genome features    #############################
#############################                                               #############################
##########################################################################################################

**BUSCO - Benchmarking sets of Universal Single-Copy Orthologs.**
###___command for BUSCO__### run_BUSCO.py -i input.fas -o output.txt file -l fungi_odb9 -m proteins -c 40
##For BUSCO runs fasta files for each species should be provided as a seperate file
##used proteome fasta in this case, for which outputs for each species will be saved in their own directory
##the output file we need, will have ".txt" extension (e.g. "short_summary_inputfungi.txt")
##to extract the "short_summary___.txt" files from multiple directories into a single directory, use "busco_outmerg.sh"