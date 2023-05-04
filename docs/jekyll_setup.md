# Jekyll Setup

### Create enviroment

1. open Terminal in Windows
2. go to your working directory  

    `cd C:/web/www/`
3. then you are creating the jekyll site  

    `jekyll new NAMEOFYOURSITE`  

    The bundler will now build up the basic structure of the directory.

    `New jekyll site installed in C:/web/www/NAMEOFYOURSITE`  

4. Open the directory of the new site to see the basic structure:

    `cd NAMEOFYOURSITE`  
    `ls`  

        Directory: C:\web\www\NAMEOFYOURSITE  

        Mode                 LastWriteTime         Length Name  
        d----          01.11.2021    16:15                _posts  
        -a---          01.11.2021    16:15             35 .gitignore  
        -a---          01.11.2021    16:15           1652 _config.yml  
        -a---          01.11.2021    16:15            398 404.html  
        -a---          01.11.2021    16:15            539 about.md  
        -a---          01.11.2021    16:15           1293 Gemfile  
        -a---          01.11.2021    16:15           1981 Gemfile.lock  
        -a---          01.11.2021    16:15            175 index.md  

5. Now you can build the jekyll website:

    `bundle exec jekyll serve`  

    This will build your first website. The server is running and you can view your website at the browser:  

    `localhost:4000`  

    The server will wait for changes in the jekyll directory.  
    After you updated the .md files jekyll will convert them into .html files and save them in the **_site** directory.  
    ***Please dont change any file in the _site-directory!***  

    If you want to upload your website on a hosted server you need only to upload the _site directory by ftp.  

6. The jekyll server keeps running in terminal until you stop him by pressing `ctrl + c`.  
If you want to start the server again you need only to enter:  
        `jekyll serve`
