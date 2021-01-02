<template id="">
  <div class="container">
    <div class="row align-items-center h-100">
  <div class="col-sm-6">
    <div class="card">
      <div class="card-body">
        <img src="../assets/facebook.svg" alt="" width="300">
        <h3>Connect with friends and the world around you on Facebook.</h3>
      </div>
    </div>
  </div>
  <div class="col-sm-6">
    <div class="card">
      <div class="card-body">
        <div class="form shadow">
          <form class="d-block" action="index.html" method="post">
            <div class="form-group">
              <input type="text" name="" value="" class="form-control" placeholder="Email address">
            </div>
            <div class="form-group">
              <input type="text" name="" value="" class="form-control" placeholder="Password">
            </div>
            <div class="form-group">
              <input type="submit" name="" value="Log In" class="form-control btn-primary">
            </div>
            <div class="text-center">
              <a href="#" class="text-primary">Forgot Password?</a>
            </div>
          </form>
          <hr>
          <div class="form-group text-center">
            <button type="button" name="button" class="btn btn-success">Create account</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

  </div>
</template>
<style media="screen" scoped="true">
  .container{
    height: 100vh;
  }
  .card{
    border: none;
    background-color: transparent;
  }
  .form{
    background-color: white;
    border-radius: 15px;
    padding: 20px;

  }
</style>
