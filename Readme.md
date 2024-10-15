<h1>Cyclist Capstone Project</h1>
<h2>Description</h2>
<p>Cyclist is the biking company which rents bikes. They have many biking stations in the locations around IL. They offer a Single trip pass, Full day pass [Casual for both passes], and Annual membership [Member]. They have been growing steadily with number of riders using their bikes. In the recent business meeting the CEO had announced the next target. It is well observed that annual memberships had given good profits than casual members. Now the CEO wants to increase the number of Annual memberships. He had assigned this role to the marketing department and as well to the Data team.</p>
<h2>Problem Statement</h2>
<p>Analyse how different were the riding habits of casual members from the annual members. Provide insights and recommendations to the team.</p>
<h2>Dataset</h2>
<p>The size of the Dataset after extracting is 10Gb, the original dataset was in zip files. We have the ride data of the decade. We are filtering the data to the latest 12 months' ride data. This is the raw data for our data analysis. </p>
<href>
<h3>Data Cleaning and Transformation</h3>
<p>Most of the values for columns 'start_lon', 'start_lat', 'end_lon', 'end_lat' were NaN. Hence we dropped these columns.</p>
<p>We had converted the 'start_at', 'ended_at' columns to Data_time datatype.</p>
<p>Added new column 'ride_Journey' which is the total time taken for the journey in Minutes</p>
<h2>Data Visualization</h2>
<p>I used PowerBI to visualize my final processed data and grasp some patterns and habits of different riders.</p>
