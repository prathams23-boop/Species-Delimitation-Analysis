# Species-Delimitation-Analysis
This program performs an automated species delimitation analysis based on genetic distance data generated from any software (such as MEGA12) and an absolute threshold comparision. Bar graphs and swarm plots visually showcasing the distance data and thresholds are also generated.
This code was specifically developed to perform a species delimitation analysis for Basella alba and Basella rubra, so the thresholds have been chosen accordingly after a thorough literature review. These values might need to be changed depending on the taxonomy of the species the user is working with.
Two markers, namely matK and rbcL have been included in this study. However, the code can be easily edited to include more markers.
 Usage: results = analyze_species_delineation('matK distance file', 'rbcL distance file')
 
