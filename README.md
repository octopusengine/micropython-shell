# micropython-shell
simple Linux terminal writen in (and for) ESP32-Micropython

<pre>
  ---------+--------------------------+--------------------
           | F: file name             |
           | M: "main.py"             |  octopusLAB 2019-20
  ---------+--------------------------+--------------------
     clear | clear display            |   
      free | free RAM (memory)        |
        df | Disk Free (flash)        |
        cd | Change Directory         | cd examples / cd ..
       pwd | Print Working Dir.       |
        ls | LiSt files and dir.      | ls examples
     mkdir | make directory           | mkdir newdir
        cp | CoPy F (defaul M)        | cp test.py back.py
        rm | ReMove F                 | rm test.py
       top | main proces info         | 
      wifi | wireless "fidelity"      | wifi on / wifi scan
      ping | Packet InterNet Groper   | ping google.com
  ifconfig | wifi InterFace conf.     |
      wget | wget URL subdir download | wget https://my.web/f.py  
      find | find "text"              | find oled 
       cat | concatenate F (defaul M) | cat back.py
       edit| edit (defaul M)          | simple "line editor"
        ./ | run F                    | ./examples/blink.py
           | run F & > process/thread | run examples/blink.py &
      exit | back to uPy              | > Micropython
  ---------+--------------------------+---------------------
</pre>
