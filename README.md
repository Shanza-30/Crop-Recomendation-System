The Crop Recommendation System is a machine learning-based project designed to help farmers and agricultural professionals identify the most suitable crop to grow based on various environmental and soil conditions. The model analyzes key agricultural parameters including nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, pH level, and rainfall to make accurate predictions.

The dataset used for training consists of real-world values representing different crop-growing conditions. After performing thorough data cleaning, exploratory data analysis (EDA), and visualizations such as distribution plots and heatmaps, the model is trained using algorithms like Random Forest, Logistic Regression, and K-Nearest Neighbors. Among these, Random Forest showed the highest accuracy and was selected for final deployment.

To enhance usability, the project includes a feature importance chart to understand which factors impact crop selection the most. It also supports real-time predictions where users can input custom values to get recommendations.

The model is saved using pkl, and a simple interface can be created using Streamlit to make the tool accessible to non-technical users. This system can assist in maximizing crop yield, improving decision-making, and supporting sustainable farming practices through data-driven insights.
