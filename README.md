# Selectable-Layer-Template-v4
 
I separated concerns of the code functions into scripts ,styling, and html. Made a data directory and moved all data files to that directory so script resources could find these files. Finally, I moved some script resources that were in the wrong place and likely have been ignored by the ide. 


1. By separating concerns I mean keeping the code for the html, javascript, and css in their own respective files (index.html, script.js, styles.css). You can take this further inside each file. You can learn more about separation of concerns here: https://dev.to/tamerlang/separation-of-concerns-the-simple-way-4jp2
2. I moved data files to their own "data" directory based on the fact that most  of the script sources said they were in the current directory (".") inside of a directory called "data" ex: ./data/line.js The period indicates the current working directory.
3. You had some script tags outside of the closing html tag (</html>) so I put all of the scripts inside the html tags and then put the javascript functions inside their own file (script.js) and linked that to the html file. They are already separated by function which allows you to quickly find what section to edit and then make or insert a new function. You can learn more about that here: https://www.w3schools.com/js/js_whereto.asp
4. When you want to include new data points, you add those files to the "data" directory and then you can use those data by making new variables or functions that are sent to that data files path: ./data/WHATEVER-DATA-FILE
5. 