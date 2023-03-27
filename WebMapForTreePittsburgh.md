# Bid for Web-based Map Redesign
This is a web-based map redesign bid for Tree Pittsburgh.

# Introduciton
The Tree Pittsburgh works to increase the number and diversity of trees, educate the community, and advocate for supporting policies. Tree Pittsburgh is requesting proposals for web-based map design, developing a custom, brand-ready base map for differentiating their organization and attracting attention to the map for future development. 

# Proposal and work plan 

Our team has the skills and knowledge required to successfully complete this project within the agreed timeframe and budget. We estimate that completing the following tasks will require **9 hours** of work: 

| Task1 | Develop a map that matches the overall look of the Tree Pittsburgh website | Time: 5h |
| ---------------| --------------- | --------------- |
|1-1 | Analyze the demand and expectation of the organization, and create a color palette that fits the overall look of the organization. | 1 h |
|1-2 | Create an accessible web page that includes screenshots at three distinct zoom levels using the redesigned base map. | 1 h |
|1-3 | Develop the custom base google map for the organization. Adjust the feature type, element type, and styler based on the color palette. | 2 h |
|1-4 | Finish and export the JSON code. | 1 h |

| Task2 | Document and create simple instructions on base map | Time: 4h |
| ---------------| --------------- | --------------- |
|2-1 | Provide a lookup table that documents the feature type, element type and stylers for all relevant features. | 1 h |
|2-2 | Provide a link on the web page to a downloadable JSON file. | 1 h |
|2-3 | Embed the redesigned basemap into the existing website. | 1 h |
|2-4 | Create simple instructions documenting and how to effectively use them. | 1 h |
 

# Price and final deliverables
For the final deliverable, the team will **embed the redesigned base map into the existing website, and provide instructions on how to use them effectively**. The overall work is **9 hours** in total. Based on the $100 per hour cost and estimated number of hours, the proposal requires **a total cost of $ 900** for completing the web page map redesign. This will ensure that Tree Pittsburgh has a modern, user-friendly website that effectively communicates its mission and encourages donations.


# Color Palette
Ecru White #FAFAF1

Cloudy     #B4ACA4

Gimblet    #C0BF78

Geyser     #CCD9DB

Pesto      #636E2E

Santa Fe   #B26B5B

![color panel](https://user-images.githubusercontent.com/128320071/227805579-e2928316-90a2-48af-815e-f97596ce6d29.png)

The colors are generated from the logo and website of Tree Pittsburgh. The background color is ecru white. The main color is green for showing the parks and green areas within the neighborhood. The cloudy color is generated from the brown trunk, which is used to represent the transportation system on the map. The red color is used to highlight public spaces such as schools and institutions. The blue is originated from the website to represent water in the water.

# Lookup table

| Feature type | Element type | Stylers |
| ---------------| --------------- | --------------- |
|Land parcel | Geometry | Color: Ecru White (#FAFAF1) |
|Landscape/Human-made | Geometry | Color: Ecru White (#FAFAF1) |
|Road | Geometry | Color: Cloudy (#B4ACA4) |
|Road | Geometry/Stroke | Color: Ecru White (#FAFAF1) |
|Road/Highway | Geometry/Stroke | Color: Cloudy (#B4ACA4) |
|Road/Highway | Geometry/Stroke | Color: Ecru White (#FAFAF1) |
|POI/Park | Geometry | Color: Gimblet (#C0BF78) |
|POI/Park | Label/Text fill outline | Color: Ecru White (#FAFAF1) |
|POI/SportsComplex | Geometry | Color: Pesto (#636E2E) |
|POI/School | Geometry | Color: Santa Fe (#B26B5B) |
|Water | Geometry | Color: Geyser (#CCD9DB) |

# Screen shots of base map
![screenshot1](https://user-images.githubusercontent.com/128320071/227804921-b26ece95-090b-4eb1-959f-4c9a085489ae.png)
![screenshot2](https://user-images.githubusercontent.com/128320071/227816911-129332f3-0f17-4824-932d-1add0caf8f7c.png)
![screenshot3](https://user-images.githubusercontent.com/128320071/227816922-3ee3ea31-8020-4e46-aa4b-e0cc34f055e0.png)

For the base map, I started with settling down the background color and water with ecru white and geyser. I tested brown for roads and found that it was too dark and might distract users’ attention from green areas, so I changed it to cloudy, with a white stroke to make it fit into the ground. Then I started testing around different colors to represent parks and green areas, fitting into the ground and water. Finally, I decided to use gimblet and pesto for various green areas to make it pop up from the map. Since Tree Pittsburgh also holds various kinds of educational events in the public space such as institutions and schools in the community, I used Santa Fe to show them on the map. There are potential chances of showing different locations of public events of Tree Pittsburgh. 


# Link to JSON file

Click for my JSON file: [TreePittsburghWebMap](TreePittsburghWebMap)


