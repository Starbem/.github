# 🚀 Descrição

> Explique de forma objetiva o que foi feito. Seja claro e direto ao ponto.  
> Exemplo: "Adiciona endpoint para criação de pedidos", "Corrige bug de exibição do modal no checkout".

---

# 📚 Contexto

> Qual o problema ou necessidade que essa PR resolve?  
> Inclua contexto de negócio, técnico, ou links de documentação quando relevante.  
> Exemplo: "Essa feature é necessária para permitir que o usuário finalize a compra com pagamento via PIX".

---

# ✅ Checklist

- [ ] Testado localmente e funcionando conforme esperado
- [ ] Cobertura de testes unitários/mocks (se aplicável)
- [ ] Testes de integração/E2E (se aplicável)
- [ ] Documentação atualizada (código ou Wiki, se aplicável)
- [ ] Logs de debug removidos
- [ ] Nome das variáveis e funções revisados (clareza e padrão)
- [ ] Analisado impacto em performance (se aplicável)
- [ ] Tratamento de erros e exceções adicionado
- [ ] Linter/Prettier rodando sem erros
- [ ] Revisão de segurança (se aplicável)
- [ ] Versão/Changelog atualizado (se necessário)

---

# 🎥 Evidências (Prints, GIFs ou Vídeos)

> Inclua imagens, vídeos ou GIFs mostrando a funcionalidade funcionando ou o problema resolvido.  
> Se não for aplicável (ex: alteração de backend puro), explicar por que não tem evidência visual.

---

# 🧪 Como testar?

> Passo a passo para o revisor testar a alteração localmente (ex: comandos, dados de exemplo, fluxo de navegação).  
> Exemplo:
>
> 1. Rodar o backend com `make run`
> 2. Acessar rota `/api/orders`
> 3. Realizar POST com payload `{ "product": "pizza", "quantity": 1 }`
> 4. Verificar resposta `200 OK`

---

# ⚙️ Informações técnicas

> Detalhes técnicos importantes: decisões de arquitetura, bibliotecas novas, alterações sensíveis.  
> Exemplo: "Adicionada lib Axios para requisições HTTP", "Refatorado serviço de autenticação para JWT".

---

# 🧩 Issue Relacionada

Closes #{Número da Issue}

> Ou relacione: "Relacionado a #{Número da Issue}"

---

# ⚠️ Riscos

> Algum risco relevante dessa alteração? Impacta outras áreas do sistema?  
> Exemplo: "Pode impactar o checkout se o serviço de pedidos falhar".

---

# 🩹 Plano de rollback

> Caso precise reverter, o que fazer? Existe feature flag?  
> Exemplo: "Desabilitar via feature flag `enable-new-checkout`", "Reverter commit `abc123`".

---

# 💡 Notas adicionais

> Alguma consideração final, dúvidas, ou pontos de atenção?  
> Exemplo: "Essa é a primeira parte da feature X, outras partes virão em PRs separadas".
