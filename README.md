# MusicService
## LogIn Page
![image](https://user-images.githubusercontent.com/70820223/221909037-b923b9b4-9850-4e77-bd9e-14957a41eed9.png)
## Main Page
![image](https://user-images.githubusercontent.com/70820223/221908900-e1b8382e-dfe5-4245-8c5a-a83ff03aa995.png)
## Track Switch
![image](https://user-images.githubusercontent.com/70820223/221909150-996172e7-08f4-4750-878c-d3ddba5d29cb.png)
## Main Function
- Sign In<br>
  Method — "POST"<br>
  Params — __username__ string, __password__ string<br>
  Returns a response to a login request<br>

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

## Playlist Data
Info about playlist:
- __Id__ int
- __PlaylistTitle__ string
- __UserName__ string
- __Duration__ date 
