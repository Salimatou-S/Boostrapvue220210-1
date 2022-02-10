<template>
<div class="row">
<div class="card" style="width:30%;">
  <img class="card-img-top" src="../assets/gite.png" alt="Card image cap">
  <div class="card-body">
    <h2 class="card-title">Gîte</h2>
    <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod. Nullam id dolor id nibh ultricies vehicula ut id elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna..</p>
    <a href="#" class="btn btn-secondary">View details >></a>
  </div>
</div>

<div class="card" style="width: 31%;">
  <img class="card-img-top" src="../assets/randonnee.png" alt="Card image cap" >
  <div class="card-body">
    <h2 class="card-title">Randonnée</h2>
    <p class="card-text">Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
    <a href="#" class="btn btn-secondary">View details >></a>
  </div>
</div>

<div class="card" style="width: 32%;">
  <img class="card-img-top" src="../assets/ski.png" alt="Card image cap">
  <div class="card-body">
    <h2 class="card-title">Ski</h2>
    <p class="card-text">Donec sed odio dui. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
    <a href="#" class="btn btn-secondary">View details >></a>
  </div>
</div>
</div>
<hr/>
</template>

<style scoped lang="scss">
.row{
    display:flex;
    justify-content:space-around;
    flex-wrap:wrap;
    margin:50px;
    color:grey;
}

.card{
    align-items:center;
    padding:20px;
    border:none;
  
}
.card-img-top{
    width:140px;
    
}

hr{
    margin:100px;
    
}

</style>


