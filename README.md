# Gabriel Januário

**Análise de Negócios e Operações · Melhoria de Processos · Digitalização Industrial**

Tenho mais de 13 anos de experiência na indústria metalmecânica, do chão de fábrica ao Planejamento, Programação e Controle da Produção (PPCP). Com as áreas operacionais e a liderança, defino regras de negócio, concilio dados de planejamento e execução e construo indicadores para decisões de capacidade, sequenciamento e prazo.

[LinkedIn](https://linkedin.com/in/gabriel-janu%C3%A1rio1) · [Case PULSO](https://github.com/gabriel-januario/pulso) · [Demonstração interativa](https://gabriel-januario.github.io/pulso/)

## Entregas profissionais

- **Controle da produção.** Implantei um controle de produção digital para rastrear o programado e o realizado. O processo implantado foi aprovado pelo Sistema de Gestão da Qualidade (SGQ).
- **Conciliação de dados e indicadores.** Cruzei a programação com os apontamentos do ERP Senior e desenvolvi indicadores de carga, capacidade e aderência à programação para análise de desvios com as áreas operacionais.

## PULSO · Análise de desempenho da usinagem

Desenvolvi um protótipo funcional para responder a uma pergunta de PPCP: **qual grupo de máquinas investigar antes da próxima reunião de carga?** O PULSO cruza apontamentos de produção, calendário fabril e escalas para calcular capacidade, utilização e perdas. A análise vai do indicador consolidado aos registros por máquina.

| Etapa | Como tratei no PULSO |
|---|---|
| Modelagem do processo | Defini o dia produtivo das 06h às 06h e a capacidade fixa a partir dos turnos validados, das horas líquidas e da disponibilidade cadastrada. |
| Regras de cálculo | Consolidei intervalos simultâneos na mesma máquina e separei a produção em turno regular da hora extra no cálculo da utilização. |
| Critérios de validação | Documentei as fórmulas e os casos de exceção. A suíte automatizada verifica, entre outros pontos, se os destinos da capacidade somam a capacidade fixa e se os totais do Excel fecham com o motor de cálculo. |

O protótipo roda no navegador com React, TypeScript e SQLite. A demonstração usa uma base transformada e permite investigar a utilização de um grupo, comparar máquinas e conferir os apontamentos antes de atribuir uma causa ao desvio.

[Roteiro da demonstração](https://github.com/gabriel-januario/pulso#roteiro-de-demonstra%C3%A7%C3%A3o) · [Regras de negócio](https://github.com/gabriel-januario/pulso/blob/main/docs/REGRAS-DE-NEGOCIO.md) · [Testes](https://github.com/gabriel-januario/pulso/tree/main/tests)

## Ferramentas, formação e certificação

**Dados e indicadores** · Excel, Power Query e Power BI  
**Planejamento e sistemas industriais** · Spider Project, Microsoft Project, ERP Senior e vivência operacional com APS/MES  
**Formação e certificação** · Tecnólogo em Gestão da Produção Industrial pela FATEC Sertãozinho · Professional Scrum Master I (PSM I)
