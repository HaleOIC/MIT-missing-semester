## Lec1 

1. ```bash
   hale@hale-virtual-machine:~$ echo $SHELL
   /bin/bash
   ```

2. `mkdir missing`

3. `man touch`

4. ```bash
   cd missing 
   touch semester
   ```

5. ```bash
   echo '#!/bin/sh' > semester
   echo 'curl --head --silent https://missing.csail.mit.edu' >> semester
   ```

6. ```bash
   hale@hale-virtual-machine:/tmp/missing$ ls -l 
   total 4
   -rw-rw-r-- 1 hale hale 61  1月 12 15:47 semester
   ```

7. ```bash
   man sh 
   ```

8. ```bash
   man chmod
   ```

9. ```bash
   hale@hale-virtual-machine:/tmp/missing$ chmod a+x semester
   hale@hale-virtual-machine:/tmp/missing$ ls -l
   total 4
   -rwxrwxr-x 1 hale hale 61  1月 12 15:47 semester
   hale@hale-virtual-machine:/tmp/missing$ ./semester
   ```

10. ```bash
    ./semester | grep last-modified > ~/last-modified.txt
    cat ~/last-modified.txt
    ```