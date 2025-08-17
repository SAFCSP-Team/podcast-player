# Podcast Player Project

## Objective
Using fundamental data structures and algorithms, solve real-world problems with a stack.

## Problem
A software development company plans to develop a podcast player system that allows users to listen to podcasts and manage playlists, your responsibility is to build a playlist tracking feature, enabling the user to keep track of their podcast playlist and navigate through it by playing new episodes or returning to previous ones.  

 
## Implementation
- Create a `playbackHistory` stack that can accommodate 10 podcasts. Each podcast should include a name, channel, speaker, guests, duration, and a category.
- Write a function `add()` to add a new podcast to the `playbackHistory` stack and print a message indicating the addition.
- Write a function `play()` to retrieve the current playing podcast info and print a message indicating that the podcast is being played. If the `playbackHistory` stack is not empty.
- Write a function `previous()` to play the previous podcast in the playback history if the `playbackHistory` stack is not empty, or it contains only one podcast. Otherwise, print a message indicating that going back is impossible. 
- Write a function `playByCategory()` to search through the `playbackHistory` for the first podcast that matches the specified category and play it. If the `playbackHistory` stack is empty or no matching podcast is found, print a message indicating that no match was found.
- Write a function `printALL()` to print all podcast names in the `playbackHistory`.
- In the main method:
  - Add 10 podcasts to the playback history.
  - Print the initial playback history.
  - Play the most recently added podcast.
  - Go back to the previous podcast.
  - Print the updated playback history.
  - Search for and play two podcasts from different categories, ensuring that one of the categories does not exist.

``` java
public class PodcastPlayer {
    public static void main(String[] args) {
      /* add your code here */
    }

}
```
## Qualification to pass
- [ ] The code should run successfully.
- [ ] Write all required functions correctly.
- [ ] Completely define the `Podcast` class.
- [ ] Completely define  the `PodcastPlayer` class.
