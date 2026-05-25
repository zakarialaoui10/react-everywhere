<div align="center">

# ⚛️ React Everywhere

</div>

> _Any application that can be written in ~~JavaScript~~ **React**, will eventually be written in ~~JavaScript~~ **React**._

React has become the default choice for AI when starting a new project. But its reach extends far beyond building web UIs. This repository collects the most **unexpected, non-obvious, and boundary-pushing** things you can build with React: from rendering video frames and generating PDFs, to controlling hardware and shipping Smart TV apps. If it can be described as a tree of components, React has probably been there already.

---

## 🧭 Table of Contents

- [🎬 Video & Animation](#-video--animation)
- [🖥️ Terminal & CLI](#️-terminal--cli)
- [🎨 Design Tools](#-design-tools)
- [📄 Documents & Emails](#-documents--emails)
- [🎵 Audio & Music](#-audio--music)
- [🎮 Games & Interactive Graphics](#-games--interactive-graphics)
- [🌐 3D & WebGL](#-3d--webgl)
- [📺 TV & Big Screens](#-tv--big-screens)
- [🔌 Hardware & Physical World](#-hardware--physical-world)
- [🥽 XR, VR & Spatial Computing](#-xr-vr--spatial-computing)
- [🗺️ Maps & Geo](#️-maps--geo)
- [🤖 AI & LLM Interfaces](#-ai--llm-interfaces)
- [📊 Data Visualization](#-data-visualization)
- [🧩 Node-Based Editors](#-node-based-editors)
- [🌀 Generative Art & Creative Coding](#-generative-art--creative-coding)
- [🧪 Custom Renderers & Experimental Targets](#-custom-renderers--experimental-targets)
- [🤝 Contributing](#-contributing)

---

## 🎬 Video & Animation

React as a video production engine. Components describe frames, timelines, and motion — then get rendered to actual video files or animated sequences.

| Project                                              | Description                                                                                                              |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [Remotion](https://github.com/remotion-dev/remotion) | Programmatic video creation with React. Define animations as components and render them to MP4 using a headless browser. |
| [React Spring](https://react-spring.dev/)            | Physics-based spring animation library that models real-world motion in UI.                                              |
| [Framer Motion](https://www.framer.com/motion/)      | Production-grade declarative animation library with gesture support and layout transitions.                              |

---

## 🖥️ Terminal & CLI

React's component model, hooks, and Flexbox layout — applied to the terminal. Build rich, interactive CLI tools as declarative component trees instead of imperative string manipulation.

| Project                                                         | Description                                                                                                              |
| --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [Ink](https://github.com/vadimdemedes/ink)                      | A React renderer for interactive command-line interfaces. Used in production by Gatsby, Parcel, Yarn 2, and Claude Code. |
| [react-blessed](https://github.com/Yomguithereal/react-blessed) | A React renderer targeting the `blessed` terminal UI library, enabling complex TUI layouts.                              |
| [Pastel](https://github.com/vadimdemedes/pastel)                | A minimal CLI framework built on top of Ink, inspired by Next.js routing conventions.                                    |

---

## 🎨 Design Tools

React components as the source of truth for design files. Instead of maintaining design and code separately, these tools render JSX directly into design tools.

| Project                                                      | Description                                                                                            |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| [React Figma](https://github.com/react-figma/react-figma)    | A React renderer for Figma. Render React components directly into the Figma canvas via the Plugin API. |
| [react-sketchapp](https://github.com/airbnb/react-sketchapp) | Render React components to Sketch documents, originally built by Airbnb to manage their design system. |
| [Spectacle](https://github.com/FormidableLabs/spectacle)     | A presentation framework that lets you build slide decks as React component trees.                     |

---

## 📄 Documents & Emails

PDF generation, Word documents, and transactional HTML emails — authored as JSX and rendered server-side or in the browser.

| Project                                                          | Description                                                                                                                |
| ---------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| [@react-pdf/renderer](https://github.com/diegomura/react-pdf)    | A React renderer that produces PDF files. Supports flexbox-based layout, fonts, images, and SVG.                           |
| [react-print-pdf](https://github.com/OnedocLabs/react-print-pdf) | PDF generation from React components with support for page breaks, headers, footers, and print-ready output.               |
| [react-email](https://react.email/)                              | Build responsive, cross-client HTML emails using React components. Adopted by Vercel, Resend, and Linear.                  |
| [docx](https://github.com/dolanmiu/docx)                         | Generate `.docx` Word documents programmatically from JavaScript, composable with React for templated document generation. |

---

## 🎵 Audio & Music

Declarative audio graphs, sequencers, and synthesizers. React's state and lifecycle management applied to the Web Audio API.

| Project                                                                 | Description                                                                                             |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| [Reactronica](https://reactronica.com/)                                 | React components for sequencing and playing music in the browser, built on the Tone.js audio framework. |
| [React Music](https://github.com/FormidableLabs/react-music) (archived) | Declarative music composition with React — define songs as component trees.                             |

---

## 🎮 Games & Interactive Graphics

React's reconciler managing game state, physics simulations, and 2D canvas scenes. Not the conventional path — but a proven one.

| Project                                                        | Description                                                                                                                               |
| -------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| [react-konva](https://konvajs.org/docs/react/)                 | React bindings for the Konva 2D canvas library. Build interactive canvas scenes with shapes, drag-and-drop, and events — all declarative. |
| [react-three-game](https://github.com/prnthh/react-three-game) | A game engine built on react-three-fiber, featuring physics integration, transform gizmos, and a level editor UI.                         |

---

## 🌐 3D & WebGL

Entire Three.js scenes expressed as JSX. Cameras, lights, meshes, and shaders — all managed through the React reconciler.

| Project                                                          | Description                                                                                                       |
| ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| [react-three-fiber](https://github.com/pmndrs/react-three-fiber) | A React renderer for Three.js. Compose 3D scenes declaratively and integrate them with React state and hooks.     |
| [Drei](https://github.com/pmndrs/drei)                           | A growing collection of useful abstractions for react-three-fiber: cameras, controls, shaders, loaders, and more. |
| [react-babylonjs](https://github.com/brianzinn/react-babylonjs)  | React bindings for Babylon.js, an alternative full-featured 3D engine with physics, GUI, and asset loading.       |
| [Leva](https://github.com/pmndrs/leva)                           | A React-first GUI panel for real-time tweaking of values in 3D scenes and creative applications.                  |

---

## 📺 TV & Big Screens

React running on constrained hardware, d-pad navigation, and living room screens. The same component model — a completely different context.

| Project                                                                                              | Description                                                                                                                        |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| [React Native for tvOS / Android TV](https://github.com/react-native-tvos/react-native-tvos)         | Official support for deploying React apps to Apple TV and Android TV, with focus management adapted for remote control navigation. |
| [react-tv](https://github.com/raphamorim/react-tv) (archived)                                        | A React renderer optimized for low-memory Smart TV platforms including LG WebOS and Samsung Tizen.                                 |
| [React Native Multi-TV App Sample](https://github.com/AmazonAppDev/react-native-multi-tv-app-sample) | Amazon's reference implementation for a cross-platform TV app targeting Android TV, Fire TV, tvOS, and web from a single codebase. |

---

## 🔌 Hardware & Physical World

React's reconciler applied to physical hardware interfaces. Describe the desired state of pins and peripherals as components — let React figure out the diff.

| Project                                                       | Description                                                                                                                                 |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| [react-hardware](https://github.com/iamdustan/react-hardware) | A React renderer for hardware devices. Expresses GPIO pin states and interactions as React components, targeting Arduino-compatible boards. |

---

## 🥽 XR, VR & Spatial Computing

WebXR rendered through React. Immersive environments and spatial interfaces described as declarative component trees.

| Project                                                                  | Description                                                                                                          |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
| [@react-three/xr](https://github.com/pmndrs/xr)                          | WebXR support for react-three-fiber. Build VR and AR experiences for Meta Quest and other WebXR-compatible headsets. |
| [react-unity-webgl](https://github.com/jeffreylanters/react-unity-webgl) | Bidirectional communication between a React application and an embedded Unity WebGL build.                           |

---

## 🗺️ Maps & Geo

High-performance geospatial rendering with React. WebGL-accelerated tiles, layers, and visualizations at scale.

| Project                                               | Description                                                                                                         |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| [react-map-gl](https://github.com/visgl/react-map-gl) | React wrapper around Mapbox GL JS and MapLibre, with support for layers, controls, and camera transitions.          |
| [Deck.gl](https://deck.gl/)                           | WebGL-powered geospatial data visualization framework by Uber, designed for large datasets and real-time rendering. |
| [react-leaflet](https://react-leaflet.js.org/)        | React components for Leaflet.js maps, well-suited for standard interactive mapping use cases.                       |
| [Kepler.gl](https://kepler.gl/)                       | Open-source geospatial analysis tool built with React and Deck.gl, supporting large-scale data exploration.         |

---

## 🤖 AI & LLM Interfaces

React as the rendering layer for streaming AI responses, agent UIs, and LLM workflow builders. This space is moving fast — these are the infrastructure-level tools worth knowing.

| Project                                         | Description                                                                    |
| ----------------------------------------------- | ------------------------------------------------------------------------------ |
| [Flowise](https://github.com/FlowiseAI/Flowise) | A visual LLM workflow builder whose entire canvas UI is powered by React Flow. |

---

## 📊 Data Visualization

Animated, interactive, and explorable data — rendered as React components with SVG, Canvas, or WebGL under the hood.

| Project                                                              | Description                                                                                    |
| -------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| [Recharts](https://recharts.org/)                                    | Composable, declarative chart library built on D3 and React SVG.                               |
| [Nivo](https://github.com/plouc/nivo)                                | Comprehensive dataviz library with support for motion, SVG, canvas, and server-side rendering. |
| [react-force-graph](https://github.com/vasturiano/react-force-graph) | Force-directed graph visualization in 2D and 3D using Canvas and WebGL.                        |
| [Deck.gl](https://deck.gl/)                                          | WebGL-powered visualization layers for maps and large datasets. Also listed under Maps & Geo.  |

---

## 🧩 Node-Based Editors

Drag-and-drop graph interfaces where nodes are React components and edges are data flows. The canonical UI pattern for AI pipelines, workflow builders, and visual programming tools.

| Project                                                          | Description                                                                                      |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [React Flow / xyflow](https://reactflow.dev/)                    | The de facto standard for building node-based editors and interactive diagram canvases in React. |
| [react-diagrams](https://github.com/projectstorm/react-diagrams) | A diagramming toolkit for React with support for custom node types and complex graph topologies. |
| [Flume](https://github.com/chrisjpatty/flume)                    | A node editor focused on extracting and managing application logic through visual graphs.        |

---

## 🌀 Generative Art & Creative Coding

React as a creative coding environment. Components encapsulate sketches, shaders, and simulations — state management drives procedural outputs.

| Project                                           | Description                                                                                                   |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| [react-p5](https://github.com/P5-wrapper/react)   | React wrapper for p5.js, enabling generative sketches to be composed and controlled as React components.      |
| [Auto-Animate](https://auto-animate.formkit.com/) | Drop-in animation utility that adds smooth transitions to any React list or layout change with a single hook. |

---

## 🧪 Custom Renderers & Experimental Targets

React's reconciler is not tied to the DOM. It is a general-purpose tree diffing engine that can target any platform — as long as you implement the host configuration interface.

| Project                                                                               | Description                                                                                                                             |
| ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [react-reconciler](https://www.npmjs.com/package/react-reconciler)                    | The low-level package used to build custom React renderers. The foundation that all non-DOM renderers are built on.                     |
| [react-nil](https://github.com/pmndrs/react-nil)                                      | A React renderer that produces no output. Used to run React's component lifecycle and side effects in headless or server-side contexts. |
| [react-test-renderer](https://www.npmjs.com/package/react-test-renderer) (deprecated) | Renders React components to plain JavaScript objects without a DOM — the basis for component snapshot testing.                          |

---

## 🤝 Contributing

PRs are welcome. This list is intentionally selective — the goal is quality over quantity.

**What belongs here:**

- Projects that use React (or React's reconciler) to target a **non-standard rendering environment** — anything other than a standard web browser rendering HTML.
- Libraries that enable React to produce **artifacts other than UI** — video files, PDFs, music, hardware signals, etc.
- Tools that demonstrate a genuinely **unexpected application of React's component model** — where the use of React is surprising, not just convenient.

**What does not belong here:**

- UI component libraries (shadcn, Radix, MUI, Chakra, etc.)
- General React utilities, hooks libraries, or state management tools
- Boilerplates, starter kits, or project templates
- Anything that uses React simply as a framework for a conventional web application
- Self-promotional submissions without significant adoption or a clearly novel concept

When in doubt, ask yourself: _Would a developer familiar with React be genuinely surprised to learn this is possible?_ If the answer is yes, it probably belongs here.
