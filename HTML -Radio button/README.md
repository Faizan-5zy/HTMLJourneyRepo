# README: HTML Radio Button

This simple HTML file demonstrates the usage of radio buttons to capture gender information in a form. Here's a breakdown of the code:

## HTML Structure

1. **Document Type Declaration (DOCTYPE):**
   - Specifies the document type and version.

```html
<!DOCTYPE html>
```

2. **HTML Document Start:**
   - Opening tag for the HTML document.

```html
<html lang="en">
```

3. **Head Section:**
   - Contains metadata about the HTML document.

```html
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Radio Button</title>
</head>
```

4. **Body Section:**
   - Contains the content of the HTML document.

```html
<body>
```

5. **Form Section:**
   - A form to capture gender information.

```html
    <!--radio button-->
    <form>
        <span>Gender : </span>
        <input type="radio" name="gender" value="male" checked> Male
        <input type="radio" name="gender" value="female"> Female
    </form>
```

6. **Closing Tags:**
   - Closing tags for body and html.

```html
</body>
</html>
```

## Description

This HTML file demonstrates a simple form with two radio buttons to capture gender information. The `name` attribute groups the radio buttons, ensuring that only one option can be selected. The `checked` attribute is applied to the "Male" option, making it the default selection. The form displays two radio buttons for "Male" and "Female". Users can choose either "Male" or "Female." By default, "Male" is selected due to the `checked` attribute.
