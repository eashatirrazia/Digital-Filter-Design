# Digital-Filter-Design
A MATLAB based App to design basic filters and visualize their magnitude response.

# Filters Implemented:
This App implements the four basic types of filters including:
* low-pass
* high-pass
* band-pass
* band-stop
Built-in MATLAB functions are used to design and visualize the magnitude response of the filters.

# Filter Specifications:
* Filter Type: It is selected from a dropdown menu in the GUI.
* Fs: It is the sampling frequency which must be more than double of the cutoff frequency.
* Fpass1: It is the the cutoff frequency for low-pass and high-pass filters
* Fstop1: It is used in combination with Fpass1 for band-pass and band-stop filters to specify the selective frequencies to pass or block.
* magnitude: It determines the attenuation of the input signal.
* Order: Order of the differential equation of a filter determines the steapness of the decay of the filter response.

# Input Specifications:
* Simple sine wave: Its frequency can be determined by the user.
* Chirp Function: It is predefined in the code with a frequency range from 100Hz to 500Hz.
* Other varying frequency signals: These are all predefined in code with the only purpose to visualize the filter response to these input signals. I aim to implement a modular design for user input as future work for this project.
