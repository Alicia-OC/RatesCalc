# RatesCalc

This is a personal project I have built on my free time.

All the commits in this repo have been manually copied from the original repo because there was sensitive data that couldn't be shared and that I missed in a few commits.
The date included in each commit description is the original date when the commits where done.
Yes, it looks ugly, I know. But my GitHub expertise doesn't allow me to re-write the commit history and delete the sensitive data without messing it up, so here we are.

I'm a Localization project manager and I have created this small app to make my work easier and more automatized.

For this app to work, you need to upload a CSV with this structure:
A - Source (English only)
B - Target
C - Vendor name
D - TR rate
E - PR rate
F - TEP rate
Then, it will calculate what rate you should ask your client based on the MarkUp factor: cost price * markup factor (MU)
Your cost is calculated by the app by getting the most ocurred rate for each chosen language and service.
The MU factor is provided by the user by tiping it in an input, by default it's 2.

This small app has been programmed only in one HTML file because the main purpose was creating a tool that could be used by anyone without hosting it somewhere. That meant no backend, no packages and basic coding with just a few options for the user.
