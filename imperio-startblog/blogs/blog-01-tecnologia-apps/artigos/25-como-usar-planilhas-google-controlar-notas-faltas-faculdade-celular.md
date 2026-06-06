# Como usar planilhas do Google para controlar notas e faltas na faculdade pelo celular

Reprovar por falta é uma das piores formas de perder uma disciplina — especialmente quando você está perto do limite e não percebeu. O mesmo vale para notas: descobrir que a média final ficou abaixo do mínimo porque você não acompanhou as parciais ao longo do semestre é uma surpresa desagradável. Com uma planilha simples no Google Sheets, acessível pelo celular, você pode controlar suas notas e faltas em tempo real e nunca ser pego de surpresa. Neste artigo, você vai aprender a montar essa planilha do zero.

## Por que uma planilha é melhor que anotar em papel

Uma planilha digital tem várias vantagens sobre o papel para controlar notas e faltas. Ela calcula automaticamente médias e percentuais de frequência assim que você insere os dados, evitando erros de cálculo manual. Está sempre com você no celular. É atualizada em tempo real e acessível também no computador. E não se perde nem se molha.

O Google Sheets é a opção ideal para estudantes porque é completamente gratuito, funciona bem no celular Android e iPhone pelo app do Google Sheets (disponível nas lojas de apps) e sincroniza automaticamente com o Google Drive.

## Como criar a planilha de controle de notas

Acesse o Google Sheets pelo celular (ou pelo sheets.google.com no computador) e crie uma nova planilha. Dê o nome "Controle Acadêmico — Semestre".

Monte a seguinte estrutura em abas separadas (uma aba por disciplina ou uma aba geral):

**Aba de notas — estrutura sugerida:**

| Coluna A | Coluna B | Coluna C | Coluna D | Coluna E |
|----------|----------|----------|----------|----------|
| Disciplina | P1 | P2 | Trabalho | Média Final |

Para calcular a média final automaticamente, use uma fórmula simples. Por exemplo, se sua universidade usa a média aritmética de três notas, na célula E2 digite:
```
=AVERAGE(B2:D2)
```

Se a sua universidade usa pesos diferentes (por exemplo, P1 vale 30%, P2 vale 40% e trabalho 30%), use:
```
=(B2*0.3)+(C2*0.4)+(D2*0.3)
```

Insira uma linha para cada disciplina e a planilha vai calcular a média automaticamente quando você preencher as notas.

## Como criar o controle de faltas e frequência

Na mesma planilha, crie uma aba (ou uma tabela separada) para controle de faltas. A estrutura básica precisa de:

| Disciplina | Aulas Previstas | Faltas | Aulas Assistidas | Frequência % | Situação |
|-----------|-----------------|--------|-----------------|-------------|---------|

Para calcular a frequência automaticamente, na célula de "Frequência %":
```
=(D2/B2)*100
```
(Aulas assistidas dividido por aulas previstas, multiplicado por 100)

Para a coluna "Situação", você pode usar uma fórmula que indica automaticamente se você está acima ou abaixo do limite. Se a frequência mínima na sua faculdade é 75%:
```
=IF(E2>=75,"OK","ATENÇÃO!")
```

Isso faz a célula mostrar "OK" se a frequência estiver acima de 75% e "ATENÇÃO!" se estiver abaixo, funcionando como um alerta visual automático.

## Como atualizar a planilha pelo celular no dia a dia

A grande utilidade da planilha é que você pode atualizá-la imediatamente após cada aula. Quando você receber uma nota ou ao sair de uma aula, abra o Google Sheets no celular e atualize os dados.

Para inserir uma nota: abra a aba de notas, encontre a linha da disciplina, toque na célula correspondente e digite o valor. A média se recalcula automaticamente.

Para registrar uma falta: abra a aba de faltas, encontre a linha da disciplina e aumente o número de faltas em 1. A frequência se recalcula e a coluna de situação atualiza imediatamente.

Esse hábito de 30 segundos após cada aula mantém sua planilha sempre atualizada e você sempre ciente da sua situação acadêmica real.

## Dica extra: use formatação condicional para alertas visuais de cor

O Google Sheets tem um recurso chamado "formatação condicional" que muda automaticamente a cor de uma célula com base no seu valor. Para células de frequência, configure:
- Verde quando a frequência for maior que 80%
- Amarelo entre 75% e 80% (zona de atenção)
- Vermelho abaixo de 75% (risco de reprovação por falta)

Para configurar no celular: selecione a coluna de frequência, toque nos três pontos no canto superior direito, selecione "Formatação condicional" e configure as regras de cor. No computador, o caminho é Formatar > Formatação condicional.

Com essa configuração, você vê instantaneamente, com uma olhada na planilha, se alguma disciplina está em zona de risco — sem precisar verificar cada número individualmente.

## Conclusão

Uma planilha simples no Google Sheets com controle de notas e faltas é uma das ferramentas mais práticas que um universitário pode ter. Com fórmulas automáticas de média e frequência, alertas visuais por cor e a capacidade de atualizar pelo celular a qualquer momento, você mantém controle total da sua situação acadêmica em tempo real. Monte a planilha no início do próximo semestre, insira todas as disciplinas e comece a registrar as notas e faltas desde a primeira aula.

---
*Categoria: Produtividade*
*Palavras-chave: planilha google controle notas faculdade, controlar faltas google sheets, planilha frequência universitária, google sheets estudante*
