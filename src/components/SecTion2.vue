<template>
    <section class="container-fluid section2">
      
         <div class="container section-info">
            <div class="about-us">
                <div class="about1">
                    <h2>About us</h2>
                    <div class="redclass"></div>
                    <p class="text-about">
                        Explore the valuable, historical, and heritage places of Turkic countries through our curated selection of articles, photos, and videos. Discover the beauty of ancient ruins, stunning mosques, medieval fortresses, and intricate tilework.
                    </p>
                    <p class="supports">Our supporters</p>
                    <div class="two-images">
                        <div class="new-responseimg">
                            <img src="../assets/images/flag.png" alt="">
                            <p>Ministry of Tourism and Cultural Heritage of the Republic of Uzbekistan</p>
                        </div>
                        <div class="new-responseimg">
                            <img src="../assets/images/huma.png" alt="">
                            <p>Organization of Turkic states</p>
                        </div>
                    </div>
                    <div class="two-buttons">
                       <a class="global other-button1" href="#">
                        <p>Explore</p>
                        <img src="../assets/images/global.png" alt="">
                       </a>
                       <a class="global other-button2" href="#">
                        <p>More about us</p>
                        <img src="../assets/images/rightarrow.png" alt="">
                       </a>
                        
                    </div>

                </div>
                <div class="about2">
                    <div class="second-slider">
                        <img class="slider-images" src="../assets/images/img1.png" alt="">
                        <img class="slider-images" src="../assets/images/img2.png" alt="">
                        <img class="slider-images" src="../assets/images/img3.png" alt="">
                        <img class="slider-images" src="../assets/images/img4.png" alt="">
                        <img class="slider-images" src="../assets/images/Image.png" alt="">
                    </div>
                </div>
            </div>  
         </div>

         <!-- four branches -->
         <div class="container">
             <div class="branches">
                <div class="branch">
                    <div class="branchname">
                        <h6>142</h6>
                        <p>Attractions</p>
                    </div>
                    <img src="../assets/images/mosque.png" alt="">
                  </div>
                  <div class="branch">
                     <div class="branchname">
                        <h6>548</h6>
                        <p>Destinations</p>
                     </div>
                     <img src="../assets/images/mosque.png" alt="">
                  </div>
                  <div class="branch">
                    <div class="branchname">
                       <h6>7</h6>
                       <p>Countries</p>
                    </div>
                    <img src="../assets/images/mosque.png" alt="">
                 </div>
                 <div class="branch">
                    <div class="branchname">
                       <h6>3</h6>
                       <p>Religions</p>
                    </div>
                    <img src="../assets/images/mosque.png" alt="">
                 </div>
            </div>
    </div>
          
        
    </section>
</template>
<script>
export default {
  name: 'SecTion2'
}

</script>

<style>
.section2{
    background-color: rgb(8, 8, 8);
  height: auto;
    position: relative;
    top: -110px;
    /* z-index: -1; */
}
.section-info{
  height: auto;
}
.section2{
background-image: url(../assets/images/vctor2.png);
background-repeat: no-repeat;
height: auto;
}
.about-us{
    display:flex;
    justify-content: space-between;
position: relative;  
padding-top: 120px;
padding-bottom: 100px;
flex-wrap: wrap;
}
.about1{
    width: 40%;
}
.about2{
    display: flex;
    justify-content: space-between;
    align-items: end;
    
}
.about1 h2{
    color: var(--White, #FFF);
font-feature-settings: 'liga' off, 'calt' off;
text-shadow: 0px 10px 50px rgba(12, 15, 48, 0.40);
font-family: "Playfair Display",serif;
font-size: 40px;
font-style: normal;
font-weight: 600;
line-height: 130%; /* 52px */
}
.redclass{
  width: 100px;
  height: 3px;
  border: 2px solid  #E54545;
  border-radius: 10px;
}
.text-about{
    color: var(--White, #FFF);
font-family: "Gilroy",sans-serif;
width: 100%;
font-size: 18px;
font-style: normal;
font-weight: 500;
line-height: 130%; /* 23.4px */
margin-top: 20px;
}
.supports{
    color: var(--White, #FFF);
font-feature-settings: 'liga' off, 'calt' off;
font-family: "Gilroy",serif;
font-size: 20px;
font-style: normal;
font-weight: 600;
line-height: 130%; /* 26px */
margin-top: 30px;
}
.two-images{
    padding: 10px;
}
.two-buttons{
    display: flex;
    align-items: center;
    gap: 30px;
    margin-top: 40px;
}
.global{
    display: flex;
    align-items: center;
    gap: 10px;
    text-decoration: none;
    color: white;
     
}
.global p{
   margin-top: 13px;
}
.other-button1{
   display: flex;
   align-items: center;
   justify-content: center;
    
 width: 150px;
    gap: 10px;
    border-radius: 8px;
background: var(--Main, #E54545);
}
.other-button2{
    display: flex;
    align-items: center;
    justify-content: center;
     
  width: 200px; 
     gap: 10px;
     border-radius: 8px;

     background: #2C2E3E;
}

.slider-images{
    cursor: pointer !important;
    object-fit: cover !important;
    transition: all 0.4s;

}

.slider-images:hover{
    transform: scale(1.5);
    transition: all 0.4s;
}
.other-button1:hover{
    cursor: pointer;
    color: white;
    background-color: #e93030;
}
.other-button2:hover{
    cursor: pointer;
    color: white;
    background-color: #1b1c24;
}
.branch{
    border-radius: 12px;
background: rgba(255, 255, 255, 0.04);

}
.branches{
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
    padding-bottom: 20px;

    flex-wrap: wrap;
}
.branch{
    display: flex;
    align-items: center;
gap: 30px;
padding-left: 20px ;
}
.branch img{
    align-self: end;
}
.branchname h6{
    color: var(--White, #FFF);
    font-family: "Gilroy",serif;
    font-size: 40px;
    font-style: normal;
    font-weight: 700;
    line-height: 130%; /* 52px */
}
.branchname p{
    color: rgba(255, 255, 255, 0.60);
    font-family: "Gilroy",serif;
    font-size: 20px;
    font-style: normal;
    font-weight: 500;
    line-height: 130%; /* 26px */
}
.new-responseimg p{
    display: none;
}
</style>