Title: Time-Based Image Display Webpage

Overview:
This webpage displays an image that changes based on the user's current local time. It uses JavaScript to detect the hour and sets the image source accordingly:

- 6am to 12pm: Morning (sunrise image)
- 12pm to 6pm: Afternoon (daytime image)
- 6pm to 6am: Night (Night image)

Assumptions:
- Images are pulled dynamically from Unsplash using keyword-based search.
- The user's system clock is assumed to be accurate.
- The display logic runs once when the page loads.

Known Issues:
- The image won't automatically update if the time changes while the page is open (requires refresh).
- Images are randomized on each reload due to Unsplash behavior.

Public URL:
https://kaylaheady.github.io/time-based-image/

How to Deploy:
1. Push the project to a GitHub repository.
2. Enable GitHub Pages under repository settings.
3. Set the source to the `main` branch and root directory.

