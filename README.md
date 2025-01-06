# Kotlin Hello World

### 1 - [Kotlin Site](https://kotlinlang.org/)
### 2 - [Kotlin Standard Library (kotlin-stdlib)](https://kotlinlang.org/)
### 3 - [Declaracao de variaveis](https://github.com/Henderson-da-rocha-porfirio/kotlin-declaracao-variaveis)
#### Kotlin exemplo

## Resolvendo Erros: 
### 1 - adicionando no projeto ou globalmente: [kotlin-stdlib.jar]()

File -> Settings -> Build, Execution, Deployment -> Build Tools -> Maven
Verifique se o "Maven home directory" está configurado corretamente


Outra alternativa é ir em:

File -> Project Structure -> Libraries (no menu da esquerda)
Clique no "+"
Escolha "Java" ou "Kotlin"
Navegue até a pasta de instalação do IntelliJ
Procure a pasta plugins/Kotlin/kotlinc/lib
Selecione o arquivo kotlin-stdlib.jar

Configurar como Global Library no IntelliJ:

File -> Project Structure
No menu esquerdo, vá em Platform Settings -> Global Libraries
Clique no "+" e escolha "Java"
Navegue até a pasta do Kotlin no IntelliJ: plugins/Kotlin/kotlinc/lib
Selecione kotlin-stdlib.jar
Agora esta biblioteca estará disponível para todos os projetos


Configurar o plugin do Kotlin no IntelliJ:

File -> Settings (ou Preferences no Mac)
Plugins
Procure por "Kotlin"
Certifique-se que o plugin está instalado e atualizado
Este plugin fará com que novos projetos Kotlin já venham com as dependências necessárias



A forma mais recomendada é usar o plugin do Kotlin, pois ele:

Configura automaticamente novos projetos
Mantém as bibliotecas atualizadas
Fornece suporte a linguagem
Adiciona templates de projetos Kotlin
Gerencia as dependências automaticamente

### 2. Erro de estabilidade:  [K2 mode]()
![image](https://github.com/user-attachments/assets/b3dc28ae-b7d6-42ec-b076-951e2d96ba8a)

Na imagem você está nas configurações do IntelliJ IDEA na seção de Kotlin, e há uma mensagem importante sobre o "K2 mode".
O K2 mode é um novo compilador do Kotlin que:

Traz melhorias de estabilidade
Oferece melhorias na análise de código
É mais rápido que o compilador anterior

A mensagem informa também que a partir do IntelliJ IDEA 2023.3:

O Kotlin será incluído automaticamente nas novas versões
Você não precisará mais atualizar o plugin do Kotlin separadamente
Cada versão principal do IntelliJ IDEA virá com a versão estável mais recente do Kotlin

A opção "Enable K2 mode" está marcada, o que é bom porque:

Você terá acesso às últimas melhorias do compilador
Melhor performance na compilação
Melhor análise de código
Mais estabilidade

Note que ativar o K2 mode requer reiniciar o IDE (como indicado pelo "Requires restart" na imagem).
