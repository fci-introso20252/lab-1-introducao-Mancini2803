# 📝 Relatório do Laboratório 1 - Introdução ao Linux

**Nome:** [Matheus Mancini]  
**RA:** [10742794]  

---

## 💡 Orientações Importantes
Este relatório é sua oportunidade de documentar não apenas o que você fez, mas principalmente o que você aprendeu. Como temos apenas um encontro semanal, é importante que você seja o(a) protagonista do seu aprendizado.

Para elaborar um relatório completo e que realmente agregue valor ao seu aprendizado, siga estas dicas:

- 📚 **Vá além do repositório**: Os materiais fornecidos são apenas o ponto de partida. Busque vídeos no YouTube, tutoriais, documentações oficiais e artigos que expliquem os conceitos de diferentes perspectivas.
- 🔍 **Seja curioso**: Quando encontrar um comando novo, não apenas execute-o - entenda o que ele faz, suas opções e em que situações reais ele é utilizado.
- 💭 **Conecte com a realidade**: Pesquise como empresas como Netflix, Google e Amazon utilizam Linux em seus servidores. Isso tornará o aprendizado mais tangível e relevante para sua carreira.
- 🎯 **Pratique além do lab**: Instale uma VM em casa, experimente distribuições diferentes, quebre coisas e conserte - é assim que se aprende de verdade!
- 🤝 **Compartilhe conhecimento**: Encontrou um tutorial bacana? Um comando útil? Compartilhe com seus colegas! O aprendizado colaborativo acelera o desenvolvimento de todos.

- **Lembre-se**: Em TI, a capacidade de aprender por conta própria é tão importante quanto o conhecimento técnico. Use este laboratório como uma oportunidade para desenvolver ambas as habilidades. Profissionais que sabem buscar, filtrar e aplicar informações são os mais valorizados no mercado!

## 1️⃣ Parte 1 - Experiência com Comandos Básicos

### 🔍 Primeiras Impressões

**1. Qual foi o comando mais útil que você aprendeu? Por quê?**

```
O comando mais útil foi o **grep**. Ele vai além da simples visualização de arquivos (como o cat) e permite a busca e filtragem rápida de conteúdo específico em um ou múltiplos arquivos. Para encontrar logs de erro ou configurações dentro de uma estrutura grande de diretórios, o grep é indispensável, economizando muito tempo na análise de dados.
```

**2. Qual comando você achou mais difícil de entender? Por quê?**

```
A utilização correta do **redirecionamento (>, >>)** e do **pipe (|)** foi, inicialmente, o ponto mais complexo. Entender que o pipe conecta a **saída** de um comando à **entrada** do próximo, e que o redirecionamento envia a saída para um arquivo, exige uma mudança de mentalidade sobre como o fluxo de dados se move no shell.

```

**3. Você conseguiu completar todos os exercícios? Se não, quais dificuldades encontrou?**

```
Sim, consegui completar todos os exercícios. Mas a minha principal dificuldade inicial foi garantir que os caminhos relativos estivessem corretos, especialmente ao navegar entre diretórios usando `cd ..` e referenciando arquivos no diretório `outputs/` a partir de outras pastas. Foi necessário revisar várias vezes os comandos `pwd` para garantir que o redirecionamento fosse para o lugar certo.

```

---

## 2️⃣ Parte 2 - Comparação Windows vs Linux

### 💻 Diferenças Observadas

**1. Liste 3 diferenças principais entre usar Windows e Linux que você notou:**

```
1. Filosofia de Operação (Terminal vs GUI): O Linux é fortemente centrado na interface de linha de comando (Shell), que é a forma mais eficiente para automatização e administração. O Windows foca na Interface Gráfica (GUI) e ferramentas visuais.
2. Estrutura de Arquivos: O Linux possui uma estrutura unificada baseada em uma **raiz (/)**, onde tudo é um arquivo, e não usa letras para drives (C:, D:). O Windows usa uma estrutura baseada em drives separados.
3. Gerenciamento de Recursos: O Linux tende a ser mais leve, estável e eficiente no uso de recursos de hardware, sendo ideal para servidores. O Windows geralmente consome mais memória e recursos do sistema.
```

**2. Para tarefas do dia a dia, qual sistema você prefere? Por quê?**

```
Para tarefas do dia a dia (navegação, edição de documentos, consumo de mídia), eu ainda prefiro o Windows. A curva de aprendizado da GUI é instantânea, e a compatibilidade com *softwares* e jogos proprietários é, em geral, maior. No entanto, para tarefas de desenvolvimento e administração de sistemas, o Linux é a escolha superior.

```

**3. Em que situações o Linux seria mais vantajoso que o Windows?**

