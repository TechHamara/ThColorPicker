<div align="center">
<h1><kbd>🧩 ThColorPicker</kbd></h1>
An extension for MIT App Inventor 2.<br>
A color picker component developed by TechHamara using Fast, allowing users to select colors with options for alpha, hex, and preview.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.thcolorpicker<br>
💾 **Size:** 28.81 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 21<br>
📅 **Updated On:** [date=2025-06-10 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small><br>
⬇️ Download Aix [here](https://buymeacoffee.com/techhamara/e/428909)<br>
🪧 
Thank you **martin-stone** for your awesome [library](https://github.com/martin-stone/hsv-alpha-color-picker-android) 

## Demo 

![ThColorPickerblocks.png](https://github.com/user-attachments/assets/83b9bbbc-e7f6-4d63-8593-5e6bfe31cde9)


![Screenshot_2025-07-05-21-55-26-940_appinventor.ai_Techhamara91.Color_Picker.jpg](https://github.com/user-attachments/assets/9c0c35fb-75f7-474e-b925-9801a1bc00b2)

![Screenshot_2025-07-05-21-55-38-192_appinventor.ai_Techhamara91.Color_Picker.jpg](https://github.com/user-attachments/assets/71290bf3-8f1b-4e11-a63c-3b88461ffff0)

![Screenshot_2025-07-05-21-56-02-538_appinventor.ai_Techhamara91.Color_Picker.jpg](https://github.com/user-attachments/assets/fd0432a7-a6ff-45ad-9e13-11bc36e31ac4)

![Screenshot_2025-07-05-21-55-58-150_appinventor.ai_Techhamara91.Color_Picker.jpg](https://github.com/user-attachments/assets/4f6d96b0-5fb5-42b0-b96b-9ec45c2a146f)



## Blocks 

![NoneSelected_Event](https://github.com/user-attachments/assets/4472d9f0-18cd-4de3-a3e4-88b38a224466)
![DialogDismissed_Event](https://github.com/user-attachments/assets/61a1084d-5453-4535-a534-edd93230d71f)
![ColorSelected_Event](https://github.com/user-attachments/assets/bcc24700-081c-400f-8c94-3c42501e4ebc)

-----

![ColorFromHSV_Method](https://github.com/user-attachments/assets/eba04d7d-bfa2-41f6-b691-2e92261ef2d4)
![ColorFromARGB_Method](https://github.com/user-attachments/assets/efa098af-7210-4947-a05f-df44a67e0e56)
![ShowColorPicker_Method](https://github.com/user-attachments/assets/b1d1755f-e46b-418c-a0f6-1624fcea7f90)
![SelectedColorHSV_Method](https://github.com/user-attachments/assets/b4f29c7e-2c88-4295-a09b-30ab3c2d111e)
![SelectedColorHex_Method](https://github.com/user-attachments/assets/7da5dc12-b3a8-4395-96bc-c03c03faa591)
![SelectedColorARGB_Method](https://github.com/user-attachments/assets/7042ff60-94c3-4980-a0d4-0a8de0c60aeb)
![SelectedColor_Method](https://github.com/user-attachments/assets/54aabb51-2f5e-4b31-abbb-09b291ebba66)
![InitialColor_Method](https://github.com/user-attachments/assets/680cc607-66bf-44cc-a78d-6d7a0989e820)

-----

![DefaultColor_Set_Property](https://github.com/user-attachments/assets/d66e5811-d0d7-49f1-8cbe-2f7892905ade)
![DefaultColor_Get_Property](https://github.com/user-attachments/assets/d39a45d3-0db7-4af4-84e5-f80bf500ecd3)
![ShowPreview_Set_Property](https://github.com/user-attachments/assets/11b2daff-b8ce-47dd-9ff7-94e5b9319e4a)
![ShowPreview_Get_Property](https://github.com/user-attachments/assets/cf6f3e5d-6859-4dce-9b3b-b4a884235b1b)
![SelectNoneButtonText_Set_Property](https://github.com/user-attachments/assets/0e9eb561-231e-4aaf-bdd8-9a9b296c75a0)
![SelectNoneButtonText_Get_Property](https://github.com/user-attachments/assets/6cde0f91-ab47-4f06-aa92-0eb66e45a424)


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

