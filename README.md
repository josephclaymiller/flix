# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF
<img src="flix.gif" width=250><br>

### Notes
I encountered a challenge loading the images because I was using HTTP instead of HTTPS. Xcode gave an error which I researched online and found a solution was to set `Allow Arbitrary Loads` to `YES` under `App Transport Security Settings` in `Info.plist`. This removed a security requirement Xcode had in place and worked to load the images, however, I later realized that there was no need to change the app settings as I hadn't copied the base URL correctly and I actually should have been using HTTPS.
