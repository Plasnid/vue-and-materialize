<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div class="container">
      <div class="row teal">
        <div class="col s1">1</div>
        <div class="col s1">2</div>
        <div class="col s1">3</div>
        <div class="col s1">4</div>
        <div class="col s1">5</div>
        <div class="col s1">6</div>
        <div class="col s1">7</div>
        <div class="col s1">8</div>
        <div class="col s1">9</div>
        <div class="col s1">10</div>
        <div class="col s1">11</div>
        <div class="col s1">12</div>
      </div>
      <div class="card-panel teal lighten-2">This is a card panel with teal lighten-2 class</div>
    </div>
    <div class="row">
      <div class="col s12">This div is 12-columns wide on all screen sizes</div>
      <div class="col s6">6-columns (one-half)</div>
      <div class="col s6">6-columns (one-half)</div>
    </div>


    <div class="row">
      <div class="col s12"><span class="flow-text">This div is 12-columns wide on all screen sizes</span></div>
      <div class="col s6 offset-s6"><span class="flow-text">6-columns (offset-by-6)</span></div>
    </div>
    
    <div class="row">
      <div class="col s7 push-s5"><span class="flow-text">This div is 7-columns wide on pushed to the right by 5-columns.</span></div>
      <div class="col s5 pull-s7"><span class="flow-text">5-columns wide pulled to the left by 7-columns.</span></div>
    </div>

  <a class="waves-effect waves-light btn">button</a>
  <a class="waves-effect waves-light btn"><i class="material-icons left">cloud</i>button</a>
  <a class="waves-effect waves-light btn"><i class="material-icons right">cloud</i>button</a>
        
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
    
  }
}
</script>
