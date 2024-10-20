# Getting Started with Speakr

**Follow these steps to launch the application on your local machine:**

### Step 1: Install dependencies
Run the following command to install all required dependencies:
```bash
npm install
```


### Step 2: Add your API key
- Visit the [Speakr](https://speakr.online), and navigate to the playground to obtain your API key.
- Once you have the key, create or update your `.env` file in the project directory by adding the following line:

```bash
REACT_APP_API_KEY = your_api_key_here
```

### Step 3: Start the application with HTTPS
Use the following command to start the application in development mode with HTTPS enabled:

```bash
HTTPS=true npm start
```