# Introdução ao Git e GitHub

- Git é um software de versionamento de códigos
- GitHub é um repositório de códigos

### Comandos Básicos e Atalhos:

- **dir** : lista todas as pastas e arquivos contidos na pasta está aberta no terminal (**ls** no Linux);

- **cd** (*change direct*) : navegar entre pastas;

- **cd ...** : voltar para a pasta anterior;

- **cls** (*clear scream*) : limpar o terminal (Ctrl + L) (**Clear** no Linux);

- **Tecla TAB** : auto completa nomes de pastas, arquivos etc;

- **mkdir** (*make directory*) : criar pastas, diretórios;

- **Silence on Sucess** (*Conceito*) : se o comando der certo, o terminal não irá retornar nada;

- **echo** : printa no terminal um texto digitado;

- **>** : redirecionador de fluxo, cria um arquivo;

- **del** : remove arquivos de dentro de uma pasta, diretório;

- **rmdir** (*remove directory*) : remove pasta, diretório (flag **/S /Q**).

  

### Tópicos Fundamentais 

#### SHA1

- É um algoritmo de criptação;
- É um algoritmo que irá "embaralhar" um arquivo de uma forma muito específica;
- A sigla significa *Secure Hash Algorithm* (Algoritmo de Hash Seguro), que são um conjunto de funções *hash* criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA);
- A encriptação gera um conjunto de caracteres identificador de 40 dígitos (esse conjunto é único);
- É um forma curta de representar um arquivo.



### Objetos Internos do Git

#### Blobs

Contém metadados do Git, que são o tipo do objeto, tamanho do arquivo.

#### Tree (árvores)

Armazenam Blobs. A tree é responsável por montar toda a estrutura onde estão os arquivos, e pode apontar para Blobs e para outras Trees.

#### Commit

É o objeto responsável por unificar e dar sentido às alterações realizadas. Permite um histórico das alterações, nome do autor, data de criação etc.

