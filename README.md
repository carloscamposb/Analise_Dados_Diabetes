## Dataset Diabetes ✏️
Este repositório contém dados relacionados ao **Diabetes** com o objetivo de realizar uma análise **descritiva** e **inferencial**. O dataset inclui informações de saúde que podem ser usadas para explorar relações entre diferentes variáveis e a presença ou ausência de diabetes.

### Objetivo
O propósito deste dataset é permitir análises que possam identificar **fatores de risco** associados ao diabetes, além de permitir a criação de **modelos preditivos** e análises de correlação entre variáveis. Os dados podem ser usados para verificar como variáveis como **idade**, **IMC**, **pressão arterial**, e **glicose** estão relacionadas ao status de diabetes.

### Dicionário de Dados 
Cada coluna do dataset representa uma característica importante relacionada à saúde dos indivíduos. Abaixo estão os detalhes de cada variável:

| **Variável**         | **Descrição**                                                                                 |
|----------------------|-----------------------------------------------------------------------------------------------|
| **Gravidez**          | Representa o número de gestações. Útil para entender se há uma correlação com o diabetes.     |
| **Glicose**           | Nível de glicose no sangue. Valores elevados podem indicar diabetes ou risco de desenvolvê-lo.|
| **Pressão Arterial**  | Medida da pressão arterial (mmHg). Pressões altas podem estar associadas ao diabetes.         |
| **Insulina**          | Nível de insulina no sangue. A insulina desempenha um papel fundamental no controle da glicose.|
| **IMC**               | Índice de Massa Corporal (IMC), calculado como peso dividido pela altura ao quadrado.         |
| **Idade**             | Idade dos indivíduos. Idade avançada pode ser um fator de risco para o desenvolvimento de diabetes. |
| **Diabetes**          | Status de diabetes (SIM ou NÃO). Indica se o indivíduo foi diagnosticado com diabetes.        |

### Análise Descritiva e Inferencial 
- **Análise Descritiva**: Realizada para fornecer um resumo dos dados por meio de métricas como **médias**, **medianas**, **dispersões** e **distribuições**. Isso ajuda a entender o comportamento dos dados e identificar padrões iniciais.
<br>

**Sendo Diabetes meu resultado. Precisamos responder as seguintes perguntas:**

---
* Quantos entrevistados possuem diabetes e quantos não possuem?<br>
* A pressao tem relação com casos de diabetes?<br>
* As mulheres com mais gestação possuem mais chances de ter diabetes?<br>
* O peso influencia no desenvolvimento da diabetes?<br>
* A relação da Insulina com a glicose podem favorecer a dibetes?<br>
* A idade é um fator para aumento da insulina e glicose?<br>
* A gestação influencia nos níveis de glicose e insulina?<br>
<br>

**Análise Inferencial**: Utilizada para **testar hipóteses** e verificar correlação entre as variáveis.
<br>

**Verificando a Correlação pelo método Spearman**

  ---
* Os dados não são normalmente distribuídos.
* A relação entre as variáveis não precisa ser linear.
* As variáveis são ordinais ou possuem muitos outliers.


**Teste de hipótese das variáveis glicose e diabetes**

  ---
* Teste de man-whitney (teste não paramêtrico para dados não normalizados)
* H0: Níveis de glicose dos diabéticos são iguais ou menores que os dos não diabéticos.
* H1: Níveis de glicose dos diabéticos são maiores que os dos não diabéticos.


### Como Usar 📂
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/dataset-diabetes.git


### Grupo: 👥
Beatriz Nader https://github.com/BiaNader <br>
Carlos Campos https://github.com/carloscamposb <br>
Ítalo Souto https://github.com/italosouto08 <br>
José Sávio https://github.com/xsaviox1 <br>
Juliane Reis https://github.com/julianereism <br>
Lucas Rodrigues https://github.com/Oliveir4lucas <br>
Ruth Xavier https://github.com/xavierruth <br>

   
