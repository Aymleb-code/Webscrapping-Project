# Webscrapping-Project

In this project, we are doing a statistical study about music evolution 
since 1958. 

To do so, we scrap data from 3 websites and 1 API: Billboard, Tubes en France, 
Wikipedia and the Deezer API. 

We scrapped the data, generated some statistical graphs around them and 
created a Flask API to gather it all in a quick UI. 

### Here are the instructions for launching the Flask API:
- Clone the GitHub repository with Git 
- If you haven't got python in your device, install it 
(the tests have been done with version 3.10)
- Install the packages of the requirements.txt file
- Run the ui.py file 
- Open the http://localhost:8080 link in your browser

### Description of the API:
In the taskbar on the top of the page, you have 4 options:
- Hot100: viusalize the HOT100 of your chosen month 
- Stats HOT100: generate statistical graphs about HOT100 evolution
- Stats Top50: generate statistical graphs about TOP50 evolution
- Etude Comparative: comparative graphs about music evolution on HOT100 and Top50


### Project files:
- hot100_scrap: scrapping of Billboard website 
- top50_scrap: scrapping of Tubes en France website 
- wikipedia_scrap: scrapping of Wikipedia website 
- top50_analysis: graphs about top50 data 
- hot100_analysis: graphs about hot100 data 
- comparison_us_fr: comparative graphs about french and US music evolution
- ui: Flask API
- templates: all Flask API pages 
- static/default: Flask images and logos 
- static/uploads: temporal folder for session images 
