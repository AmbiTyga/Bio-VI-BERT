# Data Processing
In this section we split our data to training, validation and test sets, and augment the training set for better training.

## Dataset Distribution

|      Sets      | Data-points |
|:--------------:|:-----------:|
| Training Set   |     1140    |
| Validation Set |      38     |
| Test Set       |      39     |


### Class Distribution

|      Class     | Training | Validation | Test |
|:--------------:|:--------:|:----------:|:----:|
| Aconoidasida	 |435		 |14		   |15	|
| Cestoda 		 |105		 |3		   |4		|
| Chromadorea    |125		 |5		   |4		|
| Conoidasida    |210		 |7		   |7		|
| Enoplea        |70		 |3		   |2		|
| Tubulinea      |95		 |3		   |3		|
| Zooflagellate  |100		 |3		   |4		|


### Phylum Distribution

|      Phylum    	| Training | Validation | Test |
|:-------------------:|:--------:|:----------:|:----:|
| Amoebozoa	 	|95		 |3		   |3		|
| Apicomplexa 	 	|645		 |21		   |22	|
| Nematoda    	 	|195		 |8		   |6		|
| Platyhelminthes	|105		 |3		   |4		|
| Sarcomastigophora	|100		 |3		   |4		|


### Genus Distribution

|      Genus	  | Training | Validation | Test   |
|:---------------:|:--------:|:----------:|:------:|
|Ascaris          |60		  |2		    |2	  |
|Cryptosporidium  |60		  |2		    |2	  |
|Cyclospora       |110	  |4		    |4	  |
|Dibothriocephalus|40		  |1		    |1	  |
|Entamoeba        |95		  |3		    |3	  |
|Enterobius       |65		  |3		    |2	  |
|Giardia          |100	  |3		    |4	  |
|Hymenolepis      |65		  |2		    |3	  |
|Plasmodium       |43		  |14		    |15	  |
|Sarcocystis      |40		  |1		    |1	  |
|Trichuris        |70		  |3		    |2	  |


### Species Distribution

|      Species	 	   | Training | Validation | Test   |
|:---------------------:|:--------:|:----------:|:------:|
|Ascaris lumbricoides    |60	   |2		    |2	  |
|Cryptosporidium sp.     |60	   |2		    |2	  |
|Cyclospora cayetanensis |110	   |4		    |4	  |
|Dibothriocephalus latus |40	   |1		    |1	  |
|Entamoeba histolytica   |95	   |3		    |3	  |
|Enterobius vermicularis |65	   |3		    |3	  |
|Giardia duodenalis  	   |100	   |3		    |3	  |
|Hymenolepis spp     	   |65	   |2		    |2	  |
|Plasmodium falciparum   |125	   |4	    	    |4	  |
|Plasmodium knowlesi     |3	0	   |1	   	    |1	  |
|Plasmodium malariae     |9	0	   |1	    	    |3	  |
|Plasmodium ovale        |75	   |3	  	    |2	  |
|Plasmodium vivax        |115	   |4		    |4	  |
|Sarcocystis sp.     	   |40	   |1		    |1	  |
|Trichuris Trichuria 	   |70	   |3		    |3	  |


### Form Distribution

|      Form      | Training | Validation | Test |
|:--------------:|:--------:|:----------:|:----:|
| Adult    	 |55		 |5		   |3		|
| Cyst 		 |125		 |2		   |4		|
| Egg		      |245		 |6		   |7		|
| Gametocyte     |90		 |3		   |4		|
| Oocysts        |210		 |7		   |7		|
| Schizont       |70		 |3		   |2		|
| Trophozoites   |345		 |12		   |12	|


### Sample Distribution

|      Sample    | Training | Validation | Test |
|:--------------:|:--------:|:----------:|:----:|
| Blodd    	 |435		 |14		   |15	|
| Feces 		 |385		 |11		   |12	|
| Intestine      |85		 |6		   |4		|
| Wet Mount      |235		 |7		   |8		|


