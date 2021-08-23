<template>
     <div>
    <a href="index.html" style="margin-left: 20px;color: white;">Back</a>
  </div> 
    <div class="login-form">
    <form action="/examples/actions/confirmation.php" method="post">
    <h2>Login</h2>
    <div class="form-group">
            <input type="text" class="form-control" placeholder="Username" required="required">
        </div>
        <div class="form-group">
            <input type="password" class="form-control" placeholder="Password" required="required">
        </div>
        <div class="form-group">
            <button type="submit" class="btn btn-primary btn-block">Log in</button>
        </div>
        <div class="clearfix">
            <label class="float-left form-check-label"><input type="checkbox"> Remember me</label>
            <a href="#" class="float-right">Forgot Password?</a>
        </div>        
    </form>
  <div class="text-center">Create an account? <a href="register.html">Sign Up</a></div>
</div>
</template>
<style scoped src="../assets/style/lr.css">
/* @import '../assets/style/lr.css'; */
</style>