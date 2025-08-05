<h1>Monte Carlo Portfolio Simulation</h1>

<h2>📝 About</h2>
<p>This project implements a Monte Carlo simulation to model the performance of an investment portfolio comprising Brazilian stocks (e.g., VALE3, BBAS3). It uses historical price data to compute daily returns and covariance, enabling the projection of future portfolio values based on specified asset weights.</p>

<h2>🚀 Technologies</h2>
<div>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Yahoo%20Finance-720E9E?style=for-the-badge&logo=yahoo&logoColor=white">
</div>

<h2>Features</h2>
<ul>
  <li>Fetches historical stock data using the <code>yfinance</code> library.</li>
  <li>Computes mean daily returns and covariance matrix.</li>
  <li>Supports flexible portfolio weight configurations (random, uniform, or manual).</li>
  <li>Performs Monte Carlo simulations for a 365-day portfolio value forecast.</li>
  <li>Generates plots of portfolio value trajectories.</li>
</ul>

<h2>Installation</h2>
<ol>
  <li>Clone the repository:<br>
    <code>git clone https://github.com/your-username/monte-carlo-portfolio.git</code>
  </li>
  <li>Install dependencies:<br>
    <code>pip install yfinance numpy matplotlib</code>
  </li>
</ol>

<h2>Usage</h2>
<ol>
  <li>Open the <code>monte_carlo_simulation.ipynb</code> notebook in Jupyter or run the Python script.</li>
  <li>Adjust parameters like <code>stock_list</code>, <code>mc_sims</code>, and <code>weights</code>.</li>
  <li>Execute the code to run simulations and view results.</li>
</ol>

<h2>Project Structure</h2>
<ul>
  <li><code>monte_carlo_simulation.ipynb</code>: Main notebook with simulation and visualization logic.</li>
  <li><code>requirements.txt</code>: List of required Python packages.</li>
</ul>

<h2>Example</h2>
<p>The project simulates a portfolio of VALE3 and BBAS3 stocks over 1 year, running 365 Monte Carlo simulations with a $10,000 initial investment. The output plot shows possible portfolio value trajectories.</p>
<p>
  <a href="https://colab.research.google.com/github/your-username/monte-carlo-portfolio/blob/main/monte_carlo_simulation.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
  </a>
</p>

<h2>License</h2>
<p>Licensed under the <a href="LICENSE">MIT License</a>.</p>

<h2>Contact</h2>
<p>For inquiries or contributions, open an issue on the <a href="https://github.com/your-username/monte-carlo-portfolio">GitHub repository</a>.</p>
