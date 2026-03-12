Developed by
• Murat Teksin 

Eye tracking systems are vital tools in clinic research, marketing and driver safety using pupil features, gaze monitoring and blinks. Eye trackers use cameras and infrared (IR) illumination to capture images process by algorithms. However, noise from motion, lighting, and eyewear can impair performance. This study investigated optimizing hardware—specifically IR wavelength and intensity—to ensure image quality is suitable for processing before algorithmic analysis. It tested the effects of eye color, various light intensities and conditions, three IR wavelengths of 730nm, 850nm, 940nm and protective sunglasses in a simulated cockpit. Key findings showed no significant accuracy variation due to eye color. Optimal configurations differed for computer vision and convolutional neural networks (CNNs), and whether sunglasses were worn. For instance, without sunglasses, computer vision worked best at 850nm, while CNNs performed optimally at 730nm. With sunglasses, the best wavelengths and intensities changed. The research concludes that tracking accuracy is highly dependent on specific hardware configurations. It recommends developing systems with multiple, adaptable wavelengths and light intensities to enhance reliability in dynamic environments like cars and aircraft, emphasizing that optimizing hardware is a crucial first step before software processing.


Goal of the project:

Eye pupil tracking under the compelling conditions, sunglases usage in this application.

Data Set:

Dataset is crated by acquisition in the ITU Electro-optical Laboratory. Nearly 1000 image is used for the model training and validation. Labels created with manually and recorded into the center-points.csv. 


Used environment:
Jupyter Lab - Python 3.7.6

Using Freworks:
numpy
pandas
seaborn
matplotlib
sklearn
arch
xgboost
tensorflow

See the publish here: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13674/136741I/Investigation-of-eye-tracking-performance-under-varying-wavelengths-illumination-conditions/10.1117/12.3069930.short
