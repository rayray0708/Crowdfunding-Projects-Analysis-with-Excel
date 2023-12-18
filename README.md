![Illustration of crowdfunding](https://imageio.forbes.com/specials-images/imageserve/5dfd02fc4e2917000783972d/crowdfunding-concept/0x0.jpg?format=jpg&crop=1000,563,x0,y73,safe&width=1440)
# Crowdfunding-Projects-Analysis
## Description
In this project, I'm analysing 1,000 crowdfunding projects all over the world to uncover hidden trends in order to better understand the common characteristics of successful crowdfunding projects. An Excel file with a report are included.

## Usage
To see the pivot tables and charts I generated from this dataset, please download the "CrowdfundingBook.xlsx" file and open it in Microsoft Excel. 

## Installations
Please ensure you have Excel pre-installed. Otherwise, please follow the instructions here to install Excel:
`https://support.microsoft.com/en-us/office/download-and-install-or-reinstall-microsoft-365-or-office-2021-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658`

## Crowdfunding projects analysis
The modified Excel file has 13 columns and 6 new added columns:
1. `Percentage funded`: how much money a campaign made relative to its initial funding goal
2. `outcome`: whether the campaign was successful or not. Successful campaigns were coloured green, unsuccessful red and currently live blue and cancelled purple. 
3. `Average donation`: how much each project backer paid on average.
4. `category`: campaign category.
5. `sub-category`: campaign sub-category.
6. `date created conversion`: converts the data contained in launched_at into Excel's date format using `=A1/86400000+DATE(1970,1,1)`. 
7. `date ended conversion`: converts the data contained in deadline into Excel's date format. 

![Alt text](<Screenshot 2023-12-18 at 3.11.36 pm.png>)

The following visualisations were created:
1. a pivot table that counts how many campaigns were successful, failed, cancelled, or are currently live per category
![Alt text](<Screenshot 2023-12-18 at 3.13.00 pm.png>)

2. a stacked-column pivot chart that can be filtered by country based on the table that I created
![Alt text](<Screenshot 2023-12-18 at 3.15.31 pm.png>)

3. a pivot table with a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years, and a pivot chart line graph
![Alt text](<Screenshot 2023-12-18 at 3.20.20 pm.png>)

Bonus chart:
![Alt text](<Screenshot 2023-12-18 at 3.21.51 pm.png>)

## Credits
Special thanks to the following individuals for their contribution in this project:

-Jefferey-Chieh Liu (Instructor's team)
