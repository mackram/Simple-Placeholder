
To use it you have to target each types of inputs/textarea you will use:

    $('textarea[placeholder]').simplePlaceholder();

    $('input:text[placeholder]').simplePlaceholder(); // classic input[type=text]
    $('input:email[placeholder]').simplePlaceholder(); // email fields input[type=email]
    [...] // target other input types you need