# Engine, Lean & System Pages for the Cessna 172S' G1000 Multi-Function-Display in Microsoft Flight Simulator (MSFS).

This mod's goal is to give you more information about the engine on the G1000 MFD screen, to help with setting the mixture; there is zero modifications to flying characteristics or performance.
This mod requires the "Working Title G1000 Mod" (v0.3.2 or later). 

# CESSNA 172S MIXTURE SETTING IN MSFS
(based on docs available from Cessna, Garmin, and experience with the limitations of MSFS)
 
1. Run-up: determining "max RPM mixture".
At low elevation, in ISA conditions (29.92 in HG, 15°C at sea level), the mixture will be set at or near 100% (fully rich) for taking-off in a real 172S; however in MSFS, the mixture system is badly calibrated, and the "max RPM mixture" will be at maximum 91% (lever position). Over 91% and your engine will lose power as it's choking on too rich a mixture.

So during run-up, lean the mixture to get maximum RPM. This is the mixture you will set for take-off.
Here are a few example values in ISA conditions:
- 91% at sea level
- 72% at 2 500 ft.
- 56% at 5 000 ft.
- 42% at 9 500 ft.

2. Take-off & initial climb
Set your mixture for maximum RPM for take off and the first five minutes of climb.
No flaps needed for take off on a 172, except for high elevation, short or "rough" runways.

3. Climbing
I find climbing at 80 / 85 kts works nicely in the 172S.
Every few minutes, lean the mixture slightly to keep the engine at maximum RPM.

4. Cruising
After reaching your chosen cruise altitude, set your throttle for cruise power. The manual calls for cruising at 75% of max power or less; it's easy to set, you only have to make sure the RPM needle is in the green area, which will change according to altitude:
- 2500 RPM max below 5 000 ft
- 2600 RPM max below 10 000 ft
- 2700 RPM max above 10 000 ft.

5. Leaning to "Peak / Rich of Peak"
Reminder: the engine should be cruising at 75% of max power or less (see (4)).
Let the plane accelerate to a stable speed before leaning.

On the G1000 MFD, click the "ENGINE" softkey then "LEAN".

There are two officially recommended leaning settings : 
- Best Economy     - Lean the mixture slowly until the Exhaust Gas Temperature (EGT) peaks. Done. 
- Recommended Lean - First lean to Economy Cruise, then enrich the mixture slowly until the EGT is down 50 °F from the peak.

6. Leaning to "Lean of Peak"
The Lycoming IO-360-L2A powering the 172S is NOT certified for "Lean of Peak" operation.

7. Checking CHT
Regularly, after leaning, check the Cylinder Head Temperatures (CHT), that's the best way to know if your engine is happy with your settings. 
- a CHT below 400 °F is perfect.
- a CHT of 400 to 420 °F is acceptable.
- a CHT over 420 °F should be dealt with.
Now, the G1000 gauges set the red line at 500°F but let's simulate reality here: someone paying for his engine maintenance bills will never let the CHT go that high.

To deal with a high CHT, do either :
- Enrich the mixture - if you're in Economy Cruise, go to Power Cruise (see (5)).
- Reduce power a bit - pull the throttle, therefore reducing RPM.

Your EGT will quickly go down, and your CHT should follow. Keep in mind that contrary to EGT, CHT change very slowly.

8. Descent
No need to adjust the mixture, you can keep it lean as the engine should be set at low power for descent.

9. Before landing
Enrich your mixture back up (to 91% or less for a high-altitude airfield, see (1)) so maximum power will be available in case of a missed approach. 

* Christophe Arribat a.k.a. Haddock, November 2020 *
