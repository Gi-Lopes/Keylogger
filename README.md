# Keylogger
O presente projeto trata-se de um estudo acerca do funcionamento do Keylogger, um malware. Seu funcionamento ocorre a partir de um arquivo em extensão .bat que abre um arquivo 
falso para distrair o usuário enquanto um programa malicioso roda em segundo plano.

- O arquivo .bat serve apenas para inicializar o arquivo "malware".exe (código do malware compilado e funcional em um arquivo executável) ao mesmo tempo que 
inicializa outro programa para distrair o usuário (pode ser um jogo, um documento em pdf, etc.)
  - No nosso caso, colocamos o arquivo de um jogo (windowsframe.exe) para tal finalidade distrativa.
- O código do malware não foi programado para abrir qualquer janela, logo, só é possível finalizar sua execução através do gerenciador de tarefas
- O malware captura todas as teclas digitadas pelo usuário, além de anotar a aba acessada e o horário de digitação
- Os dados não são enviados para terceiros ou divulgados, mas são salvos em um documento na própria máquina

#ATENÇÃO: O projeto em questão não possui fins maliciosos, nem deve ser usado para tal. 
