# About

VideoGeox is a browser extension that allows you to find out, where a YouTube video was located.
This is helpful for the viewer, who might always have wondered, where this music video was filmed.

It is should also be possible to contribute to the project, allowing people to themselves figure out a location where a video was recorded, and letting them add that in. 

---

# Roadmap

### Database and Backend

* SQLite database for tracking metrics
* allow for API endpoints

### Extension

* Build a simple extension, allowing to retrieve a location
* Allowing the addition of locations

### Publishing

* Implement moderation policy
* Exit local development phase

---

# Content Moderation

With supposibly anyone being allowed to add locations to anything, content moderation becomes an issue. Imagine a scenario where someone marks a creators home. Unrelated if the creator has recorded the video in said place, this should not be possible.
To avoid such a scenario it has to be thought about how to prevent this. The extension is meant to reveal locations that show public places, say that you can figure the street where your favorite music video was located.

### Possible approaches

* Big creators: Only allow for large channels and videos with a high viewercount to be annotated
* Rought location: Only display the rought location. Not ideal.
* Verified users: A users first {x} annotations would have to be verified by hand before they are shown to others.
* Whitelisting: Whitelisting of creators or even videos.
