# AutoSense AI - Interactive Mockup

AutoSense AI is an interactive mobile application mockup designed to help drivers diagnose vehicle issues in real-time. Instead of presenting generic automotive advice, it acts as a diagnostic assistant that calculates potential risks, estimates future repair costs, and recommends personalized action plans.

This project was developed as an interactive HTML/JS mockup for the [Insert Course Name] course assignment.

## Core Features & Assignment Requirements

This application fulfills the core assignment requirements by implementing both a Predictive Model and a Recommender System natively within its user flow:

### 1. Predictive Model (Failure & Cost Prediction)
The application cross-references the user's specific vehicle details (make, model, engine, mileage) with reported symptoms (e.g., strange sounds, vibrations, leaks) to generate dynamic predictions:
* **Risk and Severity Prediction:** It predicts the probability of a specific mechanical failure based on known data (e.g., highlighting a high risk for a Mechatronic Unit failure).
* **Cost Impact Forecasting:** It calculates a financial forecast, presenting the estimated cost to fix the issue immediately versus the predicted exponential cost if the driver ignores the warning.

### 2. Recommender System (Action Plan & Routing)
Following the diagnostic phase, the application generates a context-aware action plan:
* **Immediate Action Recommender:** It suggests step-by-step safety actions for the driver (e.g., maintaining low speeds, checking specific fluid levels).
* **Specialist Mechanic Matching:** Rather than displaying a generic map, the system filters and suggests local mechanics who specialize specifically in the predicted mechanical issue.

## User Flow

1. **Vehicle Profile:** The user enters their car details using dynamic, cascading dropdowns or a simulated VIN input.
2. **Issue Location:** The user interacts with a vehicle diagram to pinpoint the exact source of the problem.
3. **Data Capture:** The user provides context through an interactive UI that simulates audio recording, camera input, or the selection of detailed preset symptoms.
4. **AI Diagnosis:** The application analyzes the inputs, cross-references known manufacturer defects for that specific mileage, and presents the predictive analysis.
5. **Action Plan:** The recommender system provides immediate next steps and routes the user to relevant specialists.

## Technical Stack

* **HTML5 / CSS3:** Single-page application structure.
* **JavaScript (Vanilla):** Manages state handling, dynamic dropdown logic, UI transitions, and the mockup's interactivity without requiring page reloads.
* **Tailwind CSS:** Utilized via CDN for rapid, responsive, and consistent styling.

## How to Run

No installation, npm, or build tools are required to view the mockup. 
Simply clone the repository and open the `index.html` file in any modern web browser to interact with the application.
