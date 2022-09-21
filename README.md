- 👋 Hi, I’m @truongvu102
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script type="text/javascript" src="scripts.js"></script>
    <link rel="stylesheet" href="styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
    <title>VU QUANG TRUONG</title>
</head>
<body >
    <div class="bg-image" 
    style="background-image: url('bando.png');
           height: 100vh">
        <h1 class="text-white bg-primary text-center"> VŨ QUANG TRƯỜNG-B19DCDT250</h1>
        <div class="row " style="line-height: 40px" >
            <span class="align-text-top  ">.</span>
            
            <div class="col p-3 bg-primary text-white  " >  
                <h1 >ÁNH SÁNG</h1>
                <input  onchange="check()" type="text" style="height:30px" placeholder="nhập ánh sáng" id="n1"  >
                <script>
                    function check(){
                       var x =document.getElementById('n1').value;
                       if(x>45){
                          document.getElementById('n1').style.backgroundColor="red";
                          window.alert('CẢNH BÁO:ánh sáng quá cao');
                    
                       }else if(x<15){
                          document.getElementById('n1').style.backgroundColor="yellow";
                          window.alert('CẢNH BÁO:ánh sáng quá thấp');
                       }
                       
                       else{
                          document.getElementById('n1').style.backgroundColor="green";
                       }
                    }
                    </script>
          
             </div>
       
 

            <div class="col p-3 bg-dark text-white">
                <h1>NHIỆT ĐỘ</h1>
                <input onchange="check1()" type="text" style="height:30px" placeholder="nhập nhiệt độ " id="n2" >
                <script>
                    function check1(){
                       var x =document.getElementById('n2').value;
                       if(x>45){
                          document.getElementById('n2').style.backgroundColor="red";
                          window.alert('CẢNH BÁO:nhiệt độ quá cao');
                    
                       }else if(x<15){
                          document.getElementById('n2').style.backgroundColor="yellow";
                          window.alert('CẢNH BÁO:nhiệt độ quá thấp');
                       }
                       
                       else{
                          document.getElementById('n2').style.backgroundColor="green";
                       }
                    }
                    </script>
            </div>



            <div class="col p-3 bg-primary text-white">
                <h1>ĐỘ ẨM</h1>
                <input onchange="check2()" type="text" style="height:30px" placeholder="nhập độ ẩm " id="n3">
                <script>
                    function check2(){
                       var x =document.getElementById('n3').value;
                       if(x>45){
                          document.getElementById('n3').style.backgroundColor="red";
                          window.alert('CẢNH BÁO:độ ẩm quá cao');
                    
                       }else if(x<15){
                          document.getElementById('n3').style.backgroundColor="yellow";
                          window.alert('CẢNH BÁO:độ ẩm quá thấp');
                       }
                       
                       else{
                          document.getElementById('n3').style.backgroundColor="green";
                       }
                    }
                    </script>
            </div>
        
        </div>
          <div class="row" style="line-height: 80px">
            <span class="align-text-top">.</span>
            
            <div class="col-3 p-3  text-white text-center ">
                <h1><span class="badge rounded-pill bg-primary">
                    BUTTON 1
                    <button type="button" class="btn btn-success">ON</button>
                    <button type="button" class="btn btn-danger">OFF</button>
                </span></h1>
            </div>
            <div class="col-3 p-3  text-white text-center">
                <h1><span class="badge rounded-pill bg-primary">
                    BUTTON 2
                    <button type="button" class="btn btn-success">ON</button>
                    <button type="button" class="btn btn-danger">OFF</button>
                </span></h1>
            </div>
            <div class="col-6 p-3 bg-image "style="background-image: url('nhietdo.png');

            height: 600px">
                
            </div>
          </div>

    
    </div>
   
</body>
</html>
<!---
truongvu102/truongvu102 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
