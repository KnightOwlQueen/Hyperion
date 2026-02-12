☼ Hyperion | Orbital Observation Manifest
Hyperion is a high-fidelity, futuristic subscription platform designed for "complex observation." This repository contains the front-end architecture for the pricing engine and a dynamic, state-aware shopping cart experience.

### Core Architecture
The system utilizes a "stateless-to-stateful" bridge via localStorage, allowing plan selections from the main pricing hub to persist through the checkout funnel without a backend database.

### Key Features
Dynamic Cart Injection: Automatically reads orbital plan data (Dusk, Solar, Helios) from browser memory.

AOS (Animate On Scroll): Integrated motion physics for a cinematic entrance.

Smart Manifest Purging: Smooth CSS-transition-based item removal with automatic subtotal recalculation.

Secure Simulation: Mock authorization sequences for a premium user experience.

File,Purpose
index.html,"The main terminal; contains the ""Choose Your Light"" pricing matrix."
cart.html,The manifest viewer; handles item removal and summary calculations.
tailwind.config,Custom palette including --solar (yellow-500) and --space (black).

### License
Proprietary "Hyperion" Orbital License. Unauthorized observation of the light is strictly monitored.