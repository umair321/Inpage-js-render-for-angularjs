# Inpage-js-render-for-angularjs
<p> It is not possible to render <script> tag in html page when you are using angularjs. This module is made to overcome this problem.</p>
Very much easy to use:<br/>
<ol>
<li>
Just include js-render.js to your page
</li>
<li>
Add <strong>'ngLoadScript'</strong> to your app dependencies. E.g. angular.module('YOUR_APP_NAME', ['ngLoadScript'])
</li>
<li>
Used it as: <br/>
 <xmp>
<script type="text/javascript-lazy">
/**Your Script here**/
</script>
 </xmp>
</li>
</ol>
