Please use this command to generate the code coverage as this command excludes program.cs file that cannot be covered by test cases.

**Command : dotnet test /p:CollectCoverage=true /p:CoverletOutputFormat=lcov /p:CoverletOutput=./TestResults/lcov.info /p:ExcludeByFile=**/program.cs**

**Coverage Report Image**

![Screenshot from 2024-04-19 09-40-48](https://github.com/Srvchoudhary/DotNet_UnitTest_Assignment/assets/88824767/aea6ec6f-d413-44ec-af9a-2a9df6225c1f)

 
