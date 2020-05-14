# Ghidra Data Type for Windows Malware Analysis
This gdt file fork from [0x6d696368/ghidra-data](https://github.com/0x6d696368/ghidra-data/tree/master/typeinfo).  
I add WINHTTP APIs for Windows Malware Analysis.  

## Load gdt
1. Download the winapi_32.gdt
2. Click to Data Type Manager ▼ -> "Open File Archive"

![1](https://user-images.githubusercontent.com/18203311/81836904-0e359800-957f-11ea-8677-ef6c20789ba8.png)

3. Choose the winapi_32.gdt

![2](https://user-images.githubusercontent.com/18203311/81836912-11308880-957f-11ea-87ad-a6d3c9618903.png)

4. Selecte "Apply Funtion Data Type"

![image](https://user-images.githubusercontent.com/18203311/81974548-b2dbd680-9660-11ea-894c-0138cc1d6aa3.png)

## Example

### Before
![image](https://user-images.githubusercontent.com/18203311/81974907-31387880-9661-11ea-86b8-572749184ef3.png)

### After
![image](https://user-images.githubusercontent.com/18203311/81974929-3bf30d80-9661-11ea-845f-a6534f0aa3c7.png)
