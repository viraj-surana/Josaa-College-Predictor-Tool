**Josaa College Predictor Tool**

A lightweight, interactive Jupyter Notebook application to help JEE-qualified students predict their chances of securing admission into IITs, NITs, IIITs, and other GFTIs based on historical JoSAA data.

---

## 📌 Importance of This Tool

* **Data-Driven Decision Making**: Empowers students with insights derived from historical opening and closing ranks across multiple years and rounds to make informed institute and program choices.
* **Customized Filters**: Offers dynamic filters for gender, seat type (home/institute quota), course duration (4‑year vs. 5‑year), and buffer adjustment to accommodate safety margins.
* **Simplified Workflow**: Integrates data loading, filtering, and results export into a single notebook, streamlining the counselling preparation process.
* **Accessibility**: Run entirely in Google Colab—no local setup required, making it widely accessible to students with an internet connection.

---

## 🛠️ What This Tool Does

1. **Loads JoSAA Data**: Imports the latest `Josaa Data.xlsx` containing annual and round-wise opening/closing rank details.
2. **Dynamic Year & Round Selector**: Lets users choose counseling year and round.
3. **Exam & Eligibility Inputs**: Accepts JEE Mains and Advanced ranks, automatically enabling only the institutes for which the user is qualified.
4. **Advanced Filters**: Toggle advanced panel to include/exclude specific institutes, programs, seat types, and apply rank buffer.
5. **Results Generation**: Displays eligible programs in a sortable table and provides a one‑click download of results in Excel format.

---

## 🚀 Getting Started

> **Repository**: [Josaa-College-Predictor-Tool](https://github.com/viraj-surana/Josaa-College-Predictor-Tool)

### Prerequisites

* A Google account with access to Google Colab
* Internet connection to fetch dependencies and banner image
* Basic familiarity with Jupyter notebooks

### Folder Structure

```
Josaa-College-Predictor-Tool/
├── College Checker Tool's Code/
│   └── College_Checker.ipynb
├── Dataset Used
│   └── Josaa Data.xlsx
├── Tool Demonstration Video
│   └── College Checker Tool.mp4
└── README.md
```

---

## 📖 Usage Guide (Google Colab)

1. **Open the Notebook**

   * Navigate to the repository and open `College Checker Tool's Code/College_Checker.ipynb` in Google Colab.
   * Alternatively, click “Open in Colab” badge if available.

2. **Install Dependencies**

   * Run the first cell to install `ipywidgets` and `openpyxl`:

     ```bash
     !pip install -q ipywidgets openpyxl
     ```

3. **Upload/Link Data**

   * Ensure `Josaa Data.xlsx` is either uploaded to Colab or accessible via the specified path.
   * The notebook fetches a banner image from Google Drive automatically.

4. **Configure Inputs**

   * Enter your **JEE Mains** and **JEE Advanced** ranks.
   * Select the **Year** and **Round** from dropdowns.
   * Choose **Institute Type** (IITs, NITs, IIITs, GFTIs) based on eligibility.

5. **Apply Filters**

   * Use basic filters for **Gender**, **Seat Type**, and **Course Duration**.
   * Toggle **Advanced Filters** to include/exclude specific institutes and programs, and adjust the **Rank Buffer**.

6. **Generate Results**

   * Click **Show Results**. The tool will display matching programs and provide a download link for an Excel sheet of results.

7. **Refresh or Reset**

   * Use the **🔄 Refresh All** button to reset inputs and filters to defaults.

---

## 🎥 Demo Video

A step‑by‑step walkthrough demonstrating the tool in action is available here:

> **Demo Link**: 

---

## 🔮 Next Steps

1. **Web Deployment**: Package the notebook logic into a web application (Flask/Django/Streamlit) for live use during next JoSAA counseling (2026).
2. **CSAB Round Tool**: Adapt the filter logic and dataset to build a parallel application for CSAB special round seat allotments.
3. **User Accounts & Analytics**: Allow users to save profiles, track historical predictions, and gather usage statistics for continuous improvement.

---

## 🧑‍💻 Who Made This Tool

* **Viraj Surana** (BTech Data Science & AI, IIIT Dharwad)

  * GitHub: [viraj-surana](https://github.com/viraj-surana)
  * Email: *[suranaviraj@gmail.com](mailto:suranaviraj@gmail.com)*

**Special Thanks** to: 

* I would like to express my heartfelt gratitude to my real brother and all my cousin brothers and sisters for their valuable suggestions, encouragement, and continuous support throughout the development of this tool. Their insights helped refine both the user experience and the filtering logic.

Real Brother:
• Rishabh Surana

Cousin Brothers:
• Sambhav Kothari
• Jinesh Sanghvi
• Harsh Kothari

Cousin Sisters:
• Neha Kothari
• Kavya Jain

* A special thanks to the JoSAA Counselling Portal for providing easy access to historical data, which made this project possible.

---

## 🔗 Useful Links

* **GitHub Repository**: [https://github.com/viraj-surana/Josaa-College-Predictor-Tool](https://github.com/viraj-surana/Josaa-College-Predictor-Tool)
* **JoSAA Counselling Portal**: [https://josaa.nic.in/](https://josaa.nic.in/)
* **Linkedln:**:[Viraj's Linkedln](https://www.linkedin.com/in/viraj-surana-90a096294/)
---

