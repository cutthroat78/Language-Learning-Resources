# Oneida Anki Deck
My anki deck for the Oneida Language
# To Do
- Add Oneida (Wisconsin) Words from [this](https://www.uwgb.edu/dictionary/)
- Look at language resources to see if any other good resources to add to this anki deck
- Reorder words (Change order using position in csv file)
# Note Type Code
## Card 1: Oneida -> English
### Front
```
{{Oneida}}{{Oneida Audio}}
<div style='font-size: 15px;'>{{Dialect}}</div>
```
### Back
```
{{FrontSide}}
<hr id=answer>
{{English}}
<br>
<i>{{Oneida Example}}{{Oneida Example Audio}}</i>
<div style='font-size: 15px;'>{{Example in English}}</div>
{{Image}}
```
## Card 2: English -> Oneida
### Front
```
{{English}}
```
### Back
```
{{FrontSide}}
<hr id=answer>
{{Oneida}}{{Oneida Audio}}
<div style='font-size: 15px;'>{{Dialect}}</div>
<i>{{Oneida Example}}{{Oneida Example Audio}}</i>
<div style='font-size: 15px;'>{{Example in English}}</div>
{{Image}}
```
## Card 3: Oneida Example -> Example in English
### Front
```
{{Oneida Example}}{{Oneida Example Audio}}
```
### Back
```
{{FrontSide}}
<div style='font-size: 15px;'>{{Dialect}}</div>
<hr id=answer>
{{Example in English}}
```
## Card 4: Example in English -> Oneida Example
### Front
```
{{Example in English}}
```
### Back
```
{{FrontSide}}
<hr id=answer>
{{Oneida Example}}{{Oneida Example Audio}}
<div style='font-size: 15px;'>{{Dialect}}</div>
```
## Styling
```
.card {
  font-family: arial;
  font-size: 20px;
  text-align: center;
  color: black;
  background-color: white;
}
```
