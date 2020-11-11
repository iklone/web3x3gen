# Web 3x3 Generator

3x3 anime/manga generator for MAL using the Jikan API. Now online and in JS.
 
Based on my previous python-based 3x3gen.
 
Live version here: http://3x3.iklone.org
 
### Basic Variables:
- MAL Username: MAL profile to build grid from.
- Grid Type: What to put in the grid (anime/manga/characters/people).
- Grid Source: Where to get data from (favourites/list). Note that type characters/people grids can only be generated from source favourites.
- Grid Size: How wide/tall the grid will be in units. Eg: 3 will build a 3x3 grid, 10 will build a 10x10.

 ### Advanced Variables *(list source only)*:
- Aired Between Dates: Only include anime/manga that aired between certain dates.
- Completed Between Dates: Only include anime/manga that you completed between certain dates (requires relevant data on your account).
- Specify Studio: Only include anime/manga from a specific studio/production company/magazine.
- Specify Genre: Only include anime/manga that have a specified genre listed for them. The list of MAL genres can be seen [here](https://myanimelist.net/anime.php) for anime and [here](https://myanimelist.net/manga.php) for manga.
- User Recommendation: Will not include anime/manga that this specified user has on their list already. Can be used to generate recommendation lists for other users.
