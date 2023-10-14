# GSheet-multiFlatten
Google Sheet function to flatten CSV values

Takes a list or range that may contain comma separates values
and flattens it, returning a list of individual values

Input:
Apple
Banana, Blueberry, Blackberry
Cherry
Durian

Output:
Apple
Banana
Blueberry
Blackberry
Cherry
Durian

Can be used on a list, eg: =multiFlatten(unique(A1:A99))
Can be used on a region eg: =multiFlatten(A1:A99)
Can be used in a funtion eg: =unique(multiFlatten(A1:A99))
