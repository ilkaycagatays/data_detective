# 🔍 Data Detective

An AI-powered exploratory data analysis tool for data analysts. Upload your CSV file and let the AI automatically analyze it for you.

## ✨ What Can It Do?

### 📊 Automatic EDA (Exploratory Data Analysis)
- Instantly shows row count, column count, and data types
- Detects numeric, text, and date columns automatically
- Calculates min, max, mean, and missing value count for each column
- Visualizes missing data as a color-coded bar map
- Shows a live preview of your data in a clean table

### ⚠️ Anomaly Detection
- Detects outliers using the **IQR (Interquartile Range)** method
- Finds duplicate rows automatically
- Flags columns with high missing value rates
- AI generates a detailed anomaly report with root cause explanations and fix suggestions

### 📈 Automatic Charts
- Draws **distribution histograms** for all numeric columns
- Shows **top value frequency charts** for text columns
- Generates a **scatter plot** between the first two numeric columns
- All charts are created automatically — no configuration needed

### 💬 Natural Language Chat
- Ask questions about your data in plain language
- Examples: *"Which column has the most missing values?"*, *"What is the average salary?"*, *"Are there any outliers?"*
- Powered by Claude AI — answers are context-aware and data-specific

### ✨ Visualization Suggestions
- AI reads your data structure and suggests the best chart types
- Explains **why** each visualization is suitable for your data
- Gives you a ready-to-use roadmap for your analysis

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/data-detective.git
cd data-detective
```

### 2. Add your API key

Open `data_detective.html` and find this line:

```javascript
'x-api-key': 'YOUR_API_KEY_HERE',
```

Replace it with your Anthropic API key. You can get one at [console.anthropic.com](https://console.anthropic.com).

### 3. Run it

Open with **Live Server** in VS Code:
- Right-click `data_detective.html`
- Select **"Open with Live Server"**
- Opens at `http://127.0.0.1:5500` in your browser

---

## 📖 How to Use

1. Upload a **CSV file** from the left panel (drag & drop or click)
2. View automatic statistics in the **General Analysis** tab
3. Click **"Analyze with AI"** to get AI-powered insights
4. Check data quality issues in the **Anomalies** tab
5. Explore auto-generated charts in the **Charts** tab
6. Ask questions about your data in the **AI Chat** tab
7. Get chart recommendations in the **Visual Suggestions** tab

---

## 🛠️ Built With

| Technology | Purpose |
|-----------|---------|
| HTML / CSS / JavaScript | Frontend interface |
| [PapaParse](https://www.papaparse.com/) | CSV parsing |
| [Chart.js](https://www.chartjs.org/) | Chart rendering |
| [Anthropic Claude API](https://www.anthropic.com/) | AI analysis & chat |


