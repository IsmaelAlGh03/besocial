# BeSocial

> Discover nearby events. See who's going. Know the vibe before you arrive.

BeSocial is a social platform that lets you find local events and leisure — and connects them to your actual taste in music. Link your Spotify account and the app matches events to the genres you actually listen to. See which friends are attending before you commit.

Built as a final-year project for the DAW programme at Institut Pedralbes (2022–2023), deployed to production on Oracle Cloud.

[![Demo](https://img.youtube.com/vi/ubZ5rnnv8SI/maxresdefault.jpg)](https://youtu.be/ubZ5rnnv8SI)

---

## Features

- **Event discovery with geolocation** — browse events near you on an interactive map
- **Spotify integration** — link your account to get events matched to your listening habits and favourite genres
- **Friend attendance** — see which of your friends are going to each event before you decide
- **Social layer** — follow friends, manage your profile, interact with the community

---

## Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | React · JavaScript |
| Backend | Laravel (PHP) |
| Database | MySQL |
| Real-time | WebSockets |
| Auth | Laravel Auth · Google OAuth |
| External API | Spotify Web API |
| Deployment | Oracle Cloud |

---

## Project Structure

```
web/
├── front/   # React SPA
└── back/    # Laravel API
doc/         # Full project documentation (PDFs + videos)
```

---


 Documentation

  The doc/ folder contains the full project documentation produced during development:

  - User Manual (doc/Manual%20d'usuarí_BeSocial.pdf)
  - Component Diagram (doc/Diagrama%20de%20components.pdf)
  - Sprint Planning (doc/Planificació%20dels%20Sprints.pdf)
  - Deployment Manual (doc/Manual%20desplegament.pdf)
  - Project Evolution & Problem Log (doc/Evolució%20del%20projecte%2C%20problemes%20i%20solucions.pdf)
  - Elevator Pitch (doc/BeSocial%20-%20Elevator%20Pitch.mp4)

  ---
  Team

  Built by Ismael Al Ghani (https://github.com/IsmaelAlGh03), Damià Brea, Arnau Català, and Lucas Costa.

  ---

  ▎ ⚠️ Production deployment (besocial.cat) is no longer live.

  ---

   ## Note

  This was a school project built in 2023. The production deployment is no longer live and local setup is not guaranteed
   to work out of the box. The code is available for reference.
