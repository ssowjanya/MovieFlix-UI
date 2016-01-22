IMPLEMENTATION OF MAP

I have used Google Maps JavaScript API for the generating map and the markers are plotted as clusters. Naively plotting all the charging stations in the map will degrade the user experience to overcome this marker clusters are used . This is a client side utility library which uses grid based clustering for the collection of markers. In this approach the markers are iterated in the collection that we wish to cluster by adding each marker into the closest cluster there by forming a group of clusters within a minimum square pixel bounds. Few of the markers are relatively close and others are far apart. In order to apply the clustering algorithm the markers should be passed to the marker cluster as an array. The marker cluster will start at a specific marker and checks if the marker is in bounds of existing cluster if not then it will create a new cluster and continues the process for all the remaining markers.
	The marker cluster applies the same algorithm at different zoom levels. The markers with the count more than 9 are differentiated with the yellow color to specify the more number of stations in that particular state as shown in Figure. When hovered on the marker the label is displayed showing the name of the state and the number of charging stations and charging events at that state.

 
	BUILDING JSON FILE
The json file is given as an input to the Google maps. Json is Java Script Object Notation for the storing and exchanging of data. The latitude, longitude of the charging stations located in the different states of USA is given as input to the json file. Also the label information is updated in the file with the state title and the charging stations count. The advantage of giving the data in json format is it is a self-describing and easy to understand format where an end user can easily add the rows to the json file.
	
	STATISTICS
	Javascript libraries are used to generate the charts and graphs to display the statistics [19]. The code reads the values of the states and charging stations for the X and Y axis and will generate the different types of graphs like pie-chart bar-charts etc.

	The number of public and private stations in different states of USA explained in the column graph is shown in Figure with X-axis representing the name of the stations and the Y-axis representing the percentage level of stations.
 

	TIMELINE
The timeline shows the historical events of electric vehicles and the charging formats. The bumpy adoption of electric vehicles is presented in a yearly manner which is easy to navigate year wise evolution [7]. The years are displayed in a vertical timeline on the left side and the evolution information; images are presented towards the right side [20]. The timeline feature is presented as shown in the Figure 
 
  VIDEOS
The YouTube video which describes the process of charging an electric vehicle and the charge point service overview is embedded in the application to get to know about the application visually. The following code snippet explains embedding videos in application.

 

