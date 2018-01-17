# QoE-Dataset-VLC-Indicators

This work is proposed to describe and to share a subjective  QoE  dataset  that  assess  YouTube  video  quality in  controlled  
laboratory environment.  This  dataset  is collected  using  the  subjective  Absolute  Category  Rate  (ACR) method based
on Mean Opinion Score (MOS) ratting score. It provides a good representative panel of various QoE Influence Factors (QoE IFs), 
that allows researchers community to  work in  order to  study  and  better understand  the QoE concept.

To build this dataset, a testbed is achieved in the LiSSi laboratory (http://lab.lissi.fr/) around Paris city in France. 62 
testers prticipated in the test campaign. All of them were researchers and students from different disciplines aged 19 to 41 
years  with  few  or  no  experience  with video assessment experimentation. The collected QoE IFs concerns many video 
parameters (QoA) that VLC video player provides as indicator.


1- Source:

Creators: 

-> Lamine Amour (lamine.amour@u-pec.fr) 

-> Sami Souihi (sami.souihi@u-pec.fr)

-> Abdelhamid Mellouk (mellouk@u-pec.fr)

2- Data Set Information:

The dataset was built from a controlled laboratory testbed where 560 sample covering 18 Quality of Experience Impact Factors (QoE IFs). The used videos are of different types/complexities. 

The geographical location of the testbed was the LiSSi laboratory (http://lab.lissi.fr/) around Paris city in France. 62 testers prticipated in the test campaign. All of them were researchers and students from different disciplines aged 19 to 41 years  with  few  or  no  experience  with video assessment experimentation.  

3- Attribute Information:

The dataset is presented in different formats/files as follows: 

The content of the dataset can be uploaded with differnt formats. These formats are: 

- name.csv : Microsoft Excel 2007 file.
- name.arff : Weka files (https://en.wikipedia.org/wiki/Weka_(machine_learning)
- name.data : Open Document format (https://en.wikipedia.org/wiki/OpenDocument


Both files contain 18 QoE IFs and the Mean Opinion Scors (MOS) given by users. 

 1)  id
	
2)  V_id-video
	
3)  V_content
	
4)  V_norm-bitrate
	
5)  V_complexity
	
6)  V_complexity-class
	
7)  QoA_VLCresolution
	
8)  QoA_VLCcaching
	
9)  QoA_VLCbitrate
	
10) QoA_VLCframerate  
	
11) QoA_VLCdropped
	
12) QoA_VLCaudiorate
	
13) QoA_VLCaudioloss
	
14) QoA_BUFFERINGtime
	
15) QoD_screen_size
	
16) id_user
	
17) QoU_age
	
18) QoU_sex
	
19) MOS
	
--> Each variable belongs to a category of QoE Influence Factors (QoE IFs) that consists:
- Video content analysis results (2 to 6)
	      
- VLC player indicators (QoA) (7 to 14)
	      
- Device characteristics  (QoD)(15)
	      
- User's profil (QoU) (16 to 18)	
	      
- User's MOS scoe(19)		  
             
 --> Number of Instances : 
       
 class 1 (MOS = 1): 138  
		 
 class 2 (MOS = 2): 100
		 
 class 3 (MOS = 3): 103
		 
 class 4 (MOS = 4): 132
		 
 class 5 (MOS = 5): 89

--> Number of Attributes 
     19

  --> For Each Attribute:
   All attributes are digit except, video content type (V-content) user gender (QoU_sex) and device screen size (QoD_screen_size)

	 --> NOTES: 
     
	  - 14st (QoU_sex) User's gender.
		   0 -> Woman
		   1 -> Man
		  	  
	  
	  - 19st (MOS) Mean Opinion Scroe that a tester will give at the end of each video view.
		   5 -> Excellent
		   4 -> Good
		   3 -> Fair
		   2 -> Poor
		   1 -> Bad
	

4- Related publications

 (a) Lamine Amour, Sami Souihi, Said Hoceini, Abdelhamid Mellouk: An Open Source Platform for Perceived Video Quality Evaluation. Q2SWinet@MSWiM: pages 139-140. November 2015. 
		
 (b) Lamine Amour, Sami Souihi, Said Hoceini, Abdelhamid Mellouk: A Hierarchical Classification Model of QoE Influence Factors. WWIC 2015: pages 225-238, May 2015.

 (c) Lamine Amour, Sami Souihi, Abdelhamid Mellouk: ACR-based Subjective QoE Datasets to Quantify YouTube Video Quality. QoMEX 2018: pages xxx-xxx, 2015 (Submitted).



5- Citation Request:

The following citation is requested if you use the dataset: 

Lamine Amour, Sami Souihi, Abdelhamid Mellouk: ACR-based Subjective QoE Datasets to Quantify YouTube Video Quality. QoMEX 2018: pages xxx-xxx, 2015 (Submitted).


