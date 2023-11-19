# Ensemble Propulsion Systems

General code repository for all EPS work. Contact Tyler Mahlmann for questions and whatnot

## Pump Control and Testing
This folder is for pump control and data collection through MATLAB/Simulink. 

User Guide:

1. Open MATLAB R2023b or later. This can be done in [MATLAB Online](https://matlab.mathworks.com/) which has a free version if you don't have a license. I'll try to limit the number of fancy toolboxes used. Note that you can only use the simulated plant model in MATLAB Online-- you cannot do any code generation/hardware deployment as the Arduino blocks are not supported.
2. Ensure your computer has Git installed. Then, follow [this guide](https://www.mathworks.com/help/simulink/ug/set-up-git-source-control.html) to set up authentication for MATLAB to use Git.
3. Skip this if you've already cloned the repository onto your computer. In MATLAB right-click on the file browser and use the 'Source Control' menu to clone this repository. Use the HTTPS link.
4. Double-click 'EPS.prj' to open the project. This will set up all necessary paths for you. If you plan on working with the model, always make sure to have the project open first to completely track changes.
5. Currently the top-level model is 'FuelPumpTestControl.slx'. Open that up and have fun! 


