At the request of the of the folks over at After the Deadline this plugin has been forked. One of the key pieces that has been completed at this point is basically preventing the destruction of textareas in favor of a hide/show approach. More development and enhancements will come later.

<h4>What's New</h4>
<h5>16 March 12</h5>
<ul>
<blockquote><li>Updated the TEXTAREA code to do a final sync of the DIV content back to the TEXTAREA when restoring the TEXTAREA.</li>
</ul>
<h5>15 March 12</h5>
<ul>
<li>Updated core.getAttrib() to use the DOM getAttribute() method in Internet Explorer instead of jQuery().attr() as the jQuery function is not properly handling custom attributes.</li>
</ul>
<h5>1 March 12</h5>
<ul>
<li>Updated AtD.restoreTextArea &amp; AtD.