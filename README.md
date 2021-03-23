# BeerLambertLaw
Data analysis code for Beer Lambert law

****Mildly important notes about handling the data****

1) The paths were defined pretty poorly and without much forethought so beware when downloading the data.
2) The white LED csv files should be kept in its seperate folder (by default)
3) Don't rename the csv files specifically the white LED spectral data

****Introduction and Theory****

There are two parts to this data analysis, the red LED intensity data and the the white LED spectral data. The red LED analysis simply takes the valuess of the intensity measured and plots them agains the concentration. It is then fitted with an exponential curve following the theoretical expectation of the Beer Lamber Law. Using this, the extinction value of different coloured dyes through the red light is found.
The white LED spectral data is very similar in concept to the red LED code, however, instead of taking the wavelength for granted, the white light allows for the extinction value of a certain wavelength of light to be calculated (in the given medium). The process is described in the code, however, to briefly explain, the spectral data is averaged out at every concentration level to reduce the random errors caused by deviations in the container of liquid with every refill. A certain wavelength of light must be given with which it will plot the intensity value at the wavelength against the concentration and finally fit a curve.   
