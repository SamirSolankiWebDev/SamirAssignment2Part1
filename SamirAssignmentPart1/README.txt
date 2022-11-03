Program name: Assignment 2 Part 1
Program purpose : To review the components of an ASP.net MVC Application
Program author : Samir Solanki

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


