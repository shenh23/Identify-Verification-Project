# Identify Verification Project
This project aims to find the optimal Facial Biometrics technology for the company to ensure that employees return to work. We compared facial_recognition (open-source) against Amazon ReKognition API service in two use cases.
In use case 1, we want to know how well the two packages recognize the same person from different photos. Specifically, the algorithm compares source images (headshots) to target images (aged headshots of the same people). A collection of similarity percentages is generated by each algorithm, based on which we determined the threshold of match versus non-match.
In use case 2, we want to know how well the two packages recognize known faces in a group photo. Specifically, the algorithm compares source images (headshots) to target images (group photos), matches the faces in the images to the headshots, and produces labeled images with names and similarity scores.
