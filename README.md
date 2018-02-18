# Devanagari Layout based on Shusha
Phonetic Devanagari Layout based on Shusha for Linux

## To use:

1.	Append in file /usr/share/X11/xkb/symbols/in
2.	Add entry to /usr/share/X11/xkb/rules/evdev.xml:
```
        <variant>
          <configItem>
            <name>devanagari-shusha</name>

            <shortDescription>hi</shortDescription>
            <description>Devanagari (Shusha)</description>
            <languageList>
              <iso639Id>hin</iso639Id>
            </languageList>
          </configItem>
        </variant>
```
3.	Run: sudo dpkg-reconfigure xkb-data

## Keyboard Layout:
![Keyboard Layout](https://raw.githubusercontent.com/kanchudeep/devanagari-shusha/master/devanagari-shusha-layout.png)
