## Some Jetbrains style keyboard shortcuts for Xcode

##### Delete the current line
Just like ```cmd + backspace```
Add this to the Deletions ```<dict>```

    <key>Delete Current Line</key>
    <string>selectLine:, delete:</string>


##### Duplicate the current line
Just like ```cmd + d```
Add this to Insertions and Indentations ```<dict>```

    <key>Duplicate Current Line</key>
    <string>selectLine:, copy:, moveToEndOfLine:, insertNewline:, paste, deleteBackward:</string>

##### Copy / Cut current line
Just like ```cmd + x``` and ```cmd + c``` when on a line
Add this to a custom ```<key>``` and ```<dict>```

    <key>Copy Lines</key>
    <dict>
    <key>Cut Current Line</key>
    <string>selectLine:, cut:</string>
    <key>Copy Current Line</key>
    <string>selectLine:, copy:</string>
    </dict>
