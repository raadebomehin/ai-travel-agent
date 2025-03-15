# AI Travel Agent

AI Travel Agent is a smart travel assistant that helps users find flights and hotels based on their travel queries. The app leverages AI to fetch real-time travel information and provides users with structured travel recommendations, including pricing, availability, and booking links.

## Features
- **Flight Search**: Retrieves flight options using Google Flights API via SERPAPI.
- **Hotel Search**: Fetches hotel recommendations with details such as pricing, ratings, and amenities.
- **AI-Powered Recommendations**: Uses GPT-4o to generate structured travel suggestions.
- **Email Delivery**: Sends travel itinerary via email using Google SMTP.
- **User-Friendly Interface**: Built with Streamlit for easy interaction.

## Tech Stack
- **Frontend**: Streamlit
- **Backend**: Python, LangChain, OpenAI (GPT-4o)
- **APIs Used**:
  - Google Flights API (via SERPAPI)
  - Google Hotels API (via SERPAPI)
  - Google SMTP (for email sending)
- **Package Management**: Poetry

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.9+
- Poetry
- Streamlit
- An OpenAI API Key
- A SERPAPI Key

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ai-travel-agent.git
   cd ai-travel-agent
   ```
2. Install dependencies:
   ```sh
   poetry install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   OPENAI_API_KEY=your_openai_api_key
   SERPAPI_API_KEY=your_serpapi_key
   SMTP_USER=your_email@gmail.com
   SMTP_PASSWORD=your_email_password
   FROM_EMAIL=your_email@gmail.com
   TO_EMAIL=recipient_email@gmail.com
   ```
4. Run the app locally:
   ```sh
   streamlit run app.py
   ```

## Deployment
The app can be deployed on **Streamlit Community Cloud**:
1. Push the repository to GitHub.
2. Go to [Streamlit Community Cloud](https://share.streamlit.io/).
3. Connect your GitHub repository and deploy.

## Usage
1. Enter your travel details in the Streamlit UI.
2. The AI fetches flight and hotel recommendations.
3. View results and send them to your email.

## Contributing
Feel free to open issues or contribute via pull requests.

## License
This project is licensed under the MIT License.

## Contact
For any questions, reach out via LinkedIn: https://www.linkedin.com/in/abdurrahman-adebomehin-40aa8618a/ or email at rahman.adebomehin@gmail.com.

---
Made with ❤️ by [Abdurrahman_Adebomehin]

