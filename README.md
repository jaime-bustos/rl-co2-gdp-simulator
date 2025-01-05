# **Reinforcement Learning CO2 and GDP Simulator**

## **Overview**
This project explores the economic implications of reducing carbon dioxide (CO2) emissions using reinforcement learning (RL) simulations implemented in Python. By integrating global CO2 levels and world GDP data, this simulation models and predicts the effects of various CO2 reduction policies on future CO2 levels and GDP growth rates.

The goal is to identify cost-effective strategies for significant CO2 reductions while minimizing adverse economic impacts, using RL to balance environmental and economic objectives.

---

## **Key Features**
- **Data Integration**: Utilizes CO2 data from Mauna Loa Observatory and GDP growth data from the International Monetary Fund (IMF).
- **Reinforcement Learning Environment**: Custom RL environment using OpenAI Gym to simulate policy decisions.
- **Policy Optimization**: Explores the impact of actions such as green technology investments, carbon taxes, and electric vehicle subsidies.
- **Visualization**: Graphs showing CO2 levels and GDP growth trends under various scenarios.
- **Modeling Techniques**:
  - Linear and Polynomial Regression for CO2 predictions.
  - Reinforcement learning for policy optimization.

---

## **How It Works**
1. **Data Preprocessing**: 
   - Prepares CO2 and GDP growth data, ensuring alignment and normalization.
2. **Policy Simulation**: 
   - RL environment tests multiple policies to evaluate their effectiveness.
3. **Results Visualization**:
   - Displays CO2 reduction and GDP growth trajectories under different policy scenarios.

---

## **Results**
The RL model demonstrates potential short-term CO2 reductions but reveals challenges in maintaining long-term GDP growth. This highlights the trade-offs involved in climate policy design and the limitations of current RL models for long-term strategic planning.

---

## **Getting Started**
### Prerequisites
- Python 3.8+
- Libraries: Pandas, NumPy, Matplotlib, Scikit-learn, Stable-baselines3, Gym

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/rl-co2-gdp-simulator.git
   ```

2.	Navigate to the project directory:
    ```bash
    cd rl-co2-gdp-simulator
    ```

3.	Install the required dependencies (note: it is recommended to first create a seperate environment):
    ```bash
    pip install -r requirements.txt
    ```

### Usage
1.	Run the data preprocessing scripts for CO2 and GDP data in the Python notebook with your preferred IDE.

2. Run the RL script in the Python notebook.

3.	View the results:
	- CO2 reduction graphs
	- GDP growth impact visualization

---

## Future Improvements
- Incorporate long-term economic strategies into the RL model.
- Add multi-agent RL for more nuanced policy decision-making.
- Explore additional CO2 reduction strategies.

## References
- Mauna Loa CO2 Data
- World GDP Growth Data
- Stable Baselines3 Documentation
