# Comandos

**1. Versão do Kernel**:
``` uname -r ``` </br> </br>
**2. GUI atual**:
``` env |grep CURRENT_DESKTOP ``` </br> </br>
**3. Usuário ADM**:
``` sudo su / su - ``` </br> </br>
**4. Criar diretório**: 
``` mkdir ``` </br> </br>
**5. Remover diretório**:
``` rmdir / rm -r ``` </br> </br>
**6. Criar arquivo**:
``` touch ``` </br> </br>
**7. Acessar arquivo**:
``` cat / less ``` </br> </br>
**8. Copiar arquivo/diretório**:
``` cp / cp -r (diretório) ``` </br> </br>
**9. Mover ou Renomear arquivo/diretório**:
``` mv / mv -r (diretório) ``` </br> </br>
**10. Criar um link simbólico (atalho)**:
``` ln -s ``` </br> </br>
**11. Agrupar arquivos**:
``` tar cf <nome> * ``` </br> </br>
**12. Listar os arquivos agrupados**:
``` tar tf <nome> ``` </br> </br>
**13. Extrair os arquivos agrupados**:
``` tar xf <nome> ``` </br> </br>
**14. Compactar arquivos agrupados**:
``` gzip <nome> ``` </br> </br>
**15. Compactar arquivos agrupados (sobrepoe)**:
``` gzip <nome> ``` </br> </br>
**16. Compactar arquivos agrupados (mantém)**:
``` gzip -k <nome> ``` </br> </br>
**17. Descompactar arquivos agrupados**:
``` gzip -d <nome> / gunzip <nome> ``` </br> </br>
**18. Localizar arquivos**:
``` find / locate / whereis ``` </br> </br>
**19. Editores de texto no terminal**:
``` nano / vi ``` </br> </br>
**20. Informações sobre processos**:
``` ps -u / ps -ux / ps -uxa (todos os users) ``` </br> </br>
**21. Listar os tipos de sinais para matar processos**:
``` kill -l ``` </br> </br>
**22. Mostrar o PID (Process ID)**:
``` pgrep <app> ``` </br> </br>
**23. Matar o processo**:
``` kill <PID> / kill -s SIGHUP <PID> / kill -SIGHUP <PID> / kill -9 <PID> ``` </br> </br>
**24. Matar todos os processos filtrados**:
``` killall <app> ``` </br> </br>
**25. Start/Stop/Restart um serviço**:
``` systemctl stop/start/restart <servico> ``` </br> </br>
**26. Rodar processos em foreground/background**:
``` <processo> (foreground) / <processo> & (background) ``` </br> </br>
**27. Adicionar/Remover permissão de leitura/escrita/execução de arquivos**:
``` chmod u(user) /  g(group) / o(other) / a(all) +/- r(read) / w(write) / x(execute) ``` </br> </br>
**28. Editar dono do arquivo**:
``` chown <user> <arquivo> ``` </br> </br>
**29. Editar grupo do arquivo**:
``` chown :<grupo> <arquivo> ``` </br> </br>
**30. Editar grupo e dono do arquivo**:
``` chown <user>:<grupo> <arquivo> ``` </br> </br>
**31. Criar/Remover/Editar user**:
``` useradd -m <nome> (Criar) / userdel -r <nome> (Remover) / usermod -c " " <campo> (Editar) ``` </br> </br>
**32. Visualizar qual o user atual/id**: 
``` whoami / id ``` </br> </br>
**33. Adicionar novo grupo**: 
``` addgroup <nome> ``` </br> </br>
**34. Remover grupo**: 
``` groupdel <nome> ``` </br> </br>
