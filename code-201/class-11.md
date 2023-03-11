# Class 11 Reading Notes

## Video and Audio Content

1) Using video and audio on webpages began using plugin-based tech like flash and silverlight, however these had problems with security and accessibility. Now in order to have video and music on a webpage they have been imbedded into the HTML with 'video' and 'audio' tags. These tags are better with accessability and don't have issues with security.

2) The source tag for a video is very much the same for the img tag, this is the path from where the video exists. In addition the control tag is for controlling the video while it plays on the webpage, there are accessibility concerns here so the video must be able to stop and start at the users control. At a minimum the user must be able to start, stop and control the volume of the video.

3) Fallback content is used when the browser cant access the file path for the video or for some reason the browser doesn't support the video element. The fallback content will show allowing the user to see something instead of the video. 

4) Once upon time there were two hero's: audio and video. These two hero's would travel to distant lands using these very untrustworthy horses named flash and silverlight. These horses would sometimes take them to their wrong destination and even stop for a nap in the middle of the conquest. The hero's were tired of these unreliable companions, so they went to talk to the horse-trader to see what could be done. Their Name was HTML and he was able to trade in their unreliable horses for two knew horse who had the same name as the hero's. Now with the hero's audio and video riding their trusty steads, they are now able to travel to far off lands and saving the kingdom.

## A Complete Guide to Grid

1) The difference between flexbox and grid are huge, the ideas are similar being able to sort items on a webpage. However flexbox can really only do that on a objects that are within the same block. Grid can change the layout of the entire webpage.

2) 

- Grid-container: This is how grid will be applied, its the direct parent if all the grid items.

- Grid-item: These are the direct child elements of the parent 'grid-container' any additional tag inside the item is not considered a grid item.

- Grid-line: These are the lines that make up the structure for the Grid container. The webpage or block is broken down to columns and rows where the tags are placed.

## Responsive Images

1) Developers should makes images more responsive due to the fact that technology has grown since the early 2000's. There are many different screen sizes available to the public and webpages need to adapt to the different sizes that are available. In addition Smart phones have also created a problem with webpages. So being able to see the webpage on a smaller screen then a monitor has also made the need for making images responsive.

2)

- srcset: defines the set of images which the browser can chose from. the information is written as "the image file name and the intrinsic width in pixels. w will be the unit not px.

- sizes: defines what the media condition might be and choses the images best for that size. this is written as "the media condition (max-width:600px) followed by the width of the image when the screen size is true.

3) When the webpage loads it will start to preload and images first before the main parser has been loaded and begin to read the CSS and JAvaSCript. By using srcet on the image it will cut down on load times and will allow the image to load in the correct size instead of potentially loading in the original size and then scaling down to the correct size.