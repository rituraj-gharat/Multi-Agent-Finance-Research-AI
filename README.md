# Multi-Agent-Finance-Research-AI

PhiFusion: Intelligent Multi-Agent Research Suite

PhiFusion is an AI-driven multi-agent research suite that streamlines the retrieval, analysis, and presentation of information. By integrating specialized agents for web search and financial data analysis, the project delivers real-time insights using advanced language models and modern Python libraries.
Project Overview

PhiFusion combines two dedicated agents:

    Web Search Agent

        Situation/Task: Addressed the challenge of retrieving accurate, sourced web information to support research and decision-making.

        Action: Deployed the agent using the phi library with the Groq model (llama-3.3-70b-specdec) and integrated it with DuckDuckGo for reliable web search, ensuring all responses include verifiable sources.

        Result: Established a robust system that consistently provides credible online data.

    Finance Agent

        Situation/Task: Tackled the need for timely, comprehensive financial data accessible in a streamlined format.

        Action: Configured the Finance Agent with YFinanceTools to extract stock prices, analyst recommendations, fundamentals, and company news—presenting findings using tables and charts.

        Result: Enabled efficient real-time financial analysis crucial for data-driven decision-making.

These agents work in tandem via a user-friendly Playground interface, enabling interactive exploration and collaborative data processing.
Key Features

    Innovated Data Retrieval:

        Addressed inefficiencies by separating online search and financial analysis through dedicated AI agents.

    Enhanced Data Visualization:

        Synthesized dynamic tables and charts to clearly present financial information.

    Interactive Playground Environment:

        Developed an intuitive interface with FastAPI and Uvicorn that streamlines testing and showcasing agent functionalities.

    Modular and Scalable Architecture:

        Optimized agent orchestration, facilitating seamless integration and future expansions.

Getting Started
Prerequisites

    Python 3.8 or later

    PHI API key (set in your environment as PHI_API_KEY)

    Installed dependencies listed in requirements.txt

Installation

    Clone the Repository

bash
git clone https://github.com/your-username/PhiFusion.git
cd PhiFusion

Set Up a Virtual Environment and Install Dependencies

bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
pip install -r requirements.txt

Configure Environment Variables

    Create a .env file in the root directory with:

        text
        PHI_API_KEY=your_actual_phi_api_key

Running the Application

Start the interactive Playground by running:

bash
python app.py

The application will launch a local server. Open your browser and navigate to the provided URL (typically http://localhost:8000) to explore the multi-agent interface.
Architecture

PhiFusion utilizes a multi-agent design pattern to segregate responsibilities:

    Web Search Agent: Executes targeted web queries using DuckDuckGo and returns source-backed results.

    Finance Agent: Retrieves financial data using YFinanceTools, displaying results in clear, visual formats.

Each agent operates using the Groq model (llama-3.3-70b-specdec) integrated through the phi framework, ensuring robust performance and scalability.
Project Highlights (STAR)

    Addressed: Identified the need for accurate, source-verified information, resulting in the deployment of a specialized web search agent.

    Synthesized: Merged complementary functionalities for comprehensive web and financial data analysis into a single cohesive solution.

    Developed: Engineered an interactive Playground interface to facilitate seamless testing and demonstration of agent capabilities.

    Optimized: Fine-tuned error handling and modular design, ensuring reliable and scalable performance across diverse datasets.

Libraries and Tools

    phidata

    python-dotenv

    yfinance

    packaging

    duckduckgo-search

    fastapi

    uvicorn

    groq

Contributing

Contributions to PhiFusion are welcome! To contribute:

    Fork the repository.

    Create your feature branch: git checkout -b feature/name

    Commit your changes: git commit -m 'Add some feature'

    Push to the branch: git push origin feature/name

    Submit a pull request detailing your changes.


Contact

For support or inquiries, please open an issue in the repository or contact rgharat1@asu.edu.

This agents are made with help of Krish Naik youtube channel

PhiFusion exemplifies a modular, scalable approach to multi-agent system design by combining advanced data retrieval with insightful financial analysis. The innovative use of specialized agents and interactive interfaces paves the way for enhanced, data-driven research and decision-making.
