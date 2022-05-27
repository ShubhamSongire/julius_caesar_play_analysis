# julius_caesar_play_analysis

This is playscript of WILLIAM SHAKESPEARE's juliuscaesar play in which I have performed valence score, sentiment analysis, emotion analysis and ploteed charts for overall role and behaviour of the character throughout the play.
![image](https://user-images.githubusercontent.com/68246393/170629923-bcca5201-14a6-4b20-8179-a268074d44c1.png)


In the above dataset I have to extract only character names and their dialogues. for this I have applied findall and sub methods of regex to extract useful data from scratch file and stored it in two seperate lists one for character naems an other for their dialogues. 
  Using aboev two lists I have created dataframe using pandas library and stored data into csv file.
Here I have extracted dialogues of lead characters in the play and stored all this data into csv file like this
![image](https://user-images.githubusercontent.com/68246393/170642470-76478a26-9ea6-40b6-aabd-8ed9902082e9.png)


After above steps I have cleaned the dialogue column by removing extra white spaces and new row symbols from dialogues. Using TextBlob library I have printed valence score and sentiments of the characters for each dialogue and made two new columns in our previous dataframe for this two new values.
Then I have used nrclex library to get emotions from sentences and stored the top emotions in our database on new column.
finally I got this dataframe:-
![image](https://user-images.githubusercontent.com/68246393/170643048-4dc24b67-dce6-47a0-9c2f-a3c1d66eab68.png)

Using valence score of each dialogue I have grouped it by character name and plotted the graph for their which tells about overall behaviour and character's role in the play whether is it positive, negative or if he is spy then how he has changed his speech time to time.



