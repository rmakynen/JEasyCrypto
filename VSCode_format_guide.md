# How to Format to Google Java Style using VSCODE:
1. Install VSCode
2. Open any Java file with VSCODE
3. Install the suggested Java plugins for VSCODE. It's called "Java Extension pack". (contains: Language Support for Java™ by Red Hat; Debugger for Java; Java Test Runner;Maven for Java; Java Dependency Viewer; Visual Studio IntelliCode)
4. Go to settings. Search for "format". Scroll down until you find "settings.json" and open it and add the following lines:

"java.format.enabled": true,
"java.format.settings.url": "https://raw.githubusercontent.com/google/styleguide/gh-pages/eclipse-java-google-style.xml"

5. Now your 'settings.json' file should look something like this:

{
    "html.format.enable": false,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "java.format.enabled": true,
    "java.format.settings.url": "https://raw.githubusercontent.com/google/styleguide/gh-pages/eclipse-java-google-style.xml"
}

6. Go back to the java file and press shift + alt + F  to format the code.  (You may need to install a formatter at this stage)