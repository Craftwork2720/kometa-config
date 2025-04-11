# kometa-config
```
libraries:

  Movies:
    overlay_files:
    - file: config/overlays/rating	#audience_rating
    operations:
      mass_audience_rating_update:
      - imdb
      - tmdb
      - 2.0
	
  Series:
    collection_files:
   #- file: config/collections/miniseries #this collection is needed for overlay to labaling miniseries 
    overlay_files:
   # - file: config/overlays/miniseries
    - file: config/overlays/status
    - file: config/overlays/rating  #audience_rating
    operations:
      mass_audience_rating_update:
      - imdb
      - tmdb
      - 2.0
```	
# + In collections folder are some of my colections and posters

## Anime
![Anime](/readme3.png)


## Movies
![movies](/readme1.png)

## Series (screenshots displays different language but on github is english version)
![Series](/readme2.png)


## Posters
![posters](/posters1.png)
![posters](/posters2.png)
