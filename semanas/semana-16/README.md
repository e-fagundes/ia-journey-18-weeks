# Plano de Estudos de Inteligência Artificial
> **Formato:** 1 h por dia útil (segunda → sexta)  
> **Duração:** 18 semanas (Semana 0 opcional + 1 → 17)  
> Use as caixas de seleção para acompanhar o progresso.

## Semana 16 — Chaos Engineering aplicado a ML
- **Dia 1**  
  - [ ] Fundamentos (case Netflix)  
    - 🆓 <https://www.gremlin.com/chaos-engineering/>  
    - 💰 <https://www.oreilly.com/library/view/chaos-engineering/9781492043865/>
- **Dia 2**  
  - [ ] Chaos Mesh — injetar falhas  
    - 🆓 <https://chaos-mesh.org/>
- **Dia 3**  
  - [ ] Observabilidade (Prometheus + Grafana)  
    - 🆓 <https://prometheus.io/docs/introduction/overview/>
- **Dia 4**  
  - [ ] Experimento “pod kill” em Minikube  
    - 🆓 <https://minikube.sigs.k8s.io/docs/start/>
- **Dia 5**  
  - [ ] Documentar métricas antes/depois  
    - 🆓 <https://docs.google.com/forms>

> 🔬 **Laboratório opcional — Semana 16**  
> Rodar serviço FastAPI (Sem 13) em Minikube e derrubar 20 % dos pods; avaliar SLO.

---

## Dicas Gerais
- **Matemática:** Canal Professor Ferretto + Anki.  
- **Python:** `pre-commit` com **black** e **ruff**.  
- **pandas:** comece por `df.info()` e `df.describe()`.  
- **Visualização:** 1 gráfico = 1 mensagem (Plotly para dashboards).  
- **ML:** valide baseline simples antes de usar modelos complexos.  
- **CV:** converta BGR → RGB antes de exibir no Matplotlib.  
- **NLP:** salve pipelines spaCy com `nlp.to_disk()`.  
- **IA Generativa:** ajuste *temperature* e *top-p* ao experimentar.  
- **Git/MLOps:** branches `feature/`, `bug/`, `experiment/`; squash merge.  
- **Spaced-repetition:** 10 min na sexta para revisar decks Anki.