#	Introdução ao Git e ao Github (Rascunho da aula da DIO) 

**dir ->**  lista diretórios no windwos no linux usa-se ls.
**cd/ ->** navega entre as pastas no windwos e linux.
**p cd..** -> para voltar um nível na navegação.
**cls ->**  para limpar  a tela no windwos   no linux clear atalho ctrl +l.
**mkdir -->** cria uma pasta windwos e linux.

 **echo hello**  tras de volta o que foi passado > redicionador de fluxo
 **del workspace :**  deleta apenas arquivos.

**seta para cima :** litar históricos de comando que usei no terminal.
**rmdir workspace  /S /Q**:para deletar todo o diretório.

## 		   *COMO O GIT FUNCIONA*

**-SHA1:** CRIPTOGRÁFIA;
 *_EX. echo " OLÁ MUNDO" | openssl sha1  nome no arquivo*_



##                    Objetos fundamentais do git:

- BLOBS: (armazena o sha) echo 'conteudo' | git hash-object --stdin(devolve o ha do objeto)

  sem usar o git echo -e 'blob \conteudo' | openssl sha1


- TREES: tree: armazenam blobs , contém metadados, nome do arquivo, mota a estrutura de onde estão os arquivos e outras árvores(contém sha1)



- COMMIT: aponta  para o conteúdo todo. contém um sha1.


## 	             CHAVE SSH E TOKEN

​	Contém uma chave pública e outra priada

1. No ícone com a sua  foto no git **--> Settings**;

2. **SSH and  gpg keys;**

3. **SSH Key  --->** New SSh Keys   : Título e kay;

4. **Git bash --->** ssh-keygen -t ed25519 -c e-mail utilizado  no Git;

5. colocar uma senha;

6. **cd/  -->** caminho onde foi mostandra pelo gerenciador ;

7. **SSH** para listar os comandos;

8. **SSH id_ed25519.pub:** motra  a chave publica;

9. **copia a chave** e cola na tela  do Git no campo : SSH  de um titulo para melhor localização. vai pedir a senha do git novament e pronto.

10. **pwd -->** lista o caminho completo;

11. **inicializar o ssh**   : eval$(ssh-agent -s) =  gent pid 1382 ;

12. ls para listar --> ssh-add id_ed25519 --> senha;

    ## Iniciando o Git e criando um commit

    #### Primeiros comandos com o Git

    - Iniciar o git: -g init ;
    - Iniciar o vercionamento: git add ;
    - Criar um commit: git commit;

    fleg : ls -a ---> lista arquivos ocultos



**Fonte:** *Aula Git e GitHub da DIO*