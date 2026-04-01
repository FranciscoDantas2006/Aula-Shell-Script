# Aula-Shell-Script
Atividade - Shell Script para Automação

# Sistema de Gerenciamento via Shell Script
Este projeto consiste em um script interativo desenvolvido em Bash para facilitar tarefas comuns de administração de sistemas Linux, como monitoramento de recursos, atualização de pacotes e testes de conectividade.

# Funcionalidades
O script oferece um menu interativo com as seguintes opções:
1. Monitorar uso de disco: Exibe as partições do sistema e o espaço utilizado/disponível.
2. Listar usuários logados: Mostra em tempo real quais usuários estão conectados à máquina.
3. Atualizar sistema: Executa a sincronização dos repositórios e a atualização dos pacotes (requer privilégios de sudo).
4. Verificar site online: Permite ao usuário digitar uma URL para testar se o servidor está respondendo via comando ping.
5. Sair: Encerra a execução do script com segurança.

# Como Executar
Pré-requisitos
• Sistema Operacional Linux / Virtual Box.
• Interpretador Bash instalado.

Passo-a-passo
1. Clonar ou criar o arquivo:
Crie um arquivo chamado AulaShell.sh e cole o código fonte.

2. Dar permissão de execução:
No terminal, execute o comando:
"chmod +x AulaShell.sh"
Nota: Se receber erro de permissão negada, utilize "sudo chmod +x AulaShell.sh."

3. Rodar o script:
./AulaShell.sh

Tecnologias Utilizadas
Bash: Linguagem de script.

Comandos Linux: df, who, apt, ping, read e estruturas de controle como while e case.

Desenvolvido como parte da disciplina DEVOPS do Prof. Renato William.
   
