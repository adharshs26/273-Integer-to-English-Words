The function `numberToWords` converts a non-negative integer into its English words representation. 
It uses a helper function to recursively break down the number into chunks (units, tens, hundreds, thousands, millions, etc.). 
The `helper` function handles numbers less than 1000 by translating units, tens, and hundreds into words. 
For larger numbers, it divides the number by thousand, million, or billion, recursively converts the quotient and remainder, and combines the results with the appropriate large number label. 
The final result is built by combining these translations into a coherent English phrase.
