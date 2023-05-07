# Twitter-sentiment-analysis-and-Denodo
Creating a custom function
1.	Install the trained classifier
2.	Install eclipse
3.	Configure Eclipse to run with Java 11.
4.	Installing Denodo4eEclipse Pulgin

 
 
5.	To create the Denodo Custom function project, go to File > New > Other and type denodo in the textbox.
 
6.	 
7.	 
8.	we need to import the following libraries jar files from the LingPipe distribution: ● lingpipe-4.1.0.jar ● log4j.jar
 

 
9.	Back to the code of the custom function we will need define a constructor in our class to load the classifier as follows:
 

10.	Debug
 




11.	Export the project
 







12.	Import Extensions in Denodo
 
13.	Test
 











14.	Create a JSON Datasource
 
15.	Connecting Denodo with Twitter
 
16.	 
17.	 
18.	Create a base view
 


19.	Create a flatten view
 


20.	Add a new field sentiment with field expression mood(text)
21.	 













