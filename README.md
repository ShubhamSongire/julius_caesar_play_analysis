# julius_caesar_play_analysis

This is a playscript of WILLIAM SHAKESPEARE's Julius Caesar play in which I have performed valence score, sentiment analysis, emotion analysis, and plotted charts for the overall role and behavior of the character throughout the play. <br>
playscript:- https://github.com/ShubhamSongire/julius_caesar_play_analysis/blob/main/juliuscaesar.txt
![image](https://user-images.githubusercontent.com/68246393/170629923-bcca5201-14a6-4b20-8179-a268074d44c1.png)


In the above dataset, I have extracted character names and their dialogues. for this, I have applied findall and sub methods of regex to extract the useful data from a scratch file and stored it in two separate lists one for character names and the other for their dialogues. 
  Using the above two lists I have created a data frame using the pandas library and stored data in CSV file.
Here I have extracted dialogues of lead characters in the play and stored all this data into CSV file like this

![image](https://user-images.githubusercontent.com/68246393/170642470-76478a26-9ea6-40b6-aabd-8ed9902082e9.png)


After the above steps, I cleaned the dialogue column by removing extra white spaces and new row symbols from dialogues. Using the TextBlob library I have printed the valence score and sentiments of the characters for each dialogue and made two new columns in our previous data frame for these two new values.
Then I used nrclex library to get emotions from sentences and stored the top emotions in our dataframe on new column.
finally, I got this dataframe:-
![image](https://user-images.githubusercontent.com/68246393/170643048-4dc24b67-dce6-47a0-9c2f-a3c1d66eab68.png)

Using the valence score of each dialogue I have grouped it by character name and plotted the graph for them which tells about overall behavior and character's role in the play whether is it positive, negative or if he/she is a spy then how speech has changed from time to time.
![index](https://user-images.githubusercontent.com/68246393/170643923-dbe08878-fab9-4751-bb73-811f409a72cc.png)

This is how I analyzed the Julius Caesar play script and extracted useful information from it.

## Thank you for visiting!


