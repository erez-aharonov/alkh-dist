# ALKH - Debugging Algorithms Suite
Name inspiration: Muhammad ibn Musa al Khwarizmi

![](https://github.com/erez-aharonov/alkh-dist/blob/main/readme_files/auto-fold.gif?raw=true)
<h2>Features</h2>
<ul>
    <li>Context based auto-folding: Understand variable's data path by selectively fold and unfold blocks of code.</li>
</ul>
<h2>Properties</h2>
<ul>
<li>Local Processing: All operations are performed on the local machine, no internet connection required.</li>
    <li>CPU-only: Designed to operate without needing a dedicated GPU.</li>  
    <li>Deterministic Algorithms: Provides consistent and predictable results.</li>
</ul>
<h2>Limitations</h2>
<ul>
    <li>Data path analysis does not include:</li>
        <ul>
            <li>Inter-class instantiation and usage</li>
            <li>Inter-file</li>
            <li>Decorators</li>
        </ul>    
</ul>

## Setting up
### Prerequisites 
> Supported operating systems:
<ul>
    <li>Windows 10</li>
    <li>Windows 11</li>
    <li>Ubuntu 22.04</li>
</ul>

> Supported IDE:
<ul>
    <li>PyCharm Community</li>
    <li>PyCharm Professional</li>
</ul>

### Installation
1. Get files: <br> 
git clone https://github.com/erez-aharonov/alkh-dist.git
2. Install plugin: 
<br>Use PyCharm's UI: File->Settings->Plugins->gear-icon->Install Plugin from Disk: Choose alkh-X.X.X.zip
![](https://github.com/erez-aharonov/alkh-dist/blob/main/readme_files/pycharm_installation.png?raw=true)
3. [Optional] Change server's port: PyCharm's UI: File->Settings->Tools->ALKH->Port number, default port is 13900
![](https://github.com/erez-aharonov/alkh-dist/blob/main/readme_files/port_setting.png?raw=true)

## Usage
1. Run server: default port is 13900
    <ul>
        <li>Linux: ./server or ./server [PORT-NUMBER]</li>
        <li>Windows: server.exe or server.exe [PORT-NUMBER]</li>
    </ul>

2. PyCharm's UI:<br>
Right-click on the line of interest: Choose ALKH->Auto Fold
![](https://github.com/erez-aharonov/alkh-dist/blob/main/readme_files/auto-fold.png?raw=true)
3. Result
    <ul>
        <li>Context based folded and unfolded code</li>
        <li>Context based data path summary</li>
    </ul>
![](https://github.com/erez-aharonov/alkh-dist/blob/main/readme_files/auto-fold.gif?raw=true)

