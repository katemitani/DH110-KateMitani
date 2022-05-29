# Assignment 06: Interface Design
Kate Mitani  
DH110 Spring 2022  
10 May 2022  

## Introduction
The goal of this project was to redesign the interface of the Ukulele App in order to create a more modern and intuitive appearance for ukulele players. Ideally, the app would be accessible to people of ages and regardless of technological abilities or ukulele experience. User research and the development of personas/usage scenarios assisted me with the development of new features as well as redesigns of current features. These changes were:
1. a notebook feature that would allow users to track their progress, store notes, and easily pick up where they left off on past sessions
2. a "grouping" feature for the chord library tool that would allow users to organize extensive information more effectively
3. a redesign of the chord library tool to more closely mimic real world actions as well as industry standards
4. a redesign of the general interface (font, colors, icons) to reduce distractions and clutter and appear more modern and clean  

The purpose of an interface redesign is to refine my low-fidelity prototype into a tangible display. I converted my low-fidelity wireframes and flow into an interactive prototype using Figma. The dimensions were fit to a standard iPhone 8 screen, but are arranged in a linear way that can be easily resized to fit other dimensions. 

## Interface
### [Digitized Wireflow](https://www.figma.com/file/XTNQjEGBevrlYfaMBBQryM/DH110-Prototype?node-id=0%3A1)
### [Interactive Prototype](https://www.figma.com/proto/XTNQjEGBevrlYfaMBBQryM/DH110-Prototype?node-id=8%3A32&scaling=scale-down&page-id=0%3A1&starting-point-node-id=8%3A32&show-proto-sidebar=1)

## Chosen Wireframe
<img width="353" alt="Screen Shot 2022-05-28 at 5 25 11 PM" src="https://user-images.githubusercontent.com/102703477/170846938-97827844-0ab3-4ff8-903f-52540b756282.png">

## Layout Test

### Navigation Bar Layout
> 5 rows (0px margin, 20px gutter), 5 columns (0px margin, 0px gutter)  
<img width="353" alt="Screen Shot 2022-05-28 at 5 26 28 PM" src="https://user-images.githubusercontent.com/102703477/170846948-93055f9f-b453-447c-8648-6bda450721aa.png">  

### Notebook Layout
> 4 rows (100px margin, 20px gutter), 3 columns (25px margin, 50px gutter)   
<img width="353" alt="Screen Shot 2022-05-28 at 5 24 51 PM" src="https://user-images.githubusercontent.com/102703477/170846943-87c0b31c-13e5-4571-832e-0f7868fd5f72.png">  

### Pop-up Window Layout
> 4 rows (0px margin, 20px gutter), 15px grid
<img width="353" alt="Screen Shot 2022-05-28 at 5 25 02 PM" src="https://user-images.githubusercontent.com/102703477/170846953-3a9c8cd3-5e71-4928-8c0b-722d12fc0d7e.png">   

### Typography Variation
<img width="826" alt="Screen Shot 2022-05-28 at 5 37 40 PM" src="https://user-images.githubusercontent.com/102703477/170847162-a4986ee4-9103-4fe6-a6d6-fcff24a0ee85.png">

**Typography variation 1**: Lora + Open Sans  
**Typography variation 2**: Montserrat + Open Sans  
**Typography variation 3**: Bitter + Open Sans   
  
I decided on using Open Sans as the base font for the interactive fields (cancel, create button, and rename feature). Open Sans is established as a well loved and commonly used san serif font. It is often utilized for content text due to its readability and legibility in a variety of sizes and weights. It is also optimized for a variety of platforms including print, web, and mobile, making it a great font for a mobile app.   

