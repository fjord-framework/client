<p align="center">
  <img src="./readme_materials/fjord.png" width="500" height="200" />
</p>

# Test Client 
This repository contains a demo `HTML` file you can use to create a new `EventSource` object to stream data from Fjord. 

## Prerequisistes
1. Application Load Balancer URL 
2. Kafka Topic you will be listening for
3. UserID
4. JWT Token (if being used)

## Steps
1. Open the HTML file and fill the respective lines with your information.
2. Update line `66` to process incoming data as desired.

That's it! As data becomes available, your page will automatically render the data.