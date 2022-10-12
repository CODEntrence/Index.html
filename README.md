# Index.html
In this project we are making weight converter
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Weight Convertor</title>
  <link rel="stylesheet" href="Style.css">
  
</head>
<body>
  
  <div class="box">
    <div class="input-filed">
      <h1 class="first-unit">Kg</h1>
      <input type="number" id="value" class="value">
      <button type="button" class="convert-btn">Convert</button>
    </div>
    <div class="output-filed">
      <h1 class="second-unit">g</h1>
      <h1 class="output">Your Output</h1>
    </div>
  </div>
  <script>

const btn = document.querySelector('.convert-btn')
const val = document.querySelector('.value')
const first_unit = document.querySelector('.first-unit')
const second_unit = document.querySelector('.second-unit')
const output = document.querySelector('.output')

btn.addEventListener('click', e=>{
  
  const value = val.value
  
  
  output.innerText = `${value}kg = ${value*1000}g`
})
Footer

</script>
</body>
</html>
