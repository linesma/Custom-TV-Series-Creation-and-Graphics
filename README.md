# Custom-TV-Series-Creation-and-Graphics

The included graphics and nfo files will allow a user to create a custom "TV Show" that can be added to their Kodi or Plex library. The files included in this repository were made by me to create a seperate "Documentaries" TV Show to consolidate all of the individual documentaries I have in my collection. The information contained in this readme can also be used to create a custom TV Show for any collection of videos. The user only has to change the information contained in the nfo files (Kodi only) and add their own custom graphics.

**Usage with Kodi**

1. Download the Kodi folder from the repository to your computer.

2. Edit the data in the nfo files to reflect the information you want to have displayed.

The *tvshow.nfo* is used to provide information on the entire series. 

The *individual episode.nfo* file is used to provide information for a single episode within your series. Each video needs to have its own seperate nfo file. Make sure the you rename the nfo file to match the name of its video file. If you do not do this, Kodi will not scrape the information into your library.

3. Organize your documentaries or custom TV Show in the following manner. Folder names are in bold and file names are in italics.
```
**Documentaries**
-----*banner.jpg*
-----*fanart.jpg*
-----*poster.jpg*
-----*tvhshow.nfo*
-----*Series One.jpg*
-----*Series Two.jpg*
-----*Series Three.jpg*
-----*Series Four.jpg*
-----*Series Five.jpg*
-----*Series Six.jpg*
-----*Series Seven.jpg*
-----*Series Eight.jpg*
-----*Series Nine.jpg*
-----*Series Ten.jpg*
-----*Series Eleven.jpg*

----------**Season 1**
---------------*Documentaries_S01E01 Episode title here.mkv*
---------------*Documentaries_S01E01 Episode title here.nfo*
---------------*Documentaries_S01E02 Episode title here.mp4*
---------------*Documentaries_S01E02 Episode title here.nfo*

----------**Season 2**
---------------*Documentaries_S02E01 Episode title here.avi*
---------------*Documentaries_S02E01 Episode title here.nfo*
---------------*Documentaries_S02E02 Episode title here.wmv*
---------------*Documentaries_S02E02 Episode title here.nfo*
```
Do this for as many "Seasons" as you would like to have. Kodi will use the *banner, fanart,* and *poster* files in the **Documentaries** directory as the artwork for your newly created "Documentaries" TV series.

4. Tell Kodi what artwrok to use for each of the TV Show's seasons.

   a. Navigate to your **Documentaries** entry in your video library.

   b. Open the entry so you see the individual seasons.

   c. Highlight the season folder and press "c" on your keyboard to bring up the context menu. (If you are using a remote control, press and hold the "enter" button that is in the middle of your direction buttons to bring up this menu)

   d. Select "Manage"

   e. Select "Choose Art"

   f. Select "Poster"

   g. Select "Browse" and choose "Item Folder".

   h. Highlight the artwork you want to use for that season and select "Okay"
   
Kodi will now display your custom artwork and your TV Show/ Espisode information when you navigate to it in your library. As said before, the nfo files can be used to create and display information for your own TV Show.

**note** I am still researching how to have Kodi automatically scrape the season poster when adding a custom TV Show to one's library. Once I have that information, I will update the above directions to reflect the new information.

**Usage with Plex**

Plex does not use nfo files to scrape data automatically. So any Series/ Episode information you may want will have to be added manually. However, One can have Plex automatically scrape the custom graphics created for your custom TV show. 

1. Download the Plex folder from the repository to your computer.

2. Organize your documentaries or custom TV Show in the following manner. Folder names are in bold and file names are in italics.

**Documentaries**
-----*banner.jpg*
-----*background.jpg*
-----*poster.jpg*

----------**Season 1**
---------------*Documentaries_S01E01 Episode title here.mkv*
---------------*Documentaries_S01E02 Episode title here.mp4*
---------------*Season-01-Poster.jpg*

----------**Season 2**
---------------*Documentaries_S02E01 Episode title here.avi*
---------------*Documentaries_S02E02 Episode title here.wmv*
---------------*Season-02-Poster.jpg*

Do this for as many "Seasons" as you would like to have. Plex will use the *banner, background,* and *poster* files in the **Documentaries** directory as the artwork for your newly created "Documentaries" TV series.

You can now scan your Plex library to add your Documentaries (or custom) TV Show to your Plex library. It will automatically use your desired artwork for your custom TV show.




