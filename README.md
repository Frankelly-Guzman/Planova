# Planova - AI Event Planner

Planova is an AI-powered event planning web app designed to make organizing events seamless, efficient, and stress-free. Whether you're planning a wedding, corporate gathering, or a casual get-together, Planova leverages AI technology to provide personalized recommendations, manage budgets, and craft the perfect event itinerary.

---

## Features

- **Event Planning Assistance**: Input event details such as type, budget, location, and date to receive tailored recommendations.
- **AI-Powered Recommendations**: Suggests venues, vendors, and activities based on user preferences.
- **Budget Management**: Tracks expenses, ensuring your event stays within budget.
- **Custom Itineraries**: Generates and manages detailed event schedules.
- **Guest Management**: Create guest lists, track RSVPs, and suggest seating arrangements.
- **Theme Inspiration**: Provides unique and creative event themes with visual references.
- **Task Reminders**: Sends notifications for deadlines and key tasks.

---

## Tech Stack

### Frontend
- **React**: For building a responsive and dynamic user interface.
- **Shadcn UI / Tailwind CSS**: For clean, modern styling.
- **React Router**: For seamless navigation.

### Backend
- **Node.js / Express.js**: Handles server-side logic (alternative: Supabase for serverless backend).
- **Supabase/Firebase**: Manages authentication and real-time database.

### AI Integration
- **LangChain**: For natural language processing and conversational AI.
- **OpenAI API**: To generate creative suggestions and handle complex queries.

### APIs
- **Google Maps API**: For venue and vendor search.
- **Calendar API**: For scheduling and reminders.
- **Unsplash API**: For sourcing inspirational images.

### Deployment
- **Frontend**: Hosted on Vercel or Netlify.
- **Backend**: Deployed on AWS, Heroku, or Supabase.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/planova.git
   cd planova
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and include the following:
   ```env
   REACT_APP_OPENAI_API_KEY=your_openai_api_key
   REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   REACT_APP_SUPABASE_URL=your_supabase_url
   REACT_APP_SUPABASE_KEY=your_supabase_key
   ```

4. **Run the App Locally**:
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Usage

1. Sign up and log in to your Planova account.
2. Fill out the event details form to receive tailored recommendations.
3. Explore venue and vendor suggestions and save your favorites.
4. Use the budget tracker to manage expenses effectively.
5. Create a detailed itinerary and share it with collaborators or attendees.
6. Track RSVPs and seating arrangements with the guest management tool.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request on GitHub.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **LangChain** for powering the conversational AI.
- **OpenAI** for creative content generation.
- **Google APIs** for venue and scheduling integration.
- **Unsplash** for providing beautiful inspiration imagery.
- The open-source community for tools and resources that make projects like Planova possible.
