# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF
<img src="http://g.recordit.co/KBTRwFwJXU.gif" width=250><br>
<img src="http://g.recordit.co/swsc5XmSrh.gif" width=250><br>

### Notes
I ran into an issue where I could not do the af.setImage for my image because I had my posterView outlet set to something other than the UIImageView. I searched on the CodePath Slack and was able to resolve that issue :)

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="http://g.recordit.co/MeU49cM7uf.gif" width=250><br>
<img src="http://g.recordit.co/AnqnYYJXIx.gif" width=850><br>
<img src="https://i.imgur.com/FlL4jxR.png" width=850><br>

### Notes
Making this app was I had some issues with my ruby install and getting cocoapods to work. The `pod init` command wasn't working but that is fixed now. Getting auto layout to work was tricky, I don't think my layout is working perfectly yet but it is almost there.
