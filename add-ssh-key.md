
***<h2>Generating a new SSH key</h2>***

1. Open Terminal and Type below command in desired folder.

   ssh-keygen -t rsa -b 4096 -C "your_email@sample.com"
   ![ScreenShot](https://github.com/harshmaheshwari001/git/blob/master/1.png)

   Press Enter will prompt for File Name default name (id_rsa) and (Optional) Enter Passphrase.
   ![ScreenShot](https://github.com/harshmaheshwari001/git/blob/master/2.png)

2. ssh-key private & public generated. public key (.pub) extensions in current directory. 
   ![ScreenShot](https://github.com/harshmaheshwari001/git/blob/master/3.png)

3. Copy **harsh_rsa.pub** key.
4. Login to your [GitHub](https://github.com/) account. **Settings -> SSH and CPG Keys**. Click on **New SSH Key** button. 

5. Give Title to the Key and Paste copied public_key inside key textarea.
6. Now Click on Add SSH Key button and all done now.
   ![ScreenShot](https://github.com/harshmaheshwari001/git/blob/master/4.png)

***<u>Test you configuration</u>***
1. Create any repository or use existing respository.
2. Click on **Clone or download button** copy `HTTPs link`
3. Clone new respository with following command
    `git clone https://github.com/harshmaheshwari001/node_starter`
4. Try Git commands like `Push & Pull`. If works fine done with ssh configuration.
5. Make sure your proxy settings if any.

Happy Learning !!
