# curl

> W PowerShell to polecenie może być aliasem `Invoke-WebRequest`, gdy oryginalny program `curl` (<https://curl.se>) nie jest poprawnie zainstalowany.
> Więcej informacji: <https://learn.microsoft.com/powershell/module/microsoft.powershell.utility/invoke-webrequest>.

- Zobacz dokumentację oryginalnego polecenia `curl`:

`tldr curl -p common`

- Zobacz dokumentację polecenia PowerShell `Invoke-WebRequest`:

`tldr invoke-webrequest`

- Zweryfikuj, czy `curl` jest poprawnie zainstalowany poprzez sprawdzenie jego wersji. Jeśli to polecenie zwraca błąd, PowerShell mógł je zastąpić poleceniem `Invoke-WebRequest`:

`curl --version`
