# Responsive Web Design

Every week, millions of people come online for the first time. Google’s Next Billion Users initiative reports that the majority of people using the internet for the first time are doing so via a mobile device – not a computer, that devices are often shared with friends and family, and they tend to prefer voice and visuals over typing or reading.

Insights such as this are important for web developers and helps explain why designing with a mobile-first approach should be the industry standard. 

**What is mobile-first?**

Mobile first means writing CSS for mobile devices first and using media queries to add in styling for large screens

Using the min-width media query, for example: min-width: 600 means that at screen sizes at a minimum of 600px and above, we will start to add to the desktop layout 

**Why mobile-first?**

Websites are naturally responsive before any CSS is added

When we style for desktop first, we’re adding margins, padding, widths and moving things around. Complexity is being added. This is absolutely necessary because there is more space to work with. 

However, with a mobile device, the less available space means that not a lot of CSS is required – because mobile layouts tend to be very simple, starting simpler and adding complexity is easier than taking away complexity

**Which media queries to use?**

600px, 900px, 1200px and 1800px – These represent the 14 most common screen sizes

Ranges: 
0 – 600: Phone  
600 – 900: Tablet Portrait  
900 – 1200: Tablet Landscape  
1200 – 1800: Desktop  
1800+: Big desktop  


https://nextbillionusers.google/  
https://www.freecodecamp.org/news/taking-the-right-approach-to-responsive-web-design/ 
https://www.freecodecamp.org/news/the-100-correct-way-to-do-css-breakpoints-88d6a5ba1862/
