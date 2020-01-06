# web-design-dev-links
This is a place where I'll keep a list of resources I've come across that are helpful for web design/development.


  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: beige;
      color: #232323;
      font-size: 18px;
      font-family: sans-serif;
      font-weight: 300;
    }
    a,
    a:visited {
      font-weight: 500;
      color: #707000;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline
    }

    p, ul, h1, h2, h3, h4, h5, h6 {
      margin: .8em 0 .4em 0;
    }

    li {
      margin: .5em 0;
    }

    h1 {
      font-size: 2em;
      font-weight: 100;
    }
    h2 {
      font-size: 1.6em;
      font-weight: 100;
    }
    h3 {
      font-size: 1.1em;
      font-weight: 100;
      font-style: italic;
    }
    ul {
      margin-top: .2em;
      padding-left: 1em;
      list-style: none;
    }
    li::before {
      content: "\2022";
      color: olive;
      display: inline-block;
      width: .7em;
      margin-left: -1em;
      font-weight: 700;
    }
    header {
      margin: auto;
      padding: 40px 40px 0px 40px;
      max-width: 1000px;
    }
    section {
      margin: 0 auto 20px auto;
      padding: 5px 40px;
      max-width: 1000px;
    }
    .top-call-out {
      border: 1px solid rgb(209, 209, 187);
      border-radius: 4px;
      padding: 10px 15px;
      display: inline-block;
      background: rgb(255, 255, 238);
      box-shadow: inset 0 0 5px rgba(0, 0, 0, .2);
      font-size: .8em;
    }
    .mid-call-out {
      border: 2px dashed rgb(22, 138, 132);
      border-radius: 8px;
      padding: 10px 15px;
      display: inline-block;
      background: rgb(53, 230, 221);      
      font-size: .8em;
    }
    footer {
      width: 100%;
      background: #264348;
      color: white;
      margin: 0;
    }
    .footerContent {
      margin: 0 auto;
      padding: 40px;
      max-width: 1000px;
    }

    footer a,
    footer a:visited {
      color: white;
      text-decoration: underline;
      font-weight: 100;
    }

    footer a:hover {
      text-decoration: none;
    }

    @media screen and (max-width:675px) {
      header {
        padding: 10px 20px;
      }
      section,
      .footerContent {
        padding: 10px 20px;
      }
    }
  </style>


  <header>
    <h1>Web design/dev links</h1>
    <div class="top-call-out">
      This is a place where I'll keep a running list of resources I've come across that are helpful for web design/development.
    </div>
  </header>

  <section>

    <h2>Code validation</h2>
    <ul>
      <li>
        <a href="https://validator.w3.org/" target="_blank" rel="noopener noreferrer">W3C Validator</a> - the code validator to make sure your web page meets W3C standards.
      </li>
      <li>
        <a href="https://validator.w3.org/unicorn/" target="_blank" rel="noopener noreferrer">Unicorn</a> - the all-encompassing version of the code validator to make sure your web page meets W3C standards.
      </li>
    </ul>

    <h2>Accessibility tools</h2>
    <ul>      
      <li>
        <a href="https://webaim.org/resources/contrastchecker/" target="_blank" rel="noopener noreferrer">WebAIM: Color Contrast Checker</a> - test to see if you website meets accessibility for contrast.
      </li>
      <li>
        <a href="https://www.toptal.com/designers/colorfilter" target="_blank" rel="noopener noreferrer">Toptal Color Blind Filter</a> - test your website for color blind accessibility.
      </li>   
      <li>
        <a href="https://www.funkify.org" target="_blank" rel="noopener noreferrer">Funkify disability simulator Chrome Extension</a> - lets you test your web site simulating different abilities and disabilities.
      </li>   
      <li>
        <a href="http://colorsafe.co/" target="_blank" rel="noopener noreferrer">Color Safe</a> - helps designers create accessible color combinations.
      </li>
    </ul>

    <h2>Site performance</h2>
    <ul>
      <li>
        <a href="https://gtmetrix.com/" target="_blank" rel="noopener noreferrer">GT Metrix</a> - check your site's speed - see why it's slow and how to optimize.
      </li>
      <li>
        <a href="https://developers.google.com/speed/pagespeed/insights/" target="_blank" rel="noopener noreferrer">Google's PageSpeed Insights</a>.
      </li>
    </ul>

    <h2>Dev tools and text editors</h2>
    <div class="mid-call-out">There are so many great text editors now. Many are open source.</div>
    <ul>
      <li><a href="https://code.visualstudio.com/" target="_blank" rel="noopener noreferrer">VS Code</a> (Open source, from Microsoft)</li>
      <li><a href="https://atom.io/" target="_blank" rel="noopener noreferrer">Atom</a> (Open source, from GitHub)</li>
      <li><a href="https://brackets.io/" target="_blank" rel="noopener noreferrer">Brackets</a> (Open source, from Adobe)</li>
      <li><a href="https://notepad-plus-plus.org/" target="_blank" rel="noopener noreferrer">Notepad++</a> (Free, from Don Ho)</li>
      <li><a href="https://www.sublimetext.com/" target="_blank" rel="noopener noreferrer">Sublime</a> (Proprietary)</li>
    </ul>

    <h3>Text Editor Extensions</h3>
    <ul>     
      <li><a href="https://prettier.io/docs/en/options.html" target="_blank" rel="noopener noreferrer">Emmet</a> - lets you write HTML markup and CSS rules <em>very very quickly</em>, <a href="https://docs.emmet.io/cheat-sheet/">check out this cheat sheet</a> to get an idea of of the shortcuts available.</li> 
      <li><a href="https://prettier.io/docs/en/options.html" target="_blank" rel="noopener noreferrer">Prettier</a> - a code formatter that is pretty opinionated but widely embraced.</li>
      <li><a href="https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslintl" target="_blank" rel="noopener noreferrer">ES Lint</a> - a popular JavaScript linter.</li>
    </ul>

    <h3>Web-based code editing</h3>
    <ul>     
      <li><a href="https://codepen.io/" target="_blank" rel="noopener noreferrer">Codepen</a> - a web-based code editor that is a great place to show off your work.</li> 
      <li><a href="https://jsfiddle.net/" target="_blank" rel="noopener noreferrer">JSFiddle</a> - a web-based editor that is more minimal than Codepen - great for proofs of concept, or solving questions on StackOverflow.</li>
      <li><a href="https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslintl" target="_blank" rel="noopener noreferrer">Code Sandbox</a> - another web-based code editor with the difference that it functions more like a full IDE.</li>
    </ul>


    <h2>Dev resources</h2>  
    <ul>     
      <li>
        <a href="https://www.mozilla.org/en-US/firefox/developer/" target="_blank" rel="noopener noreferrer">Firefox Developer Edition</a> - my preferred browser for development - it has all the best tools.
      </li> 
      <li>
        <a href="https://stackoverflow.com/" target="_blank" rel="noopener noreferrer">StackOverflow</a> - the place to go when you have a question, any question.
      </li>
      <li>
        <a href="https://technicalseo.com/tools/schema-markup-generator/" target="_blank" rel="noopener noreferrer">Schema Markup Generator</a> - a cool tool for quickly making structured data (example: for a business listing).
      </li>
      <li>
        <a href="https://github.com/thedaviddias/Front-End-Checklist" target="_blank" rel="noopener noreferrer">The Front-End Checklist</a> - a nice check list for web projects, pretty comprehensive.
      </li>
      <li>
        <a href="https://www.diffchecker.com/" target="_blank" rel="noopener noreferrer">Diff Checker - Online diff tool to compare text to find the difference between two text files</a> - every coder needs
        a good diff checker tool. This one works right in the browser.
      </li>
      <li>
        <a href="https://html-cleaner.com/" target="_blank" rel="noopener noreferrer">HTML Cleaner - Word To HTML Converter</a> - ever get a copy document in Word format and struggle removing
        the formatting, or need to make some minor html edits where a simple WYSIWYG would do, then try out this great tool.
      </li>
      <li>
        <a href="https://www.cleancss.com/css-beautify/" target="_blank" rel="noopener noreferrer">CSS Formatter and Beautifier</a>
      </li>
      <li>
        <a href="http://www.initializr.com/" target="_blank" rel="noopener noreferrer">Initializr - Start an HTML5 Boilerplate project in 15 seconds!</a> - a great tool for throwing up a site fast.
      </li>
      <li>
        <a href="http://embedresponsively.com/" target="_blank" rel="noopener noreferrer">Embedresponsively.com</a> - make your embedded videos responsive with this handy tool. They will then adjust to fit the max width of their container.
      </li>
      <li>
        <a href="https://css-tricks.com/snippets/css/media-queries-for-standard-devices/" target="_blank" rel="noopener noreferrer">Media Queries for Standard Devices | CSS-Tricks</a>
      </li>
      <li>
        <a href="https://h5bp.github.io/Front-end-Developer-Interview-Questions/" target="_blank" rel="noopener noreferrer">Front-end Developer Interview Questions</a> - looking for a job? Looking to hire? Here's an exhaustive list of good
        Front-end Dev interview questions.
      </li>
      <li>
        <a href="https://easings.net/en" target="_blank" rel="noopener noreferrer">CSS Easings</a> - use this guide to visualize CSS easing functions.
      </li>
      <li>
        <a href="http://www.ascii.cl/htmlcodes.htm" target="_blank" rel="noopener noreferrer">HTML Codes - Table of ascii characters and symbols</a>
      </li>
      <li>
        <a href="https://docs.emmet.io/cheat-sheet/" target="_blank" rel="noopener noreferrer">Cheat Sheet</a> - you should be using Emmet to write your code, this cheat sheet helps you know all the shortcuts.
      </li>
      <li>
        <a href="https://mapstyle.withgoogle.com/" target="_blank" rel="noopener noreferrer">Styling Wizard: Google Maps APIs</a> - helps you style a Google Map API.
      </li>
      <li>
        <a href="https://htmlhead.dev/" target="_blank" rel="noopener noreferrer">&lt;head&gt; cheatsheet - A free guide to &lt;head&gt; elements</a>
      </li>
      <li>
        <a href="https://www.willpeavy.com/minifier/" target="_blank" rel="noopener noreferrer">HTML Minifier - Minify HTML and any CSS or JS included in your markup</a> - minify your code to make it load faster
        (note: I would only use this on high trafficked pages).
      </li>
      <li>
        <a href="https://css2sass.herokuapp.com/" target="_blank" rel="noopener noreferrer">Convert CSS to SASS</a> I find this helpful to quickly update an existing CSS project to a SASS file.
      </li>
      <li>
        <a href="http://htmltohaml.com/" target="_blank" rel="noopener noreferrer">Convert HTML into HAML</a>.
      </li>      
      <li>
        <a href="https://html5boilerplate.com/" target="_blank" rel="noopener noreferrer">HTML5 Boilerplate</a> - everything you need to jump start an HTML5 web project.
      </li>
      <li>
        <a href="https://h5bp.github.io/" target="_blank" rel="noopener noreferrer">H5BP &hearts; Open Source home of HTM5 Boilerplate.</a>
      </li>
      <li>
        <a href="https://github.com/verekia/js-stack-from-scratch" target="_blank" rel="noopener noreferrer">GitHub - verekia/js-stack-from-scratch: Step-by-step tutorial to build a modern JavaScript stack.</a>
      </li>   
      
    </ul>

    <h3>Bootstrap resources</h3>
    <ul>
      <li>
        <a href="http://bootstrapstarterkit.com/bskit-demo/" target="_blank" rel="noopener noreferrer">Bootstrap Starter Kit - HTML BUILDER</a>
      </li>
      <li>
        <a href="http://www.metabootstrap.com/" target="_blank" rel="noopener noreferrer">Meta Bootstrap &ndash; A User-Interface Library adding Hundreds of Bootstrap Layouts &amp; Features to Twitter Bootstrap</a>
      </li>
      <li>
        <a href="https://bootflat.github.io/" target="_blank" rel="noopener noreferrer">Bootflat</a>
      </li>
    </ul>

    <h3>File compression, transfer, security</h3>
    <ul>
      <li>
        <a href="https://tinypng.com/" target="_blank" rel="noopener noreferrer">TinyPNG &ndash; Compress PNG images while preserving transparency</a> - this tool uses AI to drastically reduce the
        file size of PNG and JPEG images.
      </li>
      <li>
        <a href="https://smallpdf.com/compress-pdf" target="_blank" rel="noopener noreferrer">Compress PDF &ndash; Reduce your PDF Online for Free</a> - like TinyPNG but for PDFs.
      </li>
      <li>
        <a href="https://wetransfer.com/" target="_blank" rel="noopener noreferrer">WeTransfer</a> - need to transfer a huge file to a client? WeTransfer lets you send up to 2 GB free. the only catch
        is that the file will delete after 7 days.
      </li>
      <li>
        <a href="https://www.virustotal.com/" target="_blank" rel="noopener noreferrer">VirusTotal - Free Online Virus, Malware and URL Scanner</a> - a free online tool to check files for malware. You
        drag and drop a file on the page and it runs it through most of the scanning apps. 
      </li>
    </ul>    

    <h2>Design/UI resources</h2>
    <ul>
      <li>
        <a href="https://affinity.serif.com/en-us/" target="_blank" rel="noopener noreferrer">Affinity design software</a> - A much more affordable alternative to Creative Cloud. 
      </li>
      <li>
        <a href="http://pxtoem.com/" target="_blank" rel="noopener noreferrer">PXtoEM.com: PX to EM conversion made simple.</a> - a handy tool to easily calculate the difference between pixels
        and em units.
      </li>
      
      <li>
        <a href="https://docs.balsamiq.com/desktop/text/" target="_blank" rel="noopener noreferrer">Working With Text [Balsamiq Mockups for Desktop] - Balsamiq Documentation</a> - if you use the Balsamiq app for wire-framing,
        then this documentation will be very helpful.
      </li>
      <li>
        <a href="http://www.roget.org/" target="_blank" rel="noopener noreferrer">ROGET's Hyperlinked Thesaurus</a> - this great basic thesaurus will help you expand your vocabulary. Also the site
        is very minimalist and lacking all the ad and bloat of most thesaurus/dictionary sites.
      </li>         
      <li>
        <a href="https://jonnyjordan.com/blog/disable-mouse-scroll-wheel-zoom-embedded-google-map-iframes/" target="_blank" rel="noopener noreferrer">Disable the mouse scroll wheel zoom on embedded Google Map iframes - Jonny Jordan</a>
      </li>      
    </ul> 

    <h3>UI/UX/IxD resources</h3>
    <ul>
      <li>
        <a href="https://baymard.com/blog/trigger-indicators" target="_blank" rel="noopener noreferrer">UI: Proper Indicators for Hidden Elements - Articles - Baymard Institute</a> - a nice read about when it's really
        appropriate to include a CTA.
      </li> 
      <li>
        <a href="https://twitter.com/i/moments/880688233641848832" target="_blank" rel="noopener noreferrer">Little UI Details</a> - a collection of recent UI tips
      </li>
      <li>
        <a href="https://github.com/alexpate/awesome-design-systems" target="_blank" rel="noopener noreferrer">GitHub - alexpate/awesome-design-systems: A collection of awesome design systems</a>
      </li>
      <li><a href="https://uxplanet.org/ux-vs-ui-vs-ia-vs-ixd-4-confusing-digital-design-terms-defined-1ae2f82418c7" target="_blank" rel="noopener noreferrer">UX vs UI vs IA vs IxD : 4 Confusing Digital Design Terms Defined</a>Medium article.</li>
      <li><a href="https://www.interaction-design.org/" target="_blank" rel="noopener noreferrer">Interaction Design Foundation</a>.</li>
      <li><a href="https://ixda.org/" target="_blank" rel="noopener noreferrer">Interaction Design Association</a> - <a href="https://ixda.org/community/local-groups/" target="_blank" rel="noopener noreferrer">find your local group</a>.</li>
    </ul>

    <h3>Color resources</h3>
    <ul>
      <li>
        <a href="https://color.adobe.com/" target="_blank" rel="noopener noreferrer">Adobe Color CC</a> - Color (formally Kueler) is a nice tool provided by Adobe that lets you create a color palate
        for your web project.
      </li>
      <li>
        <a href="https://bootflat.github.io/color-picker.html" target="_blank" rel="noopener noreferrer">Color Picker - All - Bootflat</a> - a great set of "flat design" color choices.
      </li>
      <li>
        <a href="https://www.w3schools.com/colors/colors_picker.asp" target="_blank" rel="noopener noreferrer">HTML Color Picker</a> - from w3schools, find a web safe color.
      </li>
    </ul> 

    <h3>Web fonts and icon fonts</h3>
    <ul>
      <li>
        <a href="https://fonts.google.com/" target="_blank" rel="noopener noreferrer">Google Fonts</a> - a great collection of embeddable web fonts; easy to add.
      </li>
      <li>
        <a href="http://fontawesome.io" target="_blank" rel="noopener noreferrer">Font Awesome</a> - icon fonts are all the rage because of their clear vector appearance and how easy they are to implement.
        Font Awesome is one of the best, and free to use.
      </li>
      <li>
        <a href="https://material.io/icons/" target="_blank" rel="noopener noreferrer">Material icons - Material Design</a> - the material icons by Google are great alternative to font awesome, and look
        just as beautiful. No reason not to use as many icon fonts as you like.
      </li>
      <li>
        <a href="https://github.com/vkarampinis/awesome-icons">A list of all the rest of the icon fonts out there</a> - many many more icon fonts listed here.
      </li>
    </ul>

    <h3>Free stock images and placeholder resources</h3>
    <ul>
    <li>
        <a href="https://www.pexels.com/" target="_blank" rel="noopener noreferrer">Free stock photos &middot; Pexels</a> - a collection of creative commons licensed images that are available
        for personal or commercial use. 
      </li>
      <li>
        <a href="https://placehold.it/" target="_blank" rel="noopener noreferrer">Placehold.it - Quick and simple image placeholders</a> - need an image placeholder, this easy to use site can provide
        you any size you need.
      </li>
    </ul>

    <h3>Lorem Ipsums</h3>
    <ul>
      <li>
        <a href="https://loremipsum.io/" target="_blank" rel="noopener noreferrer">Classic Lorem Ipsum</a> - the orignal latin placeholder text used for previewing layouts in design without actual copy.
      </li>

      <li>
        <a href="https://baconipsum.com/" target="_blank" rel="noopener noreferrer">Bacon Ipsum</a> - Lorem Ipsum for meat-eaters.
      </li>
      <li>
        <a href="https://veggieipsum.com/" target="_blank" rel="noopener noreferrer">Veggie Ipsum</a> - Lorem Ipsum for vegetarians.
      </li>
      <li>
        <a href="http://www.atrixnet.com/bs-generator.html" target="_blank" rel="noopener noreferrer">Corporate B.S. Generator</a> - sometimes you just need to fake you're a smooth talking corporate stooge, this is
        for those times.
      </li>
      <li>
        <a href="http://penelope.uchicago.edu/Thayer/E/Roman/Texts/Cicero/de_Finibus/1*.html" target="_blank" rel="noopener noreferrer">The original text by Cicero</a> - translated from Latin into English, this is the original text on which Lorem Ipsum is based.
      </li>
    </ul>
   

    <h2>Open source tools</h2>
    <ul>
      <li><a href="http://www.gimp.org/" target="_blank" rel="noopener noreferrer">GIMP</a> - raster image editor (similar to Photoshop)</li>
      <li><a href="http://www.inkscape.org/" target="_blank" rel="noopener noreferrer">Inkscape</a> - vector image editor (similar to Illustrator)</li>
      <li><a href="http://www.scribus.net/" target="_blank" rel="noopener noreferrer">Scribus</a> - desktop publishing (similar to InDesign)</li>
      <li><a href="http://www.libreoffice.org/" target="_blank" rel="noopener noreferrer">Libre Office</a> - office suite of apps (similar to Microsoft Office)</li>
    </ul>


  </section>
  <footer>
    <div class="footerContent">
      <p>
        Version 2.0 - compiled by Jonathan Huffman - with thanks to coworkers colleagues and friends.
      </p>
    </div>
  </footer>
