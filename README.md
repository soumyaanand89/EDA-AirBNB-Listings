
# EDA on AirBNB Listings

This project performs Exploratory Data Analysis (EDA) on a dataset of AirBNB listings to uncover insights related to pricing, location, and customer behavior. The analysis is conducted using Python and popular data science libraries like `pandas`, `matplotlib`, and `seaborn`.

## Project Overview

The goal of this project is to analyze the AirBNB listings data to understand key factors such as:
- Distribution of listings across neighborhoods.
- Average pricing of different room types by neighborhood.
- Potential factors influencing pricing and demand.

### Key Insights:
- **Manhattan and Brooklyn** have the highest number of AirBNB listings.
- **Entire homes/apartments in Manhattan** command the highest daily prices, while shared rooms are much cheaper across all boroughs.
- Neighborhoods with fewer listings, like **Staten Island** and **the Bronx**, may offer growth opportunities for hosts.
  
## Dataset

The dataset used for this analysis contains the following fields:
- `neighbourhood_group`: The major neighborhood group (e.g., Manhattan, Brooklyn).
- `room_type`: The type of AirBNB listing (e.g., entire home/apartment, private room, shared room).
- `price`: The price per night.
- And other relevant columns related to availability, reviews, etc.

### How to Use the Project

To run this project on your local machine:

1. Clone the repository:
    \`\`\`bash
    git clone https://github.com/your-username/EDA-AirBNB-Listings.git
    \`\`\`
   
2. Navigate to the project directory:
    \`\`\`bash
    cd EDA-AirBNB-Listings
    \`\`\`

3. Open the **EDA_AirBNB.ipynb** file in Jupyter Notebook or Google Colab to explore the analysis:
    \`\`\`bash
    jupyter notebook EDA_AirBNB.ipynb
    \`\`\`

4. Make sure that the required Python libraries are installed. You can install them using the following command (Not necessary step):
    \`\`\`bash
    pip install pandas matplotlib seaborn
    \`\`\`

5. The dataset (`your_file.csv`) is already included in the repository. The notebook directly loads this dataset to perform the analysis:
    \`\`\`python
    data = pd.read_csv('your_file.csv')
    \`\`\`

## Libraries Used

- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating visualizations.
- **seaborn**: For enhanced data visualization.