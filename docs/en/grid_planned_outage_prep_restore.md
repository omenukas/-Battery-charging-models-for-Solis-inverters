# Grid Planned Outage – Preparation & Restore

**Prepares for a planned grid outage and restores settings afterwards.**

- YAML: `../../automations/en/en/grid_planned_outage_prep_restore.yaml`
- [Lithuanian version](../lt/grid_planned_outage_prep_restore.md)

## Dependencies
- `calendar.grid_planned_outages`
- `input_boolean.manual_battery_reserve`
- `input_boolean.turn_off`
- `input_boolean.turn_on`
- `number.set_value`
- `number.solis_waveshare_backup_soc`
- `sensor.solis_waveshare_a_phase_voltage`
- `sensor.solis_waveshare_b_phase_voltage`
- `sensor.solis_waveshare_battery_soc`
- `sensor.solis_waveshare_c_phase_voltage`
- `switch.grid_time_of_use_charging_period_1`
- `switch.reserve_battery_mode`
- `switch.turn_off`
- `switch.turn_on`

## How to use
- Copy the YAML into your Home Assistant setup.
- Ensure the required helpers exist (see **Dependencies**).
- Reload automations/cards or restart Home Assistant.