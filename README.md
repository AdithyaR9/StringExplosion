# StringExplosion

Created January 2019
Uploaded July 2021 

This is a String Application that allows the user to enter a sentence and then prints the altered form of the sentence using on the following rules.

Alteration Rules:
   Words of even length
     - 2 letter words are converted to all caps 
            Ex: it = IT
     - 4 letter words are replaced with **** 
            Ex: dogs = ****
     - 6 letter words
         - Letters at locations (0 and 5) and (2 and 3)  Ex: spring = gpirns
         - 8+ letter words are broken into two words of equal length  Ex: iterator = iter ator
  Words of odd length
    - 1 letter words are replaced with %
            Ex: A = % 
    - 3 letter words
        - Replace the 1st letter with <
        - Replace the last letter with >
            Ex: cat = <a>
    -  5 letter words
        - All lowercase letters are changed to uppercase 
        - All uppercase letters are change to lowercase
            Ex: GreaT = gREAt
    - 7+ letter words
        - Letters at odd index values are removed
            Ex: strangers =srnes
