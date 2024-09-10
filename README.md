# Sentiment Analysis Web App with Azure Language Service and Streamlit

This project demonstrates a sentiment analysis web application that leverages the **Azure Cognitive Services - Language Service** for text analysis. The application has a **Python backend** to interact with Azure's sentiment analysis API and uses **Streamlit** for the frontend to provide a simple and interactive user interface.

## Features
- Real-time sentiment analysis of text input.
- Integration with **Azure Language Service** for high-accuracy sentiment evaluation.
- Simple, user-friendly web interface built with **Streamlit**.
- Easy deployment and scaling using Python and Azure.

## Architecture
1. **Frontend**: Streamlit-based web app for user interaction.
2. **Backend**: Python script that handles API calls to Azure Language Service for sentiment analysis.
3. **Azure Language Service**: Provides sentiment analysis for input text, returning `positive`, `neutral`, or `negative` sentiment.

## Technologies Used
- **Python**: Main language for backend development.
- **Streamlit**: Framework for building the interactive web UI.
- **Azure Cognitive Services**: Specifically the Language Service for sentiment analysis.
- **GitHub**: Version control and collaboration.
  
## Getting Started

### Prerequisites
- **Python 3.8+** installed on your machine.
- An **Azure subscription** with access to the **Azure Cognitive Services - Language API**.
- A **GitHub account** (for version control if needed).
  
### Azure Cognitive Services Setup

1. Create a **Cognitive Services resource** on Azure:
   - Navigate to the [Azure Portal](https://portal.azure.com/).
   - Search for **Cognitive Services** and create a new resource.
   - Choose **Language Service** and set up the required configurations.
   - Note down the **API Key** and **Endpoint URL** from the resource you created. You will need them to authenticate the API requests.

### Local Environment Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
