# what-the-code
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <title>Apply JavaScript example</title>
    <script>
    //JavaScript goes here
    document.addEventListener("DOMContentLoaded", function(){
    function createParagraph(){
    let para = document.createElement('p');
    para.textContent = 'You clicked the button!';
    docment.body.appendChild(para);
    }
    const buttons = document.querySelectorAll('button');
    for(let i=0; i <buttons.length; i++){
    buttons[i].addEventListener('click', createParagraph);
    }
    });
    </script>
  </head>
  <body>
    <button>Click me</button>
  </body>
</html>
