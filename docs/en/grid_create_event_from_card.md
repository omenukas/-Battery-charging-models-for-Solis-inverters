# Grid – Create Event from Card

**Creates a grid calendar event from a Lovelace card input.**

- YAML: `../../automations/en/en/grid_create_event_from_card.yaml`
- [Lithuanian version](../lt/grid_create_event_from_card.md)

## Dependencies
- `calendar.create_event`
- `calendar.grid_planned_outages`
- `input_button.grid_create_event`
- `input_datetime.grid_event_end`
- `input_datetime.grid_event_start`
- `input_text.grid_event_title`

## How to use
- Copy the YAML into your Home Assistant setup.
- Ensure the required helpers exist (see **Dependencies**).
- Reload automations/cards or restart Home Assistant.