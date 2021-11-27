<!DOCTYPE html>
<html lang="en"> 
    <head> 
        <meta charset="UTF-8" />
         <meta http-equiv="X-UA-Compatible" content="IE=edge" /> 
         <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    </head>
    <body>
        <script>
            let n = prompt("Enter A Number For Generate A Pattern And Open Console");
            let stars = "";
            for(let i=1; i<=n; i++){
                for(let j = 1; j < n - i + 1; j++){
                    stars += "&nbsp;"
                }
             for(let k = 1; k<= 2 * i - 1; k++){
                 stars += "*";
             }
           //  stars +="\n";
           stars += "<br/>";
            }
             for(let i = 1; i <= n - 1; i++){
                 for(let j = 1; j < i+1; j++){
                     stars += "&nbsp;"
             }
             for(let k = 1; k<= 2*(n-i)- 1; k++){
                 stars += "*";
             }
            // stars +="\n";
            stars += "<br/>";
            }
            document.write(stars);
             console.log(stars);
            
        </script>
    </body>
</html>
