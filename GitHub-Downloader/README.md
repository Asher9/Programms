<h1>GitHub-Downloader</h1>

<h2>Download</h2>
<hr>
<code>pastebin run -f rmWVAGLM name repo tree [link]</code>
<hr>
<code>wget -f https://raw.githubusercontent.com/Asher9/Asher9-s-Programms/master/GitHub-Downloader/github.lua /bin/github.lua</code><br />
<code>github name repo tree [link]</code>
<hr><br />
Benutzung: github name repo tree [link]<br />
Beispiele:<br />
<code>github Asher9 Asher9-s-Programms master Stargate-Programm</code><br />
<code>github Asher9 Asher9-s-Programms master</code><br />
<br />
Hilfetext:<br />
github ?<br />
<br />
Einbindung in Programme:<br />
1) <code>loadfile("/bin/github.lua")(name:string, repo:string, tree:string[, link:string])</code><br />
2) <code>os.execute("github name:string, repo:string, tree:string[, link:string]")</code><br />
3) <code>loadfile("/bin/pastebin.lua")("-f", "run", "rmWVAGLM", name:string, repo:string, tree:string[, link:string])</code><br />
4) <code>os.execute("pastebin run -f rmWVAGLM name:string repo:string tree:string [link:string]")</code><br />
