+# Universal Soul Personality Engine
+
+The Universal Soul Personality Engine (v4.9.0) is a narrative-focused cognitive simulation that models a "soul" composed of interacting subsystems such as 魄 states, resonance gating, and affective realism.  
+The implementation in `soul_engine.py` provides:
+
+- Modular components for conscious and subconscious processing.
+- Personality profiles with configurable affective, resonance, and resource parameters.
+- A command-line interface for interactive sessions with `/switch`, `/tick`, `/evolve`, and `/evidence` commands.
+- Smoke tests that exercise the affective realism and resonance gate behaviours.
+
+## Requirements
+
+- Python 3.9+
+- NumPy (optional – the engine will exit with an instructional message if it is missing when executed directly.)
+
+## Running the engine
+
+Launch the interactive CLI:
+
+```bash
+python soul_engine.py
+```
+
+Useful commands inside the loop:
+
+- `quit`/`exit` – leave the simulation.
+- `/switch <PERSONALITY>` – swap to a different personality profile (e.g. `ARTIST`).
+- `/evolve` – view averaged metrics collected for meta-learning hints.
+- `/evidence` – inspect acknowledgement evidence captured from responses.
+
+## Running tests
+
+Execute the bundled smoke tests to ensure the critical subsystems initialise and respond correctly:
+
+```bash
+python soul_engine.py --test
+```
+
+The tests rely only on the standard library and the provided engine code.
 
EOF
)
