# Sample State Shapes

These are abstract placeholders intended to show structure only.

## Example Capital State

{
  "state_id": "example-state-001",
  "timestamp": "YYYY-MM-DDTHH:MM:SSZ",
  "capital_buckets": {
    "liquid": "<number>",
    "illiquid": "<number>",
    "reserved": "<number>"
  },
  "exposure": {
    "personal": "<percent>",
    "business": "<percent>"
  }
}

## Example Input Scenario

{
  "scenario_id": "example-scenario-001",
  "mode": "<label>",
  "horizon": "<time-window>",
  "inputs": {
    "input_a": "<value>",
    "input_b": "<value>",
    "input_c": "<value>"
  }
}

## Example Output Projection

{
  "projection_id": "example-projection-001",
  "derived_outputs": {
    "output_a": "<value>",
    "output_b": "<value>",
    "output_c": "<value>"
  },
  "compliance_summary": {
    "status": "<ok|warning|action-needed>",
    "notes": [
      "<placeholder-note>"
    ]
  }
}
