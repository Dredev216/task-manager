# task-manager
 Um expansivo gestor de tarefas para colaboração de trabalho

Pretende-se criar uma aplicação para gestão das tarefas de uma empresa. O sistema conta com as seguintes
especificações :

O administrador pode:
    Cadastrar funcionários
    Criar tarefas
    Eliminar tarefas
    Atualizar tarefas
    Listar todas as tarefas
    Atribuir tarefa a um funcionário

Os funcionários podem:
    Fazer o login na aplicação
    Visualizar todos tarefas a ele atribuído
    Modificar o estado da tarefa (finalizar ou não finalizar)

As tarefas são compostas por:
    Descrição
    Nível de importância (baixo, médio, alto)
    Estado (não atribuída, em espera, não finalizada e finalizada)
    Data de criação
    
Estados das tarefas:
    Não atribuída: Estado inicial de uma tarefa criada
    Em espera: Uma tarefa apenas atribuída a um funcionário que ainda não finalizou
    Finalizada: Tarefa que foi feita com sucesso
    Não finalizada: Uma tarefa que não foi concluída