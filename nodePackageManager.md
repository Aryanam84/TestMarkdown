# Node Package Manager npm

Update node Package manager  
```npm install npm -g```  

Nach Modulen Suchen  
```npm search [searchkey] ```

Auflisten der installierten Module  
```npm list ```

Packet installieren bsp. express  
```npm install npm express --save```  


### Versionierung
```[major].[minor].[patch]```  
- Eine "major" Versionserhöhung enthält breaking changes.  
- Eine "minor" Versionserhöhung enthält neue Features.  
- Eine "patch" Versionserhöhung enthält Fehlerbehebungen.

## Package.json

Hier können die Verwendeten Packete eingetragen werden oder werden automatisch beim installieren eingetragen.

Bsp:
``` json
"dependencies": {
  "express": "^4.15.2"
}
```


  - version: Muss exakt version entsprechen
  -  = version: Entspricht version
  -  &gt;  version: Größer als die definierte Version
  -  &gt; = version: Größer bzw. gleich der definierten Version
  -  &lt;  version: Kleiner als die definierte Version
  -  &lt; = version: Kleiner bzw. gleich der definierten Version  


- ^ = Version with same Majorversion 
- ~ = Version with same Major and Minorversion


 

