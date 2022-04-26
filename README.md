# ![heen-small](https://user-images.githubusercontent.com/40601891/165193208-7c6858ca-cc6c-4a84-bc6e-7fb9e9eccfb2.gif) <span> <span>Ghiblify
This fork is a Google Chrome Newtab replacement framework that allows for custom defined lists of Studio Ghibli inspired backgrounds to be randomly loaded.


<img width="1440" alt="Screenshot 2022-04-25 at 7 59 44 PM" src="https://user-images.githubusercontent.com/40601891/165193305-089c9431-ef2b-40c2-983b-5b5c566b0dea.png">
## Usage
More information on https://suitangi.github.io/Minimal-Newtab/resources/MtG%20Art%20Newtab
You can clone this repository:
```
git clone https://github.com/suitangi/Minimal-Newtab.git
```
Just make sure to turn on developer options in chrome://extensions/ and 'Load Unpacked' and then select the folder where the `manifest.json` file is located.
This option allows you to [use your own background lists](#using-your-own-backgrounds).

## Features
### Clock:
- Drag to move the clock
- Click once to switch between standard 12hr and 24hr time


 
 
![chrome-capture-2022-3-25 (4)](https://user-images.githubusercontent.com/40601891/165195018-346683bb-0d72-4db7-9be1-799f61d243c0.gif)

 
 
 
 
### Movie Info:
- Shows the movie name, length, year, and a quote
- Click to show different information and in a different style
- Drag to move the info widget
 
 
 
 
![ghiblify-quotes-demo](https://user-images.githubusercontent.com/40601891/165194111-9bcf62db-2604-4797-97cd-e4c5d5deeb18.gif)
 

### Todo List:
- Type in the "New Item" box and press Enter to enter a new item
- Press enter while editing a list item to create a new list item below
- Press backspace on any empty list item to delete it
- Left click on items to edit them
- Click on the x next to the item to delete it
- Right click on the item to cross them off
- Drag and drop the item to reorder the list
- Drag the top of the list (where it says "todo list") to move the widget


 
  ![chrome-capture-2022-3-25 (2)](https://user-images.githubusercontent.com/40601891/165194432-8af2d46d-c073-4f0e-a6fe-844fbbba5848.gif)

 
 
 

### Search Bar:
- Drag the top of the search bar to move it
- Type in the box and press enter to perform a search
- On the right side of the search bar there is a ⯈ button to change the search engine

![Change search engine](https://i.imgur.com/jsSynRH.gif)

### Menu
![chrome-capture-2022-3-25 (5)](https://user-images.githubusercontent.com/40601891/165195395-45dfe764-35cc-4301-ada3-bda149823ad8.gif)

- Move the mouse to the left most part of the window to access the menu.
- Each switch in **Widgets** enables/disables respective widgets
- Each switch in **Background** enables/disables the respective source of images
- Effects: see [effects](#Effects)
- ❤ Button: Add or remove the current background to favorites
- 🗑️ Button: Remove this background (won't show this background again)
- Settings Button:
  - UI Animations: Toggles the UI Animations
  - Avoid Repeats: When on, the extension will not allow the same background to be shown back to back
  - Auto-pause background: When on, this option will pause video backgrounds when the window is not in focus to reduce cpu usage
  - Reset Data: resets the extension based on options checked, wiping the chosen data and restarts the software (use this option when the widget is lost off-screen somehow)
- About Button: see information regarding the extension
  - FAQ: redirect to FAQ page
  - Report background: used to report a broken/low quality background

### Effects
  - Brightness: adjust the brightness of the background
  - Saturation: adjust the saturation (how colorful) of the background
  - Contrast: adjust the contrast of the background
  - Blur: adjust the blur of the background (default is no blur)
 
 
![chrome-capture-2022-3-25 (6)](https://user-images.githubusercontent.com/40601891/165195666-7715bee3-f570-40f8-91db-a22c23d1300a.gif)


## Other Informataion
*Art is from the studio ghibli site for personal use.*

### Browser Permissions
These are the permission that the `manifest.json` asks for:
- Storage: To store the data relating to preferences and widgets
- Bookmark: To show the bookmarks on the right hand side tab

### jQuery
This project uses these jQuery libraries:
- [jQuery](https://github.com/jquery/jquery)
- [jQuery-confirm](https://github.com/craftpip/jquery-confirm)
- [jQuery-ui](https://github.com/jquery/jquery-ui)

## Special Thanks
To all the beta test users:
- [G-Jayakar](https://github.com/G-Jayakar)
- [DaisyFei](https://github.com/DaisyFei)
- [suitangi](https://suitangi.github.io/Minimal-Newtab/)

