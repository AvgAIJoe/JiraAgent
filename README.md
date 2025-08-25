# Jira-Agent

AI-powered JIRA ticket generation tool that transforms requirements into structured tickets with Epics, Stories, and Subtasks.

## Features

- **Professional UI**: Clean blue theme with intuitive interface
- **AI-Powered Processing**: Uses OpenAI GPT models to analyze requirements
- **Multiple Input Methods**: Upload Word documents or paste text directly
- **Structured Output**: Generates Epics, Stories, and Subtasks with descriptions
- **Smart Estimation**: Automatic story point estimation and acceptance criteria
- **Export Options**: Download as JSON, CSV, or Text format
- **Customizable**: Model selection and creativity level controls

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/AvgAIJoe/JiraAgent.git
cd JiraAgent
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
streamlit run app.py
```

### 4. Access the App
- Open your browser and go to `http://localhost:8501`
- The app will automatically open in your default browser

### 5. Configure with New API Key
- In the sidebar, enter your new OpenAI API key
- Select your preferred model and settings
- Start using the app immediately

## Alternative Setup (with Virtual Environment)

For better isolation:
```bash
git clone https://github.com/AvgAIJoe/JiraAgent.git
cd JiraAgent
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

## Requirements

- Python 3.7+
- OpenAI API key
- Internet connection

## Usage

1. **Enter API Key**: Add your OpenAI API key in the sidebar
2. **Choose Input Method**: Either upload a Word document or paste text requirements
3. **Configure Settings**: Select AI model and creativity level
4. **Generate Tickets**: Click "Generate JIRA Tickets" to process
5. **Review Results**: View the structured breakdown of Epics, Stories, and Subtasks
6. **Export**: Download results in your preferred format

## Security

The app stores the API key in session state, so you'll need to enter it each time you run the app. This ensures your API key is not stored permanently on the system.

## Author

Chandan