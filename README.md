<div align="center">
<h1><kbd>🧩 ThColorPicker</kbd></h1>
An extension for MIT App Inventor 2.<br>
A color picker component developed by TechHamara using Fast, allowing users to select colors with options for alpha, hex, and preview.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.thcolorpicker
💾 **Size:** 28.81 KB
⚙️ **Version:** 1.0
📱 **Minimum API Level:** 21
📅 **Updated On:** [date=2025-06-10 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small>

## <kbd>Events:</kbd>
**ThColorPicker** has total 3 events.

### ColorSelected
Event raised when a color is selected

| Parameter | Type
| - | - |
| color | number

### DialogDismissed
Event raised when the color picker dialog is dismissed

### NoneSelected
Event raised when the 'Select None' button is clicked

## <kbd>Methods:</kbd>
**ThColorPicker** has total 8 methods.

### ShowColorPicker
Shows the color picker dialog

### InitialColor
Sets the initial color of the color picker

| Parameter | Type
| - | - |
| color | number

### SelectedColor
Gets the currently selected color

* Return type: `number`

### SelectedColorHex
Gets the hex code of the selected color

* Return type: `text`

### SelectedColorARGB
Gets the ARGB components of the selected color

* Return type: `any`

### SelectedColorHSV
Gets the HSV components of the selected color

* Return type: `any`

### ColorFromHSV
Sets a color from HSV values

| Parameter | Type
| - | - |
| hue | number
| saturation | number
| value | number

### ColorFromARGB
Sets a color from ARGB values

| Parameter | Type
| - | - |
| alpha | number
| red | number
| green | number
| blue | number

## <kbd>Setters:</kbd>
**ThColorPicker** has total 3 setter properties.

### ShowPreview
Sets whether to show the color preview

* Input type: `boolean`

### SelectNoneButtonText
Sets the text for the 'Select None' button

* Input type: `text`

### DefaultColor
Sets the default color to use when 'Select None' is clicked

* Input type: `number`

## <kbd>Getters:</kbd>
**ThColorPicker** has total 3 getter properties.

### ShowPreview
Sets whether to show the color preview

* Return type: `boolean`

### SelectNoneButtonText
Sets the text for the 'Select None' button

* Return type: `text`

### DefaultColor
Sets the default color to use when 'Select None' is clicked

* Return type: `number`

