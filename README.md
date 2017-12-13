# shamirs-encryption
Encryption of plaintext by version of Shamir's secret sharing scheme. 

Takes in a plaintext (in '.txt' file form) and a letter to numeral key, 
and encrypts using Shamir's secret sharing scheme with a polynomial 
of specified degree. 

Given letters of plaintext, we generate a polynomial whose constant 
term is the integer number corresponding to each of those letters, and
print to a file a sufficient number of data points to reconstruct the 
polynomial
