<template>
<div class="hello">
  
  <h1> Purchase mobile Credit</h1>

   <md-toolbar class="md-large md-dense">
      <div class="md-toolbar-row">
   <md-avatar>
      <img src="https://img.favpng.com/24/19/15/logo-beeline-internet-mts-bilayn-png-favpng-KC6ZT49wt7rq0ULkxJCfUqsYJ.jpg" alt="Avatar">
    </md-avatar>
      <spanner></spanner>
    <md-button class="md-raised md-primary" @click="tooltipActive = !tooltipActive">Buy Credit</md-button>
    <spanner></spanner>
    <md-button class="md-raised md-primary">Check Credit Balance </md-button>
      <spanner></spanner>
       <md-button class="md-primary md-raised toggle" @click="toggle">Buy for Others </md-button>
 </div>
    </md-toolbar>
    <md-toolbar class="md-large md-dense">
      <div class="md-toolbar-row">
          <md-avatar>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Tele2_logo.svg/1200px-Tele2_logo.svg.png" alt="Avatar">
    </md-avatar>
    <md-button class="md-raised md-primary" @click="tooltipActive = !tooltipActive">Buy Credit</md-button>
        <spanner></spanner>
    <md-button class="md-raised md-primary">Check credit Balance</md-button>
      <spanner></spanner>
       <md-button class="md-primary md-raised toggle" @click="toggle">Buy for others </md-button>
      </div>
    </md-toolbar>
    <md-toolbar class="md-large md-dense">
      <div class="md-toolbar-row">
        <md-avatar>
      <img src="https://www.mobileeurope.co.uk/images/Companies/MTS-logo617.jpg" alt="Avatar">
   </md-avatar>
    <md-button class="md-raised md-primary" @click="tooltipActive = !tooltipActive">Buy Credit</md-button>
     <spanner></spanner>
    <md-button class="md-raised md-primary">Check Credit Balance</md-button>
      <spanner></spanner>
       <md-button class="md-primary md-raised toggle" @click="toggle">Buy for others</md-button>
      </div>
    </md-toolbar>
    <md-toolbar class="md-large md-dense">
      <div class="md-toolbar-row">
          <md-avatar>
      <img src="https://img.favpng.com/19/24/10/megafon-russia-internet-yota-mobile-service-provider-company-png-favpng-APpqY1idBBXRT29RcTG81zR47.jpg" alt="Avatar">
      
    </md-avatar>
    <md-button class="md-raised md-primary" @click="tooltipActive = !tooltipActive">Buy Credit</md-button>
       <spanner></spanner>
    <md-button class="md-raised md-primary">CCheck Credit Balance</md-button>
      <spanner></spanner>
       <md-button class="md-primary md-raised toggle" @click="toggle">Buy For others</md-button>
      </div>
    </md-toolbar>
   
  </div>
  
</template>

<script>
 export default {
    name: 'Dynamically',
    data: () => ({
      tooltipActive: true
 })
 }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang="scss" scoped>
 .md-toolbar + .md-toolbar {
    margin-top: 40px;
   
  }
  
  .md-toolbar,
  .md-avatar,
  .md-button {
    margin: 40px;
     background-color:#7DCEA0; 
  }
  .md-tabs {
    margin-bottom: 24px;
    color:rgb(0, 255, 191);
    background-color: #82E0AA ; 
  }.md-menu,
   .toggle {
    margin: 24px;
  }

  .author-card {
    padding: 8px 16px;
    display: flex;
    align-items: center;
    
    .md-avatar {
      margin-right: 16px;
    }

    .author-card-info {
      display: flex;
      flex-flow: column;
      flex: 1;
    }

    span {
      font-size: 16px;
    }

    .author-card-links {
      display: flex;

      a + a {
        margin-left: 8px;
      }
    }
  }
</style>
