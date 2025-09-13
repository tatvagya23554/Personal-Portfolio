# Personal-Portfolio
<!-- ## [View Deploy](https://personal-portfolio-beta-khaki-75.vercel.app/) -->
## <a href="https://personal-portfolio-beta-khaki-75.vercel.app/" target="_blank" rel="noopener noreferrer">View Deploy</a>

### <a href="https://drive.google.com/file/d/1aEOawOSw5ecn6PIuvYLtiFbhlyfplE-k/view?usp=sharing" target="_blank" rel="noopener noreferrer">Know the Portfolio Design</a>


### Directory Structure:
```text
├── README.md
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── public/
│   ├── images/
│   │   ├── Favicon.png
│   │   ├── arrow-down.svg
│   │   ├── arrow-right.svg
│   │   ├── bg.png
│   │   ├── chat.png
│   │   ├── client1.png
│   │   ├── client2.png
│   │   ├── client3.png
│   │   ├── client4.png
│   │   ├── client5.png
│   │   ├── client6.png
│   │   ├── code.svg
│   │   ├── concepts.svg
│   │   ├── designs.svg
│   │   ├── devices.png
│   │   ├── exp1.png
│   │   ├── exp2.png
│   │   ├── exp3.png
│   │   ├── fb.png
│   │   ├── git.svg
│   │   ├── gold-star.png
│   │   ├── ideas.svg
│   │   ├── insta.png
│   │   ├── linkedin.png
│   │   ├── logo1.png
│   │   ├── logo2.png
│   │   ├── logo3.png
│   │   ├── logos/
│   │   │   ├── JUnit.png
│   │   │   ├── angular.png
│   │   │   ├── company-logo-1.png
│   │   │   ├── company-logo-10.png
│   │   │   ├── company-logo-11.png
│   │   │   ├── company-logo-2.png
│   │   │   ├── company-logo-3.png
│   │   │   ├── company-logo-4.png
│   │   │   ├── company-logo-5.png
│   │   │   ├── company-logo-6.png
│   │   │   ├── company-logo-7.png
│   │   │   ├── company-logo-8.png
│   │   │   ├── company-logo-9.png
│   │   │   ├── express.png
│   │   │   ├── git.svg
│   │   │   ├── kafka.png
│   │   │   ├── mongo.png
│   │   │   ├── next.png
│   │   │   ├── node.png
│   │   │   ├── postgresql.png
│   │   │   ├── python.svg
│   │   │   ├── react.png
│   │   │   ├── spring_boot.png
│   │   │   └── three.png
│   │   ├── menu.svg
│   │   ├── mongo.svg
│   │   ├── person.png
│   │   ├── project1.png
│   │   ├── project2.png
│   │   ├── project3.png
│   │   ├── python.svg
│   │   ├── readme-bottom.png
│   │   ├── readme-video-kit.png
│   │   ├── readme.png
│   │   ├── screen.mp4
│   │   ├── seo.png
│   │   ├── star.png
│   │   ├── textures/
│   │   │   └── mat1.png
│   │   ├── time.png
│   │   ├── x.png
│   │   └── x.svg
│   ├── models/
│   │   ├── Optimized-room.jsx
│   │   ├── aws.glb
│   │   ├── computer-optimized-transformed.glb
│   │   ├── computer-optimized.glb
│   │   ├── docker.glb
│   │   ├── git-svg-transformed.glb
│   │   ├── java.glb
│   │   ├── node-transformed.glb
│   │   ├── optimized-room.glb
│   │   ├── python-transformed.glb
│   │   ├── react_logo-transformed.glb
│   │   └── three.js-transformed.glb
│   └── vite.svg
├── src/
│   ├── App.jsx
│   ├── components/
│   │   ├── AnimatedCounter.jsx
│   │   ├── Button.jsx
│   │   ├── ExpContent.jsx
│   │   ├── GlowCard.jsx
│   │   ├── NavBar.jsx
│   │   ├── TitleHeader.jsx
│   │   └── models/
│   │       ├── contact/
│   │       │   ├── Computer.jsx
│   │       │   └── ContactExperience.jsx
│   │       ├── hero_models/
│   │       │   ├── HeroExperience.jsx
│   │       │   ├── HeroLights.jsx
│   │       │   ├── Particles.jsx
│   │       │   └── Room.jsx
│   │       └── tech_logos/
│   │           └── TechIconCardExperience.jsx
│   ├── constants/
│   │   └── index.js
│   ├── index.css
│   ├── main.jsx
│   └── sections/
│       ├── Contact.jsx
│       ├── Experience.jsx
│       ├── FeatureCards.jsx
│       ├── Footer.jsx
│       ├── Hero.jsx
│       ├── LogoShowcase.jsx
│       ├── ShowcaseSection.jsx
│       ├── TechStack.jsx
│       └── Testimonials.jsx
└── vite.config.js
```


### Terminal commands to set up locally:

`git clone https://github.com/tatvagya23554/Personal-Portfolio.git`

`cd Personal-Portfolio`

npm create vite@latest ./ --> y --> Remove existing files and continue --> set package name --> React --> JavaScript

npm install --> npm run dev
npm install gsap @gsap/react three @react-three/fiber @react-three/drei @react-three/postprocessing --> npm install tailwindcss @tailwindcss/vite

cd ./public/models --> ls --> npx gltfjsx optimized-room.glb
npm i @emailjs/browser --> npm i react-responsive --> npm install react-countup

<!--
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
-->
