# Slicing-Button-Animation using clip-path CSS property

<p>This is a simple project that demonstrates the use of CSS <code>clip-path</code>. The project consists of an HTML file and a CSS file.</p>

<h3>HTML</h3>
<p>The HTML file contains a <code>div</code> with the class <code>loader</code>. Inside this <code>div</code>, there are two <code>span</code> elements with the classes <code>top-half</code> and <code>bottom-half</code>. These elements are used as the two halves of the loading animation.</p>

<h3>CSS</h3>
<p>The CSS file imports the Raleway font from Google Fonts, and sets some basic styles for the <code>body</code> element, including setting the height of the page to the full height of the viewport and centering the content.</p>

<p>The <code>.loader</code> class sets the width, height, border, border-radius, and text alignment for the loading animation. The <code>span</code> element is given <code>position: absolute</code> so it can be clipped and animated.</p>

<p>The <code>.top-half</code> and <code>.bottom-half</code> classes set the color and <code>clip-path</code> for each half of the animation. The <code>clip-path</code> property is used to create a triangle shape that clips the element to the top or bottom half.</p>

<p>The <code>animation</code> property is used to animate the <code>transform</code> property of the <code>span</code> elements. The animation is set to <code>split</code>, which is a keyframe animation. The <code>animation-duration</code> is set to 4s and <code>animation-iteration-count: infinite;</code> is set to repeat the animation infinitely. The <code>animation-direction</code> is set to "reverse" for the <code>bottom-half</code> class, so it runs in the opposite direction.</p>

<p>The keyframes of the animation are set to translate the <code>span</code> elements horizontally by 100% and then back to 0%.</p>

<h3>Usage</h3>
<p>To use this project, simply download the HTML and CSS files and open the HTML file in a web browser. The loading animation will be displayed in the center of the screen.</p>

<p>You can also customize the code to suit your needs, for example, by changing the colors, text, animation duration, and so on.</p>

<h3>Live Preview</h3>
<p>You can see the live version of this project by visiting the following link <a href="https://abiodunvictoria.hashnode.dev/how-to-use-clip-path-to-create-unique-image-shapes-and-effect">link</a> </p>

<h3>Conclusion</h3>
<p>This project is a simple but effective demonstration of the power of CSS animations, transitions, and transforms. It can be used as a starting point for your own projects or as a way to learn more about these techniques.</p>
