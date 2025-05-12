# API-INTEGRATION-AND-DATA-VISUALIZATION

"COMPANY" : CODTECH IT SOLUTIONS 

"NAME" : DORNALA VAISHNAVI REDDY 

"INTERN ID" : CT06DK637

"DOMAIN" : Python Programming

"DURATION" 6 WEEKS

"MENTOR" : NEELA SANTOSH

##Weather Forecast Data Analysis and Visualization using Python
This task involves the development of a small data analysis and visualization dashboard for weather forecast data using Python programming language and its popular data manipulation and visualization libraries. The core objective is to fetch, process, analyze, and visualize short-term weather forecast data for a specific city — Mumbai in this case — by interacting with a public web-based API and presenting the data trends visually.

📌 Tools and Libraries Used
Python: A versatile, high-level programming language widely used in data science, web development, automation, and software development.

Requests: A Python HTTP library used to send HTTP requests to web servers and APIs. In this task, it fetches weather forecast data from the OpenWeatherMap API.

Pandas: A powerful open-source data manipulation and analysis library for Python. It provides data structures like DataFrames that are ideal for handling structured data. Here, it stores, cleans, and manipulates the fetched JSON weather data into tabular form for analysis.

Matplotlib: A widely-used Python plotting library for creating static, animated, and interactive visualizations. It serves as the base plotting system in this project.

Seaborn: Built on top of Matplotlib, Seaborn simplifies the creation of attractive and informative statistical graphics. In this task, it is used for line plots and count plots to visualize trends and distributions in weather data.

📌 Platform and Data Source
Platform: The code can be executed in any Python-compatible environment such as Jupyter Notebook, Google Colab, VS Code, PyCharm, or a local Python setup.

Data Source: The weather forecast data is sourced from the OpenWeatherMap API, a widely-used web service providing current weather data, forecasts, and historical weather data for cities worldwide. The API provides data in JSON format, which is parsed and processed for analysis.

📌 Task Workflow
Configuration: The program begins by setting the API key, city name, and the API endpoint URL for fetching the weather forecast. The units=metric parameter ensures that temperature values are returned in Celsius.

Data Fetching: The requests library sends an HTTP GET request to the OpenWeatherMap API. The API responds with forecast data in JSON format.

Data Processing: Key weather parameters like datetime, temperature, humidity, and weather condition description are extracted from the JSON response and organized into a dictionary, which is then converted into a Pandas DataFrame for ease of manipulation.

Data Cleaning: The datetime string values are converted into Pandas datetime objects, making them suitable for time series visualization.

Data Visualization:

Temperature and Humidity Trends: Seaborn line plots visualize the changes in temperature and humidity over time, providing insights into expected weather patterns.

Weather Condition Distribution: A count plot represents the frequency of different weather conditions (like Clear, Clouds, Rain, etc.) within the forecast period.

Dashboard Presentation: The visualizations collectively form a simple weather dashboard, offering a snapshot of Mumbai’s short-term forecast.

📌 Applications and Use Cases
Weather Monitoring Dashboards: Can be extended for real-time or multi-city weather tracking systems.

Travel and Event Planning: Useful for planning events or travel schedules based on weather forecasts.

Agricultural Planning: Farmers can use such tools to anticipate rainfall, temperature changes, and other weather conditions.

Smart City Systems: Integrated into city management dashboards for infrastructure and public service preparedness.

Educational Projects: Great for academic assignments, data visualization practice, or learning API integration and data analytics.

This task exemplifies practical data science skills in API integration, data wrangling, and exploratory data analysis (EDA), demonstrating how to transform raw web data into meaningful insights through visualization.

#OUTPUT

![Image](https://github.com/user-attachments/assets/8ae6a456-94d6-4dbb-af2c-01dfcfc7a8c0)








