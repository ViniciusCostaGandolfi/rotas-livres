## 📝 Descrição
## 🔗 Tarefa Relacionada
Closes #

## 🛠 Tipo de Mudança
- [ ] 🐛 Bug fix (correção de erro)
- [ ] ✨ Nova feature (funcionalidade nova)
- [ ] ♻️ Refatoração (melhoria de código sem mudar funcionalidade)
- [ ] 🏗 Infraestrutura (Docker, CI/CD, etc)

## ✅ Checklist do Desenvolvedor (Definition of Done)
- [ ] O código compila sem erros.
- [ ] Removi comentários desnecessários e `System.out.println`.
- [ ] Testei a funcionalidade localmente.
- [ ] O código segue a arquitetura definida (Controller -> Service -> Repository).

## 🧪 Como testar
1. Subir o docker-compose.
2. Enviar uma requisição POST para `/api/v1/rota`.
3. Verificar se a mensagem chegou no RabbitMQ.