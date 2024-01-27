# Data Preparation
[L] (1.1 e 1.2) Load the dataset, clean the dataset if needed, write the introduction and do some initial plotting of the data, to show what we are working with
	[L] Load and clean data (dropped "Log Mode","Log Freq", "Timestamp"), select range of data without interference
	[L] Understand the role of calibration
	[L] Implement the consequences of calibration
	[ ] Write Introduction, with example plotting

[J] (1.3) Find correlation between data, and find a way to reduce dimensionality. Select most important features ((? TSE and UMAP ?))
	[J] Find correlation by eye (create better pairplot)
	[J] Find correlation by PCA or similar (use 90% variance retained)
	[EVERYBODY] Choose important new axis or features
	[J] Implement dimensionality reduction

# Time and Frequency Analysis
[A] Statistical Analysis

[P] Fourier Analysis: do the fourier transform, plot the spectrum, describe it a little, maybe understand what is happening by using google
	[P] Trasform and antitrasform and plot the results
	[L] Find minimas  

# Filter
[P, L] Research filter types and utility

[ ] Implement Filter from Lowpass/Bandpass/Highpass

[P] Implement Wavelet transform (and understand what it is)

[ ] Find another method to extrapolate HR

[P] Gaussian filter

# Metrics

[L] (4.1) Heart Beat per Minute with Fourier
		
[] (4.2) Heart Beat per Minute with wavelet trannsform

[ ] (4.3) Heart Rate Variability

# Algorithm (optional)

# Conclusion

[ ] Write Conclusion