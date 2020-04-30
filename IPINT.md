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
        <h1>IP Intel</h1>
        <br /><br />
        IPINT is a project that I created to simplify the SOC (Security Operations Center) process for my fellow SOC personnel during a high-profile engagement.  We frequently would pull up sites like GreenSnow.co, ThreatMiner, VirusTotal, and Shodan, to determine what we were seeing in some network traffic, and it just seemed like we kept pulling up the same sites for OSINT over and over again. <br /><br />
        In order to simplify everything, I figured it would help to create a JavaScript extension that could inject IFRAMEs onto current websites, and which would have the secondary benefit of working independantly of the actual technological platform that you were utilizing to run the SOC.<br /><br />
        IPINT is the project that I created to assist SOC personnel with their investigations.  It pulls together sites like Censys, Shodan, ThreatMiner, ThreatCrowd, AlienVault, and IPINFO, to assist SOC personnel with investigating their suspicious network traffic.<br />
      <b>Examples of IPINT in action follow:</b><br />
      <u>Example of IPINT Without Transparency:</u><br />
      <img src="/assets/images/ELK_Platform_IPINT_1.png" /><br /><br />
      <u>Example of IPINT WITH Transparency:</u><br />
      <img src="/assets/images/ELK_Platform_IPINT_1_trans.png" /><br /><br />
      <u>Example of IPINT Without Transparency:</u><br />
      <img src="/assets/images/Fidelis_Platform_IPINT_1.png" /><br /><br />
      <u>Example of IPINT Without Transparency:</u><br />
      <img src="/assets/images/Fidelis_Platform_IPINT_1_trans.png" /><br /><br />
            
      
      <footer>

      </footer>
    </div>
    <script src="{{ '/assets/js/scale.fix.js' | relative_url }}"></script>

  </body>
</html>
