**The information here is summarized from: https://aeronet.gsfc.nasa.gov<br>
<br>
The Aeronet Instrument is a CIMEL Electronique CE318 multiband sun photometer that performs measurements of spectral sun irradiance (direct sunlight measurement) and sky radiances (indirect sunlight measurement). The latest CE318-T model also performs nighttime measurements of the spectral lunar irradiance. Aeronet is equipped with eight interference filters (discussed below) that rotate through an observation period, allowing for the photon intensity to be computed at multiple wavelengths near-simultaneously.<br>
<br>
A brief description of the instrument: <br>
Sensor head fitted with 25 cm collimators is attached to a 40 cm robot base which systematically points the sensor head at the Sun, the sky and the moon according to a preprogrammed routine. <br>

The radiometer makes two basic measurements, either direct sun or sky, both within several programmed sequences. 
The direct sun measurements are made in eight spectral bands requiring approximately 10 seconds. 
Eight interference filters at wavelengths of 340, 380, 440, 500, 670, 870, 940 and 1020 nm are located in a filter wheel which is rotated by a direct drive stepping motor. 
The 940 nm channel is used for column water abundance determination. 
A preprogrammed sequence of measurements is taken by these instruments starting at an air mass of 7 in the morning and ending at an air mass of 7 in the evening. 
Optical depth is calculated from spectral extinction of direct beam radiation at each wavelength based on the Beer-Bouguer Law. 
Attenuation due to Rayleigh scatter, and absorption by ozone, and gaseous pollutants is estimated and removed to isolate the aerosol optical depth (AOD). 
A sequence of three such measurements are taken 30 seconds apart creating a triplet observation per wavelength. 
During the large air mass periods direct sun measurements are made at 0.25 air mass intervals, while at smaller air masses the interval between measurements is typically 15 minutes. 
The time variation of clouds is usually greater than that of aerosols causing an observable variation in the triplets that can be used to screen clouds in many cases. 
Additionally the 15-minute interval allows a longer temporal frequency check for cloud contamination.
In addition to the direct solar irradiance measurements that are made with a field of view of 1.2 degrees, these instruments measure the sky radiance in four spectral bands (440, 670, 870 and 1020 nm) along the solar principal plane (i.e., at constant azimuth angle, with varied scattering angles) up to nine times a day and along the solar almucantar (i.e., at constant elevation angle, with varied azimuth angles) up to six times a day. 
The approach is to acquire aureole and sky radiances observations through a large range of scattering angles from the sun through a constant aerosol profile to retrieve size distribution, phase function and aerosol optical depth. 
More than eight almucantar sequences are made daily at an optical air mass of 4, 3, 2 and 1.7 both morning and afternoon. 
Sky radiance measurements are inverted with the Dubovik and Nakajima inversions to provide aerosol properties of size distribution and phase function over the particle size range of 0.1 to 5 um.

**NOTE**
Radiance [W/sr m^2] is the energy per square meter per steradian recieved at the detector. The steradian term accounts for the direction the detected photon arrived at the detector from.
Irradiance [W/m^2] is the energy per square meter recieved at the detector. 
Solid Angle [sr] is the measure of how much of a field of view is taken up by a given object
Steradian(sr) is defined as the the area an object fills in the sphere around the observer (see: https://en.wikipedia.org/wiki/Steradian)
  For the Sun, which is sufficiently far away, the solid angle is defined as: OM = (Surface Area of a Circle w/ r = r_Sun)/(Distance between Earth and Sun)^2 = (piR_sun^2)/(Sun_Earth_Distance^2) = (pi(7e8m)^2)/((1.5e11m)^2) = 6.8e-5 sr


For Sun-Staring observations, all photons are assumed to be coming from the Sun (this is a pretty good assumption!), so we irradiance is reported
For Sky-Staring observations, there is a large range of possible solid angles for the photon to be scattered into the photometer from, so radiace is reported

The robot mounted sensor head is parked pointed near-nadir when idle to prevent contamination of the optical windows from rain and foreign particles.
