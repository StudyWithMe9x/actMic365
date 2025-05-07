$Path = "$($env:USERPROFILE)\Downloads"; $Installer = "Ohook_Activation_AIO.cmd"; $ProgressPreference = 'SilentlyContinue'; Invoke-WebRequest "https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/Separate-Files-Version/Activators/Ohook_Activation_AIO.cmd" -OutFile $Path\$Installer;
<#Expand-Archive $Path\active.zip -DestinationPath $Path\active#>


start $Path\Ohook_Activation_AIO.cmd
