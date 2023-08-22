<!DOCTYPE html>
<html>
    <head>
        <title>CSS position practice lesson 14</title>
    </head>



    <body style="
    padding-bottom: 1000px;
    padding-top: 60px;
    padding-left: 80px;
    ">


        <div style="
        background-color: black;
        color: white;
        position: fixed;
        top: 0px;
        left: 0px;
        right: 0px;
        height: 50px;
        
        ">
            Header
        </div>

        <div style="background-color: green;
        color: white;
        position: fixed;
        left: 0;
        bottom: 0;
        top: 50px;
        width: 70px;

        
        "> sidebar]
        
        <div class="absolute" style="
        background-color: red;
        position: absolute;
        color: white;
       
        top: 0;
        right: 0;
        ">
        X
        </div>
    
        </div>

        <div class="absolute" style="
        background-color: red;
        position: absolute;
        color: white;
       
        top: 10px;
        right: 10px;
        ">
        absolute
        </div>

        <div style="
            background-color: lightblue;
            height: 200px;
            width: 200px;
            position: static;
           
            
            "> Div 1</div>


        <div  style="
        background-color: lightpink;
        height: 200px;
        width: 200px;
        position: relative;
        "> Div 2
        
            <div class="absolute" style="
            background-color: black;
            position: absolute;
            color: white;
        
            bottom: 10px;
            right: 10px;
            ">
            5:00 min

            </div>
        </div>







        <p>
            position element: Static is the default value.
            "fixed" makes it stick to one spot. 
            Note that fixed float above the page.

            Top element: Used to moved fixed element.
            For example if you input top: 10px.
            It means that the fixed object has a margin of 10px
            from the top window.
            
            "Left" is the same as top.

            However. For example: THe window width is 500.
            And you set your floating item to:
                left: 50px;
                right: 50px;
            Even if your item is only 40px width.
            The left and right command will stretch your item to reach 
            the conditions, which is "left 50px and right 50px" .
            same thing with TOP and BOttom.

            
        </p>

    </body>
</html>
