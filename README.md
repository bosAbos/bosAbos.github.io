# bosAbos.github.io
Test Task
 How to create mockup from https://www.coinmarketplus.com/ page

This instruction describes how to build mockup for basic users of CSS and HTML. To create the mockup  from https://www.coinmarketplus.com/ , follow the steps below:

Step 1. Create a folder for the mockup. Download the web page  https://www.coinmarketplus.com/ in HTML format. Use online loader as you need all the elements of the page.
Step 2. Download the font ‘OpenSans-BoldItalic’ from the site. Transfer the font to the folder.
Step 3. Download the css file with insertions from here. Transfer it to the folder. After these steps, your folder will contain the following files: 
Step 4. Open the file ‘index’ with the help of  Notepad++ or Sublime Text. Add the line:  <link rel="stylesheet" type="text/css" href="insertion.css">  as it is shown on the picture below. New font will be added automatically to the mockup. 
Step 5. To add carousel with images, insert the following text as it is featured on the screenshot  :
 <div>
       <div class="CSSgal">
        <s id="s1"></s> 
         <s id="s2"></s>
              <s id="s3"></s>
              <s id="s4"></s>
               <div class="slider">
       <div><img src="https://www.coinmarketplus.com/wp-content/uploads/2018/05/blockchainasiaforum.png"></div>
       <div><img src="https://www.coinmarketplus.com/wp-content/uploads/2018/05/cryptokonf.jpg"></div>
       <div><img src="https://www.coinmarketplus.com/wp-content/uploads/2018/05/blockchaindiamonds.jpg"></div>
        <div><img src="https://www.coinmarketplus.com/wp-content/uploads/2018/05/blockercon.jpg"></div>
                 </div>
                  <div class="prevNext">
                    <div><a href="#s4"><</a><a href="#s2">></a></div>
                    <div><a href="#s1"><</a><a href="#s3">></a></div>
                    <div><a href="#s2"><</a><a href="#s4">></a></div>
                    <div><a href="#s3"><</a><a href="#s1">></a></div>
                  </div>
                  <div class="bullets">
                    <a href="#s1">1</a>
                    <a href="#s2">2</a>
                    <a href="#s3">3</a>
                    <a href="#s4">4</a>
                  </div>
                </div>
 </div>

Step 6. Add the page to github.com to represent it to the world. You can read here how to do it.

