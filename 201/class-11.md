# Reading Assignment 11



## **Video and Audio Content**

https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content
**Explain how the ability to use video and audio on the web has evolved since the early 2000s.**
Audio and video back in the early 2000's was possible through propretary software. Such as flash player (RIP) and silver light. But now since those are obsolete we use audio and video elements with the implementation of JS APIs.

**Describe the use of the src and controls attributes in the video element.**

Src: In the same way as for the img element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.

Controls: At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.

**Why is it important to have fallback content inside the video element?**
Paragraphs inside of a video tag are called fallback content in case the browser doesn't support the video. You can even include a tag just in case.

**Write a very short story where audio and video are characters.**
There were two best friends called audio and video. They were very best friends. They were very similar and could do very similar jobs. However video could display pictures while being able to talk they were able to reach a greater audience. Audio was able to only speak but they couldn't write because it was beyond their capabailities. Video could reach their message to others while supporting a different way to speak. They spoke in .mp4 while audio spoke in .mp3. Though their differences in abilities. They both fulfilled their purposes for different usages. 

## **A Complete Guide To Grid**
Source: https://css-tricks.com/snippets/css/complete-guide-grid/#aa-basics-browser-support

**How does Grid layout differ from Flex?**
Where flex changes due to the content within the container it is placed in. Grid types have to be declared and the CSS will have to define elements to append to the grid. It can be very useful especially for different screen resolutions. 


**Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**

**Grid Container**

The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.

**Grid Item**

The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.

**Grid Line**

The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.


## **Responsive Images**

**Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

The message you want to convey to a user can seriously change if the screen resolution of a device seriously changes it. The images will start becoming distorted if not a vector image, and unnessecary bandwidth can also start to be wasted with users who are using significantly smaller devices! Making images more responsive are great ways to improve user acessibility across all devices!



**Define the following img attributes srcset and sizes. Write an example of how they are used.**

srcset defines the set of images that we allow the images to choose and the size of them. It will be used in an example such as this. Say you have a 720px Image and a 360px image and the 720px image doesn't fit on the site. src set will go along its list of images and use the 360px image if it is found to be more suitable. 

Size are the list of varying sizes for an image set. srcset will most likely be working with this attribute to determine the best fit for the browser. 


**How is srcset more helpful for responsive images than CSS or JavaScript?**

It is much more useful than CSS or JS because when you load an a page on a browser, it already pre-loads all the images. It would then be inefficent to reload the page and waste more bandwidth with a new image. It's just not a very responsive method. 

[Back to Home](https://zusolaris.github.io/reading-notes/)

