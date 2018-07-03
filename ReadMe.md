# Rock Agency Theme
This Theme is designed for your public facing Rock site.  It's based upon an open source bootstrap theme, <a href="https://startbootstrap.com/template-overviews/agency/" target="_blank">Agency</a>.

This Theme includes customized layouts, adtional lava Templates, and a custom block for a staff section.

<h4>Layouts</h4>
<ul>
    <li>Homepage</li>
    <li>Full Width</li>
    <li>Left Sidebar</li>
    <li>Right Sidebar</li>
    <li>Three Column</li>
</ul>
<h4>Blocks</h4>
<ul>
    <li>Group Member List Lava</li>
</ul>
<h4>Lava Templates</h4>
<ul>
    ---ADDED---
    <li>Team.lava</li>
    <li>TimeLine.lava</li>
    <li>GroupFinder.lava</li>
    <br/>---MODIFIED---
    <li>BlogItemList.Lava</li>
    <li>Calendar.Lava</li>
    <li>PageNav.Lava</li>
    <li>PageSubNav.Lava</li>
    <li>PodcastSeriesList.Lava</li>
    <li>Calendar.Lava</li>
    <li>ScheduledTransactionSummary.Lava</li>
</ul>

<h4>Intall Notes</h4>
<ul>
    <li>A Page Attribute titled <code>Header Image</code> is needed for the header background.</li>
    <li>The Homepage layout has the option to add text inside the header.  Use the markup Below as a guide<br/>
    <pre><code>
&lt;div class="intro-lead-in"&gt;Latest Message&lt;/div&gt;
&lt;div class="intro-heading text-uppercase"&gt;My Message Title&lt;/div&gt;
&lt;a class="btn btn-primary btn-xl text-uppercase" href="#"&gt;Watch&lt;/a&gt;

</code></pre>
    </li>
    <li>
        The Timeline Lava is designed for a content channel that's manually ordered.  It required content, and two Item Attributes:<code>Image</code>, <code>Milestone Date</code><br/>
        Items don't require an image.  If you don't place an image, the title will display inside a circle with the primary theme color as the BG.
    </li>
</ul>