<h1>PERT-Monte Carlo Risk Estimation for Sprint Planning.</h1>

🚀 This project is a React application that simulates sprint durations using the PERT (Program Evaluation Review Technique) method combined with Monte Carlo simulations. It helps teams better estimate project timelines, visualize risks, and make data-driven decisions.

<h2>📚 Features</h2>

📝 Multiple Sprints & Tasks: Create multiple sprints, add tasks with optimistic, most likely, and pessimistic durations.

⚠️ Risk Factor Management: Add risk factors, set probability and impact, and assign specific tasks to those risks.

📊 Simulation & Statistics: Run Monte Carlo simulations to compare sprint durations with and without risk factors.

📈 Data Visualization: Visualize the simulation results in a histogram using recharts.

📤 Excel Import/Export: Import and export sprint, task, and risk data as Excel files for external analysis.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repository:</p>

```
git clone repository_url
```

```
cd repository_folder
```

<p>3. Install dependencies:</p>

```
yarn
```

<p>4. Start the development server:</p>

```
yarn start
```

The app will be available at http://localhost:3000.

📘 Usage

Create a Sprint: Click the 'Create Sprint' button to start a new sprint.

Add Tasks: Define task names, optimistic, most likely, and pessimistic durations.

Set Dependencies: Choose task dependencies as needed.

Add Risk Factors: Specify risk types, probabilities, and impacts. Assign risks to specific tasks or leave empty to apply globally.

Run Simulation: Execute a Monte Carlo simulation (10000 iterations) to calculate mean, percentiles, and duration differences with and without risks.

Export Results: Export tasks, statistics, and histograms to an Excel file.

Import Data: Upload an Excel file to restore saved sprint data.

📊 Visualization

The app visualizes the duration distribution in a responsive histogram using the recharts library. You can see how risk factors shift the timeline and better prepare for uncertainties.

➡️ Space for images or diagrams to showcase the app's UI and result charts

<h2>🧠 Example</h2>

Here’s a more detailed example of the app in action with multiple tasks and risk factors:

Creating a Sprint:

Click "Create New Sprint" and name it.

Add 7 tasks with duration estimates.

Adding Tasks:

![Add Task](https://github.com/user-attachments/assets/67a88b93-eb1f-4c59-bb2a-b2d1ac24f453)


Configuring Risk Factors:

![RiskFactor](https://github.com/user-attachments/assets/52a50b4d-7bd9-4a71-9ebf-c0e15e2fb34c)


Running the Simulation:

▶️ Click "Run Simulation" to run 5000 iterations.

📉 Compare the sprint duration with and without the risk factors.

📊 View the statistical breakdown (mean, percentiles) and a histogram of results.
![SimulaitionResult-](https://github.com/user-attachments/assets/97dd5061-82b3-4b71-8a98-8e16c4068c38)
![SimulaitionResult-3](https://github.com/user-attachments/assets/a1bf306c-7ae4-4c59-abee-1b3e63b404a4)

Exporting and Importing Data:

📤 Export the simulation results, tasks, and risk factors to Excel.

📥 Re-import the Excel file to continue working on the sprint later.


This more complex setup helps you experiment with various risk scenarios, optimize timelines, and make better data-driven decisions for sprint planning.

🧾 Excel Data Structure

Tasks Sheet: Task names, duration estimates.

Statistics Sheet: Mean, 75th, 85th, and 95th percentiles, and custom percentiles.

Histogram Sheet: Duration bins and counts.

RiskFactors Sheet: Risk type, probability, impact, and affected tasks.

RiskHistogram Sheet: Average contribution of each risk factor.

<h2>🚀 Future Enhancements</h2>

🟩 Gantt chart visualization.

🔧 Adjustable number of Monte Carlo iterations.

📈 More detailed risk modeling (e.g., distribution types).

📜 License

MIT License

🤝 Contributing

Feel free to fork the repository, submit issues, or make pull requests!

