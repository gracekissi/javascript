<!DOCTYPE html>
<html>
    <body>
        <h2> My First Javascript</h2>
        <button type="button" onclick="document.getElementById('demo').innerHTML= Date()"> Click me to display date and time</button>
        <p id="demo"></p>
        <button type="button" onclick="document.getElementById('demo').style.fontSize='35px'">Click me to resize font size</button>
        <button type="button" onclick="document.getElementById('demo').style.display='none'">Click me to hide the date</button>
        <button type="button" onclick="document.getElementById('demo').style.display='block'">Click me to display blocks</button>
        <h2> This is a new text to see what Javascript can do</h2>
        <p id="anew"> Javascript can change HTML content</p>
        <button type="button" onclick='document.getElementById("anew").innerHTML= "Hey Javascript Test"'> Click me </button>

        <h2>What Can JavaScript Do?</h2>

            <p>JavaScript can change HTML attribute values.</p>

            <p>In this case JavaScript changes the value of the src (source) attribute of an image.</p>
            <p id="trymath"></p>
            <script> document.getElementById('trymath').innerHTML= 5+6</script>
            <p id="trymath2"></p>
            <script> document.write (8+10)</script>
            <button type="button" onclick="document.write(4+17)">Click this</button>
            <script> window.alert(5+8) </script>
            
            <button onclick="this.innerHTML=Date()">This date is: </button>
            
            // for use in wordpress tomorrow.
            
           /* .wp-container-2 > * {
                margin-block-start: -25px;
                margin-block-end: -45px;
            }
            */

            <p id="carone"> Car one is: </p>
            <p id="cartwo"> Car two is: </p>
            <p id="checkl"></p>
            <script>
                let carname1 = "Volvo XC60"
                let carname2 = 'Volvo XC60'
                let lenght = carname1.length;

                document.getElementById('carone').innerHTML=carname1;
                document.getElementById('cartwo').innerHTML=carname2;
                document.getElementById('checkl').innerHTML=lenght;


            </script>
    </body>

</html>
