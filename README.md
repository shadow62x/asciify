```text
  :::.          .::::::.      .,~:::::     :::   :::   .-:::::'   .-:.     ::-.
  ;;`;;        ;;;`    `    ,;;;'````'     ;;;   ;;;   ;;;''''     ';;.   ;;;;'
 ,[[ '[[,      '[==/[[[[,   [[[            [[[   [[[   [[[,,==       '[[,[[['  
c$$$cc$$$c       '''    $   $$$            $$$   $$$   `$$$"``         c$$"    
 888   888      88b    dP   `88bo,__,o,    888   888    888          ,8P"`     
 YMM   \"\"`     "YMmMY"      "YUMMMMMP"   MMM   MMM    "MM,        mM"        
                                                                               
                                                                               
```                                                                               
# Turn any text into ASCII in luau with 600+ fonts! 

```text

:::   :::.    :::.    .::::::.    ::::::::::::     :::.          :::         :::     
;;;   `;;;;,  `;;;   ;;;`    `    ;;;;;;;;''''     ;;`;;         ;;;         ;;;     
[[[     [[[[[. '[[   '[==/[[[[,        [[         ,[[ '[[,       [[[         [[[     
$$$     $$$ "Y$c$$     '''    $        $$        c$$$cc$$$c      $$'         $$'     
888     888    Y88    88b    dP        88,        888   888     o88oo,.__   o88oo,.__
MMM     MMM     YM     "YMmMY"         MMM        YMM   \"\"`   """"YUMMM   """"YUMMM


```
```lua
local ascii = loadstring(game:HttpGet("https://raw.githubusercontent.com/shadow62x/asciify/main/asciify.lua"))()
```

```text
 ...    :::    .::::::.      :::.           .,-:::::/     .,::::::  
 ;;     ;;;   ;;;`    `      ;;`;;        ,;;-'````'      ;;;;''''  
[['     [[[   '[==/[[[[,    ,[[ '[[,      [[[   [[[[[[/    [[cccc   
$$      $$$     '''    $   c$$$cc$$$c     "$$c.    "$$     $$""""   
88    .d888    88b    dP    888   888      `Y8bo,,,o88o    888oo,__ 
 "YmmMMMM""     "YMmMY"     YMM   \"\"`      `'YMUP"YMM    """"YUMMM
```

                                                                    
```lua
print(ascii("hi")) -- default font is "standard"
print(ascii("hey", "doom.flf")) -- .flf is optional 
print(ascii("HELLO", "C64-fonts/1943____"))
```


```text
  :::.         ::::::::::.    :::
  ;;`;;         `;;;```.;;;   ;;;
 ,[[ '[[,        `]]nnn]]'    [[[
c$$$cc$$$c        $$$""       $$$
 888   888        888o        888
 YMM   \"\"`      YMMMb       MMM
```                                 
                                 
```lua
ascii("text", "font") -- returns text as ASCII
ascii.setfont("doom") -- sets the default font
ascii.fonts() -- lists all fonts
ascii.clearcache() -- clears the currently cached fonts
```

```text
.-:::::'       ...        :::.    :::.   ::::::::::::    .::::::. 
;;;''''     .;;;;;;;.     `;;;;,  `;;;   ;;;;;;;;''''   ;;;`    ` 
[[[,,==    ,[[     \[[,     [[[[[. '[[        [[        '[==/[[[[,
`$$$"``    $$$,     $$$     $$$ "Y$c$$        $$          '''    $
 888       "888,_ _,88P     888    Y88        88,        88b    dP
 "MM,        "YMMMMMP"      MMM     YM        MMM         "YMmMY" 
                                                                  
```

## You can find all available fonts [here](https://github.com/shadow62x/asciify/tree/main/Fonts)

