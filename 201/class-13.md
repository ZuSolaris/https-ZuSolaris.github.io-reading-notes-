#Reading Assignment 13

## Local Storage and How To Use It On Websites

**Why would a developer use local storage for a web application?**

A developer would use local storage off of someone's computer to be able to save a state or instance of the person's data or progress. This is because HTTP is stateless and by default. So everytime the page is loaded the page is wiped.

**What information should not be stored in local storage?**


You should never store personal information on local storage the ability for your information to be exploited is much too great. Cookies can be carried far and wide and security vulnerabilities are a serious thing. 


**Local storage can store what type of data? How would you convert it to that type before storing?**

Local storage can only store specific keys that are saved in strings. Objects and data will be saved but they aren't the real thing. There are native JSON.stringify() and JSON.parse() methods to work around this. Example given below!

    var car = {};
    car.wheels = 4;
    car.doors = 2;
    car.sound = 'vroom';
    car.name = 'Lightning McQueen';
    console.log( car );
    localStorage.setItem( 'car', JSON.stringify(car) );
    console.log( JSON.parse( localStorage.getItem( 'car' ) ) );

<img src="https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/93e057af-227f-4da7-831a-58df5c6eea93/console2-e1285930703974.png" alt="Profile pic of me" width="400"/>


[Back to Home](https://zusolaris.github.io/reading-notes/)