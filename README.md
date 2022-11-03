# UFOs
# Overview
The purpose of this project was to build a webpage that displays UFO sightings from a data.js file and allow the user to filter that data. The webpage was built with HTML, CSS, and JavaScript, with additional functionality provided by Bootstrap and D3.js. The webpage is responsive and will adjust to the size of the screen it is being viewed on.

# Results
The data on the webpage is originally shown in a table format as such:

![Figure 2](Figures/Fig_2.png)

The user can then filter the data with the following categories (placeholder text is shown in the input boxes to help the user know what to enter):

![Figure 1](Figures/Fig_1.png)

The user can filter the data by entering a value in the input box and when clicking out of the box, the table will automatically update to show only the data that matches the filter criteria. 

For example, if the user wanted to see all of the UFO sightings in the city of San Diego, they would enter "san diego" in the state input box and the table would update to show only the data for that city:

![Figure 3](Figures/Fig_3.png)

# Summary
A drawback of using this filtering system without a button to apply the input is that the table will update every time the user clicks out of the input box. This can be a bit distracting for the user and can make it difficult to see the data that is being filtered. Additionally, the user may not immeditately know that they need to click out of the input box to apply the filter.

One recommendation for further development would be to continuously update the table as the user types in the input box. This would allow the user to see the data that is being filtered as they type and would make it easier to see the data that is being filtered. Additionally, a dropdown menu for each category would make it easier for the user to select the data they would like to include or not include. This would also make it easier for the user to know what they can filter by, for example, there is only one entry for the country "ca" so the user would know that they can filter by country.