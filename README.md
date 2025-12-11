# drumhead-lattice

This is my project simulating a drumhead using a 2-D lattice of masses connected by springs, constrained to move along z.  

As a proof of concept, I start by simulating a string with fixed ends by a 1-D mass-spring lattice. I analyze the resonant frequencies and check that they approximate the integer harmonics. The system is visualized with a manim animation. The code for the 1-D system is found in string.ipynb.

The 2-D lattice is found in drumhead.ipynb and drumhead_vectorized.ipynb (use the latter, as it runs significantly faster). Again, I analyze the resonant frequencies and produce manim animations of the system. A heatmap is also included to visualize many-mass systems (as the manim animation does not scale well).

Manim animations can be found in media/videos/drumhead/480p15/, and the heatmap visualizations can be found in heatmap_animations/.