# Rails Chess Application
This README document details the setup, configuration, and basic usage instructions for the Rails Chess Application, a web application for playing chess online with real-time updates via Hotwire and Action Cable.
# System Requirements
- Ruby version: 3.3.0
- Rails version: 7.1.3.2
- Database: SQLite3
- Redis server for Action Cable
# Installation
Clone the repository to your local machine:
```
git clone https://github.com/BinhNguyenDang/chessEngine.git
cd chessEngine
```
Install the required gems:
```
bundle install
```
Set up the database:
```
rails db:create
rails db:migrate
rails db:seed
```
Start the Redis server for Action Cable (if needed):
```
redis-server
```
Run the application:
```
bin/dev
```
or
```
rails s
```
# Features
- Real-Time Chess Gameplay: Utilizes Hotwire and Action Cable for real-time game state updates.
- Turbo: Enhances navigation and form submission without full page reloads.
- Stimulus: Modestly manages JavaScript components.
- CSS and JS Bundling: Uses cssbundling-rails and jsbundling-rails for asset management.
- Responsive Design: Adapts layout for different devices using modern CSS.

# Development Tools
- Debugging: Integrated with debug gem for easier debugging in development.
- Web Console: Provides a web-based console on exception pages for immediate inspection.
- System Testing: Uses Capybara and Selenium for full-stack browser testing.
- Faker: Generates fake data for testing and seeds.
- Simple Form: Simplifies form markup in Rails applications.

# Configuration
The application is configured to run with the following key components:

- Puma as the web server.
- SQLite3 for the database in development and test environments.
- Redis for Action Cable to enable real-time features.



# DEMO:
![image](https://github.com/BinhNguyenDang/chessEngine/assets/146049423/2517ced1-e23a-42d2-ac1d-32f719b87e26)

![image](https://github.com/BinhNguyenDang/chessEngine/assets/146049423/faa0f169-b864-4a96-a8ec-f4f372b423cd)

![image](https://github.com/BinhNguyenDang/chessEngine/assets/146049423/bcd5cfaf-6300-4b34-86ad-706271a22cdd)

![image](https://github.com/BinhNguyenDang/chessEngine/assets/146049423/52a31ff3-67fe-4b29-b088-a8c211db9491)


