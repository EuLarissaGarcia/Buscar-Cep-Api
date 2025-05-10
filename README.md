# Buscador de Endereço por CEP  

Este repositório contém o código-fonte do arquivo viacep.html, utilizado como exemplo no curso de extensão "Trabalhando com APIs C# e JavaScript" para demonstrar o consumo da API do ViaCEP, uma API pública para buscar informações de endereços a partir de um CEP.

![preview profile.](https://imgur.com/WoxgXSn.png)


### Funcionalidades  
- Validação automática de formato de CEP  
- Preenchimento automático de dados de endereço  
- Design responsivo e acessível  
- Feedback visual claro para usuários  
- Transições suaves e efeitos hover  



---

##  Paleta de Cores

| Variável            | Código HEX   | Uso Principal                     |
|---------------------|--------------|-----------------------------------|
| `--primary-color`   | `#457687`    | Fundo do container principal     |
| `--accent-color`    | `#FFC801`    | Cabeçalho e elementos de destaque|
| `--dark-text`       | `#1B2E35`    | Textos principais                |
| `--light-text`      | `#FFFFFF`    | Textos em fundos escuros         |
| `--background`      | `#FFFFFF`    | Cor de fundo da página           |

```sh
![preview profile.](https://imgur.com/4ea3rye.png)
```


---
###  Tabela de Classes CSS  

| Classe               | Função                                                                |  
|----------------------|----------------------------------------------------------------------|  
| `.container`         | Container principal do formulário com estilo de fundo                |  
| `.header`            | Cabeçalho com título em destaque                                     |  
| `.input-group`       | Grupo de elementos de entrada (label + input)                        |  
| `.image-container`   | Container da ilustração com efeitos de hover                         |  
| `.tittle`            | Container do título e imagem lateral                                |  
| `.form-container`    | Área interna de padding para o formulário                           |  

---
###  Como Usar

1. **Digite o CEP**  
   Insira um número de 8 dígitos no campo indicado  

2. **Ative a busca**  
   - Clique fora do campo  
   - OU pressione ` Tab `  

3. **Resultado automático**  
   Os campos serão preenchidos instantaneamente:  
   ```plaintext
   Logradouro: Rua 
   Bairro: Centro  
   Cidade: São Paulo  
   Estado: SP


---
### API Utilizada  

**ViaCEP** - Serviço gratuito para consulta de CEPs brasileiros  

| Característica      | Detalhe                                                             |  
|---------------------|---------------------------------------------------------------------|  
| Endpoint            | `https://viacep.com.br/ws/{cep}/json/`                             |  
| Método              | GET                                                                |  
| Parâmetro           | CEP (8 dígitos)                                                    |  
| Resposta            | JSON com dados de endereço                                         |  
| Documentação        | [viacep.com.br](https://viacep.com.br)                             |  


## Ferramentas e Recursos

| Recurso              | Tipo          | Link                                                                 |
|----------------------|---------------|---------------------------------------------------------------------|
| **ViaCEP API**       | API de Dados  | [viacep.com.br](https://viacep.com.br)                             |
| **Freepik**          | Ilustrações   | [freepik.com](https://www.freepik.com)                             |
| **Poppins**          | Tipografia    | [fonts.google.com](https://fonts.google.com/specimen/Poppins)      |

---
## Contato
- **GitHub:** [@EuLarissaGarcia](https://github.com/EuLarissaGarcia)
- **LinkedIn:** [@eularissagarcia](https://www.linkedin.com/in/eularissagarcia)


