# testcode



<!DOCTYPE html>

<html>
    <head>
        <title>Javascript Multiplication Table</title>
        <meta charset="windows-1252">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>

        <script>
            
            document.write("<table border='1px'>");
            
            document.write("<tr style='font-size:30px;color:#fff;background-color:#000;'>");
            
            
             document.write("</tr>"); 
            
            for(k = 0; k<10; k++)
            {
                var colorCode = "";
                if(k%2 === 0)
                {
                    colorCode = "#eee";
                }else{
                    colorCode = "#99e265";
                }
                
                document.write("<tr style='background-color:"+ colorCode +"'>");
                
                for(j= 0; j< 10; j++)
                {

                 document.write("<td style='font-size:23px;'>"+j+"  "+ k + " " + + "</td>")   
                }
                
                 document.write("</tr>"); 
            }

            document.write("</table>");
            // program to create a two dimensional array

        </script>

    </body>
</html>
