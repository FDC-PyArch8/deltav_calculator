# deltav_calculator

deltav_calculator is a Python package which includes the data and functions to calculate the delta-v budget for basic maneuvres. A function is also implemented which can be used to determine the delta-v requirement between any two planets in the solar system, additionally giving an estimate for the travel time. The file deltav_ksp2 contains data from the popular space travel simulation game Kerbal Space Program 2 intended to be used together with the deltav_interplanetary function to calculate the delta-v budgets for missions within the game's fictional solar system.

# Detailed description

Includes functions which can be used to calculate the delta-v required for various orbital maneuvers as well as interplanetary and Earth-Moon system missions. Also includes data for the masses and average radii of the sun and planets for the solar system and the fictional solar system of Kerbal Space Program 2. The formulas used include Keppler's third law, the Vis-viva equation and expressions derived using energy conservation. The data was sourced from the following Wikipedia article: https://en.wikipedia.org/wiki/List_of_Solar_System_objects_by_size and the game Kerbal Space Program 2. Assumptions made include no inclination changes, instantaneous burns, no gravity assists and no air resistance.

# Purpose

Initially intended as a set of functions to calculate the values found in delta-v maps (https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Solar_system_delta_v_map.svg/800px-Solar_system_delta_v_map.svg.png) and to test out predictions with the space travel simulator Kerbal Space Program 2, this project had me learn the basics of orbital mechanics and gave me an insight into the usefulness of predicting the delta-v requirement for missions in real life.

# Installation

Using your terminal, clone the repository https://github.com/FDC-PyArch8/deltav_calculator as follows:

git clone https://github.com/FDC-PyArch8/deltav_calculator \n
cd deltav_calculator

# Dependencies

math library (pre-installed)

# Images

<img width="423" height="240" alt="image" src="https://github.com/user-attachments/assets/286731c6-8466-410d-92fe-06680b959d88" />

<img width="1019" height="778" alt="image" src="https://github.com/user-attachments/assets/3277e73f-4c85-4b56-bf16-b239d40c7d04" />
