# Rofi Black-White Theme

![theme-preview](https://github.com/user-attachments/assets/edd4452e-6ceb-4f84-9c7b-987ca5cb9368)

## .config/rofi/config.rasi
```
/**
 *
 * Author : Aditya Shakya (adi1090x)
 * Refactor : AzizEmir (AzizEmir)
 * Github : @adi1090x
 * Github : @azizemir
 * 
 * Rofi Theme File
 * Rofi Version: 1.7.3
 **/

/*****----- Configuration -----*****/
configuration {
    show-icons:                 true;
}

/*****----- Global Properties -----*****/
* {
    font:                        "JetBrains Mono Nerd Font 10";
    background:                  #000000;
    foreground:                  #FFFFFF;
    selected:                    #505050;
    active:                      #909090;
    urgent:                      #707070;
}

/*****----- Main Window -----*****/
window {
    /* properties for window widget */
    transparency:                "real";
    location:                    center;
    anchor:                      center;
    fullscreen:                  false;
    width:                       650px;
    x-offset:                    0px;
    y-offset:                    0px;

    /* properties for all widgets */
    enabled:                     true;
    border-radius:               15px;
    cursor:                      "default";
    background-color:            @background;
}

/*****----- Main Box -----*****/
mainbox {
    enabled:                     true;
    spacing:                     0px;
    background-color:            transparent;
    orientation:                 horizontal;
    children:                    [ "imagebox", "listbox" ];
}

imagebox {
    padding:                     10px;
    background-color:            transparent;
    background-image:            url("./img/wallhaven-4d8xkg_1600x1200-LAST.png",height);
    orientation:                 vertical;
    children:                    [ "inputbar", "dummy" ];
}

listbox {
    spacing:                     20px;
    padding:                     20px;
    background-color:            #000000;
    orientation:                 vertical;
    children:                    [ "listview" ];
}

dummy {
    background-color:            transparent;
}

/*****----- Inputbar -----*****/
inputbar {
    enabled:                     true;
    spacing:                     10px;
    padding:                     15px;
    border-radius:               10px;
    background-color:            @background-alt;
    text-color:                  @foreground;
    children:                    [ "textbox-prompt-colon", "entry" ];
}
textbox-prompt-colon {
    enabled:                     true;
    expand:                      false;
    str:                         "";
    background-color:            inherit;
    text-color:                  inherit;
}
entry {
    enabled:                     true;
    background-color:            inherit;
    text-color:                  inherit;
    cursor:                      text;
    placeholder:                 "";
    placeholder-color:           inherit;
}

/*****----- Listview -----*****/
listview {
    enabled:                     true;
    columns:                     1;
    lines:                       5;
    cycle:                       false;
    dynamic:                     true;
    scrollbar:                   false;
    reverse:                     false;
    border:                      0px solid;
    spacing:                     10px;
    text-color:                  @foreground;
}

/*****----- Elements -----*****/
element {
    enabled:                     true;
    spacing:                     15px;
    padding:                     8px;
    border-radius:               10px;
    background-color:            transparent;
    text-color:                  @foreground;
    cursor:                      pointer;
}
element normal.normal {
    background-color:            inherit;
    text-color:                  inherit;
}
element normal.urgent {
    background-color:            @urgent;
    text-color:                  @foreground;
}
element normal.active {
    background-color:            @active;
    text-color:                  @foreground;
}
element selected.normal {
    background-color:            @selected;
    text-color:                  @foreground;
}
element selected.urgent {
    background-color:            @urgent;
    text-color:                  @foreground;
}
element selected.active {
    background-color:            @urgent;
    text-color:                  @foreground;
}
element-icon {
    background-color:            transparent;
    text-color:                  inherit;
    size:                        32px;
    cursor:                      inherit;
}
element-text {
    background-color:            transparent;
    text-color:                  inherit;
    cursor:                      inherit;
    vertical-align:              0.5;
    horizontal-align:            0.0;
}
element.alternate.normal {
    background-color: #000000;
    text-color:       #FFFFFF;
}

/*****----- Message -----*****/
message {
    background-color:            transparent;
}
textbox {
    padding:                     15px;
    border-radius:               10px;
    background-color:            @background-alt;
    text-color:                  @foreground;
    vertical-align:              0.5;
    horizontal-align:            0.0;
}
error-message {
    padding:                     15px;
    border-radius:               20px;
    background-color:            @background;
    text-color:                  @foreground;
}
```


## .config/rofi/img/wallhaven-4d8xkg_1600x1200-LAST.png

![wolf](https://github.com/user-attachments/assets/2657f31d-3035-45b7-80ee-6f97a77e279e)

## Desktop Wallpaper

![wallpaper](https://github.com/user-attachments/assets/ba74141e-2d5c-497b-b5a5-25cbd5c44871)




