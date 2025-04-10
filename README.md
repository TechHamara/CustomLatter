<div align="center">
<h1><kbd>🧩 CustomLatter</kbd></h1>
An extension for MIT App Inventor 2.<br>
developed by th using Fast.<br>A custom component for creating and animating letters in App Inventor.<br>allows users to display and animate letters with customizable colors,n sizes, and various animation effects.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.customlatter.customlatter<br>
💾 **Size:** 22.88 KB<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-04-10 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.3</mark></small>

<br><br><br>

## Blocks

![GroupAnimationEnd_Event](https://github.com/user-attachments/assets/a297a305-e9e5-4bae-ad15-4d010eb3a3b9)
![AnimationStart_Event](https://github.com/user-attachments/assets/01c902f7-ef92-45d1-877a-d4854ba8106f)
![AnimationEnd_Event](https://github.com/user-attachments/assets/75613898-b2d2-4be5-ae8e-e0cd5db719f1)
![GroupAnimationStart_Event](https://github.com/user-attachments/assets/c0a1e348-186a-4b2f-9ad8-a3d91d7979ee)

-----

![Initialize_Method](https://github.com/user-attachments/assets/6c7c9a61-8653-4c87-ba8b-c184ce105382)
![Animation_Method](https://github.com/user-attachments/assets/2b64f336-bcd0-4789-97dd-9fe1ff16bff5)
![StartGroupAnimation_Method](https://github.com/user-attachments/assets/f49eef6a-42a3-41d2-a9f8-e8e9147f1899)
![SelectLetter_Method](https://github.com/user-attachments/assets/836dc84c-caac-477b-97d0-4c9175f0a8f1)

-----

![BodyColor_Set_Property](https://github.com/user-attachments/assets/c5e84f19-0352-471f-b65c-cf7f6863007a)
![ArmsColor_Set_Property](https://github.com/user-attachments/assets/4c4ebdd8-8a3b-42d8-a6c0-3d7e380d8a22)
![StrokeWidth_Set_Property](https://github.com/user-attachments/assets/5df72455-aae7-454d-8973-61c77342c36d)
![StrokeColor_Set_Property](https://github.com/user-attachments/assets/c5d30c8b-e265-4893-8856-2f16b7a263a8)
![Separator_Set_Property](https://github.com/user-attachments/assets/f2507234-1e89-485a-b58d-157b3bb063cb)
![LetterWidth_Set_Property](https://github.com/user-attachments/assets/d0067e8d-f9d7-41ad-8243-da1df9491721)
![LetterHeight_Set_Property](https://github.com/user-attachments/assets/f7a7080c-eef4-4184-bf3e-1e1c4b468047)
![LegsWidth_Set_Property](https://github.com/user-attachments/assets/e037b5eb-65a5-436d-9a5a-696083c40f94)
![LegsColor_Set_Property](https://github.com/user-attachments/assets/c4330c1d-0270-4e22-91da-9422e6d5177f)

## Demo

![MIT-App-Inventor-04-10-2025_05_16_PM](https://github.com/user-attachments/assets/d4fe1a74-c3a6-45aa-89c7-54904650a235)
![blocks](https://github.com/user-attachments/assets/ebaeec6e-4e84-48b5-8798-e87e1e173971)

<br>

## <kbd>Events:</kbd>
**CustomLatter** has total 4 events.

### 💛 AnimationStart
Event raised when animation starts

| Parameter | Type
| - | - |
| animationType | text

### 💛 AnimationEnd
Event raised when animation ends

| Parameter | Type
| - | - |
| animationType | text

### 💛 GroupAnimationStart
Event raised when group animation starts

### 💛 GroupAnimationEnd
Event raised when group animation ends

## <kbd>Methods:</kbd>
**CustomLatter** has total 4 methods.

### 💜 Initialize
Initialize inside an arrangement.

| Parameter | Type
| - | - |
| arrangement | component

### 💜 SelectLetter
Select letters to animate (use separator to add multiple letters). Use 
 in your letter string to create multiple lines. For example: "H E L L O" (single line), "H E LnL O" (two lines), "H EnL LnO (three lines)

| Parameter | Type
| - | - |
| letters | SelectLatter <small><mark>(helper blocks)</mark></small>

* Enums for **SelectLatter**: `A`, `B`, `C`, `D`, `E`, `F`, `G`, `H`, `I`, `J`, `K`, `L`, `M`, `N`, `O`, `P`, `Q`, `R`, `S`, `T`, `U`, `V`, `W`, `X`, `Y`, `Z`

### 💜 Animation
Apply animation to selected letter: bounce, shake, rotate, fade, scale, wave, flip, pulse, swing, spiral, pop, elastic, rubberband

| Parameter | Type
| - | - |
| animationType | AnimationType <small><mark>(helper blocks)</mark></small>

* Enums for **AnimationType**: `Bounce`, `Shake`, `Rotate`, `Fade`, `Scale`, `Wave`, `Flip`, `Pulse`, `Swing`, `Spiral`, `Pop`, `Elastic`, `Rubberband`

### 💜 StartGroupAnimation
Start group animation

## <kbd>Setters:</kbd>
**CustomLatter** has total 9 setter properties.

### 💚 BodyColor
Sets the body color of the letter

* Input type: `number`

### 💚 ArmsColor
Sets the arms color of the letter

* Input type: `number`

### 💚 LegsColor
Sets the legs color of the letter

* Input type: `number`

### 💚 LegsWidth
Sets the width of legs stroke

* Input type: `number`

### 💚 Separator
Sets the separator character for multiple letters like "H#E#L#L#O" (if # is set as separator) or use the default space separator

* Input type: `text`

### 💚 LetterWidth
Sets the width of each letter

* Input type: `number`

### 💚 LetterHeight
Sets the height of each letter

* Input type: `number`

### 💚 StrokeWidth
Sets the stroke width for letters

* Input type: `number`

### 💚 StrokeColor
Sets the stroke color for letters

* Input type: `number`

## Thanks
  TechHamara
  
