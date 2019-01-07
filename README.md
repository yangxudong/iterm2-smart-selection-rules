# iterm2-smart-selection-rules

|Notes|Regular Expression|Precision|
|---|---|---
|\`match text inside backticks\`|(?<=\`)[^\`]+(?=\`)|Very High
|[match text inside brackets]|(?<=\[)[^]]+(?=\])|Very High
|"match text inside double quotes"|(?<=")[^"]+(?=")|Very High
|the value of key=value|(?<==)[A-Za-z0-9-]+|Very High
|Hex strings (hashes)|[A-Fa-f0-9]+|Very High
