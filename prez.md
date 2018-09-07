class: center, middle

# A-Frame: Pro Mode

---

# Who is this guy?

- Brian Chirls
- NYC, US
- Does code (web), media
- CTO, Datavized, data-driven immersive media
- Likes humans, chocolate, kung fu

---

# What is Pro Mode?

- Robust Experience
- Robust Tech
- Clean, maintainable code

---

# UN/SDG Project Goals

- Clean up scene
- Easy scene-editing in A-Frame Inspector
- Improve controls (mouse, touch, VR)
- High performance and reliability

---

# Clean Scene

- Build custom A-Frame component
- Generate scene procedurally
- Easy to change w/ constants or parameters
- Perfect mathematical geometries
- Don't Repeat Yourself (DRY)
  - repeated code in functions or loops

---

# Adjusting Scene

- A-Frame Inspector
- Component schema parameters shape the scene as a whole
- Fine-tune object spacing
- 3DOF vs. 6DOF
- No motion sickness pls

---

# Better controls

- VR Controls
- Gaze cursor
- Automatic selection
  - Custom component disables gaze cursor when hand controls detected

---

# Performance

- Optimize Assets
  - Audio: mp3/aac/opus. Mono if appropriate
  - Images: JPG/PNG. Powers of Two
- Webpack
  - Minify in production
  - loaders for file types
  - Hard to configure, can fine-tune forever
- Service Workers: Offline
  - Workbox w/ webpack plugin
- Chrome Dev Tools and Lighthouse
  - 7.4MB @ 5.1 sec => 1.7MB @ 2.4 sec

---

# Bonus Round!

- Web App Manifest - installable app
- Google Analytics
- WebVR Links

---

# Code Tips

- Strict Lint Rules
- Always clean up after yourself
  - full object life cycle (create, update, destroy)
  - see A-Frame, React

---

# Development Set-Up

- Git
  - Issue tracking
  - Thorough documentation and tracking of changes
  - Great back-up tool
  - Collaboration
- Webpack Dev Server
  - Everything running local
  - Watch changes
  - write in latest JS features
- ESLint
  - Checking for code style and obvious screw-ups
  - "Code smell"

---

# Development Set-Up (2)

- Webpack Production build
  - Transpile to ES5
  - Compact and uglify code
  - Load A-Frame from CDN
  - Generate Service Worker
- Deploy
  - Firebase hosting CDN
  - Deploy in one line
  - Config stored in git (except secrets)

---

# Tools

- [A-Frame](https://aframe.io)
- [NPM](http://npmjs.com/)
- [ESLint](http://eslint.org/)
- [Webpack](https://webpack.js.org/)
- [Workbox](https://developers.google.com/web/tools/workbox/)

---

# Future/Wish List

- Even better controller UX
- AR via WebXR API
- A-Frame Inspector in VR?
- Better hot reloading
- Unit Tests

---

# Questions?

---

# Thank you

## Follow
- [@bchirls](http://twitter.com/bchirls), [@datavized](http://twitter.com/datavized)

## Work
- [datavized.com](http://datavized.com)

## Code
- [github.com/datavized](http://github.com/datavized)
- [github.com/brianchirls](http://github.com/brianchirls)