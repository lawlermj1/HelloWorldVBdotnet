
# Hello World VisualBasic 

## In Powershell, doing a dotnet compile 
cd C:\Users\lawle\Documents\dotnet\VB\Code

cd HelloWorldVBdotnet
code . 

dotnet run

-- TEST - use call operator to run executable 
& C:\Users\lawle\Documents\dotnet\VB\Code\HelloWorldVBdotnet\bin\Debug\netcoreapp3.1\HelloWorldVBdotnet.exe 


## In Powershell, doing a manual compile using vbc.exe 
-- Note no need for vbproj file 
-- Location 
C:\Windows\Microsoft.NET\Framework\v4.0.30319\vbc.exe 
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\vbc.exe 

-- compile command 
C:\Windows\Microsoft.NET\Framework\v4.0.30319\vbc.exe /t:exe /out:HelloWorldVBdotnetMan.exe Program.vb 
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\vbc.exe /t:exe /out:HelloWorldVBdotnetMan.exe Program.vb 

-- Compile text; limited to Visual Basic 2012 only. 
This compiler is provided as part of the Microsoft (R) .NET Framework, but only supports language versions up to Visual Basic 2012, which is no longer the latest version. For compilers that support newer versions of the Visual Basic programming language, see http://go.microsoft.com/fwlink/?LinkID=533241

-- TEST - use call operator to run executable 
& C:\Users\lawle\Documents\dotnet\VB\Code\HelloWorldVBdotnet\HelloWorldVBdotnetMan.exe


