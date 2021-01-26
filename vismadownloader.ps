#https://download.vismaspcs.se/downloads/visma_bokslut_2021.0_setup.exe
#https://download.vismaspcs.se/downloads/visma_bokslut_2020.12_setup.exe
#https://download.vismaspcs.se/downloads/visma_byrastod_6.0_setup.exe
#https://download.vismaspcs.se/downloads/visma_koncern_2021.0_setup.exe

$ver = 0


function download{
    
      
    while ($ver -ne 25) {
    try 
    {
    $setup = "_setup.exe"
    $webbadress = "https://download.vismaspcs.se/downloads/$visma$date.$ver$setup"
    $destination = "D:\Data\gemensam\data\Software\Visma\$visma$date.$ver$setup"
    $WebClient = New-Object System.Net.WebClient
    $WebClient.DownloadFile($webbadress,$destination)
    $ver++;
    write-host $webbadress laddades ner och lades under $destination
    
    }
    catch 
    {
    $ver++;
    }
}
}


$visma = "visma_bokslut_"
$date = Get-date -Format "yyyy"
download
Move-Item -path "D:\Data\gemensam\data\Software\Visma\*.exe" -Destination "D:\Data\gemensam\data\Software\Visma\Visma bokslut" -Force

$date = 0
$visma = "visma_byrastod_"
while ($date -le 10) {
try {
download
Move-Item -path "D:\Data\gemensam\data\Software\Visma\*.exe" -Destination "D:\Data\gemensam\data\Software\Visma\Visma byråstöd" 
$date++
}
catch {
$date++
}
}

$visma = "visma_koncern_"
$date = Get-date -Format "yyyy"
download
Move-Item -path "D:\Data\gemensam\data\Software\Visma\*.exe" -Destination "D:\Data\gemensam\data\Software\Visma\Visma koncern" -Force
