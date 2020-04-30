<html lang="{{ site.lang | default: "en-US" }}">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="chrome=1">

{% seo %}
    <meta name="viewport" content="width=device-width">
    <!--[if lt IE 9]>
    <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
  </head>
  <body>
    <div class="wrapper">
        <h1>PowerSteg</h1>
        <br /><br />
        PowerSteg is a program that I created to defeat a current generation (~2018) application layer firewall during a penetration test. <br /><br />
        During an offensive penetration test with a Fortune 10 company, we were tasked with exfiltrating files out of their network, to simulate a disgruntled employee.  
        To test their DLP (Data-Loss Prevention) system, I wrote a program to insert PowerShell commands into images, and use those commands to then run instructions to exfiltrate information past their Layer 7 Palo Alto firewall.
      
      <footer>

      </footer>
    </div>
    <script src="{{ '/assets/js/scale.fix.js' | relative_url }}"></script>

  </body>
</html>
