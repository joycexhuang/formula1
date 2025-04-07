This goes through how to extract Formula 1 driver radios from the F1 website and convert them into readable files for Praat for Mac.

This was done for an independent study (LING 399-0) at Northwestern University under Professor Ann Bradlow in the Winter 2025 quarter for the purposes of creating a F1 driver radio communications corpus.

All materials in this repo are used under a free license.

1. Download Video DownloadHelper extension from the Google Chrome Web Store.
2. Access f1tv.formula1.com.
3. Click on the desired race and then the desired driver radio (can be accessed through the sidebar on the right).
4. Click on your extensions button, then the Video DownloadHelper extension. You should be able to download the mp4 file.
5. The downloaded mp4 file should then show up in a "dwhelper" folder on your computer. Change the name for your purposes and make sure it has NO SPACES.
6. Install FFmpeg, a command line tool used to convert multimedia files between formats. The install line has been included in this repo in "install_FFmpeg".
7. Copy the code from the "mp4_to_wav" file and change the "XX" to what the name of the file is before conversion, and the desired name. Remember to change "Me" to the user's name, and adjust the path to the correct location. The settings in the "mp4_to_wav" file are my desired settings, but you can look at the FFmpeg website and adjust them to your liking.
