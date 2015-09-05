## Some Jetbrains style keyboard shortcuts for Xcode

##### Delete the current line
Just like ```cmd + backspace```
Add this to the Deletions ```<dict>```

    <key>Delete Current Line</key>
    <string>selectLine:, delete:</string>


##### Duplicate the current line
Just like ```cmd + D```
Add this to Insertions and Indentations ```<dict>```

    <key>Duplicate Current Line</key>
    <string>selectLine:, copy:, moveToEndOfLine:, insertNewline:, paste, deleteBackward:</string>
