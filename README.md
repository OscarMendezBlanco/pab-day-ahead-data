# Data for "Offering Under Pay-as-Bid in Day-Ahead Markets: Why Forecasting the Price Is Not Enough"

Input data of the case example in the paper by Ó. Méndez, Á. Bellido, P. Rodilla and C. Batlle (2026).

## Files

**`units.xlsx`**: parameters of each generating unit, one row per unit. Columns: identifier, unit type, fuel, maximum and minimum output (MW), ramp rate (MW/min and MW/h), fuel price (USD/MMBtu), heat rate (Btu/kWh), variable O&M and variable cost (USD/MWh), cold-start fuel (MMBtu) and start-up cost (USD). `WIND`, `PV` and `RTPV` are the aggregated wind, utility-scale PV and rooftop PV fleets. The identifier `2_STEAM_5` appears twice; the case uses only the first of the two rows, so it has 75 units.

**`hourly_profiles.xlsx`**: demand and available wind, PV and rooftop PV output (MW) in each of the 24 hours of the case day. `Period` runs from 1 to 24; `Hour` runs from 0 to 23 and is the index used in the paper.

**`initial_status.xlsx`**: commitment status of each unit before hour 0 (1 = on, 0 = off).
