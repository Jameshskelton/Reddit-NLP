# Reddit-NLP
The goal of this product is to use comments from Reddit.com to create a predictor for which subreddits a selection of text data would most likely to be posted on. 

Progress log: 

Got all data from https://github.com/linanqiu/reddit-dataset, using the uncleaned comments.csv linked to mega.nz

loaded data into jupyter notebook

first did eda: 
- total unique words: 18028 unique terms in data set. 
- 5 most common: 
 'like': 72197,
 'would': 51022,
 'really': 42645,
 'movie': 41400,
 'time': 38655,
 
- there are 7 metas: 'news': 408716, 'lifestyle': 384494, 'learning': 271179, 'humor': 382197, 'entertainment': 379414, 'television': 321794, 'gaming': 578206

- There are 51 unique subreddits: libertarian': 32895, 'politics': 94086, 'worldnews': 79163, 'offbeat': 24199, 'news': 81744, 'truereddit': 35294, 'conspiracy': 35197, 'conservative': 26138, 'frugal': 61664, 'motorcycles': 51482, 'sex': 46711, 'drunk': 21924, 'food': 31976, 'lifehacks': 68451, 'guns': 51530, 'progresspics': 50756, 'askscience': 21626, 'science': 35091, 'explainlikeimfive': 27319, 'askhistorians': 10181, 'youshouldknow': 79478, 'todayilearned': 74759, 'space': 22725, 'circlejerk': 17553, 'facepalm': 47129, 'jokes': 30174, 'adviceanimals': 101628, 'funny': 134469, 'imgoingtohellforthis': 51244, 'movies': 98712, 'harrypotter': 35040, 'music': 47737, 'anime': 90183, 'comicbooks': 53760, 'starwars': 53982, 'doctorwho': 33711, 'community': 41364, 'breakingbad': 34258, 'thewalkingdead': 73409, 'startrek': 42708, 'mylittlepony': 23939, 'gameofthrones': 43233, 'himym': 29172, 'tf2': 47031, 'dota2': 106696, 'leagueoflegends': 149763, 'minecraft': 33384, 'pokemon': 64448, 'gaming': 88282, 'skyrim': 35168, 'starcraft': 53434
