# MusicService
## LogIn Page
![image](https://user-images.githubusercontent.com/70820223/221909037-b923b9b4-9850-4e77-bd9e-14957a41eed9.png)
## Main Page
![image](https://user-images.githubusercontent.com/70820223/223456492-3350fb54-7c5f-4704-aae9-952f92dfe42d.png)
## Track Switch
![image](https://user-images.githubusercontent.com/70820223/223456663-a0b9ee68-8bf7-4235-ba11-e6aaa1d86616.png)
## Main Function
- Sign In<br>
  Method — "POST"<br>
  Params — __username__ string, __password__ string<br>
  Returns a response to a login request<br>

- Shuffle songs<br>
  Method — "GET"<br>
  Returns a list of songs in random order<br> 

- Repeat song/playlist<br>
  Method — "GET"<br>
  Return the repeat of the track or songs in the playlist<br>

- Sleep timer<br>
  Method — "POST"<br>
  Return the end of the playback after a period of time<br>

- Get card of artist by Id<br>
  Method —  "GET"<br>
  Params — __ArtistId__ int<br>
  Return a list of matches with request<br>

- Get songs by Id<br>
  Method — "GET"<br>
  Params — __UserId__ int<br>
  Returns a list of user's songs<br>

- Get playlists by Id<br>
  Method — "GET"<br>
  Params — __UserId__ int<br>
  Returns a list of user's playlists<br>

- Add playlist<br>
  Method — "POST"<br>
  Params — __PlaylistId__ int, __PlaylistTitle__ string, __AuthorName__ string<br>
  Returns a result of the request

- Update playlist<br> 
  Method — "PUT"  
  Params — __PlaylistId__ int, __PlaylistTitle__ string  
  Returns the result of the request 

- Delete playlist<br>
  Method — "DELETE"<br>
  Params — __PlaylistId__ int<br>
  Returns the result of the request

- Find playlists and songs<br>
  Method — "GET"<br>
  Params — __Title__ string<br>
  Returns a list of songs or playlists

- Switch song<br>
  Method — "GET"<br>
  Params — __Id__ int<br>
  Returns other song by id

# Data-Models
## Data to login
Data required for authorization:
- __username__ string
- __password__ string

## Song Data
Info about song:
- __Id__ int
- __SongTitle__ string
- __AuthorName__ string
- __Duration__ date 

## Artist Data
Info about artist:
- __Id__ int
- __Name__ string
- __Mediateka__ array of songs & playlists
## Playlist Data
Info about playlist:
- __Id__ int
- __PlaylistTitle__ string
- __UserName__ string
- __Duration__ date 
