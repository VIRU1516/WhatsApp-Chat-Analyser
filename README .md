# 💬 WhatsApp Chat Analyser

A Python-based **WhatsApp Chat Analyser** built using Streamlit. This
project analyses exported WhatsApp conversations and provides meaningful
insights through statistics, timelines, activity maps, word clouds, and
emoji analysis.

## 🚀 Features

-   **Top Statistics:** Total messages, total words, media shared, and
    links shared.
-   **Monthly Timeline:** Analyse messaging activity month by month.
-   **Daily Timeline:** Visualize daily messaging patterns.
-   **Activity Map:** Identify the busiest days and months.
-   **Weekly Activity Map:** Explore messaging activity through a
    heatmap.
-   **Most Busy Users:** Identify the most active participants in group
    conversations.
-   **Word Cloud:** Visualize frequently used words in conversations.
-   **Most Common Words:** Find the most frequently used words.
-   **Emoji Analysis:** Analyse emoji usage and identify the most
    commonly used emojis.
-   **Individual & Overall Analysis:** Analyse a specific participant or
    the entire conversation.

## 🛠️ Technologies Used

-   Python
-   Streamlit
-   Pandas
-   Matplotlib
-   Seaborn
-   WordCloud
-   URLExtract
-   Emoji

## 📂 Project Structure

``` text
WhatsApp-Chat-Analyser/
│
├── app.py
├── helper.py
├── preprocessor.py
├── stop_hinglish_marathi.txt
├── requirements.txt
├── .gitignore
├── README.md
│
└── WhatsApp-Chat-Analyser.ipynb
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

``` bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

``` bash
cd WhatsApp-Chat-Analyser
```

### 3. Create a Virtual Environment (Optional)

``` bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

``` bash
venv\Scripts\activate
```

### 5. Install Required Dependencies

``` bash
pip install -r requirements.txt
```

### 6. Run the Streamlit Application

``` bash
streamlit run app.py
```

## 📱 How to Use

1.  Open WhatsApp on your phone.
2.  Select an individual or group chat.
3.  Tap the three dots and navigate to **More → Export Chat**.
4.  Select **Without Media**.
5.  Save the exported `.txt` file.
6.  Open the WhatsApp Chat Analyser application.
7.  Upload the exported chat file using the sidebar.
8.  Select a user or choose **Overall**.
9.  Click **Show Analysis** to explore the results.

## 📊 Analysis & Visualizations

The application provides different visual insights into WhatsApp
conversations, helping users understand their messaging patterns and
communication activity.

## 🔒 Privacy

Chat data is processed in memory during analysis and is not
intentionally stored by the application.

Avoid uploading sensitive conversations to publicly accessible
deployments.

## 🔮 Future Improvements

-   Support for additional WhatsApp export formats.
-   More interactive visualizations.
-   Advanced text and sentiment analysis.
-   Improved user interface and analytics.


## Screenshots

### Home Page
![Home Page](screenshots/Home.png)

### Statistics
![Statistics](screenshots/Top_Statistics.png)

### Activity Analysis
![Activity Analysis](screenshots/Activity_Map.png)

### WordCloud
![WordCloud](screenshots/WordCloud.png)

### Heatmap
![Heatmap](screenshots/Heatmap.png)

### Emoji Analysis
![Emoji Analysis](screenshots/Emoji_Analysis.png)

### Common Words
![Common Words](screenshots/Common_Words.png)


## 👨‍💻 Author

**Viraj Satale**

Aspiring Data Scientist \| Python \| Data Analysis \| Machine Learning

This project is part of my learning journey in Python, Data Analysis,
and Data Visualization.

## 🙏 Acknowledgement

Special thanks to **CampusX YouTube Channel** for the learning resources
and guidance that helped me understand and build this project.

This project was developed for educational purposes to gain practical
experience in Python and data analysis.

------------------------------------------------------------------------

⭐ If you find this project useful, consider giving it a star on GitHub!
