Responsive-jQuery-css3-Navigation-plugin
========================================

<a href="http://scriptsell.net/dropdownmenu/">Demo</a>

This Responsive jQuery & css3 Navigation plugin dropdown menu has it all. drop down menu structure will keep your users on target. dropdown menu is easy to edit and integrate into any website. dropdown menu has 12 Theme colors, each theme can be used separately without any connection with the others and very easy to update new navigation theme. Menu is responsible and adapts to the screen of the device(computer monitor, tablet, mobile phone) ! also you can use tool trip and multi color on each navigation


<p>1) Firstly, include a copy of jQuery in your document. You can download your own copy of jQuery at <a href="http://jquery.com" target="_blank">http://jquery.com</a> or link to the Google hosted script:</p>
<pre>&lt;script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"&gt;&lt;/script&gt;  </pre>
<p>2) Download and include (Responsive jQuery &amp; css3 Navigation plugin) js plugin and css to the head of your document:</p>
<pre>&lt;link href="scriptsellMenu.css" rel="stylesheet" type="text/css" /&gt;  &lt;script type="text/javascript" src="js/scriptsellMenu.js"&gt;&lt;/script&gt; </pre>
<p>3) Call the horizontalNav function in your document ready function:</p>
<pre>$(document).ready(function() {    $('.you_menu_ul').scriptsellMenu();  });</pre>
<p>4) You can override the default settings by passing in parameters like this:</p>
<pre>$(document).ready(function() {    $('ul').scriptsellMenu({      animationSpeed:150,      theme:'light-brown',      animation:'slide',      arrow:true,      tooltrip:'bottom',      hoverelements:'',      responsivemenutext:'Reponsive menu',      dropdownWidth:250,      menuheight:37,      deviceswidth:768    });  }); </pre>
<br>
There are several settings that let you adjust the behavior of the   plugin. Each of these settings is described in this section.      
<table cellspacing="0" cellpadding="0" width="100%" class="options-table">
            <thead>
              <tr>
                <th width="20%">Key</th>
                <th width="18%">Default value</th>
                <th>Description</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>animationSpeed</td>
                <td>150</td>
                <td>The amount of time to wait before re-adjusting the navigation all effects</td>
              </tr>
              <tr>
                <td><code>theme</code></td>
                <td><code>default/custom</code></td>
                <td>You can include different theme to you menu. Search as default theme or custom  theme<br>
                Here is all default theme Name :  ( deep-blue , light-sky-blue, black ,light-grey  , green , amethyst, orange , Apple green , pink , bronze,  Light brown )<br></td>
              </tr>
              <tr>
                <td>animation</td>
                <td><code>light-sky-blue</code></td>
                <td>You need to choose  a hover animation type from default setting ! here is all default animation list (slide, slide-top , fadeinout , zoom, bounce , rotate , none)</td>
              </tr>
              <tr>
                <td><code>arrow</code></td>
                <td><code>True </code></td>
                <td><p>Enables, diable dropdown arrow (<code>True / false </code>)</p></td>
              </tr>
              <tr>
                <td><code>tooltrip</code></td>
                <td><code>top</code></td>
                <td><p>Set tooltip display position &nbsp;(<code>top / bottom</code>)</p></td>
              </tr>
              <tr>
                <td><code>hoverelements</code></td>
                <td><p>&lt;span&gt;</p></td>
                <td>The HTML fragment used for the expander.</td>
              </tr>
              <tr>
                <td>responsivemenutext</td>
                <td>Reponsive menu</td>
                <td>You can override Reponsive menu text .</td>
              </tr>
              <tr>
                <td>dropdownWidth</td>
                <td>250</td>
                <td>Set a Min-dropdown width </td>
              </tr>
              <tr>
                <td>menuheight</td>
                <td>38</td>
                <td>Set navigation height </td>
              </tr>
              <tr>
                <td><code>deviceswidth</code></td>
                <td><p>768</p></td>
                <td><p>Workable responsive width </p></td>
              </tr>
            </tbody>
          </table>
 <h4>HTML Data attribute !</h4>
 
 <table cellspacing="0" cellpadding="0" width="100%" class="options-table">
            <thead>
              <tr>
                <th width="20%">Key</th>
                <th width="18%">Default value</th>
                <th>Description</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>animationSpeed</td>
                <td>150</td>
                <td>The amount of time to wait before re-adjusting the navigation all effects</td>
              </tr>
              <tr>
                <td><code>theme</code></td>
                <td><code>default/custom</code></td>
                <td>You can include different theme to you menu. Search as default theme or custom  theme<br>
                Here is all default theme Name :  ( deep-blue , light-sky-blue, black ,light-grey  , green , amethyst, orange , Apple green , pink , bronze,  Light brown )<br></td>
              </tr>
              <tr>
                <td>animation</td>
                <td><code>light-sky-blue</code></td>
                <td>You need to choose  a hover animation type from default setting ! here is all default animation list (slide, slide-top , fadeinout , zoom, bounce , rotate , none)</td>
              </tr>
              <tr>
                <td><code>arrow</code></td>
                <td><code>True </code></td>
                <td><p>Enables, diable dropdown arrow (<code>True / false </code>)</p></td>
              </tr>
              <tr>
                <td><code>tooltrip</code></td>
                <td><code>top</code></td>
                <td><p>Set tooltip display position &nbsp;(<code>top / bottom</code>)</p></td>
              </tr>
              <tr>
                <td><code>hoverelements</code></td>
                <td><p>&lt;span&gt;</p></td>
                <td>The HTML fragment used for the expander.</td>
              </tr>
              <tr>
                <td>responsivemenutext</td>
                <td>Reponsive menu</td>
                <td>You can override Reponsive menu text .</td>
              </tr>
              <tr>
                <td>dropdownWidth</td>
                <td>250</td>
                <td>Set a Min-dropdown width </td>
              </tr>
              <tr>
                <td>menuheight</td>
                <td>38</td>
                <td>Set navigation height </td>
              </tr>
              <tr>
                <td><code>deviceswidth</code></td>
                <td><p>768</p></td>
                <td><p>Workable responsive width </p></td>
              </tr>
            </tbody>
          </table>