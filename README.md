DNA Stuffer is a very simple DNA compressor. I decided to make it simply for the fun of it. I have no intentions to make it "state of the art" by any means. 

DNA Stuffer works by assigning each codon of the DNA sequence(a set of 3 nucleotide bases) and assigning them an 8 bit binary value. These are then written to a file and compressed using a generic GZip stream. 
