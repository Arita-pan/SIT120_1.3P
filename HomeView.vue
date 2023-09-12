<script setup>

</script>

<template>
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <main>
    <h1 id="title">Chansada Kitayaso</h1>
    <img id="profile" src="https://i.pinimg.com/564x/ba/ab/e2/baabe2988b391efe1ada78bac4699f04.jpg" alt="profile">

  <div class="row">
    <!-- left block -->
    <div class="column"> 
      <div id="language">
        <h2 id="skill">Language Skills</h2>
        <h3 class="subject">English</h3>
        <div class="w3-light-grey w3-round" id="bar">
          <div class="w3-container w3-blue w3-round" style="width:100%">100%</div>
        </div>
        
        <h3 class="subject">Chinese</h3>
        <div class="w3-light-grey w3-round" id="bar">
          <div class="w3-container w3-blue w3-round" style="width:75%">75%</div>
        </div>

        <h3 class="subject">Thai</h3>
        <div class="w3-light-grey w3-round" id="bar">
          <div class="w3-container w3-blue w3-round" style="width:75%">75%</div>
        </div>

        <h3 class="subject">Lao</h3>
        <div class="w3-light-grey w3-round" id="bar">
          <div class="w3-container w3-blue w3-round" style="width:100%">100%</div>
        </div>
      </div>
    </div> 

    <!-- right block -->
    <div>
      <h2 id="software">Software Skills</h2>

      <table>
        <tr>
          <th>Photoshop</th>
          <td><img class ="imagesize" src="https://is1-ssl.mzstatic.com/image/thumb/Purple116/v4/ca/37/9f/ca379fb1-ee70-3679-4fba-b9fa0dd6fd8f/AppIcon-0-1x_U007emarketing-0-7-0-0-85-220.png/230x0w.webp"></td>
          <th>Illustrator</th>
          <td><img class ="imagesize" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Adobe_Illustrator_CC_icon.svg/1200px-Adobe_Illustrator_CC_icon.svg.png"></td>
          <th>Indesign</th>
          <td><img class ="imagesize" src="https://cdn-icons-png.flaticon.com/512/5440/5440043.png"></td>
        </tr>
      </table>
    </div>
  </div>
  </main>
</template>

<style scoped>
#title{
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  text-align: center;
  font-size: 50px;
  padding: 20px;
}
#profile{
  display: block;
  margin-left: auto;
  margin-right: auto;
}
#skill{
  margin-left: 50px;
}
.subject{
  margin-left: 70px;
}
#bar{
  width: 80%;
  margin-left: 70px;
}

.column {
  float: left;
  width: 50%;
  padding: 10px;
  /* height: 300px; Should be removed. Only for demonstration */
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

table, td, th{
  border: 1px solid #ddd;
  text-align: center;
  border-collapse: collapse;
  padding: 10px;
  margin-left: auto;
  margin-right: auto;
}



#software{
  text-align: center;
  
}

.imagesize{
  width: 100px;
}
  
</style>
