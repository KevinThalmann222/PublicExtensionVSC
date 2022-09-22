# PublicExtensionVSC

 How to public extension in vsc

1. install node js
   - (https://nodejs.org/en/)

2. open VSC
   - npm i -g generator-code
   - yo code
        New Extension Pack
        - json will be created
        - add "publisher" : "your name"
   - npm i -g vsce
   - vsce package
        - .vsix will be created
   - to install all the extension in your file
   - code --install-extension yourname.vsix

3. create an account on https://dev.azure.com
   - https://dev.azure.com/kevinthalmann222/VSCode
   - personal access token
   - New Token

   - Name -> your name
   - Organization -> All accessible organization
   - Marketplace -> Manage
   - copy token

4. publisher
   - vsce login publisher name e.g.
   - vsce login kevinthalmann222
   - vsce publish
