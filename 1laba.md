# 
@echo on 
set /p path =
if exist %path% ( 
echo takaya papka est 


for /f "usebackq delims=" %%i in (`find /n /v "" d:\tiit\*.txt ^| find "[5]"`) do (echo %%i » log.txt) 
 
pause
) ELSE ( 
echo NET PAPKI 
exit 
)
