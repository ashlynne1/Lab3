# Lab3
i
I started with converting the string into the amount of knuts.
Question 1 says it may or my not be easier to get rid of "/", and it is easier to keep the slashes because they can be used as the ]
delimiter for the split function when we are trying to multiply and add the different numbers to find the total knuts.
It took me a while to discover that ($0,1,1) was what is supposed to go in my substring, but once i did the rest of my program ran 
smoothly. 
Then I did the reverse where I took the total number of knuts and made it into galleons, sickles and knuts separated by slashes.
this is done by using basic math functions to divide the total ammount by the amount of galleons and sickles then put the amounts
into the correct format by adding in the slashes

The final question can be done by following the code of #13 on the command sheet:  awk ' BEGIN {sum=0} {sum+=$0} END {print sum}'
and applying it to the first algorithm and then converting back to the original format with knuts2string.sh
