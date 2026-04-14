# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/images/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Cap 1 - Desafio Integrador: IA entre Robôs, Sinapses e Medicina

## 👨‍👩 Grupo

Grupo de número <b>4</b> formado pelos integrantes mencionados abaixo.

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/cirohenrique/">Ciro Henrique</a> ( <i>RM559040</i> )
- <a href="https://www.linkedin.com/in/marcofranzoi/">Marco Franzoi</a> ( <i>RM559468</i> )
- <a href="https://www.linkedin.com/in/rodrigo-mazuco-16749b37/">Rodrigo Mazuco</a> ( <i>RM559712</i> )

## 👩‍🏫 Professores:

### Tutor(a) 
- <a href="https://www.linkedin.com/in/leonardoorabona/">Leonardo Ruiz Orabona</a>

### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição

<b>Referência</b>: https://on.fiap.com.br/mod/assign/view.php?id=521912&c=14144

### Parte 1: Frases de sintomas + extração de informações

Visando atender à necessidade de uma funcionalidade capaz de retornar um diagnóstico com base nos possíveis sintomas descritos por pacientes, foi desenvolvido um script que executa as seguintes ações:

- **Leitura de arquivos em formato csv**, contendo um mapa de sintomas e possíveis doenças associadas. A estrutura deve obedecer ao seguinte padrão: `[Sintoma 1], [Sintoma 2], [Diagnóstico de doença]`. Além do arquivo atual, outros poderão ser adicionados ao diretório localizado neste [link](https://github.com/RM559712/2s_fase2_cap1/tree/main/src/parte1/symptoms_map);
- **Leitura de arquivos em formato txt**, contendo sintomas descritos por pacientes. A estrutura deve obedecer ao seguinte padrão: `Frase com informações como sintomas e tempo de ocorrência`. Além do arquivo atual, outros poderão ser adicionados ao diretório localizado neste [link](https://github.com/RM559712/2s_fase2_cap1/tree/main/src/parte1/symptoms);

A partir desses parâmetros, o script é capaz de identificar os sintomas descritos pelos pacientes e retornar um diagnóstico.

É possível visualizar a estrutura do script no formato **Jupyter Notebook** a partir deste [link](https://github.com/RM559712/2s_fase2_cap1/blob/main/src/parte1/script.ipynb).

### Parte 2: Classificador básico de texto

Visando atender à necessidade de uma funcionalidade que desempenhe a função de triagem médica, foi desenvolvido um script que executa as seguintes ações:

- **Leitura de arquivos no formato csv**, contendo diagnósticos médicos rotulados com níveis de risco. A estrutura deve obedecer ao seguinte padrão: `[Sintomas], [Nível de risco]`. Além do arquivo atual, outros poderão ser adicionados ao diretório localizado neste [link](https://github.com/RM559712/2s_fase2_cap1/tree/main/src/parte2/symptoms);

A partir desses parâmetros, o script é capaz de retornar um relatório de classificação, apresentando informações como o nível de risco, gerado a partir da execução do modelo **Logistic Regression**, utilizando como base as possíveis frases com sintomas informadas pelo paciente.

Após a execução de diversos testes com as diferentes fontes de dados disponíveis para a funcionalidade, constatou-se que o desempenho se manteve satisfatório mesmo diante de grandes volumes de informações. Além disso, o comportamento da funcionalidade atendeu às expectativas em todos os cenários, estabelecendo corretamente as relações entre os sintomas apresentados pelos pacientes e os respectivos diagnósticos médicos.

É possível visualizar a estrutura do script no formato **Jupyter Notebook** a partir deste [link](https://github.com/RM559712/2s_fase2_cap1/blob/main/src/parte2/script.ipynb).

### Sobre as funcionalidades

É possível assistir um vídeo demonstrando a execução das funcionalidades mencionadas acima através deste [link](https://www.youtube.com/watch?v=Zw45XkE5xrg).

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

1. <b>assets</b>: Diretório para armazenamento de arquivos complementares da estrutura do sistema.
    - Diretório "images": Diretório para armazenamento de imagens.

2. <b>config</b>: Diretório para armazenamento de arquivos em formato <i>json</i> contendo configurações.

3. <b>document</b>: Diretório para armazenamento de documentos relacionados ao sistema.

4. <b>scripts</b>: Diretório para armazenamento de scripts.

5. <b>src</b>: Diretório para armazenamento de código fonte do sistema.

6. <b>tests</b>: Diretório para armazenamento de resultados de testes.
    - Diretório "images": Diretório para armazenamento de imagens relacionadas aos testes efetuados.

7. <b>README.md</b>: Documentação do projeto em formato markdown.

<i><strong>Importante</strong>: A estrutura de pastas foi mantida neste formato para atender ao padrão de entrega dos projetos.</i>

## 🔧 Como executar o código

Como se trata de uma versão em formato <strong>Jupyter Notebook</strong>, para execução das funcionalidades, os seguintes passos devem ser seguidos:

1. Utilizando o prompt de comando, acesse o diretório `.../2s_fase1_cap1/src` de acordo com o local de armazenamento em seu computador;
2. Execute a linha de comando `jupyter notebook` para inicializar o <strong>Jupyter Notebook</strong> a partir do diretório acessado;
3. Após a inicialização, uma nova aba será aberta em seu browser. Serão disponibilizados os seguintes diretórios:
- Diretório `parte1`: Possui os desenvolvimentos do item "Parte 1 – Frases de sintomas + extração de informações". Clique no arquivo `script.ipynb` para que seja carregado em outra aba do browser;
- Diretório `parte2`: Possui os desenvolvimentos do item "Parte 2 – Classificador básico de texto". Clique no arquivo `script.ipynb` para que seja carregado em outra aba do browser;
4. Selecione as células que deseja executar e clique no ícone "Run this cell and advance (Shift+Enter)" para executar os processos;

## 🗃 Histórico de lançamentos

* 1.0.0 - 08/10/2025

## 📋 Licença

Desenvolvido pelo Grupo 4 para o projeto da fase 2 (<i>Cap 1 - Desafio Integrador: IA entre Robôs, Sinapses e Medicina</i>) da <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a>. Está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>