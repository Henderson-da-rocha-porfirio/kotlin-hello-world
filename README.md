# Kotlin Hello World

### 1 - [Kotlin Site](https://kotlinlang.org/)
### 2 - [Kotlin Standard Library (kotlin-stdlib)](https://kotlinlang.org/)
### 3 - [Declaracao de variaveis](https://github.com/Henderson-da-rocha-porfirio/kotlin-declaracao-variaveis)
#### Kotlin exemplo

### kotlin-stdlib.jar

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
