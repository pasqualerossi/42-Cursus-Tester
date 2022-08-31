# 42-Cursus-Tester
Built By [Aidan Baker](https://github.com/Abaker-Hype). 

Link to the tester - https://github.com/Abaker-Hype/42-Cursus-Tester

This tester can check the following:

- Libft
- Get_Next_Line 
- Ft_Printf
- Exam Rank 02 - Get_Next_Line
- Exam Rank 02 - Ft_Printf

## How To Use The Tester
Step by Step Instructions on how to run this Tester. 

All of the following steps below are in Shell. 

<br>

1. Copy and paste the following in shell -

```
git clone https://github.com/Abaker-Hype/42-Cursus-Tester.git
```

Note: make sure to git clone this tester outside of your Libft/Get_Next_Line/Printf Folder, not in it.

<br>

2. ``cd`` into the 42-Cursus-Tester and type in the following in shell - 

```
vim script.sh
```

<br>

3. In the vim script.h file, under the #Libs locations (3rd Row Down from the top of the script.h file), change the path description to your own Libft, Get_Next_Line or Printf folder.

<br>

4. Then exit vim (``wq``) and type in the shell the following command -

```
make <the project name that your working on>
```  
to run the 42-Cursus-Tester, eg. ```make printf```

<br>

5. Check your results and good luck!

If you get a KO or S in this tester, then write the following to find out where exactly in the function/program that is occuring:

```
make <project name> <function_name> detail
```
