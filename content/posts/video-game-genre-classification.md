---
title: "Video Game Genre Classification"
tags: [AI, Machine Learning, Video Games, Classification, Machine Vision]
author: "Benedict Wilkins"
draft: true
cover:
    image: "" # image path/url
    alt: "" # alt text
    caption: "" # display caption under cover
---

## Datasets

- [Google Play App Dataset](https://www.kaggle.com/datasets/tapive/google-play-apps-and-games) : A list of meta-data associated with a large number of apps on google play. 

- [Video Game Cover Art](https://www.kaggle.com/datasets/veerpandya/video-game-covers)

- [Popular Video Games 1980-2023](https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023) : Curated text meta-data including genre, text summary and reviews.

- [RAWG Video Game Dataset](https://www.kaggle.com/datasets/jummyegg/rawg-game-dataset) : Textual meta-data including game genres, publishers, platforms and text reviews, nearly 500k entries.

- [PlayMyData](https://zenodo.org/records/10262075) : Textual meta-data with screen shots and video urls. Data was mined from [IGDB](https://www.igdb.com/).

- [Steam Games Dataset](https://www.kaggle.com/datasets/fronkongames/steam-games-dataset) : Collection of meta-data gathered from the Steam platform, [associated code](https://github.com/MYTE21/TC.Video.Game).

- [Video Game Classification using NLP](https://www.kaggle.com/code/cguzman09/video-game-classification-using-nlp/input) : Classifying video game (top-level) genre from the game's title using traditional MLP methods, reaches 70% training accuracy - this result is to be expected, it would generally be difficult to classify just based on the title, there would only be a weak global correlation (e.g. from sequals in the same genre, or titles containing certain words "soccer" -> "sport"). Images would contain much more information and so we may expect a better (test) accuracy.



## Websites


#### [Games that defy genre](https://www.thegamer.com/games-defy-genre-classification-minecraft-undertale/)

1. The Witness
2. Undertale
3. Papers, Please
4. Journey
5. Baba Is You
6. Death Stranding
7. Pathologic
8. The Beginner's Guide
9. Her Story
10. Minecraft

because they are player driven or open ended?

- [Cover Art Project](https://www.thecoverproject.net) : Collection of old and new game cover art (much of it is scanned in as these images didn't exist elsewhere).
- 
- [Moby Games](https://www.mobygames.com) : A massive collection of video game meta-data with screenshots and some videos.

- [Game UI Database](https://www.gameuidatabase.com/) : A collection of video games screenshots and videos with meta-data focused around UI development.

- [Interface in Game](https://interfaceingame.com/) : A collection of video games screenshots and videos with meta-data focused around UI development, also has genre meta-data. 

- [SteamDB](https://steamdb.info/tags/) : A database of steam games with various kinds of meta-data, appears to be protected against data mining.  
  
- [Game Refinery](https://www.gamerefinery.com) : Database of mobile games with meta-data including genre/category.

- [Gameopedia](https://www.gameopedia.com/tag/game-genres/) : Anaylsis and blog posts about games and the games industry. 

- [Steampeek](https://steampeek.hu/) : A recommendation engine for similar games, contains a large database of games, meta-data, genres, screen shots and links to video content.


## Tools

### Scapers
- https://github.com/JoMingyu/google-play-scraper : python scraper for google play store
- https://github.com/facundoolano/google-play-scraper : javascript scraper for google play store


## Blog posts:

- [This AI Model Can Figure Out Video Games By Its Cover](https://analyticsindiamag.com/ai-mysteries/this-ai-model-can-figure-out-video-games-by-its-cover/) : summary of [^2]

- [Daniel Primed](https://danielprimed.com/) - a blog about game analysis, nothing in particular but maybe a nice resource for people.

- [Understanding Video Game Genres and their Box Art with a Convolutional Neural Network](https://medium.com/@nicholasabergh/understanding-video-game-genres-and-their-box-art-with-a-convolutional-neural-network-eb5677cfcc42) - THis is what I want to do but on a larger scale, maybe I should contact Nicholas Bergh and we could write a paper? 


## Papers

- [What Defines Video Game Genre? Thinking about Genre Study after the Great Divide](NO LINK) David A. Clearwater
- [Recategorization of Video Game Genres](https://commons.erau.edu/cgi/viewcontent.cgi?params=/context/publication/article/2894/&path_info=hfes_2018_game_categorization_ID472.pdf): This paper
attempts to provide various ways games could be classified by focusing on the types of
emotions they evoke, the skills they require or their relations with personality or
cognitive variables.

- [Automated Genre Classification for Gaming Videos](https://ieeexplore.ieee.org/document/9287122)
- 
- [Video Game Genres](https://www.academia.edu/16546463/Video_Game_Genres)

- [Attention guided EEG based Game Genre Classification](https://typeset.io/papers/attention-guided-eeg-based-game-genre-classification-31vknem8)

- [Enhancing game classification systems with machine learning: A comparative study on techniques and legal implications](https://typeset.io/papers/enhancing-game-classification-systems-with-machine-learning-49m3kac30b)

- [Deep learning for video game genre classification](https://typeset.io/papers/deep-learning-for-video-game-genre-classification-3safkyak): http://www.arxiv.org/abs/2011.12143
- https://core.ac.uk/download/pdf/355148614.pdf same as above?  

- [From Pixels to Titles: Video Game Identification by Screenshots using Convolutional Neural Networks](https://arxiv.org/html/2311.15963v2)

- [PlayMyData: A Curated Dataset of Multi-platform Video Games](https://dl.acm.org/doi/10.1145/3643991.3644869) (see PlayMyData dataset above)

- [The Game Genre Map: A Revised Game Classification](https://dl.acm.org/doi/10.1145/2793107.2793123)

- Difference in classifications:
by game mechanic - ludologists, by narrative - narrologists (find the reference for this)

#### TO READ

https://www.academia.edu/224767/_2009_Video_Game_Genre_Evolution_and_Innovation_journal_

https://www.academia.edu/435740/Genre_and_the_Video_Game

https://www.academia.edu/385966/Genre_and_Game_Studies_Toward_a_Critical_Approach_to_Video_Game_Genres

https://www.academia.edu/75425875/Why_Video_Game_Genres_Fail

>>> https://www.academia.edu/87530656/The_nature_of_gameplay_a_videogame_classification

https://www.academia.edu/87530638/A_Gameplay_Definition_through_Videogame_Classification

https://www.academia.edu/106865903/Play_game_world_anatomy_of_a_videogame

[Video Game Genre, Evolution and Innovation](https://septentrio.uit.no/index.php/eludamos/article/view/vol3no2-3)

Apperley, Thomas H.. "Genre and game studies". University of Melbourne. Retrieved on 2009-01-23.



https://journals.sagepub.com/doi/abs/10.1177/1046878105282278?casa_token=CtFGwZtmSsEAAAAA:GDYn37BNtP8ns3IRnAj2viKyXOA-Cckx7e7FQOhJ7VAWUwySU5p1JlG643-ORbBHQrcAuDkqFGps

https://dl.acm.org/doi/abs/10.1145/2793107.2793123?casa_token=OQp0NMu3n3YAAAAA:EVNYyF9-j5j1UfKxu5r9GeP8zxQhsLxt8a6QqJyyoOWdyTAcoNvvodzN14PamcYlhbjzSZJnI7de

#### TECHNICAL TO READ


[A preliminary network analysis on steam game tags: another way of understanding game genres](https://dl.acm.org/doi/abs/10.1145/3377290.3377300?casa_token=yLe-QB5CugoAAAAA:URatMU1SQ0ugGKTDxk1kDYMieCDGFJibTm9gm9OeL8KpPzMR26imQLOGPYP3L6YqFQLaC0TP4aVQ)

[Towards Factor-oriented Understanding of Video Game Genres using Exploratory Factor Analysis on Steam Game Tags](https://ieeexplore.ieee.org/abstract/document/9350753?casa_token=ghumnVIJmOAAAAAA:Bg_SlrauUzUd_LaTsOjuYKJoL8HQQRwM2TpVyWiPI4ExW4ctudMbxkfV4a0ocCgzCucaiM2wg-RO)


### Game Genre Classification Literature

- **TODO** Chris Crawford attempted to classify video games in his 1984 book The Art of Computer Game Design. [The first attempt to systematize video games occurred in 1984 when game designer Chris Crawford came up with a convenient classification system ... ](https://boolatplay.com/en/article/%D1%81lassification-of-game-genres)


- [The Need for Recategorized Video Game Labels: A Quantitative Approach](https://gamestudies.org/2301/articles/simonson_keebler_doherty) - talks about a way of classifying game categories/genres. NOTE: I wonder if using ml to classify games based on screen shots will lead to better categories or insights about game genre similarity. 

### OTHER INFORMATION


#### How games are classified:

- By platform: generally to the nature of the computer hardware that the game is played on and not the specific branding. This would include game genres like mobile games for smartphone, tablet computers, or other similar portable devices; and browser games that can be played in a web browser. Identification of the type of hardware a game is played on implied certain limits to the type of gameplay that is available; a mobile game will typically lack as much action compared to a game playable on a home console or computer due to limitations on player input.[^1]
- By mode: referring to whether a game is single player, multiplayer, or variations on that, including massively multiplayer online (MMO) games, cooperative games, Player versus environment (PvE) or Player versus player (PvP) games, and so forth.[^1]
- By narrative: Classifying video games by their narrative style, such as science fiction or fantasy, is typically not used within the field, with the key exception of horror games, which broadly cover any game dealing with elements of horror fiction.[^1]

- By input? (see papers)

[^1]: [HandWiki](https://handwiki.org/wiki/Video_game_genre)
[^2]: [Deep learning for video game genre classification](https://arxiv.org/pdf/2011.12143)


### Other game related artefacts

- [Steam user interaction dataset](https://www.kaggle.com/datasets/tamber/steam-video-games) : how long people played a steam game 
- [Game Mechanics as Videogame Genre Identifier][https://www.globalmediajournal.com/open-access/game-mechanics-as-videogame-genre-identifier.pdf] : "It is shown that such structural video game units, as dynamics and components, do not reveal an established connection with the category “genre” and vary from one gaming project to another. The only constant parameter, presented in video games, is mechanics that are repeated in popular projects of one genre, identifying the “face” of the genre, and its established core."