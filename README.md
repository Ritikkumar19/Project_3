# Epidemic Simulator

This project simulates the spread of an epidemic through a population using a simple SIR (Susceptible, Infected, Recovered) model. The simulation tracks the number of susceptible, infected, and recovered individuals over time based on specified infection and recovery rates.

## Features

- **Customizable Parameters**: Set the population size, initial number of infected individuals, infection rate, and recovery rate.
- **Time-Steps Simulation**: Simulate the epidemic spread over a number of time steps.
- **Visualization**: Plot the epidemic curve showing the number of susceptible, infected, and recovered individuals over time.

## Getting Started

### Prerequisites

To run this project, you need to have Python installed along with the following libraries:

- `matplotlib`
- `random`

You can install the required packages using pip:

```bash
pip install matplotlib
```

### Running the Program

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ritikkumar19/epidemic-simulator.git
   cd epidemic-simulator
   ```

2. **Run the Simulation**:

   You can run the simulation using the following command:

   ```bash
   python epidemic_simulator.py
   ```

   This will execute the simulation with the default parameters and display a plot of the results.

3. **Modify Parameters**:

   You can adjust the simulation parameters by editing the `main()` function in the `epidemic_simulator.py` file. For example, you can change the population size, initial number of infected individuals, infection rate, recovery rate, and the number of simulation steps.

### Project Structure

- `epidemic_simulator.py`: Contains the main logic for simulating the epidemic and plotting the results.
- `README.md`: Documentation for the project.

### How it Works

The simulation is based on a simple SIR model:

1. **Susceptible (S)**: Individuals who are at risk of being infected.
2. **Infected (I)**: Individuals who have been infected and can spread the disease.
3. **Recovered (R)**: Individuals who have recovered and are no longer susceptible to infection.

During each time step:
- Infected individuals have a chance to recover based on the recovery rate.
- Susceptible individuals have a chance to become infected based on the infection rate and their contact with infected individuals.

The simulation records the number of susceptible, infected, and recovered individuals at each time step, and the results are plotted as an epidemic curve.

 Future Improvements

- Add more realistic parameters such as social distancing, varying infection rates, and vaccination.
- Implement more complex models such as SEIR (Susceptible, Exposed, Infected, Recovered).

Contributing

Feel free to fork the repository and submit pull requests. Contributions are welcome!
