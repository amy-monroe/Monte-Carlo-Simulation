# Visual Monte Carlo Simulation
## Live Version

[Try the live app here](https://monte-carlo-simulator-demo.netlify.app/)
## Overview

This project serves as an educational demonstration of how a Monter Carlo simulation fundamentally works, utilising interaction and visualisation to help users gain a better understanding of the concept.

<br/>
Although I am a backend engineer, I created this to in Vanilla JavaScript to serve as a visual demonstration of approximating the value of Pi (π) using a Monte Carlo approach that you can look at and interact with in your browser.

I highly recommed checking out my **Golang Command-line interface (CLI) application** that performs a Monte Carlo simulation which also estimates the value of π. The CLI tool allows users to run simulations and visualise results in a terminal environment. 
<br/>

[CLI Monte Carlo Simulation](https://github.com/amy324/Golang-Monte-Carlo-Simulator.git)

<br/>

Monte Carlo simulations represent a powerful statistical technique, combining stochastic processes and mathematical modeling to estimate complex scenarios. In this context, stochastic processes involve random, probabilistic phenomena evolving over time or iterations. 

## Estimation Formula

The fundamental formula used for this estimation is:

$$π ≈ 4 \cdot \left(\frac{{\text{Number of Points Inside the Circle}}}{{\text{Total Number of Points Generated}}}\right)$$

The simulation offers a practical demonstration of probability, geometry, and stochastic processes. It accomplishes this by randomly distributing points within a unit square and discerning if each point falls inside a unit circle. The ratio of points inside the circle to the total points generated provides an approximation of Pi.

## Operational Procedure

This simulation utilises a canvas to visualize the process, as described below:

1. A unit square is delineated.
2. Points are randomly generated within the square.
3. If a point falls inside the unit circle (centered within the square), it's marked in blue; otherwise, it's marked in red.
4. The estimated value of Pi is continuously updated based on the ratio of points inside the circle to the total points generated.

## Interactive Controls

### Real-Time Mode

- Click "Start Real-Time" to initiate real-time updates of the simulation. You can pause this mode by clicking "Pause."

### Instant Results

- Click "Instant Results" to complete the simulation by generating the remaining points and displaying the final estimation of Pi.

### Clear Canvas

- Click "Clear Canvas" to reset the canvas and all calculations, allowing you to start fresh.

## Monte Carlo Simulations and Mathematical Modeling

**Monte Carlo simulations** are a fundamental technique in the realms of statistics, mathematics, and computational science. They rely on the principles of randomness, probability, and stochastic processes to estimate complex and often intractable mathematical problems.

Within this simulation, we employ a Monte Carlo approach to estimate the value of Pi (π), one of the most renowned mathematical constants. This estimation is founded on random sampling within a unit square and incorporates mathematical modeling and stochastic processes.

## Practical Applications

Beyond the primary goal of estimating Pi, Monte Carlo simulations find applications in diverse fields:

- **Finance**: They are instrumental in assessing risk within investment portfolios.
- **Engineering**: Monte Carlo simulations facilitate the analysis of structural reliability and performance.
- **Science**: These simulations are extensively employed in physics and computational sciences to simulate particle interactions, explore quantum systems, model complex physical phenomena, and predict outcomes in nuclear and high-energy physics experiments.
- **Statistics**: They serve as invaluable tools for estimating complex integrals and solving optimization problems.
- **Algorithm Analysis**: Monte Carlo simulations play a pivotal role in evaluating the performance and efficiency of algorithms, particularly when dealing with large datasets.
- **Network Optimization**: They are used to optimize network protocols and routing algorithms, thereby enhancing data transfer efficiency and reducing latency.
- **Security Testing**: These simulations help in assessing the vulnerability of software systems and networks, identifying potential weaknesses.
- **Machine Learning**: They contribute to the enhancement of machine learning models and reinforcement learning by generating random data and scenarios to improve decision-making processes.

As well as many different uses in different fields, in terms of computing, Monte Carlo simulations are essential for optimising and fine-tuning computer systems and software applications.

## About the Author

The author of this Monte Carlo Pi Simulator is a Golang Engineer and holds a master's degree in statistics, bringing a strong background of advanced statistical theory to her programming work. She has a passion for all things math related and the goal of this project is to serve as a visual representation to showcase how statistical techniques and a solid understanding of mathematical theory can be leveraged in programming to solve interesting problems, even in small-scale applications such as this. This is a simplified version of a Monte Carlo simulation for ease of understanding.

## Contributing

Feel free to contribute to the project by opening issues, providing feedback, or submitting pull requests. Your input is valuable!

## License

This project is licensed under the MIT License.
