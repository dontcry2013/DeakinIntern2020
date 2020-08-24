# DeakinIntern2020
Day1

## Learned on July 20
* ###  mySQL  
     + Downloaded from: https://dev.mysql.com/downloads/file/? id=496310, then install.
     + Setting up the mySQL environment
     + Learn the basics about mySQL.  

        (Text version: https://www.runoob.com/mysql/mysql-administration.html.  

        Video version: https://www.bilibili.com/video/BV12b411K7Zu?p=247)
* ### VScode 
     +   Download and install
     +   Add plugins: code spell checker, tabnine.
* ### phpmyadmin
     +   Learn about phpmyadmin and search for "how to import CSV files"  
     (link: https://zhuanlan.zhihu.com/p/26964403 )
* ### Markdown
     + Search Markdown commands  
     (link: https://www.runoob.com/markdown/md-paragraph.html).
* ### Git & Github
     + Download and install git
     + Learn how to push new files on github  
    . git status : 以查看在你上次提交之后是否有修改   
    . git add NA.md : 将该文件添加到缓存  
    . git commit - am "first commit" ：缓存区内容添加到仓库中  
    . git branch -avv ： 创建分支命令  
    . git remote add origin https://github.com/dontcry2013/DeakinIntern2020.git : 指定一个简单的名字，以便将来引用  
    . (git pull:如果无法推送，先pull再push)     
    . git push :推送更改的文件  
    . git push -u origin master: 推送到远程仓库
    . git log : 查看提交历史  
    + Basic git commands tutorial : https://www.runoob.com/git/git-tutorial.html   

    
    
* * *  



 Day2

## Learned on July 27

* ###  mySQL  

     +  Learn how to import csv files into mysql   
        > Use code to import data into mysql
        >> mysqlimport --ignore-lines=1(Ignore the first line) --fields-terminated-by=,(Separation character number between data) --local -u deakin-intern(username) -p test(database name) -h mel.cloudcampus.com.au graduation_direction.csv(your csv file name)  
          

* ### phpmyadmin
     +   Learn how to create a data table in phpmyadmin
     +   Use phpmyadmin to import the csv file into the database   
         > Download the data to be imported (probably an xls file)  

         >  Convert XLS files to csv format
         >>Save XLS file as csv format  
         >>Open csv file with text document  
         >>Save the file as a file whose encoding is UTF-8  

         > Back to phpmyadmin, select "Import"   
         >Import the newly encoded file  
         >Cancel the selection in "Partial import "   
         > Select "Enable foreign key checks"  
         > Change the format to csv using LOAD DATA  
         > Change Columns separated with: ";" to ","    
          >choose Using the LOCAL keyword  
          > Import

* ### Markdown
     + Learn new commands  
     (link: https://www.runoob.com/markdown/md-paragraph.html).  
     
    
     * * * 


 Day3

## Learned on Aug 03

* ###   AEMG server  

     +  Learn how to use AEMG server 
     >How to create a new course schedule  
     >> -Select the matching project.  
     >> -Select the correct academic year, course start time,  week length , etc.  
     >>-Set course start and end times  
     +  Learn how to use Quick Arrange

     > Double-click to add a classroom, course, teacher, etc.  
     >Click it to set to the specified time  
     >Right-click to deselect
  * * * 

 Day4

## Learned on Aug 10

* ###   AEMG server  
     +   use Quick Arrange
     >Use the "Quick Arrange" feature to check and add new classrooms to the system  

     >Due to the save function being temporarily not working, data may be lost, so new download buttons have been added to make sure the entered information is not lost.   

     >When filling schedules, left click to place information, right click to cancel 

* ###   SheetJS 
  +   Learn SheetJS and learn how to convert xlsx to json and save it to a database.  

    > The learning information is available at: https://sheetjs.com/demo

    > XLSX.utils.sheet_to_csv generates CSV  
    >XLSX.utils.sheet_to_txt generates UTF16  
    >XLSX.utils.sheet_to_html generates HTML  
    >XLSX.utils.sheet_to_json generates an array of objects  
    >XLSX.utils.sheet_to_formulae generates a list of formulae

   * * * 

 Day5

## Learned on Aug 17  

* ###   AEMG server  
  +   use Quick Arrange  
  > Importing timetables by using Quick Arrange

 * ###   Sheet JS 
     > The learning information is available at: https://sheetjs.com/demo 


     > Simulate the entire process of import   
      >>-Convert xls.files to json files using this link:https://oss.sheetjs.com/sheetjs/  
      >> -Learn how to read the Json file  
      >> -Read the Json file to find the location of English classes in the timetable  
      >> -Based on this template, create a data file that we need  
      >>> { 'cohort':' 17生物技术(西塔)01班课表1',
          'term':"2018-2019年第2学期",
          'major':'专业：生物技术(西塔)',
          'data':
          [{
          'weekday': "星期三",
          'session':'第一二三节',
          'detail':'学术英语 Ⅲ —英语综合/(1-2节)1-15周/西塔学院 31-0205/唐涛/无/学术英语 Ⅲ —英语综合-0001/17生物技术(西塔)01班/通必/28/27/未安排'
          }, {}, {}]
           }   


 * ###   Json  
      > Website for learning Json :https://www.w3schools.com/js/js_json_intro.asp  

 * ###   JavaScript  
    >Learn JavaScript at: https://www.w3schools.com/js/js_arrays.asp  



  



