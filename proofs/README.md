# Proof of Google AI Usage

This directory contains verifiable artifacts and telemetry demonstrating the integration of Google AI technologies within the **POLARIS-AI** tactical maritime decision support system.

---

## Verifiable Artifacts

1. **`gemini-tactical-explainer-log.json`**:
   - Demonstrates the execution of **Google Gemini 1.5 Pro** via Google AI Studio / Gemini API.
   - Includes system prompt configuration (IMO Polar Code maritime persona), structured JSON schema generation, RIO (Risk Index Outcome) computation, candidate route risk balancing, and the generation of human-in-the-loop explainable tactical briefs.

2. **Google AI Services Employed**:
   - **Google Gemini 1.5 Pro / Flash**: Core reasoning engine for explainable tactical navigation decisions ("Why did the route change?"), risk synthesis, and Captain debriefing.
   - **Google AI Studio**: Fine-tuned prompt engineering and strict JSON output schema design matching maritime regulatory standards (IMO Polar Code POLARIS guidelines).
   - **Google Cloud Vertex AI & Google Earth Engine**: Geospatial telemetry ingestion pipelines for satellite SAR sea-ice classification and iceberg drift trajectory modeling with uncertainty corridors.
