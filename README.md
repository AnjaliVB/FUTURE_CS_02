<h1>Task 02 - Phishing Email Detection & Awareness System</h1>

<!--![Banner](https://imageio.forbes.com/specials-images/imageserve/65cb9e725c84496aeccd33c1/0x0.jpg?format=jpg&height=600&width=1200&fit=bounds)-->
<img src="https://imageio.forbes.com/specials-images/imageserve/65cb9e725c84496aeccd33c1/0x0.jpg?format=jpg&height=600&width=1200&fit=bounds" width="3000" height="400px">
<h3>Objectives of this task</h3>
<ul>
<li>Analyze real phishing email samples</li>
<li>Identify common phishing indicators</li>
<li>Classify email risk clearly</li>
<li>Explain attacks in simple, non-technical language</li>
<li>Create an awareness document that helps users avoid phishing attacks</li>
</ul>

<h2></h2>

<h3>What is Phishing ?</h3>
Phishing is a cybercrime where attackers masquerade as reputable sources via email, text, or phone to steal sensitive information like passwords, credit card details, and personal data. These fraudulent messages often create a false sense of urgency, urging victims to click malicious links or download attachments, resulting in financial loss or identity theft.Phishing attacks typically involve fraudulent communication, often through emails, messages, or websites that appear legitimate. The attacker tricks the victim into clicking a malicious link, downloading an attachment, or providing confidential information. Once the victim responds, the attacker gains access to sensitive data or systems.

<h3>Types of Phishing</h3>
<ol>
<li>Email Phishing: Mass emails sent to many users posing as legitimate organizations. </li>
<li>Spear Phishing: Targeted attacks aimed at specific individuals or organizations. </li>
<li>Smishing: Phishing conducted via SMS or text messages. </li>
<li>Vishing: Voice-based phishing using phone calls. </li>
<li>Clone Phishing: A legitimate message is copied and altered with malicious links or attachments. </li>
</ol>

<h3>Recent trends in phishing</h3>
<ol>
  <li><b>AI phishing</b>: AI phishing uses generative artificial intelligence (AI) tools to create phishing messages. These tools can generate tailored emails and text messages that lack spelling errors, grammatical inconsistencies and other common red flags of phishing attempts.</li>
  <li><b>Quishing</b>: Uses fake QR codes embedded in emails and text messages or posted in the real world. Quishing allows hackers to hide malicious websites and software in plain sight.</li>
  <li><b>Hybrid vishing</b>: These attacks combine voice phishing with other methods to evade spam filters and gain victims' trust.</h4></li>
</ol>

<h2></h2>

<h3>Tools Used</h3>

<ul>
  <li><b>MXToolbox for email header analysis</b>: MXToolbox is a free online tool widely used by IT and cybersecurity professionals to troubleshoot email infrastructure and check domain health. It offers real-time insights into DNS configurations, email deliverability issues, blacklist status, and mail server availability.
    <ul>
      <b>MXToolbox supports a wide range of functions, but its core capabilities fall into five categories:    </b>
      <li>DNS Record Lookup: Retrieve and validate DNS entries, including MX (mail exchanger), A (address), and TXT (SPF, DMARC).</li>
      <li>SMTP Diagnostics: This test will connect to a mail server via SMTP and perform a simple Open Relay Test.</li>
      <li>Blacklist Check: Scan your IP address or domain across more than 100 DNS-based blacklists (DNSBLs) to assess whether your email might be blocked or flagged as spam.</li>
      <li>Email Header Analysis: This tool will translate email headers into a human readable format and analyze the results and path of the email, which can provide informative data on anti-spam results and more.</li>
      <li>Monitoring and Alerts: Set up alerts for when domains get blacklisted and more.</li>
    </ul>
  </li>
  
  <li><b>AbuseIPDB</b>: AbuseIPDB is a popular crowdsourced database used by webmasters and system administrators to report and identify IP addresses involved in malicious activity, such as hacking, spamming, or DDoS attacks. It helps secure networks by providing a blacklist API to check IP reputations and report threats, aiming to make the internet safer. 
    <ul>
      <b>Key Aspects of AbuseIPDB</b>
      <li>Crowdsourced Security: It relies on community reports, where thousands of users submit reports on malicious IPs daily.</li>
      <li>API & Integrations: It offers a free API for querying IPs and integrates with security tools like Fail2Ban, Splunk, Maltego, and Cortex XSOAR.</li>
      <li>Abuse Score: It generates an "abuseConfidenceScore" to indicate the likelihood that an IP is malicious based on report frequency.</li>
      <li>Functionality: Users can check IP addresses, report malicious IPs, and download blacklists. </li>
    </ul>
    <ul>
      <b>Common Usage Examples</b>
      <li>Checking IP Reputation: A web developer uses the API to check if a visitor's IP has a high abuse score before allowing registration.</li>
      <li>Automating Firewall Rules: Using fail2ban to automatically block IPs that have been reported to AbuseIPDB.</li>
      <li>Threat Intelligence: Integrating AbuseIPDB with Splunk to analyze and visualize malicious network traffic.</li>
      <li>Bulk Reporting: Submitting logs of attacks in CSV format to the AbuseIPDB bulk reporter. </li>
    </ul>
  </li>
  
</ul>
