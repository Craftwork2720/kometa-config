# kometa-config
## style_v1


<p float="left">
  <img src="screenshots/v1_tv.png" height="220" />
  <img src="screenshots/v1_movies.png" height="220" />
</p>

## style_v2

<p float="left">
  <img src="screenshots/v2_tv.png" height="220" />
  <img src="screenshots/v2_movies.png" height="220" />
</p>

## style_v1

``` yaml
# style_v1
libraries:
  Movies:
    overlay_files:
    - file: config/craftwork2720/overlays/style_v1/rating	#audience_rating
    operations:
      mass_audience_rating_update:
      - imdb
      - tmdb
      - 2.0
	
  Series:
    collection_files:
  # - file: config/craftwork2720/overlays/style_v1/miniseries #this collection is needed for overlay to labaling miniseries 
    overlay_files:
  # - file: config/craftwork2720/overlays/style_v1/miniseries
    - file: config/craftwork2720/overlays/style_v1/status
    - file: config/craftwork2720/overlays/style_v1/rating  #audience_rating
    operations:
      mass_audience_rating_update:
      - imdb
      - tmdb
      - 2.0
```	

## style_v2

``` yaml
# style_v2
libraries:
  Movies:
    overlay_files:
    - file: config/craftwork2720/overlays/style_v2/rating	#audience_rating
    operations:
      mass_audience_rating_update:
      - imdb
      - tmdb
      - 2.0
	
  Series:
    collection_files:
  # - file: config/craftwork2720/overlays/style_v2/miniseries #this collection is needed for overlay to labaling miniseries 
    overlay_files:
  # - file: config/craftwork2720/overlays/style_v2/miniseries
    - file: config/craftwork2720/overlays/style_v2/status
    - file: config/craftwork2720/overlays/style_v2/rating  #audience_rating
    operations:
      mass_audience_rating_update:
      - imdb
      - tmdb
      - 2.0
```	


### Posters

<p float="left"><img src="craftwork2720/collections/posters/a24.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/bafta.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/cannes.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/current_season.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/delete_auto.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/delete.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/documentary.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/ghibli.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/miniseries.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/neon.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/oscars.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/previous_season.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/random.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/recently_added.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/recently_released.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/Year%202023.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/Year%202024.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/Year%202025.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/Year%202026.png" height="220" style="margin:5px;" />
<img src="craftwork2720/collections/posters/Year%202027.png" height="220" style="margin:5px;" />
</p>