# assignment2-PunyamAnand
New repo for Assignment02<br>
# Maheshwar Punyam Anand<br>
###### My favorite team sport is cricket and love team INDIA.<br>
Cricket is one of our **emotions** in our country. It is the **best recreation** that we have to relax our mind. i really enjoy it a lot. I'm a hardent fan of **Virat Kohli**.

***
### Team INDIA
1. M.S.Dhoni
2. Virat Kohli
3. Rohit Sharma

### Other Good Teams to watch
* Pakistan
* Australia
* New zealand

[AboutMe_Link](AboutMe.md)

***
### **Tourist Places**

The below table indicates the country's which are good to visit and few of the worlds most beautiful places. One must make a look over them atleast once in their lifetime.

|# Name of the Country |# Reason for Recommendation |# No of days would like to spend |
| :---: | :---: | :---: |
| INDIA | To view its culture and Heritage | LifeTime |
| UAE | To view its futuristic projects | 30 Days |
| USA | To learn the latest technology | 1000 Days |
| CHINA | To watch their working culture and their large established Industrial units | 30 Days |
| AUSTRALIA | Especially for kangaroos | 30 Days |

***
### **Pithy Quotes**

> Just believe in you, you can By *"Maheshwar Punyam Anand"*.

> Trust no one, Kill any one but be only one By *"Billa"*.

***
### **Code Fencing**

> SVG patterns scaling the way pattern is not cut off

Link for reference <https://stackoverflow.com/questions/61179458/svg-patterns-scaling-the-way-pattern-is-not-cut-off>

```

<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>

```

Code Snippet Link <https://css-tricks.com/snippets/svg/svg-patterns/>

