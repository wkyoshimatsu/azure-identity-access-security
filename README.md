# Resumo sobre Identidade, Autenticação e Segurança no Azure - Certificação AZ-900

Este documento contém um resumo dos principais conceitos relacionados a **serviços de identidade, autenticação e segurança no Azure**, com foco na certificação Microsoft Azure Fundamentals (AZ-900).

## 📌 Serviços de Diretório no Azure
O **Microsoft Entra** fornece soluções de identidade e acesso na nuvem. Os principais serviços incluem:

- **Microsoft Entra ID:** Serviço de gerenciamento de identidade e acesso na nuvem que fornece autenticação segura para usuários e aplicativos.
- **Microsoft Entra Domain Services:** Permite que organizações usem domínios gerenciados com suporte a autenticação Kerberos, NTLM e LDAP sem a necessidade de controladores de domínio locais.

## 🔑 Métodos de Autenticação
O Azure oferece diferentes métodos de autenticação para garantir segurança e acessibilidade:

- **SSO (Logon Único):** Permite que os usuários acessem vários aplicativos e serviços sem precisar fornecer credenciais repetidamente.
- **MFA (Autenticação Multifator):** Adiciona uma camada extra de segurança exigindo múltiplos fatores de verificação, como senha e código enviado ao celular.
- **Acesso sem senha:** Suporta métodos como Windows Hello, autenticação biométrica e chaves de segurança.

## 🌍 Identidades Externas e Acesso de Convidado
O **Microsoft Entra ID** possibilita o gerenciamento de identidades externas e o acesso de convidados:

- **Usuários Convidados:** Permitem que usuários de outras organizações acessem recursos no Azure sem precisar criar novas contas.
- **Federação de Identidade:** Integra identidades de terceiros como Google, Facebook ou outros provedores.

## 🚦 Acesso Condicional do Microsoft Entra
O acesso condicional ajuda a controlar **quem, quando e como** os usuários podem acessar os serviços no Azure:

- **Políticas Baseadas em Risco:** Bloqueiam ou exigem autenticação adicional dependendo do risco detectado.
- **Requisitos de MFA:** Podem ser ativados com base na localização, dispositivo ou função do usuário.

## 🛡️ RBAC (Controle de Acesso Baseado em Função)
O **Role-Based Access Control (RBAC)** permite que as organizações atribuam permissões específicas aos usuários:

- **Definição de Papéis:** Usuários recebem apenas as permissões necessárias para realizar suas tarefas.
- **Escopo de Acesso:** Permissões podem ser aplicadas a assinaturas, grupos de recursos ou objetos individuais.

## 🔒 Conceito de Confiança Zero
O modelo de **Confiança Zero (Zero Trust)** assume que nenhuma identidade ou dispositivo é confiável por padrão:

- **Verificação Contínua:** Cada solicitação de acesso deve ser validada e autenticada.
- **Menor Privilégio:** Usuários só têm acesso aos recursos estritamente necessários.

## 🏰 Modelo de Defesa em Profundidade
O conceito de **Defesa em Profundidade** envolve camadas múltiplas de segurança para proteção contra ameaças:

- **Proteção de Identidade:** Uso de MFA e acesso condicional.
- **Proteção de Redes:** Firewalls e segmentação de rede.
- **Proteção de Dados:** Criptografia e backups seguros.

## 🔎 Microsoft Defender para Nuvem
O **Microsoft Defender para Nuvem** ajuda na proteção de recursos do Azure contra ameaças:

- **Monitoramento Contínuo:** Detecta vulnerabilidades e ataques em tempo real.
- **Recomendações de Segurança:** Sugere melhorias de configuração para fortalecer a segurança.

## 🎯 Recursos úteis para certificação AZ-900
- [Microsoft Learn - Curso Oficial](https://learn.microsoft.com/pt-br/certifications/azure-fundamentals/)
- [Documentação do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Simulados e materiais de apoio](https://www.examtopics.com/exams/microsoft/az-900/)

📌 **Última atualização:** Junho de 2025.
