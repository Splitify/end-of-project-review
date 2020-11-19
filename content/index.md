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

#### Spotify API Completeness

Spotify's API documentation stated that genre data was available for each track.
However, no genre data was attached to the track data responses. Consequently genre data would have to be sourced from the artist's genre information - which may include genres incorrect to a specific track.

Instead, the Last.fm API was used to source genre information, specific to each track.

---

### User Feedback

Received feedback from a beta tester, and other members of the tutorial group who suggested making changes to the functionality of the application, such that it would be more useful and straightforward to an actual project user.

---

#### Time Allocation for Grouping

The last sprint required a change in the backend structure to better integrate the other features of the web application. Unfortunately this created a critical path which we could not execute on.

<!-- 
While not strictly a blocker, grouping was started late as it reused code from deleting. The deleting feature ran over time due to our backend architecture changing and needing to redo deleting after running into problems.  -->

Furthermore, the points for grouping were poorly estimated as we did not take into account how many other components grouping would interact with and the subsequent time that would be needed to handle all edge cases.

{{% /section %}}

---

### What went poorly

* Spotify lacking updated documentation - see genre data above (Last.fm)
* See grouping paragraph above
* We didn’t use the rejection feature on pivotal

* Pivotal software bugs
  * Iteration planning was execute automatically even though it was disabled
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
* Drag 'n drop inter-playlist track management ✓
* Tracks can be grouped for easier bulk edits ✓
* Sorting and filtering of playlists ✓

---

### Additional Features

* Track information (track feature graphical visualisation)
* Track audio preview (for available tracks)
* Unused genre hint

---

### Timeline

{{% section %}}

|Projected|Actual|
|:---:|:---:|
|![](timeline_projected.png)|![](timeline_current.png)|

---

### Release Roadmap

* Beta (Week 6) - Application that allows the user to log in, split, sort and filter playlists and sync it back to their account. **Delayed to Week 7**

* Release (Week 8) - Application that allows the user to log in, split, sort, filter, and group tracks, with account synchronisation. **Delayed to Week 9**

{{% /section %}}