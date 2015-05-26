# Phage Lab Simulator
We’re making a web application to simulate the experiments done in phage lab and explore the boundaries of what is predictable from existing data sources.  This web application will take the user through to process, step by step, from picking a soil sample, purifying it, repeated dilution/plating, enrichment sampling, DNA extraction, electrophoresis, and TEM imaging.

The core of the software, running on a server, will use the Django web framework and will be written in python.  There will also be pieces written in Dart, which compiles to Javascript and will run in users’ browsers.

The Phage Lab simulator is intended to allow people to try new things and experiment to the greatest extent possible, but will be limited by our ability to computationally predict experiments.  It should not allow users to specify or define experiments whose outcomes cannot be (at least somewhat) predicted on the basis of data available to the application.

The Phage Lab simulator should allow potentially “bad” experiments; those that would fail to produce useful data.  The application should present checkboxes, questions/button answers and other simple interfaces to communicate to users all of their possible choices.

The Phage Lab simulator should not try to interpret results for the user, except perhaps in a few limited cases.

## Roles:
Technical Director - Skyler Daché

Phage Representation and Selection Developer -  Shahroze Abbas 

Plating/Enrichment Developer - Bobby Allison

DNA Extraction/Electrophoresis Simulation Developer - ???

TEM Imaging Simulation Developer - ???