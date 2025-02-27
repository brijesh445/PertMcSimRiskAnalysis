PERT-Monte Carlo Risk Estimation for Sprint Planning.

🚀 This project is a React application that simulates sprint durations using the PERT (Program Evaluation Review Technique) method combined with Monte Carlo simulations. It helps teams better estimate project timelines, visualize risks, and make data-driven decisions.

📚 Features

📝 Multiple Sprints & Tasks: Create multiple sprints, add tasks with optimistic, most likely, and pessimistic durations.

🔗 Dependency Management: Define dependencies between tasks.

⚠️ Risk Factor Management: Add risk factors, set probability and impact, and assign specific tasks to those risks.

📊 Simulation & Statistics: Run Monte Carlo simulations to compare sprint durations with and without risk factors.

📈 Data Visualization: Visualize the simulation results in a histogram using recharts.

📤 Excel Import/Export: Import and export sprint, task, and risk data as Excel files for external analysis.

🛠️ Installation

Clone the repository:

git clone <repository_url>
cd <repository_folder>

Install dependencies:

npm install

Start the development server:

npm start

The app will be available at http://localhost:3000.

📘 Usage

Create a Sprint: Click the 'Create Sprint' button to start a new sprint.

Add Tasks: Define task names, optimistic, most likely, and pessimistic durations.

Set Dependencies: Choose task dependencies as needed.

Add Risk Factors: Specify risk types, probabilities, and impacts. Assign risks to specific tasks or leave empty to apply globally.

Run Simulation: Execute a Monte Carlo simulation (5000 iterations) to calculate mean, percentiles, and duration differences with and without risks.

Export Results: Export tasks, statistics, and histograms to an Excel file.

Import Data: Upload an Excel file to restore saved sprint data.

📊 Visualization

The app visualizes the duration distribution in a responsive histogram using the recharts library. You can see how risk factors shift the timeline and better prepare for uncertainties.

➡️ Space for images or diagrams to showcase the app's UI and result charts

🧠 Example

Here’s a more detailed example of the app in action with multiple tasks and risk factors:

Creating a Sprint:

Click "Create New Sprint" and name it.

Add 5 tasks with duration estimates.

Adding Tasks:

✅ Task 1: Develop Login Feature (O: 5, ML: 7, P: 10)

✅ Task 2: Build API (O: 3, ML: 5, P: 8, depends on Task 1)

✅ Task 3: Design UI (O: 4, ML: 6, P: 9)

✅ Task 4: Write Test Cases (O: 2, ML: 4, P: 7, depends on Task 2)

✅ Task 5: Final Integration (O: 6, ML: 9, P: 12, depends on Tasks 3 & 4)

Configuring Risk Factors:

⚠️ Risk 1: Server Outage

Probability: 10%

Impact: +5 days

Affects: Task 1 (Develop Login Feature)

🛡️ Risk 2: API Security Breach

Probability: 15%

Impact: +3 days

Affects: Task 2 (Build API)

Running the Simulation:

▶️ Click "Run Simulation" to run 5000 iterations.

📉 Compare the sprint duration with and without the risk factors.

📊 View the statistical breakdown (mean, percentiles) and a histogram of results.

Exporting and Importing Data:

📤 Export the simulation results, tasks, and risk factors to Excel.

📥 Re-import the Excel file to continue working on the sprint later.

➡️ Space for images to show example results, risk contribution graphs, and histograms

This more complex setup helps you experiment with various risk scenarios, optimize timelines, and make better data-driven decisions for sprint planning.

🧾 Excel Data Structure

Tasks Sheet: Task names, duration estimates, and dependencies.

Statistics Sheet: Mean, 75th, 85th, and 95th percentiles, and custom percentiles.

Histogram Sheet: Duration bins and counts.

RiskFactors Sheet: Risk type, probability, impact, and affected tasks.

RiskHistogram Sheet: Average contribution of each risk factor.

🚀 Future Enhancements

🟩 Gantt chart visualization.

🔧 Adjustable number of Monte Carlo iterations.

📈 More detailed risk modeling (e.g., distribution types).

📜 License

MIT License

🤝 Contributing

Feel free to fork the repository, submit issues, or make pull requests!

