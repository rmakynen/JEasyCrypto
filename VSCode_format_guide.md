# How to Format to Google Java Style using VSCODE:
1. Install [VSCodium](https://github.com/VSCodium/vscodium) or [VSCODE](https://github.com/microsoft/vscode).
2. Open any Java file with VSCodium (or VSCODE)
3. Install these plugins from **Settings** -> **Extensions**:
* Language Support for Java(TM) by Red Hat
* Visual Studio IntelliCode.
4. Go to settings. Search for text: **format**. Scroll down until you find **settings.json** and open it and add the following lines:
```
"java.format.enabled": true,
"java.format.settings.url": "https://raw.githubusercontent.com/google/styleguide/gh-pages/eclipse-java-google-style.xml"
```
5. Now your **settings.json** file should look something like this:
```
{
    "html.format.enable": false,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "java.format.enabled": true,
    "java.format.settings.url": "https://raw.githubusercontent.com/google/styleguide/gh-pages/eclipse-java-google-style.xml"
}
```
6. Go back to the java file and press **shift + alt + F**  to format the code.
