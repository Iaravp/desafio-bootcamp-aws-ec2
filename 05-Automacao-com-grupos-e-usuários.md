A automação é fundamental para gerenciar recursos na nuvem de forma eficiente. No IAM, os **grupos de usuários** são uma forma poderosa de automatizar a gestão de permissões. Em vez de atribuir políticas a usuários individualmente, você as atribui a um grupo, e todos os usuários que pertencem a ele herdam essas permissões. Isso simplifica o processo de onboarding de novos colaboradores e a manutenção de permissões.

O passo a passo para a automação com grupos de usuários inclui:

1.  **Criação do Grupo:** Defina um nome para o grupo (ex: 'Desenvolvedores', 'Administradores').
2.  **Anexação de Políticas:** Atribua políticas de permissão ao grupo (ex: permissão para criar instâncias EC2).
3.  **Adicionar Usuários:** Adicione os usuários a este grupo.

As **Instâncias EC2** são a espinha dorsal da computação na AWS. Elas são essencialmente **máquinas virtuais** que você pode configurar para rodar o que precisar, como servidores web, bancos de dados ou qualquer outra aplicação.

![BOOTCAMP SANTANDER CODE GIRLS (3)](https://github.com/user-attachments/assets/05e75b83-5df2-42fb-9ed5-30d63f7674ad)
