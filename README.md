# Xcode Key Bindings

## Why?

Because I came from a Jetbrains IDE world and I want the same keyboard shortcuts in Xcode (I know AppCode exists)

## How?

Add these bindings to the correct ```<dict>``` here:

    /Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Resources/IDETextKeyBindingSet.plist

Then restart/open Xcode and go to:

Xcode -> Preferences and click the Key Bindings tab.

Use the search to find your new bindings and add keyboard shortcut

You may need to remove current shortcuts if you get any conflicts when adding these keyboard shortcuts
