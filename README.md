# Lime Scooter Gen 3 Battery Info
Tell the difference between a Gen 3 scooter and a Gen 2.5 scooter.

Gen 2.5 scooters have a max meter range of 24140 (24.2km remaining), whereas Gen 3.0 Limes have a mater range of atleast 32180+.

Gen 3.0 scooters become half charged when they reach 11km whereas a Gen 2.5 scooter becomes half charged at 6km.

Gen 3.0 scooters become low battery when they reach 5km whereas a Gen 2.5 scooter becomes low battery at 2.1km

This is how you can tell the difference when using Lime's API as it outputs `"meter_range": 24140,` and `"battery_level": "high",` - This sample is using a Gen 2.5 scooter
