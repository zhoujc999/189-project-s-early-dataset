# CS189-Early-Project-S-Dataset

Project Members: Jingchao Zhou, Simran Regmi


How to Generate Data:
  All Files used for Data-Set Generation are located in the code folder!
  1) write_csv.py: Use this script to generate the csv that contains the location data for Venus.
     - The csv files contain the right ascension and declination at 7:00AM and 7:00PM every day in a given year.
  2) add_noise.py: Use this script to add gaussian noise to the right ascension and declination values from the csv generated by write_csv.py.
     - The csv files contain the right ascension and declination (in seconds and arc seconds respectively) at 7:00AM and 7:00PM every day in a given year.
  3) take_screenshot.py: Use this script to screenshot the images from the sky for given time.
     - The filename of the image is the timestamp of the observation image.
