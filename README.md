# Frequent-Words-With-Mismatches-And-Reverse-Compliment
Biologically, DNA A cannot only bind to  perfect DNA A boxes but also bind to their slight  variations like Mismatches and reverse complement. Our  approach will find those mismatches along with its reverse compliment.

Input: A DNA string Text as well as integers k and d.

Output: All k-mers Pattern maximizing the sum Countd(Text, Pattern) + Countd(Text, Pattern) over all possible k-mers.

For example:
  Sample Input: 
                ACGTTGCATGTCGCATGATGCATGAGAGCT
                4 1
  In the Sample input we are given the DNA sequence along with the length of the k-mer ‘k’ and the number of at most mismatches ‘d’. In the above example the text is DNA sequence   4 is the k-mer (length)  and 1 is d (most mistaches).
  
  Sample Output:
                 ATGT ACAT
   The DnaA boxes obtained from the input DNA sequence, “ATGT” is the most frequent 4-mer with 1 mismatch, along with its reverse complement “ACAT” is obtained as the output.
              