```
O Linux é mais vantajoso em situações que exigem estabilidade, segurança, customização e automatização em escala.
```

---

## 3️⃣ Parte 3 - Reflexões sobre Sistemas Operacionais

### 🎯 Importância para SI

**1. Por que é importante para um profissional de Sistemas de Informação conhecer Linux?**

```
É crucial porque a **infraestrutura da internet e dos serviços de TI modernos é construída sobre Linux**. Servidores, *data centers*, tecnologias de *cloud* (como Kubernetes e Docker) e grandes *softwares* corporativos rodam em Linux. Um profissional de SI que não domina o Linux não consegue administrar a infraestrutura principal ou interagir eficientemente com as ferramentas de *DevOps* e *Cloud Computing*.

```

**2. Como o conhecimento de comandos Linux pode ajudar na gestão de TI de uma empresa?**

```
O conhecimento de comandos permite a automatização de tarefas (via scripts Shell), a administração remota de servidores (via SSH), a análise rápida de logs (troubleshooting eficaz) e o gerenciamento eficiente de recursos do sistema. Em uma empresa, isso se traduz em maior produtividade, menor tempo de inatividade do sistema e redução de custos operacionais.
```

**3. Cite 3 aplicações práticas do Linux no ambiente empresarial:**

```
1. Servidor Web e Aplicações: Utilizando distribuições como Ubuntu Server ou CentOS para hospedar sites, APIs e bancos de dados (ex: pilha LAMP/LEMP).
2. Virtualização e Cloud: Servindo como sistema operacional *host* para máquinas virtuais e *containers* (Docker/Kubernetes).
3. Segurança e Firewall:** Utilizado para construir firewalls, sistemas de detecção de intrusão e ferramentas de auditoria de segurança devido ao seu controle granular de permissões.
```

---

## 4️⃣ Parte 4 - Comandos e Outputs

### 📊 Análise dos Resultados

**1. Quantos arquivos você criou no diretório `outputs/`?**

```
Total de arquivos: 19
```

**2. Qual foi o tamanho total do diretório `meu_diretorio` que você criou?**

```bash
# Use o comando: du -sh meu_diretorio/
Tamanho: 16K
```

**3. Liste os 5 comandos que você mais usou durante o laboratório:**

```
1. cd
2. ls
3. pwd
4. cat
5. grep
```

---

## 5️⃣ Parte 5 - GitHub e Versionamento

### 🔧 Experiência com Git

**1. Você já tinha usado Git antes? Se sim, em que contexto?**

```
Não, esta foi a primeira vez 
```

**2. Qual a importância do versionamento de código para empresas?**

```
1. Permite Colaboração Segura: Múltiplos desenvolvedores podem trabalhar no mesmo código sem sobrescrever o trabalho uns dos outros.
2. Garante Rastreabilidade: Cada alteração é rastreada, permitindo saber *quem*, *quando* e *por que* modificou uma linha de código.
3. Facilita a Recuperação: Em caso de erro grave (*bug*) ou falha, a equipe pode reverter instantaneamente o código para qualquer estado anterior estável.
```

---

## 6️⃣ Parte 6 - Aplicações Futuras

### 🚀 Próximos Passos

**1. Que tipo de tarefas você poderia automatizar usando comandos Linux?**

```
1. Backup e Sincronização: Criar um script para compactar (usando `tar`) e enviar automaticamente arquivos importantes para um servidor remoto (usando `scp` ou `rsync`) todas as noites.
2. Monitoramento de Logs: Criar um *script* que use `grep` para monitorar logs de aplicações em tempo real, alertando o administrador por e-mail quando encontrar palavras-chave como "ERROR" ou "FAIL".
```

**2. Você consideraria usar Linux como sistema operacional principal? Por quê?**

```
Pretendo conhecer mais sobre o SO linux
```

---

## 💡 Feedback do Laboratório

**O que você achou mais interessante no laboratório?**

```
O mais interessante foi descobrir sobre os **pipes (|)** e o **grep**. Ver como comandos simples podem ser combinados para realizar tarefas complexas de processamento e filtragem de dados em uma única linha de comando demonstra a elegância e a eficiência da filosofia UNIX.
```

**O que poderia ser melhorado para próximos labs?**

```
sem criticas
```

---

## 📤 Checklist Final

Antes de enviar, verifique:

- [X] Preenchi todas as seções do relatório
- [X] Completei todos os exercícios em EXERCICIOS.md
- [X] Salvei todos os outputs na pasta outputs/
- [X] Criei o diretório meu_diretorio com os arquivos solicitados
- [X] Fiz git add, commit e push

---
