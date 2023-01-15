# Installing
For install download zip of this repo OR use git clone https://github.com/AndriyYankovenko/CW_parallel_computing.git in folder where you want.
# Building
After installing repo unzip files.rar in folder with projects like on image below:![image](https://user-images.githubusercontent.com/17770595/212561502-5e01847b-d9c2-4473-83cb-3a3d6b901597.png)
1.	If this is your first time running this program in a specific directory, or if you have added new files in your directory, you're going to have to create a new index (Depending on the size of your path of choice, this may take some time): 
-	First of all, you are going to have to set the PATH variable to the path of your text files like in the example below. Also, if you don’t have the libraries nltk and PySimpleGUI installed, execute install_packages.py to quickly install them.
-	If you have already created an index, but you have updated your data in the PATH directory, delete the example-inverted-index.txt file in your program’s directory, so the program will create a new one the next time it is executed.
-	If you want to, you can change the name of your index, just make sure it ends in .txt and keep in mind from now on the program will only save and load indexes with that given name.
![image](https://user-images.githubusercontent.com/17770595/212561520-dd4b011c-8b68-4a7f-9ad5-fcc152500b17.png)
2.	If an inverted index exists in the program’s directory, once you execute the program, a UI will open where you will have the option to type various search questions. This program not only does it allow you to search for specific terms and phrases, but you also have the ability to execute various Boolean queries.
3.	If you want to execute a Boolean query, you have to strictly write it in this form: “(a AND b) OR (b AND c AND d) OR e” etc. Where a, b, c, d, e can either be a single term or a phrase. Any other attempt to execute a Boolean query will not work.
4.	Execute your query and click one of the results that appear below to open the desired .txt file.
