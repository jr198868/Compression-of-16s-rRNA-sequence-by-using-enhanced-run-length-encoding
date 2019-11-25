#### Compression-of-16s-rRNA-sequence-by-using-enhanced-run-length-encoding

##### ABSTRACT:


	
![Screenshot](https://github.com/jr198868/Compression-of-16s-rRNA-sequence-by-using-enhanced-run-length-encoding/raw/master/materials/Graphic_abstract_5.jpg)

![Screenshot](https://github.com/jr198868/Compression-of-16s-rRNA-sequence-by-using-enhanced-run-length-encoding/raw/master/materials/Graphic_abstract_6.jpg)

##### Standard of Procedure:

	Step 1: Sequence cleaning 
	Step 2: Run-length encoding and append the encoded data into the final_seq_data 
	step 3: Construct modified (enhanced) Run-length encoding 
	Step 4: level II encoding for the sequence compression
	Step 5.1: Find the commonly repeated subsequence with 6 characters 
	Step 5.2: Construct the index (str(i) +'*') which will be used to "encode" the repeated sequences
	Step 5.3: Construct a dictionary {Commonly repeated subsequence: index}
	Step 6: Run level II encoding
	

##### This project is still ongoing! More cases of the commonly repeated subsequence other than 6 characters will be discussed.

