## Hints

1. Navigating to the correct folder will take a combination of `cd /paths` and `ls` to figure out where to go. If you're lost, in most file browsers you can also open the terminal starting from there

2. The command for creating a folder (directory) is `mkdir`, which is short for "make directory"

3. The command to open vim is either `vim` or `vi` + the name of the file that you want to open. Both commands should work. The command to open nano is simply `nano` + the name of the file that you want to open. 

4. The `mv` command can also rename a file: `mv test.txt practice.sh`. 

5. `chmod` is how you update permissions. You may also need to use `sudo` to run as an admin. You can double check that this worked with `ls -l`. 

6. To run a file, add `./` to the beginning of the file name, so `./practice.sh`. 

7. You can use `cd ..` to move down a directory. To remove a directory, we need to add the recursive flag to the remove command: `rm -r practice`. 

8. The command is `ssh -i path/to/your/key.pem ubuntu@domainname.click`.

9. To look for hidden files, you'll want to use the `-a` flag with `ls`.

10. The `-l` flag of `ls` shows a lot more information about each file, including last modified date, file / directory size, and the permissions

11. To exit, you can either type `exit` or close the terminal. 