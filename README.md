
# Profile Page  

In this project we were directed to create a full website to showcase ourselves. By using the design of the example that was given I made modification to it that made it feel more personalized
to me. I gathered the inforamtion that I wanted to share on this page and then decided on the location of the inforamtion. I created 4 section on the page each holding different information. 
They are About Me, pictures of my dogs, Previous Work, and contact inforamtion. 

The about me does exactly what the title suggests, it gives a breif overview of myslef and my hobbies. I shared my current full time position along with information about the boot camp I am taking.
I also shared information about my dogs which I included pictures of in the next section.

In the previous work section I used my limited knowledge of flexbox to creaet multiple sizing boxes that have links to my previous work. The first one is the only one that holds any links, 
whereas the others are placeholders for my upcoming projects taht will be completed. I created a border and a transition of opacity when the user hovers over the boxes. I also created 
smaller boxes that hold the name and a very breif description of the link it's attached to. 

The final section is the contat me page, which houses multiple ways of getting in touch with me. I ahve included my email address with a clickable link to open the users default mail application
and populate my email as the to target. The other link go to my LinkedIn, GitHub, and my Instagram accounts. 


## Authors

- [@marshallrizzuto](https://github.com/Zoot83)


## Features

- Display block
- Class properties
- Margin and Border
- Text-align
- Flexbox
- Postioning
- Algin
- Tranistions
- Box Styling



## Usage/Examples

 Styling Flexbox to have other box with images overlapping

 In this code it created a section that would create a flexbox that would be using ro rather thent he previous column alignment. It also showcases the use of positioning of the other
 boxes to be position in the bottom left of the image. By creating this section I can easily copy this code and add on the exact code with its corrisponding information. This code also showcases the use of mulitple
 div tags to asign the approprate style and properties for each section. 

<div class="text-box">
              <div class="other-projects">
              <!-- We dont have anymore projects so these are acting as place holders -->

                <img class="projects" src="./assets/images/mountain.jpg" alt="mountain"/>
                <div class="mini-box">
                  <h4>Check Back Soon!</h4>
                </div>

              </div>

              <div class="other-projects">
                <!-- We dont have anymore projects so these are acting as place holders -->
  
                  <img class="projects" src="./assets/images/ocean.jpg" alt="ocean"/>
                  <div class="mini-box">
                    <h4>On Its Way!</h4>
                  </div>
                </div>
```
This next section is the css that goes along with the code above. With this code is seen that flexbox is used to aligna nd position the related elements to the desired location. This also
shows that we are able to set new properties by targeting the specific element we want to change. 

.other-projects{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    height: 150px;
    position: relative;
    margin-bottom: 10px;
    width: 50%;
}

.projects{
  width:100%;
  height:100%;
  border: #2aefcb solid 5px;
  margin: 5px;
  opacity: 50%;
}
