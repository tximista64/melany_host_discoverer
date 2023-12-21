<h1>melany24_host_discovery</h1>
<h2>A Bash Network Quick Host Discoverer</h2>



![image](https://github.com/tximista64/melany_host_discoverer/assets/91343277/375433f6-aa24-49e7-8706-02242dd7ae5b)



<h2>How 2</h2>
Download it<br />
<code>git clone https://github.com/tximista64/melany_host_discoverer</code><br />
Set it executable<br />
<code>chmod +x melany24.sh</code><br />
Use it<br />
<code>./melany24.sh 192.1.1</code><br />
You can output the results in a file<br /> 
<code>./melany24.sh 192.168.1 > hosts.txt</code><br />
A use of nmap with the output file could be relevant<br />
<code>for ip in $(cat hosts.txt); do nmap -A $ip -oX scan & done</code>
<br />
