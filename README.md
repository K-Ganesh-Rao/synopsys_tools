# synopsys_tools

1. Source synopsys_tool to create workking environment
````
$ csh
$ source .cshrc
````
2. Run VCS command and give respective path of design filr
   ````
   $ vcs ./folder_name/rtl_file_name.v  ./folder_name/testbench_name.v
   ````
3. Compile /execute  design
   ````
   $ ./simv
   ````
4. Open GUI window
   ```
   $ dve dump.vcd
   ```
