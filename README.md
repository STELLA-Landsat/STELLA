<h1>STELLA: Build your own scientific instrument to investigate visible and invisible light.</h1>
<br />
STELLA stands for Science and Technology Education for Land/ Life Assessment. A STELLA instrument uses state-of-the-art light sensors to measure visible and near infrared light spectra. The Landsat satellites make similar measurements of the Earth from space. Landsat science has democratized those spectral measurements by making the data freely available to the public. STELLA helps to democratize scientific instrumentation by making it feasible for an interested person to build their own <a href="https://landsat.gsfc.nasa.gov/stella/">spectrometer</a>. 

When you build your own instrument, you learn to think about the capabilities and limitations of that instrument. The limits of our scientific instruments set the limits of human understanding, so understanding those capabilities and limitations is key to scientific discovery.


STELLA Description
<br />
The STELLA instruments measure light spectra in the 450 to 860 nm wavelengths, with six bands in the visible and six bands in the near infrared. STELLA stands for Science and Technology Education for Land/ Life Assessment. The STELLA broadband spectrometer can be used to [TBD capabilities proved in use]. We designed these inexpensive instruments (~$200 each) to be assembled and programmed by anyone interested in building their own spectrometer. Two versions of the STELLA instrument (1 and 2) require skill with protoboard soldering; one version (Q) is assembled with connectors only, no soldering required. Each instrument records data to a micro SD card, with a real time time and date stamp and data batch number. The STELLA-1 instrument takes and records data at a maximum of once per second. The STELLA-2 makes two measurements per second, and the STELLA-Q makes TBD measurements per second. The sample interval and the number of samples per average can be set by the user. The software is written in Circuit Python, a Python programming language variant for microcontrollers, with emphasis on readability so that a novice may be able to understand it, though no knowledge of Python is needed, since programming the instrument is by drag-and-drop file copying. The housing parts and spacers needed for assembly are designed to be 3D printed on a fused-filament printer of 200mm cube volume. The STELLA-Q requires no 3D printed parts.

All STELLA versions measure light spectra, air temperature, and humidity, and log the measurements with a UTC (Universal Coordinated Time) timestamp. The STELLA-1 and STELLA-2 are also sensitive to thermal infrared, to measure the surface temperature of materials with high optical emissivity. STELLA-1 and 2 measure barometric pressure, which serves as a proxy for altitude. STELLA-2 is optimized for drone use, weighing 110g with the housing included. STELLA-1 can be stripped of housing and display to be flown on a drone as well, at a similar mass.

We chose the sensors for precision, accuracy, stability, and cost. In particular, the spectral sensor's band pass filters are silicon thin film interference filters, which are highly stable over time and temperature.

Visible Irradiance: 450, 500, 550, 570, 600, 650nm bands, with centers +/- 5nm. Measurement bands are 40nm FWHM (full-width half-max). Irradiance is measured in µW/cm^2, to +/-12%. The field of view is 40 º FWHM.

Near Infrared Irradiance: 610, 680, 730, 760, 810, 680nm bands, with centers +/- 5 nm. Measurement bands are 20nm FWHM. Irradiance is measured in µW/cm^2, to +/-12 %. The field of view is 40 º FWHM.

Thermal Infrared Remote Surface Temperature: A beam-defined thermopile sensor measures surface temperature to +/- 0.5 ºC for emissive (non-shiny) surfaces. Most natural and many constructed surfaces are highly emissive, with the exception of bare metal surfaces. We chose the field of view, 35 º, to nearly match that of the spectral sensors.

Due to the fields of view of the sensors, the diameter of the measurement area is approximately the same as the stand off distance (0.7x). At 1m distance, the sensors average the irradiance over a circular area of about 1 m in diameter. At 10 m standoff, as from a drone or tower, the area of the measurement is approximately 10 m in diameter.

Humidity: +/-3 % relative humidity (S1 and S2), +/-1.8 % (Q)

Air Temperature: +/-0.3 ºC

Barometric Pressure: +/- 1 hPa (S1 and S2). Optional additional sensor for version Q.

STELLA-2 additional capabilities: 3 axis accelerometers, gyroscopes, and magnetometers. Bluetooth connection with Adafruit's Bluefruit Connect app for iPhone and Android.

The STELLA-1 can be hand held, or mounted on the end of a 1/2" diameter wooden dowel to increase reach. The STELLA-2 can be mounted on a drone using rubber bands at built-in pick points, or a smartphone may be attached to the instrument to take co-aligned photos of the measurement area.
The STELLA-Q can be assembled with double-stick tape, on a pair of craft sticks, a 30 cm ruler, or the end of a 1 m stick.
