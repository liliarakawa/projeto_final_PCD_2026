<p align="center">
 <img width="1050" height="150" alt="Banner README - PCD_2026 (1)" src="https://github.com/user-attachments/assets/7257259a-6876-4d45-a486-a5b6edc35f84" />
</p>

<p align="center">
 <img width="1050" height="150" alt="Banner README - PCD_2026" src="https://github.com/user-attachments/assets/ff0ac416-5998-4749-a5f6-d6163cae0515" />
</p>


# Caracterização composicional de sequências de DNA
Projeto final da disciplina de Práticas em Ciências de Dados (PCD)- 1º Semestre de 2026 | Ilum Escola de Ciência (CNPEM)


### **Descrição**
Este projeto implementa, em Python, um conjunto de ferramentas para análise de sequências de DNA voltadas a aplicações em bioinformática. A partir de uma sequência de nucleotídeos fornecida pelo usuário (ou gerada aleatoriamente), o programa realiza validação, cálculo de composição de bases, busca de motifs relevantes, simulação de mutações pontuais e geração de relatórios textuais e gráficos, consolidando os resultados em um painel visual e em arquivos de saída.

---

### **Principais Funcionalidades**
- **Validação de sequências:** verifica se a entrada é uma string composta apenas pelas bases A, T, C e G, normalizando maiúsculas/minúsculas e espaços.
Contagem de bases: calcula a frequência absoluta de cada nucleotídeo (A, T, C, G) na sequência.
 - **Cálculo de conteúdo GC e AT:** determina o percentual de bases G+C e A+T na sequência, indicadores relevantes da estabilidade e origem do material genético.
- **Complementar reverso:** gera a fita complementar reversa da sequência, simulando o pareamento de bases do DNA.
- **Busca de motifs:** localiza padrões específicos (como códons de início ATG, códons de parada TAA/TAG/TGA e caixa TATA) e motifs personalizados definidos pelo usuário, retornando todas as posições de ocorrência.
- **Análise por janela deslizante:** calcula o conteúdo de GC ao longo da sequência em janelas de tamanho configurável, permitindo identificar regiões de maior ou menor conteúdo GC.
- **Simulação de mutações:** introduz mutações pontuais aleatórias na sequência, de acordo com uma taxa de mutação definida, registrando posição, base original e base mutada.
- **Geração de relatório textual:** produz um relatório completo e formatado com todos os resultados da análise, exportável em arquivo .txt.
- **Geração de painel gráfico:** cria visualizações (gráfico de barras da composição de bases, gráfico de pizza do conteúdo GC/AT e gráfico de linha do GC por janela deslizante), exportadas como imagem .png.
- **Interface interativa via input:** permite ao usuário configurar individualmente o nome do indivíduo, a sequência (manual ou aleatória), motifs extras, taxa de mutação e opções de salvamento dos arquivos gerados.


### **Tecnologias Utilizadas**
- **collections (Counter) —** biblioteca padrão utilizada para contagem eficiente das bases nitrogenadas.
- **random —** biblioteca padrão utilizada na geração de sequências aleatórias e na simulação de mutações.
- **os —** biblioteca padrão utilizada para manipulação de diretórios e caminhos de arquivos.
- **Matplotlib (pyplot e gridspec) —** biblioteca utilizada para a criação dos gráficos e do painel visual de resultados.
- **Jupyter Notebook —** ambiente utilizado para o desenvolvimento, documentação e execução interativa do projeto.

---

## Professores

- Daniel R. Cassar
- James Moraes de Almeida
- Leandro Lemos

## Autoria
- Angelica Aracava Lopes

---
## Referências
ALBERTS, Bruce et al. **Biologia molecular da célula**. 6. ed. Porto Alegre: Artmed, 2017.

HUNTER, John D. Matplotlib: a 2D graphics environment. **Computing in Science & Engineering**, v. 9, n. 3, p. 90–95, 2007. DOI: 10.1109/MCSE.2007.55.

LESK, Arthur M. **Introdução à bioinformática**. 2. ed. Porto Alegre: Artmed, 2008. 384 p.

NATIONAL HUMAN GENOME RESEARCH INSTITUTE. **Single nucleotide polymorphisms (SNPs)**. Bethesda: NHGRI, 2024.

VAN ROSSUM, Guido; DRAKE, Fred L. **Python 3 reference manual**. Scotts Valley: CreateSpace, 2009. ISBN 9781441412690.

WATSON, J. D.; CRICK, F. H. C. **Molecular structure of nucleic acids: a structure for deoxyribose nucleic acid**. Nature, Londres, v. 171, p. 737–738, abr. 1953. DOI: 10.1038/171737a0.

---

*Este projeto foi desenvolvido com o auxílio de IA generativa (Claude) para esclarecimento de dúvidas, ajustes no projeto e organização de fontes.*
