# Remote Run Manager - demo

An offline demo of Remote Run Manager, a web app where ICT teams run their own signed PowerShell scripts against a computer.

**Open the demo:** https://timmahood.github.io/RRManager-Demo/

Everything runs in your browser on sample data. No scripts are run and nothing is sent anywhere. Use **View as** at the top of the page to see the app as an app admin, a script owner, an area executor (Service Desk, On Call), or someone with no access.

Try the **One computer / Several computers** switch at the top of an area page: pick the saved group *Ward 5A PCs*, or the AD group *SG-Devices-Outpatients-Kiosks*, press **Check all**, then **Run** a script to watch it work through the computers.

Script options: as the Service Desk executor, run **Get-VoipNumberOwner**. It needs no target computer (it looks a phone number up on the server), its form checks the number before running, and **Site** offers suggested values. Other scripts show drop-downs, ranges and the command the options add up to.

All team names, computers, accounts and groups are made up.
