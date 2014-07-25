#Invoke-VoiceTextWebAPI

for using the  [VoiceText Web API beta](https://cloud.voicetext.jp/)  for PowerShell.

## Set Execution Policy

run the following command as Administrator.

```
Set-ExecutionPolicy RemoteSigned
```

## Module Import
### PowerShell 3.0- ( Win8 - )

make one of the following directory, and put Invoke-VoiceTextWebAPI.psm1

```
$env:USERPROFILE\Documents\WindowsPowerShell\Modules\Invoke-VoiceTextWebAPI\Invoke-VoiceTextWebAPI.psm1
C:\Program Files\WindowsPowerShell\Modules\Invoke-VoiceTextWebAPI\Invoke-VoiceTextWebAPI.psm1
C:\WINDOWS\system32\WindowsPowerShell\v1.0\Modules\Invoke-VoiceTextWebAPI\Invoke-VoiceTextWebAPI.psm1
```

### PowerShell - 2.0 ( Win7 and other old Windows OS )

run the following in addition to the PS 3.0-

```
Import-Module Invoke-VoiceTextWebAPI
```

## Usage

```
PS C:\> Invoke-VoiceTextWebAPI -APIKey [YourAPIKey]: -Text いかの足10本！ -OutFile C:\ika.wav -Speaker hikari -Emotion anger -EmotionLevel 2 -Pitch 125 -Speed 125 -Volume 125
```
   
## License
Copyright (c) 2014 ikaikaika. Licensed under the MIT license.
