## What is data tag? ##
The data tag is used to provide a machine readable version of its own contents. It displays the data in a special format. It is useful in the case where your data needs to be in a certain format because it may be processed by a script, but this might not be the format that you'd like your users to see.

Let's take a scenario to understand it well:

Suppose you have to represent some numbers to your users with letter (i.e. one, two, three and so on) but you have script that sorts the numbers in ascending or descending orders. So your script needs numbers in a format like 1, 2, 3... etc.

## Example1 of data tag ##
```html
 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>HTML 5 revision: data tag</title>
    <!-- CDN Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
        integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
</head>

<body>
    
    <ul>  
        <li><data value="101">Java Tutorial</data></li>  
        <li><data value="111">SQL tutorial</data></li>  
        <li><data value="121">HTML tutorial</data></li>  
        </ul>  

    <!-- JQuery needed for Bootstrap's JavaScript plugin -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- CDN Bootstrap min JavaScript-->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"
        integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa"
        crossorigin="anonymous"></script>
</body>

</html>
```


