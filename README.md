# WorkingName

### WorkingName is a virtual reality application to aid in exposure therapy.


## Background & Overview

[Exposure therapy][exposure] is a technique in behavior therapy that has existed since the 1950s and is thought to help treat anxiety disorders.  Exposure therapy involves exposing the patient to the source of anxiety or a representation of it without the intention to cause harm.  According to [this study][study], exposure therapy is the most successful known treatment for phobias.  

Virtual Reality technology represents an incredible new tool for exposure therapy.  Through VR, the core principle of causing no harm to the patient is much more easily fulfilled.  Therapists also have more direct control over the intensity and type of anxiety source.  Cost of treatment is greatly reduced since anxiety sources are digital.    

We intend to create an exposure therapy VR app that will immerse our user in four of the most common phobias: Agoraphobia (fear of crowds), Acrophobia (heights), Arachnophobia (spiders), and Aquaphobia (water).

This project involves:

- Collecting pre-existing VR assets. We will not create original assets given our time constraint.
- Building a frontend interface where users can experience our VR scenes and navigate between
them with a browser or VR headset.
- Hosting our assets in a way that allows for a smooth UX.

## Functionality & MVP

- We will gather a complete set of assets (Pano image/video, sound effects, normal video) for each
of the four phobias.
- We will combine those assets into an immersive VR experience for each phobia.
- We will have a user interface that allows users to select a phobia from a main menu to enter that scene.  Once inside the scene, there will be a button for the user to return to main menu.
- Production README

#### Bonus Features

- Intensity: User or doctor can control intensity level of immersion.  This could take the form of louder sound, more renderings of the anxiety source, or more intense interactions with the anxiety source.
- Proprietary Assets: With the correct hardware (360 camera, sound recorder), assets could be even more finely tuned for exposure therapy.   

## Design Documents

### Wireframes

- [Component Hierarchy][hierarchy]


## Technologies & Technical Challenges

#### Backend:

#### Frontend:

- React
- React-VR

### Assets

[Assets][assets] were collected from various sources:
- Pano Images: [Flickr][flickr]
- 360 Video: [Youtube][youtube]
- Video: [Pixabay][pixabay]
- Sound effects: [Ambient Mixer][ambientmixer], [Soundbible][soundbible], [Zapsplat][zapsplat]


### Hosting


## UX


## Accomplished over the Weekend

- Each team member read chapters 1-4 of [this][ebook] tutorial, then implemented the app in
chapter 8 to get a sense of the React-VR structure and workflow.
- Full sets of assets (Pano image/video, sound effects, normal video) were collected for four
main phobias (spiders, heights, open water, and crowds).
- Hosted a sample pano image on Github Pages to get a sense of load times.

## Group Members & Work Breakdown

Our group consists of three members: John Lugtu, Nicholas Evans, and Mike Brinkman.

### Day 1

### Day 2

### Day 3

### Day 4

### Day 5

### Day 6


[hierarchy]: ./docs/hierarchy.md
[assets]: ./docs/ASSETS.md
[flickr]: https://www.flickr.com/groups/360degrees/
[pixabay]: https://pixabay.com/
[soundbible]: http://soundbible.com/
[zapsplat]: https://www.zapsplat.com/
[youtube]: https://www.youtube.com/
[ambientmixer]: https://www.ambient-mixer.com/
[ebook]: https://medium.com/coding-artist/learn-react-vr-chapter-1-hello-virtual-world-202241c0cb63
[exposure]: https://en.wikipedia.org/wiki/Exposure_therapy
[study]: https://en.wikipedia.org/wiki/Exposure_therapy#cite_note-17
