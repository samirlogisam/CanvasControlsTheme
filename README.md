In today's article, I would like to share a quick solution i've put in place for one of my projects, where the colours keep changing and I wanted to be ready for any theme changes when required.

The different theme colours would be stored in a collection which will be referenced by the different Power Apps controls instead of hard coded.

I have created a simple screen, which allows me to set the different colours such as:
<ul>
 	<li>Button fill,</li>
 	<li>Button text,</li>
 	<li>Border,</li>
 	<li>Chevron background colour ...etc.</li>
</ul>
I wanted also to view the rendering of the most used controls:
<ul>
 	<li>Textbox</li>
 	<li>Text input</li>
 	<li>Dropdown</li>
</ul>
<a href="https://samtech365.com/wp-content/uploads/2023/10/Screenshot-2023-10-17-at-23.02.54.png"><img class="aligncenter size-full wp-image-100759" src="https://samtech365.com/wp-content/uploads/2023/10/Screenshot-2023-10-17-at-23.02.54.png" style="height:1030" /></a>
<h1>Application Strucure</h1>
The app has one screen only, with two containers:
<h2>Colours definition</h2>
In the left section, you will be able to set the different colours,

The colours values are expected in Hex format, we will use the ColorValue function to convert the colours to RGBA format.

If you want to learn more about ColorValue, ColorFade and different ways to convert hex to rgba and apply transparency, please visit the Microsoft reference -&gt;

<a href="https://learn.microsoft.com/en-us/power-platform/power-fx/reference/function-colors">Color enumeration and ColorFade, ColorValue, and RGBA functions in Power Apps - Power Platform | Microsoft Learn</a>

In addition, this panel, will render the collection definition, which you can just copy and paste in your project.
<h2>Preview panel</h2>
This area is the preview area, it allows you to view and amend the colours if you are not happy with the results.

Enjoy !

&nbsp;
