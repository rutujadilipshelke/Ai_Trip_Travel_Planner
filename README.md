# AI Trip Travel Planner
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/500157df-9a7f-4eb6-93fe-71660bba4d06" />


An AI-powered travel planning application that generates personalized travel itineraries based on user preferences, destination, budget, and trip duration.

## Features

* Generate customized travel itineraries
* AI-powered trip recommendations
* Destination suggestions
* Budget-based planning
* Day-wise travel schedule
* Interactive and user-friendly interface
* Integration with Google Cloud Platform services

## Tech Stack

### Frontend

* Streamlit

### Backend

* Python

### AI Services

* Google Gemini API
* Google Cloud Platform (GCP)

### Database

* SQLite / Firestore (if applicable)

## Project Structure

```text
Ai-Trip-Travel-Planner/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
├── assets/
├── src/
└── utils/
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/rutujadilipshelke/Ai_Trip_Travel_Planner.git
cd Ai_Trip_Travel_Planner
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Mac/Linux:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in the root directory:

```env
GOOGLE_API_KEY=your_api_key
```

## Run the Application

```bash
streamlit run app.py
```

The application will start locally and open in your browser.

## Screenshots

Add screenshots here.

### Home Page

![Home Page](screenshots/home.png)

### Generated Itinerary

![Itinerary](screenshots/itinerary.png)

## Future Enhancements

* Hotel recommendations
* Flight integration
* Weather forecasting
* Maps integration
* Multi-language support
* User authentication

## Author

Rutija Dilip Shelke

GitHub: https://github.com/rutujadilipshelke

