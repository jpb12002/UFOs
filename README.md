# UFO Sightings with JavaScript

## Overview of the Project
The purpose of this analysis was to display gathered UFO sighting data as a table on an HTML webpage. We also used JavaScript to create filters by which users of the webpage can filter the table to find specific UFO sightings that match the user inputs. Finally, we used CSS and Bootstrap functionality to help create visualizations and stylistic formatting for the webpage. 

## Results
### Webpage Contents

![Image of Webpage with Labels](https://github.com/jpb12002/UFOs/blob/main/Webpage_Labels.png)

1. Navigation Bar
  - The "UFO Sightings" text at the top left corner of the webpage can be clicked to refresh the webpage.
 
2. Page Header
  - Shows the webpage title "The Truth Is Out There" overlaid on an image of Earth at night. 

3. Article Title
  - Shows the article title "UFO Sightings: Fact or Fancy? Ufologists Weigh In" on the left-hand side of the webpage.

4. Article
  - Full blog article text included on the right-hand side of the webpage.

5. Filters for the Table
  - The image above shows the empty filters and all UFO sighting tables entries. By entering applicable data into the filters, such as "1/10/2010" in the "Enter Date" filter, only the UFO sighting data that matches that criteria is displayed:

![Image of Date Filter](https://github.com/jpb12002/UFOs/blob/main/Date_Filter.png)

  - By entering more data into the filters, such as "nc" in the "Enter State" filter, the UFO sighting data that matches the criteria is further narrowed: 

![Image of Date and State Filter](https://github.com/jpb12002/UFOs/blob/main/Date_State_Filter.png)

  - Users need to either click on the webpage after entering their filters or hit the "Enter" key on the keyboard to update the table with the new data.

6. Table of Sightings Data
  - This table contains all of the UFO sighting data that users can search for by entering data into the filters. The amount of table data displayed is narrowed as more filters are used. 

## Summary
### Drawback
One drawback of this new filter design is the text input for the filters needs to be an exact match of the characters in the UFO sightings table. For example, entering "01/10/2010" into the "Enter Date" filter will not yield any results because none of the dates in the table begin with "01" as the month. Similarly, entering "NC" into the "Enter State" filter will not yield any results because none of the states in the table are capitalized. 

### Recommendations
- Use dropdown menus for the filters with all possible options rather than relying on users to input the exact correct text. 
- Keep the "Filter Table" button since some users may not find it intuitive to hit the "Enter" key or click on the webpage after inputing their filters. 
