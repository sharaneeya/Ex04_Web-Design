# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
<html>
<head>
  <title>Agricultural Search</title>
</head>
<body>
  <h1>Agricultural Search</h1>
  <h2>Sowing</h2>
  <a href="https://www.google.com/search?q=sowing&source=lmns&bih=754&biw=1536&rlz=1C1CHBD_enIN1033IN1033&hl=en&sa=X&ved=2ahUKEwjjvcTk28z-AhVfA7cAHdpuA0YQ_AUoAHoECAEQAA">
    <img src="sowing.jpeg">
  </a>
  <h2>Tillage</h2>
  <a href="https://www.google.com/search?q=tillage&bih=754&biw=1479&rlz=1C1CHBD_enIN1033IN1033&hl=en&sxsrf=APwXEdf2YZXP6GgCjXeDbJFKndDsBjHnpA%3A1682689748029&ei=1M5LZIK2Aazv4-EP2MWmyAI&ved=0ahUKEwiC8Mrl28z-AhWs9zgGHdiiCSkQ4dUDCA8&uact=5&oq=tillage&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQA0oECEEYAFAAWABgAGgAcAB4AIABAIgBAJIBAJgBAA&sclient=gws-wiz-serp">
    <img src="tillage.jpeg">
  </a>
  <h2>Pruning</h2>
  <a href="https://www.google.com/search?q=pruning&source=lmns&bih=702&biw=938&rlz=1C1CHBD_enIN1033IN1033&hl=en&sa=X&ved=2ahUKEwjgze6f2sz-AhUy83MBHZlJBtUQ_AUoAHoECAEQAA">
    <img src="pruning.jpeg">
</a>
<h2>Harvesting</h2>
<a href="https://www.google.com/search?q=harvesting&source=lmns&bih=696&biw=1536&rlz=1C1CHBD_enIN1033IN1033&hl=en&sa=X&ved=2ahUKEwj0meWl3Mz-AhVBnNgFHXqCBskQ_AUoAHoECAEQAA">
<img src="harvesting.jpeg">
  </a>
</body>
</html>


## OUTPUT
![image](https://github.com/sharaneeya/Ex04_Web-Design/assets/119670918/2a1e4522-de9f-4165-bb59-d14f5a677343)

![image](https://github.com/sharaneeya/Ex04_Web-Design/assets/119670918/0098f7b9-a3b6-439c-892f-3abe14946c9f)



## RESULT
 Images as hyperlinks is implemented successfully.
