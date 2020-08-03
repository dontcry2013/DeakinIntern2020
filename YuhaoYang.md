# DeakinIntern2020

## 20 July 2020
### What I learn today
* Install MySql and build MySql environment
* Install VScode
* Markdown syntax
(https://www.jianshu.com/p/191d1e21f7ed)
* How to use Git and Github
```
echo "XXXX" >>                                                              FILENAME Import "XXXX" to the file that the name is the FILENAME
git status                                                                  Check the git status
git add FILENAME                                                            Add file
git commit -m/-am 'what you want to metion here'                            -m is add. -am is update
git remote add origin https://github.com/dontcry2013/DeakinIntern2020.git   Add remote host
git push -u origin master                                                   Push file to Github
git pull                                                                    Pull all files that have been changed in the remote host to your host
git clone https://github.com/dontcry2013/DeakinIntern2020.git               Clone
```
* Know about phpmyadmin
(https://blog.csdn.net/u012767761/article/details/78238487)

### The future work
* find a way to import .csv file to MySql
* learn how to use phpmyadmin

## 27 July 2020
### What I learn today
* How to use the mysqlimport related command in vscode to push data from a csv file to the appropriate location in a table in phpmyadmin.
```
1. download xlsx
2. export csv or copy to VS, and then replace the space with comma
3. create table in phpmyadmin according to the file structure
4. mysqlimport import
mysqlimport --ignore-lines=1(Ignore the first line) --fields-terminated-by=,(Separation character number between data) --local -u deakin-intern(username) -p test(database name) -h mel.cloudcampus.com.au graduation_direction.csv(your csv file name)
```
* other way to import data is to operate on phpmyadmin
```
1. download xlsx
2. export csv and open it on txt and change the code mode to ult-8 and save
3. create new table on phpmyadmin
4. choose the tbale that you want to import data and click import button
5. choose file
6. Cancel partial insertion
7. Change the format to csv using LOAD DATA
8. Set the field separator to，
9. choose Using the LOCAL keyword
10. done
```
## 03 August 2020
### What I learn today
* How to use AEMG server
```
1. create new project in Class Timetable
2. add sessions in new project
3. click quick arrange
4. Fill in the appropriate spaces according to the class schedule

```
