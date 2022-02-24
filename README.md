# kali-nethunter
Este é um script pelo qual você pode instalar o Kali nethunter (Kali Linux) em seu aplicativo termux sem telefone enraizado

Etapas para instalação
Baixar script em HOME curl -LO 
https://github.com/Mundoprogramador/kali-nethunter
Dê permissão de execução
chmod +x kalinethunter
Executar script./kalinethunter


#Uso
1- Use o comando startkalipara iniciar o nethunter. O usuário padrão é kali e a senha padrão também é kali .
2- se você deseja iniciar o nethunter como usuário root, use o comando startkali -r.

#Guia VNC
01-Para iniciar uma sessão vncvnc start
02- Para parar uma sessão vncvnc stop
03- Para verificar o status (exibição e número da porta) da sessão vncvnc status
04- Se o usuário for kali , por padrão vnc start, iniciará o vncserver com DISPLAY=:2& PORT=5902e para o usuário root DISPLAY=:1&PORT=5901


