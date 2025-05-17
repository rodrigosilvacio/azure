Passo a passo para criação do Azure Data Factory (ADF) pelo portal do Azure:


1. Acesse o Portal do Azure

 Acesse: [https://portal.azure.com](https://portal.azure.com)
 Faça login com sua conta.

2. Crie um novo recurso

 No menu esquerdo, clique em "Criar um recurso".
 Em seguida, pesquise por "Data Factory" na barra de busca.
 Clique em "Data Factory" nos resultados e depois em "Criar".

3. Preencha os dados básicos

Na aba "Informações básicas", preencha os seguintes campos:

| Campo                    | Descrição                                                         |
| ------------------------ | ----------------------------------------------------------------- |
| Assinatura               | Selecione a assinatura do Azure que será usada.                   |
| Grupo de Recursos        | Selecione um existente ou crie um novo.                           |
| Nome da Fábrica de Dados | Defina um nome único para o ADF.                                  |
| Região                   | Escolha a região mais próxima de onde os dados serão processados. |
| Versão                   | Escolha V2, que é a versão atual.                             |

Clique em "Avançar: Git Configuration >".

4. Configuração de Git (opcional)

 Você pode configurar um repositório Git (Azure DevOps ou GitHub).
 Se não quiser configurar agora, selecione "Configure mais tarde".

Clique em "Avançar: Revisar + criar".

5. Revisar e Criar

 Revise todas as configurações.
 Clique em "Criar" para iniciar a implantação.

Aguarde alguns minutos até a criação ser concluída.

6. Acessar o Data Factory

Após a implantação:

 Clique em "Ir para o recurso".
 Clique em "Iniciar Studio" para abrir o ADF Studio, a interface web de desenvolvimento.

7. O que fazer a seguir no ADF Studio

Com o Data Factory criado, você pode:

 Criar pipelines de ETL.
 Criar e configurar Linked Services (conexões com fontes/destinos de dados).
 Criar Datasets.
 Usar Triggers para agendamento.
 Testar e publicar seu fluxo de dados.
