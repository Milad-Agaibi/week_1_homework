# Repository: week_1_homework
Code Refactor

Refactor Assignment

- Refactor code using a commercial site: https://www.radum.com.au/

- Work includes:
   1. Made the title concise and descriptive: Radum: Cabinets, Cable, CCTV, Security
   2. Format the HTML file
   3. Format 5 files of the referenced CSS style sheets. To access them, I had to use
      the absolute path.
   4. Remove reference (commented out) for non-existant CSS style sheet:
      https://d39o10hdlsc638.cloudfront.net/radum/bundles/site/css/layout.css?v=1.01
   5. Modified style_5.css (template/css/custom/main-1564019890.css) to import fonts
      directly from the web:
      @import url('https://fonts.googleapis.com/css?family=Lato');
   6. Modified style_5.css (template/css/custom/main-1564019890.css) div id="nav"
      (nested in div id="nav-outer") adding effects to make it more readable on hover:
      #nav a:hover,#nav .navbar .nav > .active > a{
        color:#a54749;
        background-color: yellow;
        font-weight: bold;
        border: 1px solid;
      }
   7. Modified style_4.css (href="template/css/custom/combined-13.css) to highlight "LOGIN"
      when mouse hovers:
      #above-header-inner > div.login:hover a {
        text-transform: uppercase;
        background-color: #DC143C;
        color: #ffffff;
        font-weight: bold;
      }
   8. Ensured that alt exists for each img element and initialised it to: "none"


Sources and references:
   - cleancss.com
   - https://codebeautify.org/
   - https://jigsaw.w3.org/
   - https://validator.w3.org/
   - https://www.freeformatter.com/html-validator.html
   - http://www.css-validator.org/