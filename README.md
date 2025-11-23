
# Apresentação do Projeto – Sistema de Curadoria

## Slide 1 – Título
**Sistema de Curadoria de Recursos Digitais**  
Projeto acadêmico – Java + MySQL

---

## Slide 2 – Contextualização (Por quê?)
**Problema:** falta de uma plataforma simples para que usuários possam cadastrar, organizar e gerenciar recursos digitais.  
**Objetivo:** criar um sistema de curadoria com login, cadastro de usuários e registros de recursos.  
**Público-alvo:** pessoas que precisam organizar materiais de estudo e conteúdo técnico.  
**Justificativa:** promove organização, categorização e registro de autoria.

---

## Slide 3 – Escopo do Projeto
- Sistema desktop desenvolvido em Java (Swing).  
- Banco de dados MySQL.  
- Módulos: autenticação, gestão de usuários, cadastro e listagem de recursos.  
- Restrições: usuários podem cadastrar apenas até dois interesses.

---

## Slide 4 – Tecnologias Utilizadas
- **Java 17**  
- **Swing** para interface gráfica  
- **JDBC** para conexão com banco  
- **MySQL 8**  
- **Git/GitHub** para versionamento  
- **IDE:** NetBeans ou IntelliJ

---

## Slide 5 – Funcionalidades
- Login e autenticação  
- Cadastro de usuários  
- Controle de ativação/inativação  
- Cadastro de recursos (título, autor, categoria)  
- Listagem de recursos por usuário

---

## Slide 6 – POO Aplicado
- Classes: `Usuario`, `Recurso`  
- Encapsulamento: getters e setters  
- Polimorfismo visualizado no uso de DAOs  
- Organização modular (DAO, Models, Interface)

---

## Slide 7 – Banco de Dados
Tabelas:  
- **usuarios**  
- **usuario_interesses**  
- **recursos**  
Relacionamentos via *foreign keys*.

---

## Slide 8 – Demonstração (O quê?)
- Tela de login  
- Painel de administração  
- Cadastro de usuários  
- Telas de cadastro/listagem de recursos  
*(Vídeo de apoio deve ser preparado)*

---

## Slide 9 – Status Atual
- Todas as funcionalidades principais implementadas.  
- Sistema executável e funcional.  
- Possíveis melhorias futuras.

---

## Slide 10 – Reflexões Finais
**Aprendizados:**  
- Conexão Java + MySQL  
- Estrutura MVC simplificada  
- Boas práticas de POO  

**Dificuldades:**  
- Tratamento de erros SQL  
- Integração da interface com o DAO  

**Futuro:**  
- CRUD completo com edição de recursos  
- Dashboard de estatísticas  
- Interface mais moderna

---

## Slide 11 – Finalização
**Entrega:**  
- PowerPoint  
- Repositório GitHub  
- Documentação completa