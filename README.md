# Ecommerce Product Recommendation System

A web-based recommendation system for Walmart.com products, built with Flask and Bootstrap. Users can search for products, view personalized recommendations, and interact with trending items.

## Features

- **Product Search:** Search for products and specify the number of recommendations.
- **Personalized Recommendations:** Content-based filtering using product reviews and metadata.
- **Trending Products:** Display of popular items with brand, rating, and review count.
- **User Authentication:** Sign up and sign in modals (UI only).
- **Theme & Zoom Settings:** Switch between color themes and adjust zoom from the settings modal.
- **Responsive Design:** Built with Bootstrap for mobile and desktop compatibility.

## Project Structure

- `app.py` — Flask backend serving routes and recommendations.
- `main.html` — Main web interface template (Jinja2).
- `recommendation_project.ipynb` — Data analysis and model development notebook.
- `marketing_sample_for_walmart_com-walmart_com_product_review__20200701_20201231__5k_data.tsv` — Source product review data.
- `README.md` — Project documentation.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Flask
- pandas

### Installation

1. Clone this repository.
2. Install dependencies:
   ```sh
   pip install flask pandas
   ```
3. (Optional) For notebook exploration:
   ```sh
   pip install notebook
   ```

### Running the Application

1. Start the Flask server:
   ```sh
   python app.py
   ```
2. Visit [http://localhost:5000](http://localhost:5000) in your browser.

## Usage

- Use the search bar to find products and get recommendations.
- Click "Sign Up" or "Sign In" to open authentication modals.
- Change theme or zoom level from the "Settings" menu.
- View recommended products and details in modal popups.

## Data

The project uses Walmart.com product review data (`marketing_sample_for_walmart_com-walmart_com_product_review__20200701_20201231__5k_data.tsv`) for generating recommendations.

## Development

- Modify `recommendation_project.ipynb` for experimenting with recommendation algorithms.
- Update `main.html` for UI changes.
- Extend `app.py` for new backend features.

## License

For educational and research use only.

## Contact

For questions or feedback, email: er.rkjangir9602@gmail.com