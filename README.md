# Drug-Target

This repository contain the data and MATLAB code for the paper :

Descripotion:

Two algorithms are applied to select important proteins.
The first Algorithm approximates the balanced partitioning problem with spectral partitioning. In this algorithm, we try to disrupt the maximum number of backup pathways with the removal of the minimum number of essential proteins.

To run the First Algorithm (Run L.m), use the following matlab command line:
"[Cut,S0]=L(ComplexNetwork,ProteinID,All_name_Proteins);"
Input:
ComplexNetwork: The complex network (tab delimited MAT-File with n columns and n rows, for n nodes).
ProteinID:  The nodes of network (you can use the no. of selected proteins or tab delimited MAT-File with n rows).
All_name_Proteins: The name of Proteins (tab detimited MAT-File with names of all proteins).

Output:

Cut: The name of selected proteins.

S0: The no. of selected proteins.

In addition, We present a ComplexNetwork related to the biological process of Sars_Covid-2 and
ProteinIDrelated to its nodes from all proteins in the Example.mat file.

The second Algorithm tries to cause maximum disruption in the network by selecting the least number of essential proteins. The measure for selecting these essential proteins is a value called betweenness and  available here http://bs.ipm.ac.ir/softwares/DPC/DPC.zip









