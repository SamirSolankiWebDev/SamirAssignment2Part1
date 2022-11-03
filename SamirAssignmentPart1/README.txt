Program name: Assignment 2 Part 1
Program purpose : To review the components of an ASP.net MVC Application
Program author : Samir Solanki
Date Created :- 2022-01-11

First Step :- Created the application and merge with github in the file

- Comment the code as per the documents in Startup.cs file
     /*services.AddDefaultIdentity<IdentityUser>(options => options.SignIn.RequireConfirmedAccount = true)
                .AddEntityFrameworkStores<ApplicationDbContext>();*/
-new code -services.AddDefaultIdentity<IdentityUser>()
                .AddEntityFrameworkStores<ApplicationDbContext>();*/

                - Started debugging the code it didnt worked because i have not comment the code in "LaunchSetting.json" File
                //  "sslPort": 44310
                -After comment this file it Started working


- Change the nav class from navbar-light to navbar dark and bg-white to bgprimary

Added Aditional file in layout.css
<script src="https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.js"></script>
<script src="https://cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js"></script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/toastr.js/latest/js/toastr.min.js"></script>
<script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
<script src="https://kit.fontawesome.com/e19c476714.js"></script>


