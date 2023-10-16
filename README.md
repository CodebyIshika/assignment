# Assignment 
# My Project
My project is a simple website that I created using HTML and CSS. This website has a static table that give some information about the data type such as registered users, published articles, authors, messages and visits. 
![My current website]( https://github.com/CodebyIshika/assignment/blob/main/Screenshot%20.png )
## Reason behind this website
As I just started learning programming languages, so I really want to create a websites using the codes that I have already learnt. I have learnt just basics of HTML and CSS so I wanted to create a website using them. So, I made this table using hypothetical data to test my understanding of codes.
## Decisions
When I decided to make this website, I just want to create a simple website that has a static table in it. That's why after making header and footer, I made a table that display some information.While doing this, I focused on the following considerations:
- **Colour Contrast:** I used minimalist colours in my table to ensure readability.
- **Icons:** I used different icons with different colours for each data type to make data type more clear and visible.
```css
.one i {
color:#4663e6; /* this is used to give colour to icon */
background-color: #dadffa; /* this is used to give colour to background of icon */
}

.two i {
    color: #008040;
    background-color: #99ccb2;
}

.three i {
    color: #ff4162;
    background-color: #ffc9d2;
}

.four i {
    color:#fe5b36;
    background-color:#fed6cc ;
}

.five i {
    color: #8c198c;
    background-color: #dcbadc;
}
```
- **Heading:** I tried to use relevant heading for my each row of table to give users proper idea about that row. Below is the html code that I used to create headings of the rows of table.
``` html
<table> <!-- table tag is used to create a table -->
    <thead> // <!-- <thead> tag is used to specify header content of a table -->
        <tr> // <!-- this tag defines a row in html table -->
           <th></th> <!-- <th> tag defines a heading of a particular row -->
           <th>Data Type</th>
           <th>Total</th>
           <th>Last 7 Days</th>
           <th>Latest Records</th>
           <th></th>
        </tr>
    </thead>            
 </table>
```
## Challenge
While creating this website, I faced a number of challenges. Some of the challenges are listed below:
1. **Border:** I find it really challenging to create a space between each border because I haven't done that before. But after searching the process of this on google, I realised I just have to separate the border using border collaspe.
     ```css
     table {
      width: 100%;
      border-collapse: separate; /* this is used to separate the border */
      border-spacing: 0 15px; /* this is used to put some space between each border */
     }
      ```
2. **Alignment:** Alligning the content of the table is also really difficult for me.
   ```css
   tbody tr td {
    align-items: center; /* this will align the content to the center of the row cell */
    overflow: hidden; /* this will make extra content of a block element invisible */
     }
   ```
## Improvements
1. **Alignment within the icons:** I feel that I will be able to align icons if I kept on working on that as icons are not that much properly aligned right now. In my current websites, icons are liitle above than middle so they are not aligning properly with the text of the table.
![ icon alignment in current website ]( https://github.com/CodebyIshika/assignment/blob/main/icons.png )
2. **Links:** After sometime, I think I will be able to link show more button to some other pages by creating those pages.
3. **Reponsiveness:** I will be able to make my website more responsive in future. After that, it will look appropriate on different size screen.
## Conclusion
I think this is all about my simple website that I created and I think I will be able to make this website more beautiful after learning some other codes.


