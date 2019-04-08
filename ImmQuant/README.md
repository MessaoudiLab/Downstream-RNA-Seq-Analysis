## ImmQuant
### 1. Download ImmQuant from http://csgi.tau.ac.il/ImmQuant/

### 2. Create an input file
Columns required are:
```
Gene
Control(s)
Other groups
```
Save the file as as .txt (Tab Delimited Text) file
See input.txt file as example

### 3. Using the program
- Open the ImmQuant.jar program and follow the commands down below
```
1. Click "Run"
2. Click "Run deconvolution"
3. Browse/select input file
4. Select Human
5. Click "Next"
6. Select DMAP or IRIS (both are based on different databases) in the Deconvolution properties tab. IRIS is commonly used
7. Select "Perform calculation using a control group"
8. Select "Choose by Column numbers" and type in the column numbers of control group (i.e. 1-2). Note Gene ID does not count as column 1
9. Click "Next"
10. For Output file, name output data. Click "browse" and select directory where output data will be saved.
11. Click "Run"
```
