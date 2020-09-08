Computer Architecture Programming Assignment   
---------------------------------------------
2020 Fall SCE212, Ajou University

* There are two small practice about basic c programming.
  * PA0-A: Comprehension about Pointer
  * PA0-B: Practice File I/O & Parsing String values 

* You should fill the empty functions in both PA0-A and PA0-B.
* **Do not modifiy main() function.**
  
---------------------------------------------

### How to build
* Both PA0-A and PA0-B
```shell
$ pwd
/home/sce212/st201900000/PA0-A or /home/sce212/st201900000/PA0-B
$ make
successfully build completed!
```

### How to test
* You can test your result with sample_input and sample_output.
* Just type command `make test` in your shell and check your test results.

#### Case 1: PA0-A
```shell
# Check your current directory path
$ pwd
/home/sce212/st201924165/PA0-A

# Execute your binary file with input arguments.
$ ./pa0_a 0 1 2 3

# Output (This is not answer)
x1: 0, y1: 1, x2: 2, y2: 3
sum_x: 0
sum_y: 0
calc_area1: 0
calc_area2: 0
The reverse is (null)

# Test
$ make test
```

#### Case 2: PA0-B
```shell
# Check your current directory path
$ pwd
/home/sce212/st201924165/PA0-B

# Execute your binary file with input arguments.
$ ./pa0_b sample_inputs/input0/file_input sample_inputs/input0/dir_input

# Output
main.c
README.md
.gitignore
figure1.png
figure2.png

# Test
$ make test
```
