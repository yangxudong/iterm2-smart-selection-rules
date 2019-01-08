# iterm2-smart-selection-rules

|Notes|Regular Expression|Precision|
|---|---|---
|\`match text inside backticks\`|(?<=\`)[^\`]+(?=\`)|Very High
|[match text inside brackets]|(?<=\[)[^]]+(?=\])|Very High
|"match text inside double quotes"|(?<=")[^"]+(?=")|Very High
|the value of key=value|(?<==)[A-Za-z0-9-]+|Very High
|Hex strings (hashes)|[A-Fa-f0-9]+|Very High


好看的命令提示符：
export PS1='\n\e[1;37m[\e[m\e[1;32m\u\e[m\e[1;33m@\e[m\e[1;35m\H\e[m \e[4m`pwd`\e[m\e[1;37m]\e[m\e[1;36m\e[m\n\$'
