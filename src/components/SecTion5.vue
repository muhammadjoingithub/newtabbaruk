<template>
     <section class="container-fluid section5">
          <div class="container news-leading">
            <center>
                <div class="countries-text">
                    <h2>News</h2>
                    <div class="slowdown-row"></div>
                    <p>Leading news about Turkic states </p>
                </div>
             </center>

             <div class="news-items">
                 <div class="news-boxes first">
                    <div class="text0f-news1">
                        <img src="../assets/images/first1.png" alt="">
                        <div class="textof21">
                            <h2>Organization of Turkic States to adopt “EU model”</h2>
                            <p class="first-child1">The Organization of the Turkic States has accepted Turkish Cyprus as the observer state in a landmark decision for the Turkish Cypriots.</p>
                            <p class="last-child1">November 10 2022</p>

                        </div>
                    </div>
                 </div>
                 <div class="news-boxes1 last">
                
                    <div class="text0f-news">
                        <img src="../assets/images/twice2.png" alt="">
                        <div class="textof2">
                            <h2>Organization of Turkic States pledges observer status for Turkish Cyprus</h2>
                            
                            <p class="last-child">November 10 2022</p>

                        </div>
                    </div>
              
                    <div class="text0f-news">
                        <img src="../assets/images/three3.png" alt="">
                        <div class="textof2">
                            <h2>Turkic states hold key position in Europe’s energy security: Erdoğan ANKARA</h2>
                            
                            <p class="last-child">March 16 2023</p>

                        </div>
                    </div>
                 </div>
             </div>
            
             <div class="button-div">
                <p>All news</p>
                <img src="../assets/images/rightarrow.png" alt="">
             </div>
          </div>
    </section>
</template>
<script>
export default {
  name: 'SecTion5'
}
</script>
<style>
.section5{
    background-color: rgb(8, 8, 8);
     height: auto;
}
.news-items{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 20px;
    padding: 30px;
}
.news-boxes1{
    row-gap: 10px;
    /* padding:15px ; */
    /* background-color: red; */
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    /* align-items: center; */
}
.text0f-news:hover{
    border-radius: 12px;
    border: 1px solid rgba(255, 255, 255, 0.04);
    background: rgba(255, 255, 255, 0.04);
    backdrop-filter: blur(15px);
    transition: all 0.2s ease-in-out;
    transform: scale(1.1);
    cursor: pointer;
}
/* .margin-top{
    margin-top: 20px;
    padding: 30px;
} */
.text0f-news{
    
    border-radius: 12px;
border: 1px solid rgba(255, 255, 255, 0.20);
/* background: var(--Black, #07091C); */
}
.news-boxes2{
   width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 20px;
    padding: 10px;
    border-radius: 12px;
border: 1px solid rgba(255, 255, 255, 0.20);
/* background: var(--Black, #07091C); */
}
.text0f-news img{
    border-radius: 10px;
    padding: 8px;
}
.textof2{
    padding-top: 10px;
}
.news-boxes{
    width: 45%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 20px;
    padding: 10px;
    border-radius: 12px;
border: 1px solid rgba(255, 255, 255, 0.20);
/* background: var(--Black, #07091C); */
}
.first:hover{
    border-radius: 12px;
border: 1px solid rgba(255, 255, 255, 0.04);
background: rgba(255, 255, 255, 0.04);
backdrop-filter: blur(15px);
transition: all 0.2s ease-in-out;
transform: scale(1.1);
cursor: pointer;
}
.text0f-news1{
    display: flex;
  gap: 10px;
  padding: 2px;
}
.text0f-news1 img{
    background: lightgray 50% / cover no-repeat;
    border-radius: 5px;
    object-fit: cover;
}
.text0f-news{
    display: flex;
  gap: 20px;
  padding: 2px;
}
.text0f-news{
    display: flex;
}
.first{
    width: 58%;
   
}
.last{
 width: 40%;
 
}
.textof21 h2{
    color: var(--White, #FFF);
    font-family: "Gilroy"sans-serif;
    font-size: 22px;
    font-style: normal;
    font-weight: 700;
    line-height: 130%; /* 31.2px */
}
.first-child1{
    color: var(--White, #FFF);
    font-family: "Gilroy"sans-serif;
    font-size: 16px;
    font-style: normal;
    font-weight: 500;
    line-height: 130%; /* 20.8px */
}
.last-child1{
    color: rgba(199, 187, 187, 0.6);
    font-family: "Gilroy"sans-serif;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 130%; /* 20.8px */
 /* margin-top: 90px; */
 padding-top: 60px;
  
    
}
.last-child{
    color: rgba(255, 255, 255, 0.60);
    font-family: "Gilroy"sans-serif;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 130%; /* 20.8px */
    margin-top: 20px;
}

.textof2 h2{
    color: var(--White, #FFF);
    font-family: "Gilroy"sans-serif;
    font-size: 18px;
    font-style: normal;
    font-weight: 600;
    line-height: 130%; /* 23.4px */
}
.button-div{
   display: flex;
   align-items: center;
   justify-content: center;
position: relative;
left: 84%;
width: 150px;
border-radius: 8px;
background: #2C2E3E;

}
.button-div:hover{
    transform: scale(1.1);
    transition: all 0.2s ease-in-out;
}
.button-div p{
    margin-top: 15px;
    color: #FFF;
font-family: "Gilroy",sans-serif;
font-size: 16px;
font-style: normal;
font-weight: 600;
line-height: 150%; /* 24px */
}
</style>
