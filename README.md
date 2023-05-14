# Run locally
    * Run this command "git clone https://github.com/TakyMalika/react_native_jobs.git"
    * Run "npm install"
    * Open a browser and go to https://rapidapi.com/hub
        * Sign in and create an account 
        * Search for "JSearch"
        * Subscribe to JSearch
        * In JSearch, click on it's "Endpoints" section
        * Checkout it's "Code Snippets" and copy the "X-RapidAPI-Key"
        * Come back to the local repository and open './hook/useFetch.js' and './app/search/[id].js' files
        * In './hook/useFetch.js', go to line 13. Paste the copied "X-RapidAPI-Key" inside the empty string
        * In './app/search/[id].js', go to line 29. Paste the copied "X-RapidAPI-Key" inside the empty string
    * Run "npm start"
    * Enjoy playing around
        * To test it on web, follow the link showing on the terminal
        * To test it on IOS or android, download Expo and scan the QR code shown on the terminal 

# Tech stack
    * React Native
    * Expo
    * JSearch API
