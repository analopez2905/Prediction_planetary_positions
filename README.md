# Prediction of Mars, Jupiter and Saturn positions 
Project realized for the Computational Methods course. It uses astronomical databases, interpolation techniques, root search and basic knowledge of position astronomy and python.This project was conducted for the Computational Methods course with the aim to demonstrate the knowledge gained in the course and apply it practically. The JPL database was used to download data for more than one complete orbital period for each planet. Considering the varying orbital periods of each planet, a different number of data points were used in each case. Ecliptic coordinates and Julian date were conveniently employed. The cubic spline interpolation technique was used to determine the position of each planet at any given time within its orbital period. Errors were calculated by comparing with the actual data, which was also accessible.

Through the bisection method, the roots were found, which helped estimate the orbital period of each planet along with their respective errors.

Finally, a coordinate transformation was carried out computationally using matrices, to derive the equatorial coordinates, which are more commonly used in astronomy.

The repository includes access to the downloaded data, a Jupyter notebook detailing the step-by-step process along with calculations, results, graphs, and animations.

Ana María López Aristizábal - analopeza2905@gmail.com - [https://github.com/analopez2905/Prediction_planetary_positions]
