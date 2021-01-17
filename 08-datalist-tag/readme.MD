## What is datalist tag? ##
Autocompletion is a pattern that all web users are familiar with. When you do a search, your search engine suggests terms. When you type a new email message, your mail client suggest recipients. This functionality, however, has not been available to web developers without a nontrivial amount of JavaScript. One of the new HTML5 elements, the , brings this autocomplete functionality to the Web natively. 

## Creating datalist ##
To show how a datalist works, let’s start with a traditional text input:
```html
<label for=”favorite_team”>Favorite Team:</label>
<input type=”text” name=”team” id=”favorite_team”>
```

This field asks a user to provide his or her favorite sports team. By default, the user will be given no additional help to complete the field. But by using a datalist, you can provide a list of options the user can select from to complete the field. To do this, define a datalist with an option element for each suggestion:
```html
<datalist>
  <option>Detroit Lions</option>
  <option>Detroit Pistons</option>
  <option>Detroit Red Wings</option>
  <option>Detroit Tigers</option>
</datalist>
```
To tie a datalist to an input element, give the input element a list attribute and the datalist an id attribute that match. Here’s an example:

```html
<label for=”favorite_team”>Favorite Team:</label>
<input type=”text” name=”team” id=”favorite_team” list=”team_list”>
<datalist id=”team_list”>
  <option>Detroit Lions</option>
  <option>Detroit Pistons</option>
  <option>Detroit Red Wings</option>
  <option>Detroit Tigers</option>
</datalist>
```

## Example1 of datalist tag ##
```html
 <body>

    <label for=”favorite_team”>Favorite Team:</label>
    <input type=”text” name=”team” id=”favorite_team”>
    
    <datalist id=”team_list”>
        <option>Detroit Lions</option>
        <option>Detroit Pistons</option>
        <option>Detroit Red Wings</option>
        <option>Detroit Tigers</option>
      </datalist>

    <!-- JQuery needed for Bootstrap's JavaScript plugin -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- CDN Bootstrap min JavaScript-->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"
        integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa"
        crossorigin="anonymous"></script>
</body>
```


