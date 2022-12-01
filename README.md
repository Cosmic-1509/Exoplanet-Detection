# Exoplanet-Detection

I have Attended this workshop in BITS Pilani Hyderabad and it was a great expereince for me. I have learned numerous concepts in python and tensorflow.
In this project we have collected details about various planets from the Mikulski Archive for Space Telescopes (MAST) data set from NASA.

Here we have used lightkurve in Python to identify the graphs of the planets and deduce which is a exoplanet and which is not. Using Tensor flow, we gave inputs to the AI machine to identify the exoplanets from the MAST Data. As it takes less than a second for the AI to give us the result for each planet for a human it would take an even longer time, hence we are giving the data inouts to the machine to do the work for us.

Here after running this command 'model.fit(X_train,y_train, epochs = 50)' we get the following output where all the 50 ephochs are runned and compared with all the 196 columns in the MAST data set.
In the image below we can see that we git an accuracy of 95%. The planets can be determined if they are an exoplanet or not by convolution of the data in between [1,-1]. We get the outputs in binary as '1' or '0' where '1' - indicates its an exoplanet and '0' - indicates its not an exoplanet.

![image](https://user-images.githubusercontent.com/117498713/205128647-22f66638-ee5a-4091-8eb5-47b33935990d.png)
