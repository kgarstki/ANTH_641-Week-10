# Week 10 Exercise 1 TimeMapper

## Part One – Create a dataset from Open Context and use it in TimeMapper

We’re going to create a TimeMap about the types of ceramics found through time in the survey area of the Pyla-Koustopetria Archaeological project (read about the project here). The benefit of the TimeMap is combining geospatial information with chronological information, while at the same time conveying an archaeological narrative. Below are some instructions on the exercise, but I recommend first watching the video associated with this activity – it will go into more detailed explanation on how to use the tools. 
1. To begin, we’ll create the dataset we’ll use. Go to the Open Context project page, and click on the sample data records. Limit the search to just those records that are “Linked to images.” Export these data as a csv file (there should be 935 records). 

2. We will now significantly edit the dataset. Save a new file as “PKAP_edit” from the dataset you’ve download, just so we can go back in case we mess up. We’re focused on telling a very specific story – how do ceramic styles change over time in this region. So, we’re going to cut these 935 records to 15. First, sort by the “Period” column alphabetically. Then go through and highlight 15 full records, each from a different chronological period. Delete all of the other records except those 15. 

3. Next, we’ll only keep the columns we need to use for TimeMapper. Delete all columns except: URI, Project Label, Project URI, Latitude, Longitude, Early BCE/CE, Late BCE/CE, Chronotype, Period, Find Color, Fabric group, Extant Part. And create a new column called: “Description”. Also add a new column called “Location” – this will be a formula column created like so: =CONCATENATE(D2,",",E2). D2 is a stand in for the Latitude column of a record and E2 is a stand in for the Longitude column. 

4. Give half of your records a sentence or two textual descriptions of the ceramics (make sure to include the period it’s from).

5. Make sure the TimeMapper Template is downloaded. We’ll copy and paste full columns from PKAP_edit into our template. Copy the following: 
•	Chronotype > Title
•	Early BCE/CE > Start
•	Late BCE/CE > End
•	Description > Description
•	URI > Web Page
•	Location > Location
•	Project Label > Source
•	Project URI > Source URL

6. Upload this TimeMapper excel sheet into your Google Drive and “Save as Google Sheets.”

7. Next is the most time-consuming part. Use the record URI and go to the artifact Open Context page. Next choose one of the linked images towards the bottom of the page, which will open a new tab. Click the blue “Download File” button on the right. This will open a new tab – copy the link of this tab, do not download the file. Paste this link into the “Media” cell for that artifact record in your Google Sheet.  

8. In your google sheet, go to File and Publish to the Web. And click Publish. Then click on Share in the top right corner. Make sure your document is open to the public. Copy the link that is provided to you – this is what you’ll paste into TimeMapper. 

8. Now your data should be all set. Go to the TimeMapper site. TimeMapper is an open-source project of Open Knowledge Foundation Labs. It is possible thanks to a set of awesome open-source components including TimelineJS, ReclineJS, Leaflet, Backbone and Bootstrap. You can find the full open-source source for TimeMapper on GitHub here. 

9. You can log in with your Twitter log in, or you can create a map anonymously – the main benefit of logging in is that you can return to your different projects. Click “Get Started Now.” Paste your Google Spreadsheet URL into the Data Source and Title your Map. Last thing to do is Publish it.   

## Part Two – Create your own TimeMap from a unique data source. 

I want you now to create a brand new TimeMap from the skills you learned above. You can use any dataset you’d like, as long as you have 10 entries. Remember, you’re using this platform to tell a story that highlights the spatial and temporal components of an archaeological context. You don’t have to use media in your TimeMap, but it always helps. Try to include enough description that a non-archaeologists can follow your narrative. 
Include the link to both TimeMaps you’ve created (from parts 1 and 2) in your blog post for the week.  

