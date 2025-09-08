# How to use this rag AI Teaching assistant on your own data
## step 1- collect your videos
Move all your videos files to the videos folder

##  step 2- convert to mp3
convert all the video files to mp3 by running video_to_mp3

## step3- convert mp3 to json
convert all the mp3 files to json by running mp3_to_json

##  step4- convert the json files to vectors
use the file preprocess_json to convert the json files to a dataframe with embeddings and save it as a joblib pickle

## step 5- prompt generation and feeding to LLm
Read the joblib file and load it into the memory. Then create a relevant prompt as per the user query and feed it to the LLM
