# Morans-I
Calculation of Moran's I from X Y coordinates and variable of interest

Moran's I and interated significance base on a z distribution (normal)

Inputs are a list of (x,1) longitude values with matching (y,1)
lattitutude values and matching variable of interest, VarIn, of length (x,1) 

Weigthted calculation can be altered but is as default a logaritmic linear decay
function up to maximum distance MaxD. Significance interations include
bts runs of data permutations
