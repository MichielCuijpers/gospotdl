[![BCH compliance](https://bettercodehub.com/edge/badge/MichielCuijpers/gospotdl?branch=main)](https://bettercodehub.com/)

# [WIP]GoSpotDl
A Golang implemetation of spotdl (Python) 

I am learning go and thought implementing spotdl would be a good learning experience.

**Btw this is nowhere near as good as the [original](https://github.com/spotdl/spotify-downloader).**

## Usage
1 - Get the package
  - `$ go get -u github.com/s1as3r/gospotdl`

2 - Install the package
  - `$ go install github.com/s1as3r/gospotdl`

3 - Enjoy  
  - `$ gospotdl $spotifylink` 

*Alternatively*:

1 - Clone this repo
  - `$ git clone https://github.com/s1as3r/GoSpotDl`

2 - Install the Dependencies
  - `$ cd GoSpotDl`
  - `$ go get -d ./...`

3 - Build GoSpotDl
  - `$ go build`

4 - Enjoy
  - `$ ./gospotdl $spotifylink`

  
**Note: If you get 0 matches found error, then replace the provided ytapi key with your own in provider.go**

## To-Do
- [ ] Change to YTMusic Api.
- [ ] Tests.
- [ ] Fix ProgressBar when downloading multiple songs.
- [x] Parallel Downloads.
- [ ] Download best audio avaiable.
- [ ] Documentation.
