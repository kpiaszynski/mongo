# MongoDB
## Assignment 3
## Katie Piaszynski
              
## Set-Up
- Open MongoDB           
- Create a new cluster          
- Load sample datasets (specifically mflix) following the below link              
https://www.mongodb.com/docs/guides/atlas/sample-data/
- Open MongoDB Compass            
- Connect to cluster following the below link            
https://www.mongodb.com/docs/guides/atlas/connection-string/
- Click on the sample_mflix tab
- Open the MongoDB Shell (Mongosh)

## Movies released in 1983 with runtimes greater than 200 minutes
This query looks into the "movies" section of the sample dataset "sample_mflix"      
- It chooses all movies that match the criteria of being in the year 1983, and runtime values greater than ($gt) 200 minutes long
- For the display of movies that match these criteria, we only want the runtime, title, and year                
- We then want the displayed data to be sorted with the shortest runtime first, to longest          
            
![image](https://github.com/user-attachments/assets/b7771897-fb5e-4b8c-90cb-a90d98df5fc2)

## Movies released after 2014 with an IMDB rating of over 9
This query also looks into the "movies" section of the sample dataset "sample_mflix"       
- It chooses all movies that match the criteria of being released after the year 2014 ($gt), and imdb ratings greater than ($gt) 9            
    - The ratings of the movies are nested within the IMDB section, which necessitates the additional labeling ("imdb.rating")          
- For the display of movies that match these criteria, we only want the title, year, and IMDB rating    
- We then want the displayed data to be sorted with the highest rating, to shortest                
                
![image](https://github.com/user-attachments/assets/9770e0c5-5eec-47f3-a840-ded3b108a84c)
