# Analisando a funcionalidade **Cadastro de Usuário** segundo a metodologia STRIDE

---
## S - Spoofing (Falsificação)

**a) Existe risco?**
R: Sim.
**b) Qual seria o risco?**
R: Um atacante pode tentar criar uma conta usando o endereço de e-mail ou identidade de outra pessoa.
**c) Que tipo de atacante se beneficiaria?**
R: Alguém que deseja se passar por outra pessoa para realizar ações fraudulentas, como obter acesso a informações confidenciais ou realizar compras não autorizadas.
---
## T - Tampering (Adulteração)

**a) Existe risco?**
R: Sim.
**b) Qual seria o risco?**
R: Um atacante pode tentar interceptar e modificar os dados enviados durante o processo de cadastro, como alterar o nome, endereço ou outras informações pessoais.
**c) Que tipo de atacante se beneficiaria?**
R: Alguém que deseja manipular os dados do usuário para fins maliciosos, como inserir informações falsas ou obter acesso não autorizado a recursos.
---
## R - Repudiation (Repúdio)

**a) Existe risco?**
R: Sim.
**b) Qual seria o risco?**
R: Um usuário pode negar ter realizado o cadastro, alegando que outra pessoa o fez em seu nome.
**c) Que tipo de atacante se beneficiaria?**
R: Alguém que deseja realizar ações ilegais ou fraudulentas e, posteriormente, negar a responsabilidade por elas.
---
## I - Information Disclosure (Divulgação de Informação)

**a) Existe risco?**
R: Sim.
**b) Qual seria o risco?**
R: Informações confidenciais fornecidas durante o cadastro, como nome, endereço, número de telefone ou senha, podem ser expostas a terceiros não autorizados.
**c) Que tipo de atacante se beneficiaria?**
R: Alguém que deseja roubar dados pessoais para fins de roubo de identidade, fraude financeira ou outros crimes.
---
## D - Denial of Service (Negação de Serviço)

**a) Existe risco?**
R: Sim.
**b) Qual seria o risco?**
R: Um atacante pode inundar o sistema com solicitações de cadastro falsas, sobrecarregando o servidor e impedindo que usuários legítimos se cadastrem.
**c) Que tipo de atacante se beneficiaria?**
R: Alguém que deseja interromper o serviço ou impedir que novos usuários se registrem.
---
## E - Elevation of Privilege (Elevação de Privilégio)

**a) Existe risco?**
R: Sim.
**b) Qual seria o risco?**
R: Um atacante pode explorar vulnerabilidades no processo de cadastro para obter acesso a privilégios administrativos ou outras áreas restritas do sistema.
**c) Que tipo de atacante se beneficiaria?**
R: Alguém que deseja obter controle total do sistema ou realizar ações que não seriam permitidas com uma conta de usuário normal.
---