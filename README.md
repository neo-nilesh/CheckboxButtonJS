# CheckboxButtonJS
Get value of checked checkbox and add class if checked using JavaScript
Check checkbox button/options with js Here are 3 checkboxes options with value as red, blue and green.

And one text box used to show the value of all selected checkboxes.

var checkboxesChecked = [];
to store selected checkboxes values.

var index = checkboxesChecked.indexOf(this.value);
to check value is already exist in array (checkboxesChecked) or not.

if ( this.checked == true ) {
  //to add class on label of the checked checkbox
  this.parentElement.classList.add("active");
  
  //to add value of the checked checkbox array
  checkboxesChecked.push(this.value);
