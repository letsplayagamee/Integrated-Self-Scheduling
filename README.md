# Integrated-Self-Scheduling

############################## COPYRIGHT ##############################
All rights reserved. The authorized use of this data is limited to informational and educational purposes only, and NOT for operational or commercial purposes.


############################## DESCRIPTION ############################## 
This is the data set used in the computational experiments of the paper: Integrated Stochastic Optimal Self-Scheduling for Two-Settlement Electricity Markets, which is co-authored by Kai Pan and Yongpei Guan.


############################## LIST OF FOLDERS ############################## 
Generator_Data is a folder with the data of generators used in the paper.


Data_for_Tables_1-3 is a folder with randomly generated instances for Tables 1 - 3 of the paper.


Data_for_Table_4 is a folder with randomly generated instances for Table 4 of the paper.


Data_for_Table_5 is a folder with randomly generated instances for Table 5 of the paper.


Data_for_Figures_8-9 is a folder with randomly generated instances for Figure 8 - 9 of the paper.


Data_for_Table_7 is a folder with historical wind and price data for Table 7 of the paper.


############################## DETAILS ############################## 
Generator_Data: 
	The file Generator_0.dat contains the physical data of a coal-fired generator mentioned in Section 5.1 of the paper.
	The files Generator_1.dat, Generator_2.dat, Generator_3.dat, and Generator_4.dat contain the physical data of four thermal generators, which are mentioned in Table 6 of the paper.


Data_for_Tables_1-3: 
	Each file contains a randomly generated instance used to generate the results in Tables 1 - 3. The filename of each file follows the same following format: (i) COSM stands for Compare Offer Submission Models; (ii) L stands for the minimum-up/-down time limits of the generator; (iii) K stands for the number of branches for each non-leaf node in the scenario tree \mathcal{T}; (iv) T stands for the total number of periods/stages; (v) Inst stands for an instance. For example, COSM_L2_K2_T10_Inst1.csv constains the data for the first instance considering the minimum-up/-down time limits at 2, the number of branches for each non-leaf node at 2, and the total number of periods at 10. In each file, the values of L, K, and T are provided in the first part; the values of day-ahead prices at each period are provided in the second part; the values of real-time prices and renewable generation output in each scenario at each period are provided in the third part.


Data_for_Table 4: 
	Each file contains a randomly generated instance used to generate the results in Table 4. The filename of each file follows the same following format: (i) COSM stands for Compare Offer Submission Models; (ii) L stands for the minimum-up/-down time limits of the generator; (iii) T stands for the total number of periods/stages; (iv) Sce stands for the total number of scenarios; (v) Inst stands for an instance. For example, COSM_L4_T24_Sce250_Inst1 contains the data for the first instance considering the minimum-up/-down time limits at 4, the total number of periods at 24, and the total number of scenarios at 250. In each file, the values of L and T are provided in the first part; the values of day-ahead prices at each period are provided in the second part; the values of real-time prices and renewable generation output in each scenario at each period are provided in the third part.


Data_for_Table 5: 
	Each file contains a randomly generated instance used to generate the results in Table 5. The filename of each file follows the same following format: (i) COSM stands for Compare Offer Submission Models; (ii) L stands for the minimum-up/-down time limits of the generator; (iii) K stands for the number of branches for each non-leaf node in the scenario tree \mathcal{T}; (iv) T stands for the total number of periods/stages; (v) Arbitrage/NoArbitrage indicates whether no arbitrage case is considered; (vi) Inst stands for an instance. For example, COSM_L2_K2_T10_Arbitrage_Inst1.csv contains the data for the first arbitrage instance considering the minimum-up/-down time limits at 2, the number of branches for each non-leaf node at 2, and the total number of periods at 10. In each file, the values of L, K, and T and whether considering arbitrage are provided in the first part; the values of day-ahead prices at each period are provided in the second part; the values of real-time prices and renewable generation output in each scenario at each period are provided in the third part.


Data_for_Figures_8-9: 
	Each file contains a randomly generated instance used to generate the results in Figures 8 - 9. The filename of each file follows the same following format: (i) CVaR stands for Conditional Value at Risk model; (ii) L stands for the minimum-up/-down time limits of the generator; (iii) K stands for the number of branches for each non-leaf node in the scenario tree \mathcal{T}; (iv) T stands for the total number of periods/stages; (v) Alpha stands for the value of \alpha in Section 5.5. For example, CVaR_L4_K2_T9_Alpha0.9 contains the data considering the minimum-up/-down time limits at 4, the number of branches for each non-leaf node at 2, the total number of periods at 9, and the value of \alpha at 0.9. In each file, the values of L, K, T, and \alpha are provided in the first part; the values of day-ahead prices at each period are provided in the second part; the values of real-time prices and renewable generation output in each scenario at each period are provided in the third part.


Data_for_Table_7: 
	Each file contains the historical wind and price data used to generate the results in Table 7. According to the paper, the data are divided into two groups. The files Group_1_Day_Ahead_Price.csv, Group_1_Real_Time_Price.csv, and Group_1_Wind_Output.csv contain the day-ahead prices, real-time prices, and wind outputs in Group 1; the files Group_2_Day_Ahead_Price.csv, Group_2_Real_Time_Price.csv, and Group_2_Wind_Output.csv contain the day-ahead prices, real-time prices, and wind outputs in Group 2.
