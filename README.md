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
The FIR filter is designed using a systematic and modular approach, incorporating key components that contribute to its efficiency and functionality. One of the essential elements is the Filter Coefficients, which are predefined constants that determine the filter’s impulse response. These coefficients dictate how each input sample influences the final output, ensuring proper signal shaping and controlled signal modification.

Another crucial component is the Delay Line, which consists of a shift register that stores past input values required for convolution-based filtering. This mechanism allows the filter to operate over multiple input samples, enhancing signal accuracy by considering historical data in its computations. By retaining past samples, the delay line ensures smooth and stable filtering behavior.

The Weighted Summation serves as the core of the FIR filter operation. In this process, past input samples are multiplied by their corresponding filter coefficients and summed together to produce the final filtered output. This summation effectively removes unwanted noise while amplifying or preserving desired signal components, making the FIR filter highly suitable for applications in noise reduction, signal smoothing, and feature extraction.

 Verilog-Based Implementation Approach: 
    The filter is designed using register-based storage for input samples and a clock-driven execution mechanism. The reset functionality ensures that all stored values are cleared, bringing the filter to a known initial state. Each incoming sample is processed in real time, with previous samples contributing to the final output through coefficient-based multiplication.


# SIMULATION AND TESTBENCH 
  The simulation validates the functionality of the FIR filter through key observations:

   Reset Behavior: When reset is triggered, the system initializes all internal registers and sets the output to zero, ensuring predictable startup conditions.
   Filtering Response: Upon receiving an input sequence, the filter applies its predefined impulse response, producing an output that closely follows the expected theoretical results.
   Time-Domain Verification: The simulation results confirm the correctness of the filtering operation, demonstrating that the output represents a weighted sum of recent inputs as dictated by the FIR coefficients.

  ![Image](https://github.com/user-attachments/assets/ec634183-fbaf-45ef-97b3-63ca91e6810a)
