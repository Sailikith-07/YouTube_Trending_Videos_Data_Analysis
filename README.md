# 📊 YouTube Trending Videos Data Analysis

This project analyzes trending YouTube videos using Python. The dataset includes video and channel metadata such as views, likes, duration, categories, captions, and more. The goal is to understand what drives a video to trend and identify patterns that contribute to higher viewer engagement.

---

## 📁 Dataset Overview

* **Source:** [Kaggle - YouTube Trending Videos](https://www.kaggle.com/datasets/anushabellam/trending-videos-on-youtube)
* **Rows:** 115
* **Columns:** 19
* **Scope:** Trending videos with different categories
* **Time Period:** \[2007-03-30 to 2016-06-04] 
---

### 🔑 Key Columns:

* `channelId`, `channelTitle`, `publishedAt`, `videoId`, `videoTitle`, `videoDescription`,
* `duration`, `durationSec` , `viewCount`, `likeCount`, `dislikeCount`, `commentCount`,   
* `videoCategoryId`,`videoCategoryLabel`, `definition`, `caption`, `Licensed Content`

---

## 🧪 Objective

To explore and analyze what makes videos trend on YouTube by:

* Examining relationships between views, likes, duration, and comments
* Identifying high-performing content features
* Visualizing trends across video characteristics

---

## 🧹 Process Summary

1. **Data Cleaning**

   * Removed duplicates and handled missing values
   * Converted and standardized date and duration formats

2. **Exploratory Data Analysis**

   * Analyzed views, likes, comments, and video durations
   * Visualized correlations between engagement activities

3. **Insights & Conclusion**

   * Videos with more likes and comments tend to trend more
   * Videos published between 9 AM to 12 PM and 1 AM to 4 PM get more  views.
   * Interestingly videos with more dislikes are reason for less views

---

## 📈 Key Visuals

*  Comparing top 10 videos with more views with likes, dislikes and comments
* Barplots showing correlations between views and different engagement activities
* Barplots showing duration and their frequency for top 15 trending videos

---

## 📌 Tools Used

* **Python**
* **Pandas**
* **Matplotlib**, **Seaborn**
* **Google Colab**

---

## 📖 How to Open the Jupyter Notebook

This project includes a Jupyter Notebook file (`YouTube_Trending_Data_Analysis.ipynb`) that contains the full code, analysis, and explanations.

### Recommended ways to open and view the notebook:

- **Google Colab** (Free and easy):  
  1. Go to [https://colab.research.google.com](https://colab.research.google.com)  
  2. Upload the notebook file or open it directly from Google Drive.  
  3. All code and markdown (text) cells will render properly.

- **VS Code**:  
  1. Open the folder containing the notebook in VS Code.  
  2. Click on the `.ipynb` file to open it.  
  3. Make sure the notebook opens in the **Jupyter Notebook Editor** view (not plain text).  
  4. If it opens as JSON or plain text, right-click the file, select **“Reopen With” → “Jupyter Notebook Editor”**.

- **Jupyter Notebook/Lab (Local environment)**:  
  1. Install Jupyter via Anaconda or pip if not already installed.  
  2. Run `jupyter notebook` or `jupyter lab` in your terminal.  
  3. Navigate to the notebook file in the browser and open it.

---

If you see raw JSON text when opening the notebook, it means it’s not opening in the proper notebook viewer. Use one of the above methods to view the formatted notebook with code and markdown rendered.


## ✅ Conclusion

This analysis highlights the major traits of trending YouTube content. Creators aiming to increase visibility can focus on:

* Publish time 
* Targeting high-interest categories (e.g., People & Blogs, Science & Technology)
* Optimizing video length for engagement(6 to 14 )

---

## 📂 Files in This Project

| File                                    | Description                                  |
| --------------------------------------- | -------------------------------------------- |
| [Youtube\_Trending\_data\_analysis.ipynp](https://github.com/Sailikith-07/YouTube_Trending_Videos_Data_Analysis/blob/main/Yotube_Trending_data_analysis.ipynb) | Jupyter Notebook with full code and analysis |
| `README.md`                             | Project overview                             |
| [`Youtube_Trending_videos_data.csv`]( https://github.com/Sailikith-07/YouTube_Trending_Videos_Data_Analysis/blob/main/Youtube_Trending_videos_data.csv)      | Dataset used for analysis                    |
| ['cleaned_data.csv](https://github.com/Sailikith-07/YouTube_Trending_Videos_Data_Analysis/blob/main/cleaned_data.csv)                      | cleaned dataset                              |

---

## 🔗 Credits

* Dataset from [Kaggle-Trending videos on Youtube](https://www.kaggle.com/datasets/anushabellam/trending-videos-on-youtube)
* YouTube Trending data publicly available under fair usage

---

## 📬 Contact

For queries,  feedback, connect via \gundetisailikith@gmail.com.

