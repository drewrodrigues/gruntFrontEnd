# gruntFrontEnd
A way to structure your website, to standardize and increase productivity when creating websites.

:white_check_mark: SCSS -> CSS conversion

:white_check_mark: CSS minification

:white_check_mark: JS compilation & minification

:o: Image compression

:o: Linting

---

### Workflow
###### Live Updating Workflow
```bash
git clone <this repo url>
cd <this repo>
npm install
grunt
```
###### Minification Before Pushing To Production
```bash
grunt min
```

---

### File Structure
| Directory     | Purpose |
| ---      | ---       |
| /. | The root directory just holds grunt configuration as well as npm package information |
| app/ | This is where your website will live. Place html here. |
| app/css | Place all of your scss in here. |
| app/css/partials | Place partial scss here. *Example: app/css/partials/_jumbo.scss*. |
| app/js | This will hold your minified javascript file *main.min.js*. |
| app/js/src | Place all js in here. It will be minified into one file. |

---

### End Files For Production

---

### Example Project Structure
