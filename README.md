# mars-images-by--nasa
This Project uses nasa API to fetch Images and their data using Javascript and presents them using html
https://narayanshastri.github.io/mars-images-by--nasa/

### **Code Overview:**
1. **Head Section:**
   - Includes meta tags for compatibility and responsiveness.
   - Links the Bootstrap library for styling.
   - Adds an inline `<style>` tag for custom CSS (currently empty).

2. **Script:**
   - Defines the `bodyload` function to fetch data from NASA's API.
   - Processes the JSON response and dynamically populates a table with rover photos, IDs, camera names, and rover names.

3. **Body Section:**
   - A button triggers the `bodyload` function to load and display data.
   - A table structure is provided with headers to display the fetched data.
