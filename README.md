# 🍳PantryChef An AI-Powered Virtual Pantry & Recipe Assistant

# Project Overview
PantryChef is a smart kitchen management application that helps users reduce food waste and simplify meal planning. It allows users to maintain a virtual inventory of their fridge and generates personalized cooking suggestions using AI based on the ingredients they already have.

# Core Functions
1. Virtual Fridge Management
Inventory Tracking: Users can easily add newly purchased food items to their "Virtual Fridge".

Visual Organization: Keep track of what's in stock to avoid duplicate purchases and manage food expiration.

2. Smart Recipe Generator
Ingredient-Based Search: Users can select specific ingredients from their virtual pantry.

Personalized Recipes: Based on the selected items, the app searches for and returns relevant recipes.

AI Integration: Utilizing OpenAI, the app can provide creative culinary ideas tailored to available ingredients.

3. Multimedia Cooking Guides
Video Tutorials: In addition to text-based instructions, the app returns cooking videos for the selected recipes to provide a step-by-step visual learning experience.

# Tech Stack
Backend: Python (FastAPI)

AI Engine: OpenAI API (for intelligent recipe generation)

Database: SQLAlchemy (for managing pantry inventory and user data)

Frontend: HTML, CSS (using Jinja2 templates for dynamic rendering)

# Project Structure
backend/database.py: Handles database connections and session management.

backend/models.py: Defines the data structures for food items and recipes.

frontend/templates/: Contains the UI pages like food.html, recepie.html, and add-food.html.

# Start

Navigate to the backend folder.

Install dependencies: pip install -r requirements.txt.

Configure your .env file with your OpenAI API key.

Run the server: uvicorn main:app --reload.

Access the App:

Open your browser and go to http://127.0.0.1:8000.
