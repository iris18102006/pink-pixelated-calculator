# Pink Pixel Calculator
A cute, retro-styled pixel art calculator built with HTML, CSS, and JavaScript. Featuring floating pixel hearts, twinkling sparkles, and a chunky 8-bit aesthetic!


IT FEATURES:

- Pixel Art Design — Chunky borders, 3D button shadows, and retro scanlines for that authentic 8-bit feel
- Floating Hearts — 6 pixel hearts bobbing gently around the calculator
- Twinkling Sparkles — Decorative pixel stars scattered across the background
- Keyboard Support — Use your keyboard just like a real calculator
- Responsive — Centered layout that works on any screen size
- Color-Coded Buttons — Blue-grey numbers, pink clears, and an orange equals button

HOW TO USE

Action * Input
Numbers - Click buttons or press `0-9`
Operators - Click `+ − × ÷` or press `+ - * /`
Calculate - Click `=` or press `Enter`
Clear All - Click `C` or press `Esc` / `C`
Clear Entry - Click `CE`
Backspace - Press `Backspace`
Percent - Click `%` or press `%`
Decimal - Click `.` or press `.`

BUILT WITH:

HTML5 — Semantic structure
CSS3 — Grid layout, keyframe animations, SVG rendering
Vanilla JavaScript — Calculator logic and keyboard events
Press Start 2P — Retro pixel font via Google Fonts
SVG Pixel Art — Custom pixel art renderer for crisp hearts at any size



///IF YOU WANT TO COSTUMIZE IT FEEL FREE TO DO SO///
 
//Change the Background Color

body { background-color: #2d1b2e; /* Your color here */}


//Add More Hearts

<div class="deco heart-deco7" id="heart7"></div>


//And render it in JavaScript:

renderPixelArt('heart7', heartMap, heartColors, 5);


//Change Heart Colors


const heartColors = {
    'R': '#e91e63',  /* Outline */
    'H': '#ff69b4',  /* Fill */
    'W': '#ffffff'   /* Highlight */};

    
//Adjust Animation Speed on CSS

.heart-deco1 {
    animation: float1 4s ease-in-out infinite; /* Change 4s */}

 
//File Structure//

pink-pixel-calculator/
├── calculator.html    # Everything in one file!
└── README.md          # This file

//Credits:
Font: Press Start 2P by CodeMan38
Inspiration: Retro gaming aesthetics


//License:
Feel free to use, modify, and share! Made with love and pixels 


"Math is better when it's cute!" ✨🎀
