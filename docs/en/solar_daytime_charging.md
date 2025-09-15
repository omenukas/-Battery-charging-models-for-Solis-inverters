# Battery Charging from Solar – Daytime Logic

**Charges the battery from solar during the day based on forecasts and thresholds.**

- YAML: `../../automations/en/en/solar_daytime_charging.yaml`
- [Lithuanian version](../lt/solar_daytime_charging.md)

## Dependencies
- `input_boolean.solar_winter_mode`
- `input_datetime.time_cutoff`
- `input_number.daily_peak_generation_threshold`
- `input_number.generation_forecast_threshold`
- `sensor.solcast_pv_forecast_forecast_today`
- `sensor.solcast_pv_forecast_peak_forecast_today`
- `sensor.solis_waveshare_battery_soc`
- `switch.feed_in_priority_mode`
- `switch.turn_off`
- `switch.turn_on`

## How to use
- Copy the YAML into your Home Assistant setup.
- Ensure the required helpers exist (see **Dependencies**).
- Reload automations/cards or restart Home Assistant.