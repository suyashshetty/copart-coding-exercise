Team Members:
1. Suyash Shetty
2. Shreyas Kondlekar
3. Prathamesh Patil

1. MOST APPROPRIATE FACILITY:
	1. Class Files : 
		1. CompareZipCodeDistance
		2. CopartFacility
		3. CopartFacilityLocator
		4. CustomerInfo
	2. We have used .csv file(id_zip.csv) for database. All the data regarding city, zipcode, state is fetched from the .csv file
	3. External jar file json-simple-1.1.jar
	4. Used this api: https://www.zipcodeapi.com/rest/SH8Be5Im18StbtqknXgm9a9aoJZsukum2CXhHGDJOvd0ZDknBAJKLSV9CVC6g6si/distance.json/12345/94523/mile


2. ZIP CODE LOOKUP
	1. Class Files
		1. ZipCodeLookUp
		2. ZipCodeLookUpDemo
	2. External jar file json-simple-1.1.jar
	3. Used this api: http://maps.googleapis.com/maps/api/geocode/json?

3. DNA Sequencing
	1. Class Files
		1. DNASequence
		2. DNASequenceDemo
		3. DNASequencing

4. PIECE OF CAKE
	1. Class Files
		1. PieceOfCake
		2. PieceOfCakeDemo
	2. In this we have provided two options to user :
		1. File:
			User should use the file for input data. Input data should be in following format
				1. Number of Cakes
				2. Area of Cake 1
				3. Area of Cake 2
		2. Console:
			User will add data on console

PROJECT IDEAS
2. Event/Messaging Queues
	1. Problems can occured in this
		1. The message can get deleted before the data from the database get inserted into database.
		2. Data from particular message can be get inserted into undesried database.
	2. Solutions:
		1. Before deleting the message, it should be checked whether the data from the message is inserted into database or not.
		2. Check/ flag should be used to check whether the data from message is inserted into desired database.
	
	