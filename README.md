# Doc-CSS.html
<!DOCTYPE html>
<html>
  <head>
   <body>
    <div class="wrap"></div>
   </body>
   <style>
    div.wrap {
     max-width: 800px;
     margin:0 auto;
    }
    body {
     background-color: rgb(0,43,54);
    }
    /* Header/Logo Title */
    .header { color:rgb(181,137,0);
    text-align:center;
    background: #073642;
   }
   </style>
   <meta charset="utf-8">
   <title>My page title</title>
   <style>
    a{
     color:rgb(211,54,130);}
      /* mouse over link */ 
      a:hover
      {color:rgb(203,75,22);
    }
   <link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300|Sonsie+One" rel="stylesheet" type="text/css">
   <link rel="stylesheet" href="style.css">

   <!-- the below three lines are a fix to get HTML5 semantic elements working in old versions of Internet Explorer-->
   <!--[if lt IE 9]>
     <script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.js"></script>
   <![endif]-->
   </style>
  </head>

<body>
  <!-- Here is our main header that is used across all the pages of our website -->
  <div class="header">
     <style>
     h1{
      font-size:50pt
     }
     div {
  padding: 50px;}
    </style>
     <h1>Header</h1>
    </div>

   <nav>
     <ul>
       <style>
      .center {
        text-align: center;
      }
      .flex-container {
       display: flex;
     }
     .flex-container > div{
      margin: 50px;
   padding: 20px;
   font-size: 25px;
 }
 .body{width:65%;float:left;padding-left:5%;}  
 .right{width:15%;float:left;} 
 </style>
 
 <ul>
  <div class="flex-container">
       <div><a href="#">Home</a></div>
       <div><a href="#">Our team</a></div>
       <div><a href="#">Projects</a></div>
       <div><a href="#">Contact</a></div>
     </style>
      </ul>

      <!-- A Search form is another common non-linear way to navigate through a website. -->
      <form>
       <input type="search" name="q" placeholder="Search query">
       <input type="submit" value="Go!">
     </form>
   </nav>
<!-- Here is our page's main content -->
<main>
 <style>
  div {color: rgb(131 148 150);
  }
  
 </style>
 <div>
  <!-- It contains an article -->
  <article>
   <section>
    <style>
     div{ padding-top: 50px;}
     </style>
     <div class="body">

    <h2>Article heading</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Donec a diam lectus. Set sit amet ipsum mauris. Maecenas congue ligula as quam viverra nec consectetur ant hendrerit. Donec et mollis dolor. Praesent et diam eget libero egestas mattis sit amet vitae augue. Nam tincidunt congue enim, ut porta lorem lacinia consectetur.</p>
    <p style="border:3px; border-style:solid; border-color:rgb(42,161,152);padding-top: 50px;">
     Subsection<br>Donec ut librero sed accu vehicula ultricies a non tortor. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean ut gravida lorem. Ut turpis felis, pulvinar a semper sed, adipiscing id dolor.
     <br>Pelientesque auctor nisi id magna consequat sagittis. Curabitur dapibus, enim sit amet elit pharetra tincidunt feugiat nist imperdiet. Ut convallis libero in urna ultrices accumsan. Donec sed odio eros.</p>
   </p>
   <p style="border:3px; border-style:solid; border-color:rgb(42,161,152);padding-top:50px;">
    Another Subsection<br>Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus. Cum soclis natoque penatibus et manis dis parturient montes, nascetur ridiculus mus. In rutrum accumsan ultricies. Mauris vitae nisi at sem facilisis semper ac in est.
   
    <br>Vivamus fermentum semper porta. Nunc diam velit, adipscing ut tristique vitae sagittis vel odio. Maecenas convallis ullamcorper ultricied. Curabitur ornare, ligula semper consectetur sagittis, nisi diam iaculis velit, is fringille sem nunc vet mi.</br></p>
   </div>
  </section>
    </article>
     <!-- the aside content can also be nested within the main content -->
     <style>
      b {
        color: red;
      }
      /* mouse over link */
      b:hover {
        color:rgb(38,139,210);
      }
      </style>
       
       <aside>
        <style>
         b {
           color: red;
         }
         /* mouse over link */
         b:hover {
           color:rgb(38,139,210);
         }
         </style>
         </div>
        </body>
       </html>
       
             <aside>
              <style>
               h4 {
                color:rgb(133,153,0);
               }
               .column {
      float:right;
      column-width:10px;
      padding:15px;
     }
               </style>
                 <div class="right">
           <h4>Related</h4>
           <ul>
            <li><b href="#">Oh I do like to be beside the seaside</b></li>
            <li><b href="#">Oh I do like to be beside the sea</b></li>
            <li><b href="#">Although in the North of England</b></li>
            <li><b href="#">It never stops raining</b></li>
            <li><b href="#">Oh well...</b></li>
          </ul>
          </div>
         </section>
         </aside>
        </div>
  
     <!-- And here is our main footer that is used across all the pages of our website -->
 
     <div class="footer">
      <style>
       .footer {
            position: fixed;
            padding: 10px 10px 0px 10px;
            bottom: 0;
        }
       p1 {
        background-color:rgb(7,54,66);
        color:rgb(131,148,150);
    }
   </style>
   <p1>©Copyright 2050 by nobody. All rights reversed</p1></footer>
</div>
</div>
</html>

