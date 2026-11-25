########################################################

Nebular Emission Line Grid	

Pless 2024
Email: lpless@swin.edu.au

########################################################

BPASS models (Eldridge et al. 2017) v2.1
Cloudy v23.01 (Chatzikos et al. 2023, Gunasekera et al. 2023)

——————————————————————————————————————————————————————————————

HDF5 file structure
—————————————————————————————————————————

- C/O fraction						#solar value is 0.44, value range chosen like in Gutkin et al. 2016
	- Xsi						#dust to metal mass ratios, [0.1, 0.3, 0.5]
		- log(n_H)				#log of hydrogen density in gas cloud, [1.0, 2.0, 3.0, 4.0]
			- age				#age of SSP producing ionising radiation
				-dataset		#selected lines at different metallicities
							#names of datasets follow 
							#CO_x.xxx_U_x.x_n_x.x_age_x.xxe+0x_xsi_0.x



——————————————————————————————————————————————————————————————

Dataset Structure
—————————————————————————————————————————
Quantity			Description/Units						
———————————————————————————————————————————————————————————————————	
Z 				metallicity, absolute value, solar ~0.015				
Hα				all lines are intrinsic, given in reference to Hβ		
Hβ				units erg cm−2 s−1						
O 	I 	6300 A		blended line							
O 	II 	3727 A		blended line 3726.03+3728.81A				
O 	III 	1666 A		blended line						
O 	III 	4959 A									
O 	III	5007 A									
S 	II	6724 A		blended line 6716.44+6730.82A
N	II	6548 A
N 	II	6584 A
N 	V	1243 A		blended lines around 1240 A
He 	I	3965 A
He	I	4471 A
He	I	5876 A
He 	I	6678 A
He 	II	1640 A
He	II	4686 A
C	III	1909 A
C	IV	1551 A
Si	III	1892 A
n_H				average hydrogen density in gas cloud after photoionisation model	
