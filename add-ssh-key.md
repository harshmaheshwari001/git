
<h2><b><i><u>Generating a new SSH key</u></i></b></h2>

1.Open Terminal and Type below command in any folder.

   ssh-keygen -t rsa -b 4096 -C "your_email@sample.com"
 ![ScreenShot](https://github.com/harshmaheshwari001/git/blob/master/1.png)

Press Enter will prompt for File Name default name (id_rsa) and (Optional) Enter Passphrase.
![ScreenShot](https://github.com/harshmaheshwari001/git/blob/master/2.png)

2. ssh-key generated private & public with .pub extensions in current directory. 
![ScreenShot](https://github.com/harshmaheshwari001/git/blob/master/3.png)

3. Copy <b>harsh_rsa.pub</b> key.
4. Now GoTo <b>Settings -> SSH and CPG Keys</b>. Click on <b>New SSH Key</b> button. 

5. Give Title to the Key and Paste copied public_key inside key textarea.
6. Now Click on Add SSH Key button and all done now.
![ScreenShot](https://github.com/harshmaheshwari001/git/blob/master/4.png)

<b><i><u>Test you configuration</u></i></b>
1. Create any repository or use existing respository.
2. Click on <b>Clone or download button</b> copy HTTPs link
3. Clone new respository with following command
    git clone https://github.com/harshmaheshwari001/node_starter
4. Try Git commands like Push & Pull. It works done with ssh configuration.

Happy Learning !!
