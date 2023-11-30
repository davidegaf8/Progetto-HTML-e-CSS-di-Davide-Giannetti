# Progetto-HTML-e-CSS-di-Davide-Giannetti

*TECHNICAL STRUCTURE
I thought of writing the code in pure HTML and CSS without using external libraries, because since this was my first project I thought it could be a good exercise to further establish and put into practice the concepts I had just studied.
I divided the site into 4 pages and used 2 main breakpoints to make everything responsive and suitable for any type of device.
I tried to keep the code lean and organized by commenting where necessary to give myself the possibility to modify it later by implementing it with Javascript for example.

*STYLE 
As for the style, I opted for a minimal design that remained elegant and professional at the same time.
As regards the choice of colors, I used shades of blue to reflect the logo I had previously created, all on a whitesmoke background.
This combination of style and color aims to convey the sensation of something modern and technological with intuitive and pleasant navigation.

*HEADER
I created a very simple but elegant and intuitive header where there is the logo (which is also a link to the home page) on one side and the navigation pages on the other.
The underlined element indicates the page we are on, obviously only in the desktop version, because below 900px I have inserted a pop-up menu.

*HOMEPAGE
I divided the home page mainly into 2 divs: one containing the photo and the other a short description with links to my social channels and the CV in PDF format to download. I used the “display:flex” property for arranging the divs so as to be able to better manage the flex-direction when the viewport is reduced.
I used 2 breakpoints, the first at 900px and the second at 675px, in this way I was able to always maintain a clear and coherent arrangement of the elements.
I used animations with the @keyframes property. I tried to recreate the "typing keyboard" effect without using JS but with an animated after element.

*ABOUT PAGE
On the about page I made a very quick description of myself, my background and my main passions and I tried to project it visually with a series of images that recalled exactly what was present in the description.
Here too, thanks to the flex-direction and the use of 2 different image formats, I was able to manage the position of the elements on the page by making them adapt to the size of the viewport this time with a single breakpoint at 900px.

