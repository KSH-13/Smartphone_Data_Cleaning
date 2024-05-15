# Smartphone Data Cleaning Project


In this project, a dataset containing information about various smartphone models was cleaned and preprocessed. The raw data was initially scraped from the web using the Beautiful Soup library in Python and consisted of the following columns:

1. Model Name
2. Price
3. Rating
4. SIM
5. Processor
6. Battery
7. RAM
8. Display
9. Camera
10. Card
11. Operating System (OS)

The data cleaning process involved several steps to ensure the dataset's quality and usability:

1. **Removing Non-Smartphones**: The dataset was filtered to remove any entries that did not represent smartphone devices, ensuring that the data consisted solely of relevant information.

2. **Handling Missing Values and Correcting Errors**: Various data cleaning techniques were applied to handle missing values, correct errors, and standardize formats across the dataset. This step ensured the data's consistency and reliability.

3. **Column Splitting**: Several columns in the original dataset contained multiple features combined into a single column. These columns were split into multiple subcolumns to facilitate better data analysis and feature engineering. The split columns included:

   - **Model Name and Company Name**
   - **SIM**: Subcolumns for 5G support, NFC support, and IR blaster availability
   - **Processor**: Subcolumns for processor name, processor brand, number of cores, and processor speed
   - **RAM**: Subcolumns for RAM and internal memory
   - **Battery**: Subcolumns for battery capacity and fast charging support
   - **Display**: Subcolumns for screen size, resolution, refresh rate, and additional display features
   - **Camera**: Subcolumns for the number of rear and front cameras, primary rear camera specs, and primary front camera specs

By splitting these columns, the data became more structured and easier to analyze, enabling more granular insights into the features and specifications of each smartphone model.

The cleaned and preprocessed dataset resulting from this project can be used for various purposes, such as analyzing smartphone trends, building recommendation systems, or training machine learning models for tasks like price prediction or feature prioritization.
