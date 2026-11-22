# LLM-Powered Exploratory Data Analysis (EDA) Platform

An AI-powered web application that automates Exploratory Data Analysis (EDA) by combining Python-based data processing, interactive visualizations, and Large Language Model (LLM) integration.

Upload a CSV dataset and generate statistical summaries, identify missing values, visualize data distributions, and receive AI-generated analytical insights.

## 🚀 Features

- **CSV Data Upload:** Upload datasets directly through an interactive web interface.
- **Automated Data Preprocessing:** Handle missing numerical values using median imputation and categorical values using mode imputation.
- **Statistical Analysis:** Generate descriptive statistics and dataset summaries using Pandas.
- **AI-Powered Insights:** Integrate Ollama with Gemma 2B to generate natural language insights from dataset summaries.
- **Data Visualization:** Automatically generate histograms for numerical features.
- **Correlation Analysis:** Generate correlation heatmaps to identify relationships between numerical variables.
- **Interactive Interface:** Simple and user-friendly interface built using Gradio.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data processing and analysis |
| Gradio | Interactive web application |
| Ollama | Local LLM integration |
| Gemma 2B | AI-powered insight generation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/esha-singh-rathore/llm-powered-eda-platform.git

cd llm-powered-eda-platform
```

### 2. Install Dependencies

```bash
pip install gradio pandas matplotlib seaborn ollama
```

### 3. Install Ollama

Download and install Ollama:

https://ollama.com/

### 4. Download the Gemma Model

```bash
ollama pull gemma:2b
```

Ensure Ollama is running locally before launching the application.

### 5. Run the Application

```bash
python app.py
```

Open the Gradio application using the local URL displayed in your terminal.

## 📊 Application Workflow

1. Upload a CSV dataset.
2. The application loads and preprocesses the dataset.
3. Missing numerical and categorical values are handled automatically.
4. Statistical summaries and missing-value reports are generated.
5. Dataset summaries are sent to Gemma 2B for AI-powered insights.
6. Histograms and correlation heatmaps are generated.
7. View the EDA report and visualizations through the Gradio interface.

## 📁 Project Structure

```text
llm-powered-eda-platform/
│
├── app.py                  # Main application
├── README.md               # Project documentation
└── requirements.txt        # Project dependencies
```

## 🔮 Future Enhancements

- Support for Excel and additional data formats.
- Interactive charts and advanced visualizations.
- Automated outlier detection.
- AI-powered recommendations for data cleaning.
- Downloadable EDA reports.
- Advanced feature correlation and relationship analysis.

## 👩‍💻 Author

**Esha Singh**

GitHub: [@esha-singh-rathore](https://github.com/esha-singh-rathore)

---

*Built using Python, Data Analytics, and Large Language Models.*
