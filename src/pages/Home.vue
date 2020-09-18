<template>
<div>
  <div class="hero">
    <div class="content">
      <h4 class="shade q-pl-md text-white"> aloft NG</h4>      
    </div>
    <div class="shader q-pl-md text-white">
      Improving rural livelihood by providing<br>
      access to and management of funds.
    </div>  

    <div class="text-center">      
      <a href="https://forms.gle/vjTkndAYoCQ26d3x6" target="_blank"><q-btn class="profilebtn" color="secondary" label="Get Profiled" /></a>
    </div>
  </div>

<div class="section row q-px-lg q-py-md">
  <div class="col-xs-12 col-sm-6 col-md-6">
    <span class="text-h4">Our Initiative</span>
    <p>
      With the declining level of economic growth, income inequality, 
      unemployment, corruption, bad governance and inappropriate macroeconomic 
      policies, Aloft NG moves to profile over 10,000 rural dwellers with the 
      aim of alleviating poverty by providing access to micro-capital, local 
      business management and improved financial inclusion. <br>  

       <q-btn class="q-mr-sm" outline color='primary' label="Learn more" />
       <a href="https://forms.gle/vjTkndAYoCQ26d3x6" target="_blank"><q-btn color="primary" label="Get Profiled" /></a>
    </p>
  </div>

  <div class="col-xs-12 col-sm-6 col-md-6">
    <q-img src="images/pic3.jpg" spinner-color="white" style="height: auto; max-width: 350px" />
    
  </div>
</div>
<!-- T H R E E  C A R D S -->
  <div class="q-pa-md row justify-center q-gutter-md">
<!-- Card I -->    
    <q-card class="my-card">
      <img src="images/pic2.jpg">

      <q-card-section>
        <div class="text-h6">Poverty Alleviation</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        More than half of Nigeria's population live in abject poverty, and 60% of 
        rural dwellers are malnurished and have no secure source of income.
      </q-card-section>
    </q-card>
<!-- Card II -->
    <q-card class="my-card">
      <img src="images/pos.jpg">

      <q-card-section>
        <div class="text-h6">Financial Inclusion</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        The Nigerian rural communities are mainly unbanked and hence lack primary
        Financial Management or Small Business operation skill.
      </q-card-section>
    </q-card>
    
<!-- Card III -->
    <q-card class="my-card">
      <img src="images/pic1.jpg">

      <q-card-section>
        <div class="text-h6">Improved Livelihood</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        Proper profiling and provision of access to small busines capital as 
        well as monitoring of overall business operations will undoubtedly change 
        the narrative.
      </q-card-section>
    </q-card>    
  </div>  

</div>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>


<style>
 .hero{
   height: 400px;
   background-image: url('/images/family.jpg');
   background-size: cover;
 }

 .content{
   position: absolute;
   size: 5rem;
 }

.shade{  
    padding: 10px;
    background-color: rgba(0, 0, 0, .3);
    border-radius: 15px 0px 15px 0px;
    margin-bottom: 5px;
    margin-right: 5px;
    transition: 0.4s;
    position: relative;    
}

.shader{  
    padding: 10px;
    margin-top: 110px;
    background-color: rgba(0, 0, 0, .3);
    border-radius: 15px 0px 15px 0px;
    margin-bottom: 5px;
    margin-right: 5px;
    transition: 0.4s;
    position: absolute;    
}

a{
    text-decoration: none;        
}

.my-card{
  width: 100%;
  max-width: 330px;
}

.profilebtn{
  margin-top: 250px;
}

.section{
  margin-left: 20px;
  margin-right: 20px;
}
</style>