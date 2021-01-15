<!DOCTYPE html>
<html lang="pl">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp"
              crossorigin="anonymous">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
              crossorigin="anonymous">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ekko-lightbox/5.3.0/ekko-lightbox.css" />
        <link rel="stylesheet" href="https://github.com/Toriach/bootstrapProject1/blob/master/css/style.css">
        <title>CV</title>

    </head>

    <body>
        <div class="container">
            <header id="main-header">
                <div class="accordion bg-dark" id="accordionExample" >
                    <div class="row no-gutters">

                        <div class="col-lg-4 col-md-5">
                            <img src="img/person1.jpg" alt="NoFaceFound">
                        </div>
                        <div class="col-lg-8 col-md-7">
                            <div class="row no-gutters emptyRow50PX"><!-- empty row as margin :) --> </div>

                            <div class=" row no-gutters myCustomRow"> <!-- row with name and icons -->
                                <div class="col-md-1"></div> <!-- empty column as margin :) -->

                                <div class="col-md-3">
                                    <h1 class="h1-name">John Doe</h1>
                                </div>
                                <div class="col-md-2">
                                    <a href="https://twitter.com/?lang=pl" target="_blank"><i class="fab fa-twitter socialMediaIcons"></i></a>                                    
                                </div>
                                <div class="col-md-2">
                                    <a href="https://www.facebook.com/tomek.sowinski.1" target="_blank"><i class="fab fa-facebook socialMediaIcons"></i></a>                                   
                                </div>
                                <div class="col-md-2">
                                    <a href="https://www.instagram.com/" target="_blank"><i class="fab fa-instagram socialMediaIcons"></i></a>                                 
                                </div>
                                <div class="col-md-2">
                                    <a href="https://github.com/Toriach/websiteProjects" target="_blank"><i class="fab fa-github socialMediaIcons"></i></a>                                    
                                </div>
                            </div>

                            <div class="row no-gutters emptyRow50PX"><!-- empty row as margin --> </div>

                            <div class="row no-gutters jobTitleBar"><!-- job title description --> 
                                <p class="jobTitleParagraph">Experienced Full Stack Web Developer</p>
                            </div>

                            <div class="row no-gutters testRow">
                                <div class="col-md-3">
                                    <button class="btn bg-primary btn-lg btn-block mainMenuButtonsWithIcons" type="button" data-toggle="collapse" data-target="#homeHidenSection" aria-expanded="true" aria-controls="homeHidenSection">
                                        <i class="fas fa-home fa-2x d-block"></i>Home</button>
                                </div>

                                <div class="col-md-3">
                                    <button class="btn bg-success btn-lg btn-block mainMenuButtonsWithIcons" type="button" data-toggle="collapse" data-target="#ResumeHidenSection" aria-expanded="true" aria-controls="ResumeHidenSection">
                                        <i class="fas fa-graduation-cap fa-2x d-block"></i>Resume</button>
                                </div>

                                <div class="col-md-3">
                                    <button class="btn bg-warning btn-lg btn-block mainMenuButtonsWithIcons" type="button" data-toggle="collapse" data-target="#WorkHidenSection" aria-expanded="true" aria-controls="WorkHidenSection">
                                        <i class="fas fa-folder-open fa-2x d-block"></i>Work</button>
                                </div>

                                <div class="col-md-3">
                                    <button class="btn bg-danger btn-lg btn-block mainMenuButtonsWithIcons" type="button" data-toggle="collapse" data-target="#ContactHidenSection" aria-expanded="true" aria-controls="ContactHidenSection">
                                        <i class="fas fa-envelope fa-2x d-block"></i>Contact</button>
                                </div>

                            </div>
                        </div>
                    </div> <!-- end of upper row -->

                    <!-- hiden rows -->
                    <!-- Home -->
                    <div class="row no-gutters">
                        <div class="col-md-12 collapse homeHidenSection bg-primary " id="homeHidenSection" aria-labelledby="homeHidenSection" data-parent="#accordionExample">  
                            <div class="row ">
                                <div class="col-md-12 ">
                                    <div class="card bg-primary">
                                        <div class="card-body ">
                                            <h2>Welcome to My Page</h2>
                                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="row ">
                                <div class="col-md-12 ">
                                    <div class="card bg-light">
                                        <div class="card-body">
                                            <h3>My Skills</h3>
                                            <p style="color: black">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                                            <hr>
                                            <h4>HTML 5</h4>
                                            <div class="progress">
                                                <div class="progress-bar bg-success" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                                            </div>
                                            <h4>CSS 3</h4>
                                            <div class="progress">
                                                <div class="progress-bar bg-success" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                                            </div>
                                            <h4>JavaScript</h4>
                                            <div class="progress">
                                                <div class="progress-bar bg-warning" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
                                            </div>
                                            <h4>PHP</h4>
                                            <div class="progress">
                                                <div class="progress-bar bg-success" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
                                            </div>
                                            <h4>Python</h4>
                                            <div class="progress">
                                                <div class="progress-bar bg-success" role="progressbar" style="width: 70%" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100"></div>
                                            </div>
                                            <br>

                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Resume -->
                    <div class="row no-gutters">
                        <div class="col-md-12 collapse  bg-success" id="ResumeHidenSection" aria-labelledby="WorkHidenSection" data-parent="#accordionExample">                         
                            <div class="html-rainbow-text" style="text-align: center;">
                                <span style="color:#9400D3">TODO</span><br><span style="color:#0000FF">this</span><br><span style="color:#FFFF00">page</span><br><span style="color:#FF0000">:)</span>
                            </div>
                        </div>
                    </div>

                    <!-- Work -->
                    <div class="row no-gutters">
                        <div class="col-md-12  collapse close  bg-warning" id="WorkHidenSection"  aria-labelledby="WorkHidenSection" data-parent="#accordionExample">                         
                            <div class="html-rainbow-text" style="text-align: center;">
                                <span style="color:#9400D3">TODO</span><br><span style="color:#0000FF">this</span><br><span style="color:#FFFF00">page</span><br><span style="color:#FF0000">:)</span>
                            </div>
                        </div>
                    </div>

                    <!-- Contact -->
                    <div class="row no-gutters">
                        <div class="col-md-12 collapse close  bg-danger" id="ContactHidenSection" aria-labelledby="ContactHidenSection" data-parent="#accordionExample">                       <div class="html-rainbow-text" style="text-align: center;">
                            <span style="color:#9400D3">TODO</span><br><span style="color:#0000FF">this</span><br><span style="color:#FFFF00">page</span><br><span style="color:#FF0000">:)</span>
                            </div>
                        </div>
                    </div>

                    <div class="row"><!-- download Resume Row -->

                        <div class="col-md-4 downloadResumeRow">
                            <button class="btn btn-outline-light downloadResumeButton"><i class="fas fa-cloud"></i> Download Resume</button>
                        </div>



                    </div>
                </div>


            </header>
        </div>







        <script src="http://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
                crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
                crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T"
                crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/ekko-lightbox/5.3.0/ekko-lightbox.min.js"></script>


    </body>

</html>
