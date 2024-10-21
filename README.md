# TRIP-PLANNER-CREWAI

Here’s a sample **README** file for your **Trip Planner Crew AI** project:

---

# Trip Planner Crew AI

**Trip Planner Crew AI** is an intelligent system that helps travelers plan optimal trips by leveraging Crew AI agents. The agents work collaboratively to gather information, suggest destinations, and create travel itineraries based on user preferences, ensuring a seamless travel experience.

## Features

1. **City Selection Expert**: Analyzes travel destinations based on weather, season, and prices to recommend the best cities for your trip.
2. **Local Expert**: Provides detailed insights on attractions, local customs, and activities in your selected destination.
3. **Travel Concierge**: Assists in creating an optimized itinerary based on your preferences (e.g., activities, dining, nightlife) while balancing budget and packing suggestions.
4. **Dynamic Resource Gathering**: Uses a search tool to gather up-to-date information from the web, ensuring that travel suggestions are timely and relevant.
5. **Optimized Planning**: Integrates a calculator to balance itinerary options, travel costs, and available resources.

## How It Works

### Agents
- **City Selection Expert**: Gathers real-time data from various sources and suggests the best city for your trip based on factors like current weather conditions, travel costs, and events.
- **Local Expert**: Provides personalized recommendations for activities, cultural insights, and tips on maximizing your experience in your chosen city.
- **Travel Concierge**: Builds a full travel itinerary with options for transportation, activities, and accommodations, all while adhering to your budget and preferences.

### Tools
- **Search Tool**: Fetches live travel data, including weather updates, local attractions, and events.
- **Calculator Tool**: Helps optimize trip details like budget allocation, travel schedules, and activity durations.

## Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/crewAIInc/crewAI-examples.git
   ```

2. **Install Dependencies**:
   Ensure that you have Python 3.8 or higher installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Environment Variables**:
   Create a `.env` file in the root directory and add your API keys:
   ```bash
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Run the Application**:
   Run the main script:
   ```bash
   python main.py
   ```

## Usage

1. When prompted, input your travel preferences such as your starting location, cities of interest, travel dates, and any specific interests (e.g., food, nightlife, adventure).
2. The system will provide you with an optimized trip plan including destination recommendations, local insights, and a personalized itinerary.

## Example

```
## Welcome to Trip Planner Crew
-------------------------------

From where will you be traveling from?
>> Patna

What are the cities options you are interested in visiting?
>> Kolkata, Delhi

What is the date range you are interested in traveling?
>> 3rd to 10th November

What are some of your high-level interests and hobbies?
>> Food, markets, nightlife

## Here is your Trip Plan
-------------------------
City Selection: Kolkata recommended due to favorable weather and budget-friendly options.
Local Expert: Popular attractions include Victoria Memorial, local food tours, and markets.
Travel Concierge: Day 1 - Arrival, Day 2 - Food tour, Day 3 - Sightseeing, Day 4 - Night markets...
```

## Dependencies
- Python 3.8+
- `langchain-community==0.0.20`
- `crewai==0.11.0`
- `requests`
- `python-dotenv`

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

We welcome contributions! Please fork the repository and submit a pull request.

---

This README provides clear instructions on how to use, set up, and run your **Trip Planner Crew AI** project. Let me know if you need further adjustments!
