# index.html
search engine 
<!DOCTYPE html>
<HTML lang="en">
    <title>Google Search</title>
    <header>
        <style>
        .search{
            align-content: center;
           text-align: center;
           
           
           }
           .button{
               border: transparent;
               background-color: rgb(198, 168, 247);
               text-align: center;
               border-radius: 11px;
               width: 2inpy -m pip --version;
               }
           
           
           a:link, a:visited {
               background-color: #f44336;
               color: white;
               padding: 14px 25px;
               text-align: center;
               text-decoration: none;
               display: inline-block;
           border-radius: 18px;}
               a:hover, a:active {
                   background-color: red;
                 }
                 .images{    border: none;
                   background: transparent;}
                   .advanced{    border: none;
                       background: transparent;}
                   .original{ border: none;
                       background: transparent;}
           .optiones{
               float: right;
               border: none;
               background-color: rgb(198, 168, 247);
               border-radius: 12px;
           display: inline-block;
           width: auto;
           
           }
           .typein{
               border-radius: 19px;
               width:auto;
               width: 5.5in;
               height: 30px;
           
           }
           .title-search{
               margin-left: 260px;
           }
           .entry{
               font-size: 30px;
           }
           .search-advanced{
               padding: 10px;
               display: inline-block;
           
           }
           .typein-advanced{
               width: 4in;
               border-radius: 10px;
               float: right;
               display: inline-block;
           }
           .button-advanced{
               background-color: rgb(91, 121, 255);
               color: white;
               border: none;
               height: 25px;
           
           }
        </style>
           
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,inicial-scale=1">
        <!-- <link rel="stylesheet" type="text/css" href="stle.css"> -->
        <!-- <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous"> -->
        <div class="optiones">
            <span><button class="images"><a href="images.html">Image Search</a></button></span>
            <span><button class="advanced"><a href="advanced.html">Advanced Search</a></button></span>
    </div>
    </header>

    <body>
       
        <div class="search">
            <div class="title-search"><img src="logo1.png" alt="SEARCH" width="600px" height="400px" ></div>
        <form action="https://www.google.com/search">
           <div> <input maxlength="2048" name="q" type="text" aria-autocomplete="both" aria-haspopup="false" autocapitalize="off" autocomplete="off" autocorrect="off" autofocus="" role="combobox" spellcheck="false" title="search"class="typein" ></div>
           <div><input type="hidden"></div>
           <span> <input type="submit" value="Google Search"class="button"  > </span>
           <span><input type="submit" value="I’m Feeling Lucky" class="button"></span>
        </form>
    </div>
    </body>

   
</HTML>
