O modelo de responsabilidade da AWS é compartilhado: a AWS gerencia a segurança da **nuvem** (a infraestrutura), enquanto o cliente é responsável pela segurança **na nuvem** (os dados e as aplicações).
A **conta raiz (root)** é a conta de super privilégios. Ela deve ser usada apenas para tarefas administrativas muito específicas e de alta criticidade. Para o dia a dia, é essencial criar usuários com permissões específicas para cada necessidade.

O **IAM (Identity and Access Management)** é o serviço que permite gerenciar o acesso a todos os serviços e recursos da AWS. Suas práticas de segurança incluem:

* **Políticas de permissões:** Definir exatamente o que cada usuário ou grupo de usuários pode fazer.
* **Autenticação Multifator (MFA):** Adicionar uma camada extra de segurança para a conta raiz e para usuários privilegiados.
* **Gestão de Faturamento:** Monitorar o uso dos serviços e configurar alertas para evitar custos inesperados.

![BOOTCAMP SANTANDER CODE GIRLS (1)](https://github.com/user-attachments/assets/8a960887-3df9-4f2a-b636-625cbbd4a80a)
