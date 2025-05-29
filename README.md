

# Travesthetics

Travesthetics is a dynamic, location-based travel recommendation website that suggests the best places to visit based on your current city and the type of outing—be it a family trip, a romantic date, or a fun excursion with friends. The app integrates the GeoApify API to fetch local attractions and uses ExpressJS for the backend, along with EJS templating for the frontend.


THIS PROJECT HAS BEEN UPGRADED WITH REACT AND OTHER FEATURES 
https://github.com/Targetx25/Travesthetics-2.0

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Location-Based Recommendations:** Automatically detects the user's city to provide tailored suggestions.
- **Contextual Filtering:** Filters recommendations based on outing type (family, date, friends).
- **Real-Time Search:** Utilizes the GeoApify API to fetch up-to-date information on local attractions.
- **Responsive Design:** Clean and interactive UI built with EJS for a seamless user experience.

## Technology Stack

- **Backend:** ExpressJS (JavaScript)
- **Frontend:** EJS templating, CSS
- **API Integration:** [GeoApify API](https://www.geoapify.com/)
- **Other Tools:** Node.js, npm

## Installation

Follow these steps to run Travesthetics locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/travesthetics.git
   cd travesthetics
   ```

2. **Install Dependencies:**

   Ensure that Node.js and npm are installed on your system. Then run:

   ```bash
   npm install
   ```

3. **Configure Environment Variables:**

   Create a `.env` file in the project root and add your GeoApify API key along with any other configurations:

   ```env
   GEOAPIFY_API_KEY=your_geoapify_api_key_here
   PORT=3000
   ```

4. **Start the Server:**

   ```bash
   npm start
   ```

5. **Access the Application:**

   Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to start exploring Travesthetics!

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes. For major changes, open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

