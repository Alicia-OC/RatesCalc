# RatesCalc

# Translation Rate Calculator

## About

This is a personal project I built in my free time to make my work as a Localization Project Manager more efficient and automated.  

**Note:** All commits in this repository have been manually copied from the original repository due to sensitive data that couldn't be shared. Some commits were missed, and the date included in each commit description reflects the original commit date. I acknowledge it may look a bit messy, but my GitHub expertise doesn't yet allow me to rewrite commit history and remove sensitive data without causing issues. I'll work on this in the future! 😊

## Purpose

The app is designed to be a simple tool for anyone who needs to quickly calculate translation rates based on vendor data. Since the goal was to make it easily accessible without needing to host it, I kept the app simple with no backend, no dependencies, and minimal options for the user.

## How to Use

1. **Upload Your CSV**  
   Prepare your CSV file and upload it to the app.

2. **CSV Structure**  
   Ensure your CSV follows this structure:
   - **A**: Source Language (currently, the app only works with English)
   - **B**: Target Language
   - **C**: Vendor Name or ID
   - **D**: Translation Rate (TR)
   - **E**: Proofreading Rate (PR)
   - **F**: TEP (Translation + Editing + Proofreading) Rate

3. **Select Languages**  
   Choose the target language(s) you want to calculate the rate for. You can select more than one!

4. **Enter Markup**  
   Input your desired markup factor. The default value is `2`.

5. **Click the Button!**  
   Once you’ve entered all the information, click the button! The app will calculate the appropriate rate to ask your client based on the most frequent rate for each selected target language and the markup factor:
   ```text
   Client Rate = Cost Price * Markup Factor (MU)
