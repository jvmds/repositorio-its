# Organização De Um Repostório

Pensando na estruturação de um repositório para um software de código aberto é importante que tenha seções bem definidas sem entretanto burocratizar de mais o processo de manutenção ao ponto de torná-lo mais difícil de manter que propriamente o código. Desta forma, julgo importante que tenha os seguintes itens:

* **Pastas**
  * **src**: essa pasta é destinada a adicionar todo o código fonte da aplicação.
  * **doc**: essa por sua vez é destinada a manter toda a documentação da aplicação.
  * **res**: essa outra seria destinada a armazenar os recursos estáticos da aplicação, como: imagens e ícones.
  * **test**: conterá todos os testes que garantem a qualidade da aplicação (testes unitários e/ou de integração).
* **Arquivos**
  * **.gitignore**: muito importante para definir os arquivos que não serão rastreados para versionamento, como arquivos temporários ou binários gerados da compilação.
  * **.gitattribute**: aqui conseguimos definir atributos para os arquivos e diretórios em nosso repositório.
  * **CONTRIBUTORS.md**: nesse arquivo conseguimos prestigiar em certa medida aquelas pessoas que dedicaram tempo e esforço na melhoria do projeto.
  * **CHANGELOG.md**: nesse documento descrevemos a evolução do projeto, como: as versões que foram surgindo, as correções de problemas que foram resolvidos.
  * **CODE_OF_CONDUCT.md**: Como é um projeto onde qualquer um pode contribuir é importante definir algumas regras para manter um desenvolvimento saudável e é nesse arquivo onde podemos adicionar essas regras.
  * **LICENSE**: é nesse arquivo onde definimos as licenças que serão usadas em nossa aplicação. Para o exemplo atual escolhemos a licença MIT, pois é simples e muito permissiva, sem pegadinhas nas entrelinhas, o que proporciona e estimula a contribuição.
  * **README.md**: traz uma explicação suncita sobre o que é a aplicação.
  * **SECURITY.md**: por último mas não menos importante, o arquivo security é onde descrevemos, por exemplo: as versões da aplicação que ainda são mantidas e como os contribuidores podem mandar relatórios de vulnerabilidades.
