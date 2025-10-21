

# Bot Battlr

This a Bot Battlr Browse through a list of robots, view their details, and enlist them into your army.



## Features

- **Browse Bots**: View all available bots with their stats and information
- **Enlist Bots**: Add bots to your army (each bot can only be enlisted once)
- **View Bot Details**: Click on any bot to see detailed information
- **Release Bots**: Remove bots from your army without deleting them
- **Discharge Bots**: Permanently remove bots from both your army and the server


### Installation

1. Clone the repository:
   ```bash

  git clone `git@github.com:David-kuron1996/code-challenge-bolt.git`

   cd bot-battlr
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the JSON server:
   ```bash
   npm run server
   ```
   This will start a local server at `http://localhost:3000/bots`

4. In a separate terminal, start the React app:
   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000/bots`

## Project Structure

```
bot-battlr/
|- public/
- index.html...
|- src/
|   - components/
|   │   - App.js
|   │   - BotCollection.js
|   │   - BotCard.js
|   │   - BotSpecs.js
|   │   - BotArmyCard.js
|   │   - YourBotArmy.js
|   │   - SortBar.js
|   |- App.css
|   |- index.css
|   |- index.js
|- db.json
|- package.json
|- README.md
```

## API Endpoints

- `GET /bots` - Fetch all bots
- `DELETE /bots/:id` - Delete a bot by ID

## Usage

1. **Browse Bots**: The main page displays all available bots in a grid layout.
2. **View Bot Details**: Click on any bot card to see detailed information.
3. **Enlist Bots**: Click the "Enlist" button to add a bot to your army.
4. **Manage Your Army**: In the "Your Bot Army" section, you can release or discharge bots.

## Technologies Used

- **React**: Frontend framework for building the user interface
- **json-server**: Mock API server for development
- **CSS**: Styling for the application


### Making Changes to the API

The application uses a local JSON server for development. To modify the bot data:

1. Edit the `db.json` file
2. The changes will automatically reflect in the application if the server is running

## Contributing

This project is private and maintained for educational purposes. If you have suggestions or improvements, please create a pull request.

## License

This project is private and not intended for public distribution.

