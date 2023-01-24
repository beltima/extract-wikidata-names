extract given names from wiki data

update (new to old): 

in <Extract_Wiki_Data_names_try_02.ipynb> -- new!!
1. Created one function called similar_full_names to get the similar names when input is a name
2. Proof of concept of getting real (first+last) pairs of full names from various sources, ie, politicians, athletes, singers etc. 
3. having problems with jsondecodeerror, likely due to the server responded with a 204 No Content response, not yet fixed. 

in <Extract_Wiki_Data_names_try_01.ipynb>: 
used package "qwikidata", better than the previous one
1. find similar first names baesd on a given first name
2. fiind (first name + last name) pairs based on the same first name
3. find (first name + last name) pairs for female politicians

in <Extract_Wiki_Data_names_try_00.ipynb>
1. only tried with getting similar names for Gregory atm, will run code on all names gathered. 
