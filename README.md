# SignalForge AI

**ForgeHacks 2026 — AI + Business**

SignalForge AI turns business CSV data into clear insights, predictions, and recommendations for small teams that do not have a dedicated analyst.

## Track fit
ForgeHacks AI + Business prompt: build an AI-powered solution that turns business data into clear insights, predictions, or recommendations that help people make better decisions.

## AI components
- TensorFlow.js neural time-series forecasting trained locally in the browser
- anomaly detection
- Pearson driver analysis
- recommendation layer based on forecast, anomalies, and drivers

The AI is part of the product itself, not only a coding assistant.

## Demo
Open `index.html`.
1. Click **Load demo dataset**
2. Choose `Revenue`
3. Click **Run AI analysis**
4. Review the forecast, anomaly count, top drivers, executive brief, and recommended actions

You can also upload your own comma-separated CSV. Numeric columns are detected automatically.

## Tech
HTML5, CSS3, JavaScript, TensorFlow.js, Chart.js.

## Privacy
The current MVP processes uploaded business data locally in the browser and does not send raw CSV data to an external AI API.

## Built during ForgeHacks
SignalForge AI is a new project created during the ForgeHacks 2026 build window for the AI + Business track.

## Limitations
This is a hackathon MVP. Forecasts are lightweight and designed for fast browser training. Correlation does not imply causation. Recommendations are decision-support signals, not professional financial advice.

## Next
Seasonality-aware forecasting, scenario simulation, saved workspaces, richer explainability, and KPI-specific playbooks.
