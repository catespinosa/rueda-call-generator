# Project Overview

## Project Description

The rueda de casino call generator plays the roll of the "caller" in the rueda so you can practice the turns.

## Functional Components 

This is a breakdown of the top level functionality for final project

* When the user clicks the call generator button, a new turn pattern will be displayed along with description and video if available






<!-- ## Helper Functions
Use this section to document all helper functions. These functions should be versatile enough to be reused in other projects

Function to parse API response and push objects into array and then it's called within another function.


	function parseResults(result){

	    var all_tracks = []; //this is a placeholder for what we want to return

	    //console.log('this is the tracks array',all_tracks)

	    result.forEach(function(row){

	      var onetrack = {

	        title : row.name,

	        artist : row.artists[0].name,

	        album : row.album.name,

	        link : row.preview_url,

	        image : row.album.images[2].url

	      };

	      all_tracks.push(onetrack); //we want to push the object in to the all tracks array

	    });

	    return all_tracks;
	 };
 -->


## Additional Libraries
 Use this section to list all supporting libraries and their role in the project

* Jquery
* Bootstrap


<!-- ## JSON Data Keys
 Use this section to list specific JSON Data Key mappings. 



## jQuery Functional Requirements
 Use this section to list some, but not all, of the jQuery methods discovered while working on this project.
 

## Change Log
 Use this section to document what changes were made and when.

|11/11/16 | Changed project goal... no pressure :)|

|11/19/16 | oauth access token expired so could not get user playlists, switched to get an api response with several track ids.|

|11/19/16 | Added BS thumbnails in HTML and not jquery because I couldn't make it work|

|11/23/16 | Changed how to display songs from BS table to BS modal|


## Issues and Resolutions
 Use this section to list of all issues encountered and their resolution

ERROR: 401 Unauthorized when trying to grab user's playlists using access token. Did not realize access token expires.

RESOLUTION: https://developer.spotify.com/web-api/get-several-tracks/ Grabbed several tracks by ID and got a response that contains an object whose key is tracks and whose value is an array of track objects in JSON format.


**ERROR**: [object%20Object]:1 GET file:///Users/mzy36638/Desktop/GA_JSD/catespinosa.github.io/jsd920_class_repo/projects/final_project/public/[object%20Object] net::ERR_FILE_NOT_FOUND                             
**RESOLUTION**: Needed to target the image URL within the images {} object


 -->





