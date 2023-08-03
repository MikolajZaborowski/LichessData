# Chess Game History Analysis Project

Welcome to the Chess Game History Analysis repository!

# Technologies
- Phyton \
   -Pandas \
   -NumPy \
   -Scikit-learn \
   -XGB classifier \
   -SeaBorn \
   -TensorFlow 
- Tableau

# Introduction
This project is dedicated to analyzing the history of my chess games on the Lichess platform.
Using the powerful Lichess API, I retrieved comprehensive data on my gameplay, which served as the foundation for this analysis.
The primary objective behind this undertaking was to gain valuable insights into my chess performance
and build predictive models capable of estimating the outcomes of my future games.

# Purpose
The main purpose of this project is to identify areas for improvement in my chess strategy and decision-making during games.
By leveraging data science techniques and machine learning algorithms, I sought to uncover patterns, trends,
and potential weaknesses that may have gone unnoticed during actual gameplay.
Armed with this knowledge, I hope to enhance my skills and become better chess player.

# Repository Structure
Main project is in 'project' folder.
The repository is organized as follows:

 - '[data/](data/)': Contains the raw and preprocessed data used in the analysis, modeling and visualisations;
 - '[notebooks/](notebooks/)': Jupyter notebooks detailing the data cleaning, feature enginiring, feature filtering and model development process;
 - '[models/](models/)': Saved machine learning models for outcome prediction;
 - '[original_data_gathering/](original_data_gathering/)': notebook detaling gathering data from Lichess and simple data cleaning and data organization;
 - '[reference_data_models/](reference_data_models/)': notebooks that i work on and test new staff.

# Order of exploring project:

1. '[project/original_data_gathering/gathering_data.ipynb](project/original_data_gathering/gathering_data.ipynb)project/original_data_gathering/gathering_data.ipynb': whole data gathering, first data cleaning and organizing data.
2. '[project/notebooks/MASTER_DATA.ipynb](project/notebooks/MASTER_DATA.ipynb)': Data cleaning, feature enginiring, feature selection, different model classifiers testing, creating final best model classifiers, creating basic NN classifier
3. Visualizations - below ↓
   
# Viasualizations
The important visuals with key findings are created in Tableau at this link: 
  https://public.tableau.com/views/Chess_Analysis/Story1?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link
  Quick informations about visuals:
   - 'Chess openings': winrate for every opening (4 first moves) from top 20 most frequent ( diff for me as white and as black ), color -> numer of games played with that opening;
   - 'Number of moves played per player': Number of games played (Y axis) by number of moves played in game (grouped by 3 moves) (X axis), color -> winrate for number of moves;
   - 'Rank difference': Number of games played (Y axis) by rank difference (grouped by 20 rank points) (X axis), color -> winrate for rank difference;
   - 'My moves before castle': Number of games played (Y axis) by number of my moves played before castle (grouped by 3 moves) (X axis), color -> winrate for number of moves before castle;
   - 'Enemy moves before castle': Number of games played (Y axis) by number of enemy moves played before castle (grouped by 3 moves) (X axis), color -> winrate for number of moves before castle;
   - 'Time of games': Number of games played (Y axis) by total duration of game in seconds (grouped by 20 seconds) (X axis), color -> winrate for game duration;

Additionly plot of my ranking points for different speeds + number of games played in time:
  https://public.tableau.com/views/Book2_16890080408260/Dashboard1?:language=en-GB&:display_count=n&:origin=viz_share_link

If you have any questions about viasualizations or you are intrested in findings fell free to reach my via:
  - email: mikolajzaborowski2000@gmail.com
  - Linkedin: www.linkedin.com/in/mikolajzaborowski

# Next develop stages:
  - Working on attributes of draws results;
  - Changing projekt to object oriented programing;
  - Creating simple web app with flask to process similar work with different lichess data profiles;

# Authors
   - https://github.com/MikolajZaborowski
   - https://github.com/Mateusz-Matejko

My lichess profile - https://lichess.org/@/EvilSaintPL
