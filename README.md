# Nuclear Annihilation Simulator

**Experience the devastating power of nuclear weapons in this interactive world map simulator.**

**[➡️ PLAY THE SIMULATOR LIVE HERE ⬅️](https://palegreen-oryx-833914.hostingersite.com/)**

This single-page web application allows users to simulate nuclear detonations anywhere on a world map and observe the estimated consequences. Click on the map to choose a target, configure the bomb's yield, and watch the simulated shockwaves spread. The simulator provides an estimate of casualties, damage radius, and maintains a log of all detonations and their cumulative global impact.

The ultimate, grim objective? Witness the depletion of the estimated global human population.

## Features

*   **Interactive World Map:** Powered by Leaflet.js, allowing easy navigation and targeting.
*   **Configurable Detonations:**
    *   Adjust bomb power (yield in Kilotons/Megatons) using a slider.
    *   Configure the number and duration of visual shockwave animations.
*   **Visual Explosion Effects:**
    *   Animated fireball/flash at ground zero.
    *   Expanding shockwave rings to visualize the blast's reach.
*   **Casualty & Impact Estimation:**
    *   Calculates estimated fatalities and injuries for each detonation based on proximity to a vast database of world cities and their populations.
    *   Considers a casualty gradient – higher impact closer to the city center within damage zones.
    *   Special consideration for capital cities, simulating a potentially wider area of influence.
    *   Accounts for a "background" global population not explicitly listed in the city database.
*   **Persistent Population Depletion:**
    *   Each city's population and the global unlisted population are depleted with each bomb.
    *   Fatalities are capped at the remaining population in an affected area – people cannot "die twice."
*   **Live Impact Reporting:**
    *   **Current Bomb:** Shows estimated fatalities, injured, and severe damage radius for the latest detonation.
    *   **Bomb Log:** A running history of all bombs dropped, including ID, yield, approximate location (nearest major city or coordinates), time, and casualties for that specific event.
    *   **Global Status:** Tracks the initial world population, cumulative worldwide fatalities, cumulative worldwide injured, and the total *remaining* global population.
*   **Educational/Awareness (Cautionary):** While a simulation, it aims to provide a stark visualization of the potential scale of nuclear conflict.

## How to Play

1.  **Open the Simulator:** Navigate to [https://palegreen-oryx-833914.hostingersite.com/](https://palegreen-oryx-833914.hostingersite.com/)
2.  **Configure (Left Panel):**
    *   Use the "Bomb Power" slider to set the yield of the nuclear weapon.
    *   Optionally, adjust the "Number of Shockwaves" and "Wave Duration" for the visual effect.
3.  **Target (Map):**
    *   Navigate the world map to your desired target location.
    *   Click on the map to detonate the bomb.
4.  **Observe (Map & Right Panel):**
    *   Watch the explosion animation on the map.
    *   Review the "Current Impact" report on the right panel for details about the last detonation.
    *   Check the "Bomb Log" for a history of all events.
    *   Monitor the "Global Status" to see the cumulative effect and the remaining world population.
5.  **Repeat:** Continue dropping bombs to see their effects across the globe and on the total population.

## Technology Used

*   **HTML5**
*   **CSS3**
*   **JavaScript (Vanilla)**
*   **Leaflet.js:** For the interactive map.

## Disclaimer

This is a simplified simulation created for educational and illustrative purposes. Real-world nuclear weapon effects are incredibly complex and depend on numerous factors not fully modeled here, including:

*   Altitude of detonation (airburst vs. groundburst)
*   Specific weapon design and efficiency
*   Terrain and geography
*   Weather conditions
*   Building structures and population density variations within cities
*   Sheltering and emergency response
*   Long-term effects like nuclear fallout (only briefly mentioned in text).

The casualty figures are estimations based on simplified models and a large, but not exhaustive, city database. **This simulator should NOT be used for precise strategic planning or to trivialize the horrific reality of nuclear war.** Its goal is to raise awareness about the scale of potential destruction.

## Future Considerations (Potential Ideas)

*   More detailed fallout modeling.
*   Different types of bombs (e.g., neutron, EMP).
*   More sophisticated population density mapping within cities.
*   Saving/loading simulation states.
*   User accounts and leaderboards (if desired for a more "game-like" experience, though the theme is serious).

---

Enjoy (in a cautionary way) the simulator!
