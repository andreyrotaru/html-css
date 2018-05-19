<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha256-916EbMg70RQy9LHiGkXzG8hSg9EdNy97GazNG/aiY1w=" crossorigin="anonymous" />
    <link rel="stylesheet" href="form.css">

    <title>Document</title>
</head>
<body>
  <!-- Trigger the modal with a button -->
<button type="button" class="btn btn-default btn-sm" data-toggle="modal" data-target="#loginModal"><span class="glyphicon glyphicon-user"></span> Sign In</button>


<!-- Modal -->
<div id="loginModal" class="modal fade" role="dialog">
  <div class="modal-dialog">

    <!-- Modal content-->
    <div class="modal-content">
      <div class="modal-header">
        <h4 class="modal-title">Login</h4>
        <button type="button" class="btn btn-default btn-sm" data-toggle="modal" data-target="#home">Register</button>
        <button type="button" class="close" data-dismiss="modal">&times;</button>
      </div>
      <div class="modal-body">
        
        <form id="login" action="/action_page.php">
            <div class="form-group">
              
              <input type="email" class="form-control" id="email" placeholder="Your email">
            </div>
            <div class="form-group">
              
              <input type="password" class="form-control" id="pwd" placeholder="Password">
            </div>
            <div class="checkbox">
              <label><input type="checkbox"> Remember Me</label>
            </div>
            <button type="submit" class="btn btn-primary">LOG IN</button>
            <div>
                <button type="submit" class="btn btn-default">Forgot Password?</button>
            </div>
        </form>
       <div id="home" class="tab-pane fade">
            <form id="register" action="/action_page.php">
                <div class="form-group">
                    <input type="text" class="form-control" id="name" placeholder="Your Name">
                </div>
                 <div class="form-group">
                    <input type="email" class="form-control" id="email" placeholder="Email">
                </div>
                 <div class="form-group">
                    <input type="password" class="form-control" id="pwd" placeholder="Password">
                </div>
                 <div class="form-group">
                    <input type="password" class="form-control" id="pwd" placeholder="Confirm Password">
                </div>
                <button type="submit" class="btn btn-primary">CREATE ACCOUNT</button>
            </form>
        </div>
    </div>
      
    </div>
  </div>
</div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js"></script>
</body>
</html>
