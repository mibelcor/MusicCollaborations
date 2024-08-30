# NETWORK ANALYSIS OF THE EVOLUTION OF MUSICAL COLLABORATIONS BETWEEN ARTISTS AND BETWEEN GENRES OVER THE PAST TWO DECADES

# DESCRIPTION

This project aims to analyze the evolution of musical collaborations between the artists and the genres over time through network analysis. To achieve this, data is extracted from both Los 40 and Spotify using their APIs, and databases are created for building and analyzing the networks.

The main script for the project is **`Network_Analysis_Code.py`**, which performs the core network analysis, including creating edge lists from the extracted data, calculating key network metrics, and generating visualizations of the results. The other scripts serve as guides for understanding the data extraction and cleaning processes.

# CONTENTS

The repository includes the following scripts and data:

### 1. Scripts

- **`Code_Explanation_API_Los40.Rmd`**: This script extracts data from the Los 40 API. It includes detailed instructions for accessing the API and extracting relevant information, as well as cleaning the obtained data. This script serves as a guide to understand the data extraction and cleaning process for Los 40 data.

- **`Code_Explanation_API_Spotify.Rmd`**: This script extracts data related to musical genres from the Spotify API. It contains instructions for authentication and data retrieval, as well as the data cleaning process. This script serves as a guide to understand the data extraction and cleaning process for Spotify data.

- **`Network_Analysis_Code.Rmd`**: This is the main script for performing network analysis. It includes creating edge lists from the extracted data, calculating key network metrics, and generating visualizations of the results.

### 2. Databases

- **`artistas_totales.csv`**: Contains a list of artists with their identifiers and global genres, obtained from Spotify and Gabriel P. Oliveira’s genre mapping database.

- **`data_los40_final.csv`**: Cleaned database from Los 40, including all collaborations recorded from 2006 to 2024.

- **`raw_data_los40.csv`**: Raw data extracted from Los 40’s weekly charts, covering the period from 2006 to 2024.

# REQUIREMENTS AND INSTRUCTIONS

1. **Download the Databases**: Ensure you download the three databases (`artistas_totales.csv`, `data_los40_final.csv`, and `raw_data_los40.csv`) and place them in the same directory where you will be working with the scripts.

2. **Spotify API Setup**: To access the Spotify API, you will need to obtain authentication and a token. Instructions for this process are included in the `Code_Explanation_API_Spotify.py` script.

3. **Required Libraries**: The necessary libraries are specified in each script.

# RECOMMENDATIONS

If you experience slow processing, don’t get discouraged. It is recommended to process data chunk by chunk to achieve the desired results. Follow the detailed steps in the scripts for the best outcomes.



