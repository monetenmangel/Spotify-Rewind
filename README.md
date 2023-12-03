# SPOTIFY REWIND
Create your own Spotify Rewind!

## Use your own Spotify data to pimp your Spotify Wrapped
The original can be found here: https://public.tableau.com/app/profile/benmangel/viz/SpotifyRewind2023/001Start?publish=yes

Data can be found here: https://www.spotify.com/us/account/privacy/

You have to be signed in and you have to use the "Extended Streaming History". It takes usually 2-3 weeks until the data arrive.

## How to rebuild
1. Use the .ipynb file to union the .json files from spotify into one .csv file.
2. Connect the Alteryx workflow with the created file
3. Add the client secret and client id from your spotify app (API) to the "Spotify_OAuth.yxmc"
4. Replace the file in the Tableau workbook with the output from the Alteryx workflow
5. Adjust the background .svg to your name. A good tool to adjust the .svg files is for example Figma. If you own an Adobe Illustrator licence feel free to play with the original file.
6. Enjoy! ✨
