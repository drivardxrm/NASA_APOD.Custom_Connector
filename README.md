# NASA Astronomy Picture of the Day - PowerPlatform Custom Connector

Custom connector used to fetch NASA's Astronomy Image of the Day (APOD)

Get your free NASA API Key @ https://api.nasa.gov/ 

# Installation

To install the connector, follow these instructions from the custom connector gallery 
https://www.connector.gallery/installation

# Inputs
![image](https://user-images.githubusercontent.com/38399134/133945953-96437955-e917-45f7-8ece-8943d9ab7caa.png)

| Properties         | Description                                                                                  | 
|-------------------|----------------------------------------------------------------------------------------------|
| Date         | YYYY-MM-DD (Optional : leave blank to retrieve today's image)                       |         

# Outputs

| Properties         | Description                                                                                  | 
|-------------------|----------------------------------------------------------------------------------------------|
| copyright         | copyright information                       |         
| date       | Date of the APOD query (YYYY-MM-DD)                       |         
| explanation       | Description of the APOD image                                                                  | 
| media_type       | 'image' or 'video'                                                                  | 
| service_version       | Version of the API                                                                  | 
| thumbnail_url       | thimbnail image when the media_type is 'video'                                                                  | 
| title       | Title of the APOD image                                                                  | 
| url       | URL of the image or video                                                                  |
| hdurl       | URL of the image in HD format                                                                  |



# Usage

Once installed, in the Power Automate editor, select the '**Custom**' tab and select the '**Nasa - Picture of the day**' connector.

![nasa_apod_create](https://user-images.githubusercontent.com/38399134/133869598-27068647-c63a-4c81-aef7-b20ecb39094a.png)

Name your connection and enter your free API key

![nasa_apod_create2](https://user-images.githubusercontent.com/38399134/133869571-f695e652-ae20-4e77-90d5-f86fb3a297f9.png)

(Optional) Choose the date of the image to retrieve. Leave blank to retrieve today's image.

![image](https://user-images.githubusercontent.com/38399134/133945953-96437955-e917-45f7-8ece-8943d9ab7caa.png)

The output of the action will look like this

![image](https://user-images.githubusercontent.com/38399134/133946033-ecba1d63-486c-45ec-84ed-dab1050388f7.png)
![image](https://user-images.githubusercontent.com/38399134/133946046-7bcc3746-6b6d-48c2-bdfd-5e2ee2b9d3fc.png)

You can then use the output as you wish in your flow. 
For example here the image and description are used to create an In-App notification

![image](https://user-images.githubusercontent.com/38399134/133946142-96ef4d05-5405-4066-912f-b5059ca4d08c.png)







