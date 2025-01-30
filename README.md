# DIGITAL FILTER DESIGN

*COMPANY NAME* : CODTECH IT SOLUTION

*NAME* : HARSH PAWAR

*INTERN ID*  : CT08IQU

*DOMAIN* : VLSI

*BATCH DURATION* : January 5th, 2025 to February 5th, 2025

*MENTOR NAME* : NEELA SANTOSH

# DESCRIPTION

This task focuses on the design, implementation, and simulation of a Finite Impulse Response (FIR) filter using Verilog HDL. FIR filters play a crucial role in digital signal processing (DSP) applications, providing advantages such as linear phase response and stable filtering operations. This project demonstrates the development of a basic FIR filter architecture and its simulation results.

Overview of FIR filter :
   The FIR filter is designed using a systematic and modular approach, incorporating key components that contribute to its efficiency and functionality:
     1. Filter Coefficients: These are predefined constants that determine the filter’s impulse response. They dictate how each input sample influences the final output, ensuring proper signal shaping.
     2. Delay Line: A shift register stores past input values, which are required for convolution-based filtering. This mechanism ensures that the filter operates over multiple input samples, improving signal accuracy.
     3. Weighted Summation: The heart of the FIR filter operation, where past input samples are multiplied by the corresponding coefficients and summed to produce the final filtered output. This process helps in removing unwanted noise and enhancing desired signal components.

Verilog-Based Implementation Approach:
    The filter is designed using register-based storage for input samples and a clock-driven execution mechanism. The reset functionality ensures that all stored values are cleared, bringing the filter to a known initial state. Each incoming sample is processed in real time, with previous samples contributing to the final output through coefficient-based multiplication.


# SIMULATION AND TESTBENCH 
  The simulation validates the functionality of the FIR filter through key observations:

   Reset Behavior: When reset is triggered, the system initializes all internal registers and sets the output to zero, ensuring predictable startup conditions.
   Filtering Response: Upon receiving an input sequence, the filter applies its predefined impulse response, producing an output that closely follows the expected theoretical results.
   Time-Domain Verification: The simulation results confirm the correctness of the filtering operation, demonstrating that the output represents a weighted sum of recent inputs as dictated by the FIR coefficients.

  
