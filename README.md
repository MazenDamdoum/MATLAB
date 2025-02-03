Windowed Low-pass Filter Comparison:
This MATLAB script compares the frequency response of low-pass filters designed using different window functions. Each window function provides different characteristics, and this script aims to illustrate their effects on filter design.

**Instructions**

Requirements: 

This script requires MATLAB installed on your system.

Interpreting Results: Simply execute the script in MATLAB. After execution, the script generates plots comparing the frequency responses of low-pass filters designed using various window functions.

Window Functions Compared:

Kaiser Window (N1): A parameterized window function with adjustable sidelobe attenuation.

Blackman Window (N2): Known for its wide main lobe and good sidelobe suppression.

Hann Window (N3): Provides good sidelobe suppression but with a wider main lobe compared to Blackman.

Hamming Window (N4): Similar to Hann but with a smaller main lobe and slightly worse sidelobe suppression.

Dolph-Chebyshev Window (N5): Offers very sharp cutoff with the tradeoff of high sidelobe attenuation.



Results:
The script generates individual plots for each filter's frequency response and a final plot comparing all five windows for visual comparison.

Notes:
Each filter is designed with a specified cutoff frequency and window length.
The actual sidelobe attenuation is computed and displayed for each filter.
