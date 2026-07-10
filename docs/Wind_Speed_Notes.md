# 10-meter Wind Speed

## Why Wind Speed?

- Wind removes heat from the surface.
- Higher wind speed increases cooling.
- Important factor in heatwave prediction.
- Standard meteorological variable.

## Why 10-meter Wind?

- Standard height used worldwide.
- Represents near-surface atmospheric conditions.
- Used in weather forecasting and climate studies.

## Why not 50-meter Wind?

- Represents higher atmosphere.
- More useful for wind energy studies.

## Why not Wind Gust?

- Temporary peak wind.
- Not representative of normal atmospheric conditions.

## Why U and V Components?

- IMDAA stores wind as:
  - U (East-West component)
  - V (North-South component)

Wind Speed is calculated as:

Wind Speed = √(U² + V²)

## Dataset Information

Variables:
- 10u : Eastward wind
- 10v : Northward wind

Units:
- m/s

Dimensions:
- Time
- Height
- Latitude
- Longitude

## Observations

- Wind speed ranges approximately from 2–9 m/s.
- Represents total air movement across Delhi.

## Conclusion

Wind Speed is used in the final machine learning dataset because it directly affects surface cooling and heat distribution.