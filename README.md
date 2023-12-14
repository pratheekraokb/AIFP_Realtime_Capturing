## Clone the Github Repo

git clone -b master git@github.com:pratheekraokb/AIFP_Realtime_Capturing.git

## Install Following Python Libraries

1. pip install opencv-python
2. pip install numpy
3. pip install scikit-learn
4. pip install joblib
5. pip install pygame
 
Open this folder in vs code and run the python file (implementCode.py),
If you want to change the music to be produced after animal detection make changes in following line
  music_filename = "Implementation_Folder/music/ELEPHANT - Sound Effect.mp3"
Within Implementation_Folder/music/ upload the mp3 music to be played and then change the path in above line. DONE !

Now for every 20 seconds image will be captured and classified,
