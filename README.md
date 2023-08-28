<h1>Offensive</h1>
<b> Vuln detection </b>
<li><a href="https://es-la.tenable.com/products/nessus/nessus-essentials">Nessus</a></li>
<li><a href="https://openvas.org/">Openvas</a></li>
<li><a href="https://www.zaproxy.org/">OwaspZap</a></li>
<li><a href="https://portswigger.net/burp/communitydownload">BurpSuite</a></li>
<br>
  
<b>Headers</b>
<li><a href="https://securityheaders.com/">SecurityHeaders</a></li>
<li><a href="https://www.ssllabs.com/ssltest/">SSLLabs</a></li>
<li><a href="https://github.com/drwetter/testssl.sh">TestSSL</a> </li>
<li><a href="https://github.com/rbsec/sslscan">Sslscan</a></li>
<br>

<b>Brute force</b>
<li><a href="https://github.com/mohamm4dx/SilverBullet">Silverbullet</a></li>
<li><a href="https://github.com/openwall/john">JohnTheRipper</a></li>
<li><a href="https://github.com/vanhauser-thc/thc-hydra">Hydra</a></li>
<br>

<b>SQL</b>
<li><a href="https://github.com/sqlmapproject/sqlmap">SqlMap</a></li>
<br>
  
<b>Osint / Info gathering</b>
<li><a href="https://maltego.com">Maltego</a></li>
<li><a href="https://github.com/laramies/theHarvester">TheHardvester</a></li>
<li><a href="https://github.com/aboul3la/Sublist3r">Sublist3r</a></li>
<li><a href="https://github.com/TheRook/subbrute">Subbrute</a></li>
<li><a href="https://github.com/projectdiscovery/subfinder">Subfinder</a></li>
<br>

<b>Data leak</b>
<li><a href="https://haveibeenpwned.com/">HaveIBeenPwned</a></li>
<br>

<b>Explotation</b>
<li><a href="https://www.metasploit.com/">Metasploit</a></li>
<br>

<b>GMaps API</b>
<li><a href="https://github.com/ozguralp/gmapsapiscanner/">GMapsApiScanner</a></li>
<br>

<b>Search engines</b>
<li><a href="https://shodan.io">Shodan</a></li>
<li><a href="https://search.censys.io/">Censys</a></li>


<h1>Deffensive</h1>

<b>Antivirus/Antirootkit</b>
<li>Clamav</li>
<li>RKHunter</li>
<br>

<b>Security Evaluation</b>
<li>Debsecan</li>
<li>Lynis</li>
<br>

<b>IDS</b>
<li>Snort</li>
<br>

<b>WAF</b>
<li>ModSecurity</li>
<br>

<b>Secure Headers</b>
<li>Apache mod_headers</li>

	Header always set Access-Control-Allow-Origin "https://website.com"
	Header always set Strict-Transport-Security "max-age=31536000; includeSubdomains;"
	Header set X-XSS-Protection "1; mode=block"
	Header set X-Content-Type-Options "nosniff"
	Header always set Access-Control-Expose-Headers "Content-Security-Policy, Location"
	Header always set Content-Security-Policy "default-src https: wss: data: 'unsafe-inline' 'unsafe-eval';frame-ancestors 'self';object-src 'self';script-src 'unsafe-inline' 'unsafe-eval' 'self' maps.googleapis.com stackpathcdn.com static.zdassets.com google.com api.eu-1.smooch.io static.zdassets.com cdn.ckeditor.com oss.maxcdn.com d3js.org gyrocode.github.io ws.sharethis.com netdna-ssl.com hotjar.com c64.assets-yammer.com unpkg.com ajax.googleapis.com googleapis.com www.google-analytics.com google-analytics.com code.jquery.com cdnjs.cloudflare.com cdn.jsdelivr.net gstatic.com vimeo.com stats.g.doubleclick.net googletagmanager.com cdn.tiny.cloud cdn.datatables.net maxcdn.bootstrapcdn.com momentjs.com stackpath.bootstrapcdn.com clubandalbrok.com www.clubandalbrok.com;img-src data: blob: 'self' *.googleapis.com *.gstatic.com *.googleusercontent.com static.zdassets.com *.tinymce.com *.eulen.com *.google.com *.google-analytics.com *.google.es code.jquery.com cdnjs.cloudflare.com cdnbigbuy.com"
	Header set X-Frame-Options SAMEORIGIN
	Header always set Referrer-Policy "strict-origin"
	Header always set Permissions-Policy "accelerometer=(),gyroscope=(),magnetometer=(),microphone=(),midi=(),payment=()"