I wanted to test out Open Sans in combination with Lora (a well balanced contemporary serif font), Montserrat (a classic geometric sans serif font), and Bitter (a contemporary serif font ideal for electronic readability). In general, combinations of serif and sans serif are recommended to add contrast, however a combination of certain sans serif fonts can also be complementary. [Research](https://geniusee.com/single-blog/font-readability-research-famous-designers-vs-scientists) has shown that there is very little difference between the two in terms of readability and legibility, however sans serif fonts are slightly preferred for those with impaired vision, children, and the elderly. All 3 font variations come in a variety of weights and are optimized for screen appearances, guaranteeing readability and legibility.  

After some consideration, I decided to go with variation 2 (Montserrat + Open Sans). I liked how complementary the two sans serif fonts were to each other. They were similiar such that they would be cohesive and non-distracting, but different enough so that they subtly mark different associations (Open Sans for interactivity and Montserrat for titles and labels). In addition, they are both well loved and highly recognizable fonts that Figmas has listed as an ideal pairing for UX design. While I considered Bitter due to its consideration of electronic readability, aesthetically I liked the modern rounded look of Montserrat compared to the sharper features of Bitter's serif. 
  

### Shape Variation
<img width="826" alt="Screen Shot 2022-05-28 at 5 39 07 PM" src="https://user-images.githubusercontent.com/102703477/170847202-8ad6c762-647f-46c3-b32d-5a472dc01a04.png">
**Shape variation 1**: square window, square button  
**Shape variation 2**: square window, rounded button (corner radius=10)  
**Shape variation 3**: rounded window (corner radius=8), rounded button (corner radius=10)  

When looking at some of my favorite and most-used apps for inspiration (GoodNotes, Twitter, iMessage, etc.), I took note of the commonly used rounded edges for a lot of elements. This wasn't originally something I had in mind -- I had actually just assumed that most pop up windows, buttons, text boxes, and fields were sharp and rectangular. This common industry standard for modern apps combined with my desire to achieve a clean, modern, and minimalist design prompted me to go with variation 3 (rounded window, rounded button).  

### Color Schemes
<img width="541" alt="Screen Shot 2022-05-28 at 5 50 34 PM" src="https://user-images.githubusercontent.com/102703477/170847458-b2b08bf0-eb7b-4a64-8e82-79cf3fe743d0.png">
My main decision for a teal and orange color scheme was in efforts to achieve some resemblance of the original Ukulele App design. I originally imported the original interface to a color picker website and isolated the main teal color, which left me with a muted teal color (HEX #37545B). However, I ended up adjusting the tone and tint of the color to achieve a more vibrant version (HEX #236B7C). I adjusted the darkness to obtain a dark variation (HEX #1E3035). I selected an orange with a strong tint (HEX #FFD8BB) to complement the teal as well as the orange notebooks. I once again adjsuted the darkness to obtain a dark variation (HEX #853800). In addition, I added a solid black overlay that I toned down to 25% transparency to achieve the darkened background that occurs behind a pop-up window to emphasize the content. This was overlaid on top of the page but underneath the pop-up window, resulting in a tinted background.

### Impression Test  
My participant did not want to have a recording shared, so here is the [transcript of the impression test](https://docs.google.com/document/d/1bcK5Vo78qd7GR46oQqpz-QZnGv4zeix23M50pb3R9UU/edit?usp=sharing)  

In my impression test, I showed my participant the first screen of my prototype (Notebook page), and then a few pages of task 1 (create notebook). For the first page, I showed my participant the screen for about 5-10 seconds and then asked them to give me their first impressions. Their feedback was:
- Looks very simple, kind of like a draft. Needs more icons, color, or definition
- Eyes did not go to the bottom menu bar. If the color was brighter or less muted/close to gray they would notice it more
- Didn't think the rectangles for the notebooks were very useful. Thought there should be something else, like thumbnails of the notebook contents (e.g. something similar to Google docs)
- Too much blank white space
- Most familiar with apps like Google Notes, Google Drive, Excel, etc., and when comparing to that it feels very plain  

Summary:  
Overall, my participant found it intuitive but too simple. Interestingly, I had ended up changing the color scheme to be a bit darker due to the results of the contrast/accessibility check. However, my participant noted that it looked black and white and not teal and white--so, while it passed the accessibility checker, it wasn't the most aesthetically pleasing. For changes for a future iteration, I plan on adjusting the color scheme a bit more, adding more visually pleasing design elements to the notebooks themselves (such as icons, realistic notebooks, thumbnails, etc.) and possibly adjusting the text sizes to be a bit larger and more visible. 

### Accessibility Check  
<img width="684" alt="Screen Shot 2022-05-28 at 6 01 02 PM" src="https://user-images.githubusercontent.com/102703477/170847724-fe839e85-925c-4f7a-a9fa-59a798e5c8bf.png">
<img width="684" alt="Screen Shot 2022-05-28 at 6 01 55 PM" src="https://user-images.githubusercontent.com/102703477/170847731-7e359266-7150-4298-a791-e5be57870118.png">
<img width="684" alt="Screen Shot 2022-05-28 at 6 03 57 PM" src="https://user-images.githubusercontent.com/102703477/170847734-c2701337-4f56-4444-9ded-92b3dc4ebb13.png">
<img width="684" alt="Screen Shot 2022-05-28 at 6 03 27 PM" src="https://user-images.githubusercontent.com/102703477/170847737-b334a4cf-9435-4305-be66-5d03a3ca344f.png">
<img width="684" alt="Screen Shot 2022-05-28 at 6 03 40 PM" src="https://user-images.githubusercontent.com/102703477/170847738-7879e1d6-b4f0-4467-9c27-071f5bac2487.png">


## Design System
### Typography  
**Heading**: Montserrat, 24pt, letter spacing: 0%   
**Subheading**: Montserrat, 18pt, letter spacing: 0%  
**Body Text**: Montserrat, 14pt, line height: 21, letter spacing: 0%  
**Subtitle**: Montserrat, 10pt, line height: 13, letter spacing: 0%  
**Interactive Text (User Input)**: Open Sans, 16pt, letter spacing: 0%    
**Interactive Text (Button)**: Open Sans, 16pt, letter spacing: 0%    

### Color Scheme  
**Background Color**: white (#FFFFFF) --> orange (#FFD8BB) --> teal (#4AB1C9)
**Background Tint Layer Color**: black (#000000), transparency 25%  
**Navigation Bar Color**: teal (#236B7C)
**Accent Color**: dark teal (#274148)  
**User Input Text Color**: dark gray (#575757)  

### Elevation Style  
Drop Shadow Depth:  
> **Popup Windows**: x=0, y=4, blur=4, color= #000000, transparency=25%    
> **Buttons**: x=-1, y=1, blur=1, color= #000000, transparency=25%  
> **Dropdown Menus**: x=-4, y=4, blur=1, color= #000000, transparency=35% <br/>  

Stroke weight:  
> **Dropdown Menu Border**: weight=2  
> **Popup Window Border**: weight=1  
> **Divider Lines**: weight=0.25  
> **Menu Icon Location**: weight=1, rounded edges

### Layout  
A majority of the wireframes utilized a 15px grid with elements snapped to fit. Pop-up windows were centered with 60px margins. Text within popup windows utilized 15px padding. The bottom menu bar was bottom-flushed with a 60px height. Icons were segmented in 5 columns and center-alignment with approximately 30px margins in between. Menu icons were 25px x 25px and popup window icons were 20px x 20px.  
