# hotbeans.site.github.io.utsas
body 
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
    border-right: 1px solid #9c7070;
}

    li:last-child {
        border-right: none;
    }

    li a {
        display: block;
        color: rgb(158, 74, 74);
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
    }

   
        li a:hover:not(.active) {
            background-color:red;
        }

.active {
    background-color:darkseagreen;
}

{
    font: 12px Arial,sans-serif;
    margin: 0px;
}

html, body {
    height: 100%;
   
}
 
* html #outer { /* ie6 and under only*/
    height: 100%;
}

.header {
    padding: 10px 20px;
    background: #acb3b9;
    height: 100px; 
}

    .header h1 {
        font-size: 24px;
    }

.container {
    width: 100%;
    height: 100%;
    background: rgb(194, 149, 65);
}
.section {
    width: 100%;
    height: 70%;
    opacity: 1;
    
}
.footer {
    background: #105c9e;
    text-align: center;
    padding: 5px;
    height: 10%;
}
table, th, td 
{
    border:3px solid black;
}

.all-browsers {
    margin: 0;
    padding: 5px;
    background-color: lightgray;
  }
  
  .all-browsers > h1, .browser {
    margin: 10px;
    padding: 5px;
  }
  
  .browser {
    background: white;
  }
  
  .browser > h2, p {
    margin: 4px;
    font-size: 90%;
  }
  div.gallery {
    margin: 8px;
    border: 4px solid #ccc;
    float: left;
    width: 180px;
  }
  
  div.gallery:hover {
    border: 5px solid #777;
  }
  
  div.gallery img {
    width: 100%;
    height: auto;
  }
  
  div.desc {
    padding: 30px;
    text-align: center;
  }
