# 🚀 SellOut EasyTrack

Sistema de controle de vendas com interface moderna em Java, integração com MySQL e geração de relatórios gráficos interativos.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-UI-green?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![FlatLaf](https://img.shields.io/badge/FlatLaf-3.6-blue?style=for-the-badge)
![JFreeChart](https://img.shields.io/badge/JFreeChart-1.5.5-purple?style=for-the-badge)

---

## 📋 Descrição

O **SellOut EasyTrack** é uma aplicação desktop corporativa desenvolvida em **Java Swing moderno com FlatLaf**, utilizando arquitetura **MVC + DAO**, integração real com banco de dados **MySQL** via JDBC, e geração de relatórios com gráficos profissionais usando **JFreeChart**.

O sistema permite:
- Registro de vendas reais.
- Visualização de relatórios e gráficos de desempenho.
- Exportação de relatórios em **CSV**.
- Interface moderna, amigável e responsiva.

---

## 💻 Tecnologias Utilizadas

| Tecnologia        | Descrição                                         |
|--------------------|----------------------------------------------------|
| Java SE 17+        | Linguagem principal do projeto                    |
| Swing + FlatLaf    | Interface gráfica moderna e refinada              |
| MySQL 8+           | Banco de dados relacional                         |
| JDBC               | Conexão Java com MySQL                            |
| JFreeChart         | Geração de gráficos dinâmicos e profissionais     |

---

## 🎯 Funcionalidades

- ✅ Registro de vendas  
- ✅ Dashboard moderno com cards e gráficos integrados  
- ✅ Geração de relatórios gráficos em tela  
- ✅ Exportação de dados para **CSV**  
- ✅ Conexão real com banco de dados **MySQL**  
- ✅ Interface intuitiva estilo ERP moderno  

---

## 🗄️ Estrutura de Pastas
📁 sellout\_easytrack
├── 📦 controller
├── 📦 dao
├── 📦 model
├── 📦 util
├── 📦 view
└── 📄 Main.java

````

## 🛠️ Requisitos

- JDK 17 ou superior
- MySQL Server 8 ou superior
- IDE Java (IntelliJ, Eclipse, NetBeans, etc.)
- Conexão ativa com o banco de dados

---

## 🗃️ Configuração do Banco de Dados

```sql
CREATE DATABASE sellout_easytrack;

USE sellout_easytrack;

CREATE TABLE vendas (
    id INT AUTO_INCREMENT PRIMARY KEY,
    produto VARCHAR(100) NOT NULL,
    quantidade INT NOT NULL,
    valor_unitario DECIMAL(10,2) NOT NULL,
    data_venda DATE NOT NULL
);
````

### 💡 Configuração da conexão

No arquivo:

```
util/ConexaoDB.java
```

Edite as credenciais:

```java
private static final String URL = "jdbc:mysql://localhost:3306/sellout_easytrack";
private static final String USER = "seu_usuario";
private static final String PASSWORD = "sua_senha";
```

---

## ▶️ Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/sellout_easytrack.git
   ```

2. Importe em sua IDE Java.

3. Adicione as bibliotecas no `Classpath`:

    * `flatlaf-3.6.jar`
    * `jfreechart-1.5.5.jar`
    * `mysql-connector-j-9.3.jar`

4. Execute a classe:

   ```bash
   Main.java
   ```

---

## 📈 Relatórios e Exportações

* **Gráfico em tela:** Exibe gráfico de barras com desempenho mensal.
* **Exportação CSV:** Exporta vendas registradas para arquivo `.csv`.

---


---

## 📚 Padrões de Projeto Utilizados

* **DAO (Data Access Object)**
* **Singleton (Conexão DB)**
* **MVC (Model - View - Controller)**
* **POO Completo (Encapsulamento, Herança, Polimorfismo, Coleções, Exceptions Personalizadas)**

---

## 📦 Bibliotecas

| Biblioteca        | Versão |
| ----------------- | ------ |
| FlatLaf           | 3.6    |
| JFreeChart        | 1.5.5  |
| MySQL Connector/J | 9.3    |

---

## 📑 Licença

Este projeto foi desenvolvido para fins acadêmicos e demonstração de conceitos de **POO completa, arquitetura em camadas, integração com banco de dados real e UI moderna em Java**.

---

## 🤝 Autores

**Yasmin Kimura** |
[LinkedIn](https://www.linkedin.com/in/yasmin-kimura-b374b72b7/)

**André Flores** |
[LinkedIn](https://www.linkedin.com/in/andréflores/)

**Roger Alencar** |
[LinkedIn](https://www.linkedin.com/in/roger-alencar-it/)

**Kevin Benevides** |
[LinkedIn](*)

