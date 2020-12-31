This application uses CSS variables 

-- is the way to use the variables that will be modified

Select inputs, using QuerySelectorAll targeting the inputs

QuerySelectorAll returns a Node list of the 
inputs(in our case spacing, base, blur) & if you explore the __proto__ it displays the type of methods that can be used for this data type 
    ex. forEach method

In the handleUpdate function we use document.documentElement.style to update the variable's  current value (with .setProperty method), and the suffix of that attribute
            ex. blur value + px