


![Act](https://www.vincentriva.fr/Act.svg)
# Act
Act is a contemplative and poetic adaptation of books in VR.

- [Requirements](#requirements)
- [Setup](#setup)
- [Project](#project-structure)
- [Conventions](#conventions)
- [Rules](#rules)
- [Librairies](#libraries)
- [Diagrams](#diagrams)
- [Credits](#creadits)
- [License](#license)

## Requirements
- Windows 7 SP1+ or newer, 64 bits only.
- MacOS 10.9+

## Librairies
- Unity 2017.3+
- Google VR SDK 1.130+
- Google Resonance 1.2.1+

## Setup
- Download Unity 2017.3 or newer version.
[https://unity3d.com/fr/get-unity/download](https://unity3d.com/fr/get-unity/download)
- Clone the project (or download the zip file)
 `git clone https://github.com/XXX/act-noir`
- Go the directory and open the first scene `Assets/Scenes/Act1.unity`

## Project structure
```
├── Animations
├── Materials
├── Models
├── Packages
    ├── GoogleVR
    ├── ResonanceAudio
├── Prefabs
├── Resources
├── Scenes
├── Scripts
├── Shaders
├── Sounds
├── Textures
```

## Conventions
- Each asset **must** be placed in the correct folder.
- Each asset **must** be prefixed by his type (`MAT_` for materials, `SHD` for shaders etc...)
- You **must** give a comprehensive name to each asset.
- You **must** create prefabs if an element is used twice or more.

## Rules
If you're interrested in creating your own Act project, here some rules that we strongly recommend to follow :
### Story
- You **shouldn't** restrict yourself about a story because of its complexity.
- You **must** advice for explicit or mature content **BEFORE** the download (e.g. in App Store description).
- You **should** be adapting a poetic, fictionnal or biographic story.
- You **should** be writing at the first person.

#### For a long story
- The story **must** have between 300 (three hundred) and 2000 (two thousands) words.
- If your story has more than 450 (four hundred fifty) words, then you **must** divide it by acts.
- An act **must** have between 200 (two hundred) and 400 (four hundred) words.

#### For a condensed story
- Your story **must** have between 300 (three hundred) and 500 (five hundred) words.

### Adaptation
- The story **must** be presented with several mediums (e.g. text, picture, sound, narrator etc...)
- Graphics and sound design **must** be minimalist and abstract.
- The story **must** be narrated by an external voice actor.
- 
#### For a long story
- The experiment **must** be around 5 (five) minutes long.
- The experiment **should** have around 3 interactions with the user.

#### For a condensed story
- The experiment **should** be below 15 (fifteen) minutes long.
- Each act **must** be around 4 (four) minutes long.
- Each act **should** have 1 or 2 interactions.

#### Animations
- Interactions **must** be based on vision (e.g. not using the Cardboard button).
- Transitions **must** be fluid.
- Elements **must** guide the user through the experiment.

#### Sound design
- Sounds **must** be spatialized.
- Sounds **must** guide the user through the experiment.
- Voices **should** be adapted to the story.

## Diagrams
![UML Class Diagram](https://www.vincentriva.fr/Act.jpg)

## Credits
Act is owned by :
- Marie Reyboz (Project Manager, UX/UI Designer)
- Sarah Hulsken (UX/UI Designer)
- Gweltaz Calori (Developer)
- Vincent Riva (Developer)

## License
Act is released under the Attribution-NonCommercial-ShareAlike 4.0 International license (CC BY-NC-SA 4.0).