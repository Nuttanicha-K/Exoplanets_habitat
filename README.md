# exoplanets_habitat
This project focuses on using unsupervised machine learning to cluster exoplanets and assess their potential habitability. The data is sourced from the NASA Exoplanet Science Institute. Currently, the plan is to apply the K-Means clustering method, although this approach may be adjusted as new challenges(problems) arise during the project.

The main goal of this project is to apply computer science techniques to help identify and analyze exoplanets, offering an alternative approach compared to traditional physics methods. As a physics student, this project serves as an educational tool to enhance my coding skills while providing a new perspective on astronomy from the viewpoint of a computer scientist. 

I might not have included the flowchart and the theory behind features i have used at the moment due to frequent changes throughout the project for now.
If you notice any issues or have any suggestions, feel free to share your advice.

EDIT 1:
In the **First draft** file, the selected features include planet radius, planet mass, stellar mass, effective temperature, and distance. The features I focused on are the Earth reference units, specifically planet radius and planet mass. However, the output data from this version does not provide the clear analysis I had initially expected. This may include incorporating other factors like orbital period and stellar temperature to gain a more comprehensive understanding of the data.

EDIT 2:
In the second version of this project, I revised the clustering approach by applying a **Gaussian Mixture Model (GMM)** instead of the previous K-Means method. This change allows for more flexible cluster boundaries and can better capture the underlying structure of the data.
The following features were used to represent each exoplanet:

1.**pl_rade** – Planetary Radius  
2.**pl_bmasse** – Planetary Mass  
3.**st_mass** – Stellar Mass  
4.**pl_orbper** – Orbital Period  
5.**sy_dist** – System Distance from Earth  
6.**st_teff** – Stellar Effective Temperature
After applying GMM, **Earth was found in Cluster 0**, indicating that the planets in this cluster exhibit similar physical and orbital characteristics. I then scaled the feature data and ranked the top 10 planets in Cluster 0 based on similarity to Earth.

The planet **LP 791-18 d** was identified as the **most similar to Earth**.

📄 For the full unofficial report and clustering dataset, see the Google Docs link in the project description.

**work in progress**

next thing i'm going to do is considering and analyzed all the clusters i got to achive the goal of the project which is assessing the exoplanets potential habitability.
