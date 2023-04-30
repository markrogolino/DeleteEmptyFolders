Get-ChildItem -Path "E:\" -Recurse | Where-Object {$_.PSIsContainer -and @(Get-ChildItem $_.FullName -Force).Count -eq 0} | Remove-Item -Recurse
