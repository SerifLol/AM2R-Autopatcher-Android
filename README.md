# AM2R-Autopatcher-Android
A repository containing patch data and scripts in order to automatically install the latest AM2R Community Updates on Android via Termux.

Modified by me to actually work since SVN is no longer supported by github afaik.

### How to use
Open up Termux and execute the following command to install the latest Community Updates:  
`pkg install wget && wget -O patcher.sh https://github.com/SerifLol/AM2R-Autopatcher-Android/raw/main/patcher.sh && chmod +x patcher.sh && ./patcher.sh`

you must download this projects source code and put the source code in ~/storage/downloads/AM2RAutopatcher/

directory should look like this


AM2RAutopatcher/

../HDR_HQ_in-game_music/

../Data/

../patcher.sh


you may delete this folder once you're done running it
