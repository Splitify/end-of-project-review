---
title: "Splitify | End of Project Sprint Review"
layout: "bundle"
outputs: ["Reveal"]
---

![](https://splitify.github.io/branding/textmark/textmark@150.png)

End of Project Sprint Review

---

### Development Incidents

{{% section %}}

#### Time Allocation for Grouping

* Code refactor delayed progress for grouping
  * Critical path
* Story point estimation for grouping

<!-- The last sprint required a change in the backend structure to better integrate the other features of the web application. Unfortunately this created a critical path which we could not execute on. -->

<!-- 
While not strictly a blocker, grouping was started late as it reused code from deleting. The deleting feature ran over time due to our backend architecture changing and needing to redo deleting after running into problems.  -->

<!-- Furthermore, the points for grouping were poorly estimated as we did not take into account how many other components grouping would interact with and the subsequent time that would be needed to handle all edge cases. -->

---

#### Spotify API Completeness

* Spotify's API doesn't include `genre` data in each Track
* Only available in the Artist
* Not good!
* Used Last.fm instead

<!-- Spotify's API documentation stated that genre data was available for each track.
However, no genre data was attached to the track data responses. Consequently genre data would have to be sourced from the artist's genre information - which may include genres incorrect to a specific track.

Instead, the Last.fm API was used to source genre information, specific to each track. -->

---

### User Feedback

Received feedback from a beta tester, and other members of the tutorial group who suggested making changes to the functionality of the application, such that it would be more useful and straightforward to an actual project user.

{{% /section %}}

---

### What went poorly

* Grouping
* Spotify API documentation - genre data (Last.fm)
* Pivotal feature availability
* Pivotal software bugs
  * Arbitrary iteration planning
  * Had to apply a manual velocity override which would reset each time pivotal was reloaded

---

### What Went Well

* Our epics were mostly satisfied.
* Pivotal gave us a guide on how much work should be done per week
* Pull Request templates and deploy previews
* Got user feedback

---

### Advertised Features

* Splitting of large playlists by track information ✓
* Spotify account integration ✓
* Track visualisation  ✓
* Reorganise sub-playlists ✓
* Tracks can be grouped for easier bulk edits

---

### Additional Features

* Select multiple playlists
* Genre selection
* Track list count and genre count
* Playlist for Liked Songs

---

### Timeline

{{% section %}}

|Projected|Actual|
|:---:|:---:|
|![](timeline_projected.png)|![](timeline_current.png)|

<!-- ---

### Release Roadmap

* Beta (Week 6) - Application that allows the user to log in, split, sort and filter playlists and sync it back to their account. **Delayed to Week 7**

* Release (Week 8) - Application that allows the user to log in, split, sort, filter, and group tracks, with account synchronisation. **Delayed to Week 9** -->

{{% /section %}}