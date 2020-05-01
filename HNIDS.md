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
        <h1>Host-Based Network Intrusion Detection System<a href="https://github.com/exaybachay-ak/RedVsBlue/blob/master/HNIDS.ps1"> (Github link)</a></h1>
        <br /><br />
        HNIDS.ps1 began, as most of my programming projects do, as an idea that spontaneously occurred to me one day.  I was working on the SOC (Security Operations Center) and noted how frequently I tended to look up hashes and ip addresses to determine the nature of files and systems that were communicating with hosts on my network.
        <br /><br />
        I had already began to work on RedVsBlue, which is a project that aims to tie all of my projects together, and become a platform for any pentester or SOC analyst.  HNIDS fit perfectly into this project, where my goal is to have HNIDS run at a specific interval (every hour, or less if specified), and comb through Sysmon logs to gather all IP addresses and file hashes, and then catalog them to report back if any stick out as being worth further investigation.  
        <br /><br />
        Ultimately, this project is still in its early stages, but I can envision a case where there will be 2 variants of this script.  One will be the "everyone can and should use this" version, which just scans logs and reports back to the user if it sees anything that may be odd or suspicious.  The second version would be for deployment across a whole enterprise, which would send alerts via email to your enterprise's SOC team to enable faster incident response.
      <br /><br />
      <img src="/assets/HNIDS_Screenshot.png" />

      
      <footer>

      </footer>
    </div>
    <script src="{{ '/assets/js/scale.fix.js' | relative_url }}"></script>

  </body>
</html>
