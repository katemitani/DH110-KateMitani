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

The purpose of an interface redesign is to refine my low-fidelity prototype into a tangible display. I converted my low-fidelity wireframes and flow into an interactive prototype using Figma. The dimensions were fit to a standard iPhone 8 screen, but is arranged in a linear way that can be easily resized to fit other dimensions. 

## Interface
### [Digitized Wireflow](https://www.figma.com/file/XTNQjEGBevrlYfaMBBQryM/DH110-Prototype?node-id=0%3A1)
### [Interactive Prototype](https://www.figma.com/proto/XTNQjEGBevrlYfaMBBQryM/DH110-Prototype?node-id=8%3A32&scaling=scale-down&page-id=0%3A1&starting-point-node-id=8%3A32&show-proto-sidebar=1)

## Chosen Wireframe
![Screen Shot 2022-05-10 at 4 42 40 PM](https://user-images.githubusercontent.com/102703477/167741971-2df17e0b-511a-4deb-be8d-ee7e10668966.png)
### Layout Test
![Screen Shot 2022-05-10 at 4 45 41 PM](https://user-images.githubusercontent.com/102703477/167742210-01b398d3-c43a-41f9-8a21-9200581fa39c.png)
![Screen Shot 2022-05-10 at 4 53 25 PM](https://user-images.githubusercontent.com/102703477/167742780-5cf511c5-0c37-436c-9f92-4d9515e66a61.png)  
For my notebook and new notebook pop-up text box layout, I utilized a 15px grid, 3 columns (25px margin, 50px gutter), and 4 rows (100px margin, 20px gutter). For my menu bar, I utilized a 15px grid, 5 column (0px margin, 0px gutter), and 5 rows (0px margin, 20px gutter).   

### Typography Variation
![Screen Shot 2022-05-10 at 5 44 37 PM](https://user-images.githubusercontent.com/102703477/167746855-1cab3bcc-adee-4cd2-8967-5a99dee2459a.png)
**Typography variation 1**: Lora + Open Sans  
**Typography variation 2**: Montserrat + Open Sans  
**Typography variation 3**: Bitter + Open Sans   
  
I decided on using Open Sans as the base font for the interactive fields (cancel, create button, and rename feature). Open Sans is established as a well loved and commonly used san serif font. It is often utilized for content text due to its readability and legibility in a variety of sizes and weights. It is also optimized for a variety of platforms including print, web, and mobile, making it a great font for a mobile app.   

I wanted to test out Open Sans in combination with Lora (a well balanced contemporary serif font), Montserrat (a classic geometric sans serif font), and Bitter (a contemporary serif font ideal for electronic readability). In general, combinations of serif and sans serif are recommended to add contrast, however a combination of certain sans serif fonts can also be complementary. Serif fonts are more legible than sans serif fonts for smaller scales, making it ideal for body text and subtitles. All 3 font variations come in a variety of weights and are optimized for screen appearances, guaranteeing readability and legibility.  

After some consideration, I decided to go with variation 1 (Lora + Open Sans). While I liked the look of Montserrat, I felt it was a little bit too close to Open Sans. I wanted to achieve some differentiation between the interactive elements and the main content text, and felt this was easily achievable with the implementation of both serif and san serif fonts. While I considered Bitter due to its consideration of electronic readability, aesthetically I liked the subtle curves of Lora compared to the sharper features of Bitter's serif.   

### Shape Variation
![Screen Shot 2022-05-10 at 7 58 06 PM](https://user-images.githubusercontent.com/102703477/167759965-13e64a59-229f-4052-800e-569f194ac295.png)
**Shape variation 1**: square window, square button  
**Shape variation 2**: square window, rounded button (corner radius=10)  
**Shape variation 3**: rounded window (corner radius=8), rounded button (corner radius=10)  

When looking to some of my favorite and most-used apps for inspiration (GoodNotes, Twitter, iMessage, etc.), I took note of the commonly used rounded edges for a lot of elements. This wasn't originally something I had in mind -- I had actually just assumed that most pop up windows, buttons, text boxes, and fields were sharp and rectangular. This common industry standard for modern apps combined with my desire to achieve a clean, modern, and minimalist design, I decided to go with variation 3 (rounded window, rounded button).  

### Color Schemes
![Screen Shot 2022-05-10 at 8 27 53 PM](https://user-images.githubusercontent.com/102703477/167763250-52eaec3e-1cb8-4cd5-a98f-fccd5b73e76d.png)  
I decided on using white with a subtle usage of a monochromatic color scheme for accent colors in order to achieve a minimalist design. In efforts to achieve some resemblance of the original Ukulele App design, I imported a screenshot of the original interface to a color picker website and isolated the main teal color. This left me with an accent teal (HEX #37545B). I adjusted the tone and tint of the color to achieve a muted, brighter (whiter) version of this teal as my second accent color (HEX #58858B). As a subtler detail, I added a solid black overlay that I toned down to 25% transparency to achieve the darkened background that occurs behind a pop-up window to emphasize the content. This was overlayed on top of the page but underneath the window, resulting in the tinted background.   

### Impression Test  
### Accessibility Check  
<img src="https://user-images.githubusercontent.com/102703477/167785242-ae18a49d-5df5-4929-a034-1aa0d968fdbc.png" width="500"> <img src="https://user-images.githubusercontent.com/102703477/167785251-f4cae109-d460-41e0-b633-14a844ec1b28.png" width="500">

## Design System
### Typography  
**Heading**: Lora, 24pt, letter spacing: 0%   
**Subheading**: Lora, 16pt, letter spacing: 0%  
**Body Text**: Lora, 14pt, line height: 21, letter spacing: 0%  
**Subtitle**: Lora, 10pt, line height: 13, letter spacing: 0%  
**Interactive Text (User Input)**: Open Sans, 14pt, letter spacing: 0%    
**Interactive Text (Button)**: Open Sans, 12pt, letter spacing: 0%    

### Color Scheme  
**Background Color**: white (#FFFFFF)   
**Background Tint Layer Color**: black (#000000), transparency 25%  
**Accent Color**: dark teal (#37545B)  
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
A majority of the wireframes utilized a 15px grid with elements snapped to fit. Pop-up windows were centered with 60px margins. Text within popup windows were left-aligned with 30px margins and 15px line spacing. The bottom menu bar was bottom-flushed with a 60px height. Icons were segmented in 5 columns and center-alignment with approximately 30px margins in between. Menu icons were 25px x 25px and popup window icons were 20px x 20px.  
