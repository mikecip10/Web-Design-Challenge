# Web-Design-Challenge

## Objective: For this homework we be created a visualization dashboard website using visualizations we've created in a past assignment (weather data).

### [Link to website]: (file:///D:/CODE/Homework%2011/Web-Design-Challenge/landing.html)

### The website includes:
1.) A landing page that allows the user to determine which chart they want to see a deeper analysis on.

2.) A navigation tab that allows the user to browse through the various pages.

3.) A comparison tab that allows the user t0 visualize all the charts.

4.) A data tab that allows the user to see the raw data set that was used to create the charts/analysis



## LANDING PAGE

![image](https://user-images.githubusercontent.com/83014623/126922347-e616221c-3f28-45c1-9c3f-d7485d10bb60.png)

## LATITUDE vs. TEMPERATURE

![image](https://user-images.githubusercontent.com/83014623/126922650-2a23e61a-8bf8-41b0-b2c4-d99a72d4e1cb.png)

## LATITUDE vs. CLOUDINESS

![image](https://user-images.githubusercontent.com/83014623/126922799-f0b4f2bd-6413-480c-a174-c05cadee7256.png)

## LATITUDE vs. HUMIDITY

![image](https://user-images.githubusercontent.com/83014623/126922919-70d55e9a-484b-48ff-ba25-d9f5724cbc86.png)

## LATITUDE vs. WIND SPEED

![image](https://user-images.githubusercontent.com/83014623/126923057-d5e06270-1dea-4ed5-8d81-6a66d28a8a9d.png)

## COMPARISON PAGE

![image](https://user-images.githubusercontent.com/83014623/126923251-b258b730-296d-4a5e-9d0c-3b198425d0f8.png)

## DATA PAGE

![image](https://user-images.githubusercontent.com/83014623/126923318-a8787192-731b-410a-88f7-f0e038ccf2f9.png)



## The instructions for this homework are listed below:

### Website Requirements
For reference, see the "Screenshots" section below.
The website must consist of 7 pages total, including:

### A landing page containing:

An explanation of the project.
Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.


### Four visualization pages, each with:

A descriptive title and heading tag.
The plot/visualization itself for the selected comparison.
A paragraph describing the plot and its significance.

### A "Comparisons" page that:

Contains all of the visualizations on the same page so we can easily visually compare them.
Uses a Bootstrap grid for the visualizations.

The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

### A "Data" page that:

Displays a responsive table containing the data used in the visualizations.

The table must be a bootstrap table component. Hint

The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here

### The website must, at the top of every page, have a navigation menu that:

Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).

Finally, the website must be deployed to GitHub pages.
When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.
Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

### Considerations

You may use the weather data or choose another dataset. Alternatively, you may use the included cities dataset and pull the images from the assets folder.
You must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
Be sure to use a CSS media query for the navigation menu.
Be sure your website works at all window widths/sizes.
Feel free to take some liberty in the visual aspects, but keep the core functionality the same.
