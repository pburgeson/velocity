# Brainstorming
Reocrd of ideas of functionality to include and potential methods.

## Live engine power measurement
* Measurement of RPM straightforward but torque is harder
* Strain gauge measurement on frame
   - Examples include [these](https://www.digikey.com/en/products/filter/strain-gauges/559?s=N4IgjCBcpgzA7ATiqAxlAZgQwDYGcBTAGhAHsoBtEAFgAYxFqAOEEu%2BJseVmsW%2BZj1iIArLQBsEEuMRNYcEAF0SABwAuUEAGU1AJwCWAOwDmIAL4kGTZNBDpI2fMTKUQtJRZABaAEwo7UHoArs7kkFQiHp5%2B4SB4elhGAATGWEHGBB5AA)
   - Challenge in ensuring accuracy
   - Could install and then calibrate with application of known torques
   - Verify with FEA
* Pancake load cells at engine mounts
   - High accuracy, simple to install
   - Examples include [these](https://www.te.com/en/product-CAT-FLS0012.html)
   - Cannot bolt engine to high preload values without limiting resolution
   - Engine mounting of an airplane now reliant on a sensing element
* Shaft torque sensor
   - Ideas include [these](https://binsfeld.com/how-to-measure-torque-on-an-existing-shaft/)
   - Applying sensor to rotating shaft is a major challenge
   - Getting data off sensor is a challenge (requires slip ring)
   - Adding element to an aircraft shaft higher risk than typical installations
