````js
const display = document.getElementById('display');

function appendToDisplay(input) {
    display.value += input;

}

function clearDisplay() {
    display.value = '' ;

}

function calculate() {
   // display.value = eval(display.value);
   
    try {
        display.value = eval(display.value);
    } 
    catch (error) {
        display.value = 'Error';
        
    }

}
````



<img width="640" alt="image" src="https://github.com/w77sh/JS-calculator/assets/74508174/7855c07a-5411-48ff-8428-1c5cb8fd5224">
