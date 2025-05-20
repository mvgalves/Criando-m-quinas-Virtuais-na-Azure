# 💻 Criação de Máquina Virtual na Microsoft Azure

Este repositório contém anotações, resumos e dicas práticas sobre o processo de criação e configuração de máquinas virtuais na plataforma Microsoft Azure. O conteúdo foi desenvolvido como parte do desafio prático da DIO.

---

## 🔧 Etapas Realizadas

1. **Criação da conta na Azure**  
   Acesse [portal.azure.com](https://portal.azure.com/) e registre-se com uma conta Microsoft. A plataforma geralmente oferece um crédito gratuito inicial para novos usuários.

2. **Acesso ao portal Azure**  
   Após o login, você será direcionado ao painel principal do Azure. É possível visualizar recursos, criar novos serviços e gerenciar tudo a partir deste painel.

3. **Criação de um recurso de máquina virtual**  
   No menu lateral ou na barra de pesquisa, clique em "Máquinas virtuais" e depois em "Criar". Escolha "Máquina Virtual do Azure".

4. **Configuração da VM (SO, tamanho, autenticação, regras de porta)**  
   - Escolha o sistema operacional (por exemplo, Windows ou Ubuntu).
   - Defina o tamanho da máquina (CPU, memória).
   - Escolha o método de autenticação (senha ou chave SSH).
   - Abra portas de acesso, como a 22 (SSH) ou 3389 (RDP), conforme necessário.

5. **Acesso remoto via RDP ou SSH**  
   - Para Windows: use o Remote Desktop Protocol (RDP).
   - Para Linux: acesse via SSH usando terminal ou ferramentas como PuTTY.

6. **Gerenciamento básico (iniciar, parar, reiniciar)**  
   A partir do portal, é possível iniciar, parar, reiniciar ou excluir a VM conforme sua necessidade.

7. **Remoção de recursos**  
   Para evitar custos, exclua a VM e o grupo de recursos ao finalizar os testes.

---

## 🧠 Conceitos Importantes

- **O que é uma máquina virtual?**  
  É um ambiente de computação emulado que funciona como um computador físico, permitindo a execução de aplicações e serviços de forma isolada.

- **Diferenças entre RDP e SSH**  
  - RDP (Remote Desktop Protocol): utilizado para acessar máquinas Windows com interface gráfica.  
  - SSH (Secure Shell): utilizado para acessar máquinas Linux via linha de comando com segurança.

- **Regiões e disponibilidade**  
  Os recursos da Azure são distribuídos por regiões globais. Escolher uma região próxima ao seu público-alvo melhora a performance e a latência.

- **Grupos de recursos**  
  Permitem agrupar recursos relacionados para facilitar o gerenciamento e a organização. Excluir um grupo remove todos os recursos associados.

- **Tamanho da VM e cobrança**  
  O custo da VM depende do tamanho escolhido (quantidade de vCPUs e RAM) e do tempo de execução. VMs menores são mais baratas e ideais para testes.

---

## 📝 Dicas Úteis

- Use **tags** para organizar os recursos
- Verifique os custos estimados antes de criar a VM
- Crie **grupos de recursos** para facilitar a exclusão posterior
- Encerre a VM quando não estiver utilizando para **evitar cobranças**
- Utilize a calculadora de preços da Azure para estimar gastos: https://azure.microsoft.com/pt-br/pricing/calculator/

---

## 📚 Fontes e Referências

- [Portal da Microsoft Azure](https://portal.azure.com/)
- [Documentação Oficial](https://learn.microsoft.com/pt-br/azure/)
- Curso da [DIO - Digital Innovation One](https://web.dio.me/)

---

## 🚀 Autor

Desenvolvido por Marcus Vincius
