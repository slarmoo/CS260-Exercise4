# cs260-exercise4
## Terminal commands practice

There is a [hints](./hints.md) file that you can look at if you're stuck. 

1. Open this folder in a POSIX compliant terminal 
    - Mac - The terminal
    - Linux - The shell / console
    - Windows - git bash

2. Next, let's create a folder called "practice", and move into it. 

3. Now let's create a file "test.txt". Text editors like vim and nano will automatically create a file if it doesn't exist yet. Add `echo hello world` as text inside of the file. Run `cat test.txt` to see what you wrote. 
    - For vim, if you can't edit the file press either "i" or "insert". If you're having trouble escaping press "escape", then type ":wq" and press enter. 
    - For nano, the commands should be listed at the bottom. To exit, make sure you first write out, then exit. 

4. Next, rename test.txt to "practice.sh". 

5. Now let's update the permissions of practice.sh to also be able to execute files. You can do this with the `+x` flag. 
    - Note that on windows this may not work properly. If you would like to test you can remove write permissions with the `-w` flag, or remotely shell into your startup server and repeat the above steps. 

6. Run the file and see your message!

7. Finally, change directories back to the root folder of this project and delete the directory. Remember to double check that you're removing the correct directory when doing this!

8. For this next section, you'll need to remotely enter your startup server. Run the command to do so. 

9. See what files are in there. You'll want to check even for hidden files

10. Check the permissions of your caddy file. They should be `lrwxrwxrwx`

11. Exit your remote session

Congratulations! You should now be ready to answer any command questions on your midterm
