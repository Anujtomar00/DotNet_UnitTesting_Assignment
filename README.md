Please use this command to generate the code coverage as this command excludes program.cs file that cannot be covered by test cases.

**Command : dotnet test /p:CollectCoverage=true /p:CoverletOutputFormat=lcov /p:CoverletOutput=./TestResults/lcov.info /p:ExcludeByFile=**/program.cs**

**Coverage Report Image**
![covergae](https://github.com/Anujtomar00/DotNet_UnitTesting_Assignment/assets/94008199/b4cfc569-8cef-4d92-8ff1-8e38bae80a86)
