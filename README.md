# html-colornames-select-generator
This script parses input copy-pasted from w3schools html color names page and generates a list of PHP "echo" commands to display a select element

I exported this from CodePen and imported it to GitHub without testing. I _think_ it _should_ work.

## Usage
- Copy the input from https://www.w3schools.com/colors/colors_names.asp (starting at "AliceBlue" and ending "YellowGreen #9ACD32") and paste it into the `input` variable in `script.js`
- Open `index.html`

## Output

The generated output should look similar to this:
```
echo "<select>";
echo "<option value=\"AliceBlue\">AliceBlue</option>";
echo "<option value=\"AntiqueWhite\">AntiqueWhite</option>";
[...]
echo "<option value=\"Yellow\">Yellow</option>";
echo "<option value=\"YellowGreen\">YellowGreen</option>";
echo "</select>";
```
