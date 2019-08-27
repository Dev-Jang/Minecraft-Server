# Minecraft-Server

## Step 1. Download Java
<pre><code>apt install java</code></pre>

<br>
## Step 2. Download Screen
<pre><code>apt install screen</code></pre>

<br>
## Step 3. Download The Forge Installer
Now download the version 1.12.2 [Forge Installer](https://files.minecraftforge.net/).

<br>
## Step 4. Configure New Minecraft Server
### Install Server
<pre><code>java -jar forge-1.12.2-14.23.5.2838-installer.jar --installServer</code></pre>
### Run Server
<pre><code>java -Xms1024M -Xmx2048M -jar /minecraft/forge-1.12.2-14.23.5.2838-universal.jar nogui</code></pre>
### Accept the EULA
<pre><code>vim eula.txt
eula=true</code></pre>
### Run Server again
<pre><code>java -Xms1024M -Xmx2048M -jar /minecraft/forge-1.12.2-14.23.5.2838-universal.jar nogui</code></pre>

<br>
## Optional Step. Create Booter.sh
<pre><code>vim booter.sh</code></pre>
<pre><code>screen -S mine java -Xms1024M -Xmx2048M -jar /minecraft/forge-1.12.2-14.23.5.2838-universal.jar nogui</code></pre>
done.
