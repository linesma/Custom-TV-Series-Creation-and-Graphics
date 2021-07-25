# Custom-TV-Series-Creation-and-Graphics

The included graphics and nfo files will allow a user to create a custom "TV Show" that can be added to their Kodi or Plex library. The files included in this repository were made by me to create a seperate "Documentaries" TV Show to consolidate all of the individual documentaries I have in my collection. The information contained in this readme can also be used to create a custom TV Show for any collection of videos. The user only has to change the information contained in the nfo files (Kodi only) and add their own custom graphics.

**Usage with Kodi**

1. Download the Kodi folder from the repository to your computer.

```
git clone https://github.com/linesma/Custom-TV-Series-Creation-and-Graphics/git
```

2. Edit the data in the nfo files to reflect the information you want to have displayed.

The *tvshow.nfo* is used to provide information on the entire series. 

The *individual episode.nfo* file is used to provide information for a single episode within your series. Each video needs to have its own seperate nfo file. Make sure the you rename the nfo file to match the name of its video file. If you do not do this, Kodi will not scrape the information into your library.

3. Organize your documentaries or custom TV Show in the following manner. Folder names are in bold and file names are in italics.
<pre>
<b>Documentaries</b>
-----<i>banner.jpg</i>
-----<i>fanart.jpg</i>
-----<i>poster.jpg</i>
-----<i>tvshow.nfo</i>
-----<i>season01-poster.jpg</i>
-----<i>season02-poster.jpg</i>
-----<i>season03-poster.jpg</i>
-----<i>season04-poster.jpg</i>
-----<i>season05-poster.jpg</i>
-----<i>season06-poster.jpg</i>
-----<i>season07-poster.jpg</i>
-----<i>season08-poster.jpg</i>
-----<i>season09-poster.jpg</i>
-----<i>season10-poster.jpg</i>
-----<i>season11-poster.jpg</i>
-----<i>season-all-poster.jpg</i>

----------<b>.actors</b>
---------------<i>first actor's first name_last name.jpg</i>
---------------<i>example:</i> Annie_Willows.jpg
---------------<i>second actor's first name_last name.jpg</i>
---------------<i>example:</i> Silver_Dog.jpg

----------<b>Season 01</b>
---------------<i>Documentaries_S01E01 Episode title here.mkv</i>
---------------<i>Documentaries_S01E01 Episode title here.nfo</i>
---------------<i>Documentaries_S01E02 Episode title here.mp4</i>
---------------<i>Documentaries_S01E02 Episode title here.nfo</i>

----------<b>Season 02</b>
---------------<i>Documentaries_S02E01 Episode title here.avi</i>
---------------<i>Documentaries_S02E01 Episode title here.nfo</i>
---------------<i>Documentaries_S02E02 Episode title here.wmv</i>
---------------<i>Documentaries_S02E02 Episode title here.nfo</i>
</pre>
Do this for as many "Seasons" as you would like to have. Kodi will use the *banner, fanart,* *poster*, *season01-poster*, and *season-all-poster* files in the **Documentaries** directory as the artwork for your newly created "Documentaries" TV series.

4. Scrape your custom TV Show into your Kodi library. Kodi uses local artwork and information by default. If it does not see any information, it will then scrape the data from [tvdb.com](https://www.thetvdb.com/) or [themoviedb.org](https://www.themoviedb.org/).
   
Kodi will now display your custom artwork and your TV Show/ Espisode information when you navigate to it in your library. As said before, the nfo files can be used to create and display information for your own TV Show.

**note** I am still researching how to have Kodi automatically scrape the season poster when adding a custom TV Show to one's library. Once I have that information, I will update the above directions to reflect the new information.

**Usage with Plex**

Plex does not use nfo files to scrape data automatically. So any Series/ Episode information you may want will have to be added manually. However, One can have Plex automatically scrape the custom graphics created for your custom TV show. 

1. Download the Plex folder from the repository to your computer.

2. Organize your documentaries or custom TV Show in the following manner. Folder names are in bold and file names are in italics.

<pre>
<b>Documentaries</b>
-----<i>banner.jpg</i>
-----<i>background.jpg</i>
-----<i>poster.jpg</i>

----------<b>Season 1</b>
---------------<i>Documentaries_S01E01 Episode title here.mkv</i>
---------------<i>Documentaries_S01E02 Episode title here.mp4</i>
---------------<i>Season-01-Poster.jpg</i>

----------<b>Season 2</b>
---------------<i>Documentaries_S02E01 Episode title here.avi</i>
---------------<i>Documentaries_S02E02 Episode title here.wmv</i>
---------------<i>Season-02-Poster.jpg</i>
</pre>

Do this for as many "Seasons" as you would like to have. Plex will use the *banner, background,* and *poster* files in the **Documentaries** directory as the artwork for your newly created "Documentaries" TV series.

You can now scan your Plex library to add your Documentaries (or custom) TV Show to your Plex library. It will automatically use your desired artwork for your custom TV show.

**Graphics Used folder**

The graphics used folder contains all the grpahics I used to create the artwork for my "Documentaries" TV Show. I have included them it you want to make more season posters.



