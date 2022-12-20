# Steam-Powered Stream Snatcher

The ultimate tool for harvesting YouTube videos with elegance and efficiency.

## Description

This script allows you to download YouTube videos from the command line for free. It can handle both single videos and playlists. The script also includes a progress bar to show the download progress and ensures that the downloaded files have safe filenames (no spaces or strange characters).

You can choose to download the highest quality version of the video by setting the *i_want_the_highest_quality* variable to True, or you can opt for a lower quality version by setting it to False. The default value is False.

If the destination folder specified in the script ("downloads" by default) does not exist, it will be created for you.

## Usage

To use the script, run the following command in your terminal:

```bash
python3 yt_download.py URL [DESTINATION]
```

Replace URL with the URL of the YouTube video or playlist you want to download. The DESTINATION parameter is optional, and if it is not specified the files will be saved in the downloads folder.

## Dependencies
This script requires the following libraries:

os
sys
pytube
tqdm
unidecode
re

### Installing Dependencies
To install the required libraries for this script, you can use the pip package manager. pip is usually installed by default with Python, but if it is not installed on your system, you can install it by running the following command:

```
python3 -m ensurepip --upgrade
```

Once pip is installed, you can install the dependencies for this script by running the following command:

```
pip install -r requirements.txt
```

## Disclaimer
Please note that downloading YouTube videos may violate the terms of service of YouTube. This script is intended for educational purposes only, and the user is responsible for any consequences of using it.