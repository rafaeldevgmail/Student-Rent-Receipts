# 📄 Rental Manager

> Aplicativo mobile de gerenciamento de locações desenvolvido com **Flutter** para organizar contratos, pagamentos e emissões de recibos de forma simples.

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=flat-square&logo=dart&logoColor=white)
![SQLite](https://img.shields.io/badge/Database-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Offline](https://img.shields.io/badge/Mode-Offline%20First-2ecc71?style=flat-square)
![Mobile](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-444?style=flat-square)
![Shared Preferences](https://img.shields.io/badge/Preferences-shared__preferences-6c63ff?style=flat-square)
![PDF](https://img.shields.io/badge/PDF-Generation-e53935?style=flat-square)

---

## 📱 Sobre o Projeto

O **Rental Manager** é uma aplicação criada para facilitar o gerenciamento de locações, projetado para lidar com as particularidades de kitnets e moradias estudantis. O diferencial do projeto é a flexibilidade no controle de custos fixos e variáveis, além de uma gestão precisa de quem emite e quem recebe os pagamentos.

O projeto foi publicado no GitHub já em sua versão funcional.

<div align="center">
<img title="" src="./assets/images/Receipt Manager.jpg" alt="Receipt Manager" width="350">
</div>

* * *

🚀 Engenharia e Regras de Negócio

* **Gestão de Entidades:**
  
  * **Cadastro de Estudantes:** Gestão específica para o público universitário/estudantil.
    
  * **Gestão de Beneficiários:** Flexibilidade para definir quem consta como emissor no recibo oficial.
    
* **Lógica de Cobrança de Excedentes:**
  
  * Implementação de algoritmos para cálculo de **taxas extras (água, luz, etc.)** baseados em consumo excedente, integrados automaticamente ao valor final do recibo.
* **Persistência e Arquitetura:**
  
  * **SQLite (sqflite):** Armazenamento relacional para as entidades de Beneficiários, Estudantes e o histórico de Cobranças.
    
  * **Padrão IRepository:** Camada de abstração que desacopla a lógica de negócio do banco de dados, facilitando a manutenção e garantindo a inversão de dependência.
    
  * **SharedPreferences:** Utilizado para configurações rápidas e persistência de estados de sessão.
    

* * *

🛠️ Tecnologias Utilizadas

* **Linguagem:** Dart
  
* **Framework:** Flutter
  
* **Banco de Dados:** SQLite (`sqflite`) para dados relacionais.
  
* **Preferências:** `shared_preferences` para configurações de usuário.
  
* **Geração de PDF:** Layouts customizados para recibos detalhados.
  
* **Arquitetura:** Interface-based Repository Pattern e princípios SOLID.
  

* * *

📸 Funcionalidades em Destaque
------------------------------

## Recibos

<img title="" src="./assets/images/Screenshot_20260310_174048.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_174045.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_174150.jpg" alt="Home" width="200">

## Inclusão de Beneficiários e Estudantes

<img title="" src="./assets/images/Screenshot_20260310_173257.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_170829.jpg" alt="Home" width="200">

## Fluxo de Gerenciamento de Cobranças Extras (como Beneficiários e Estudantes)

<img title="" src="./assets/images/Screenshot_20260310_170847.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_170838.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_174218.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_174040.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260311_091921.jpg" alt="Home" width="200">

# Configurações

<img src="./assets/images/Screenshot_20260310_170747.jpg" title="" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_170930.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_170936.jpg" alt="Home" width="200"><img title="" src="./assets/images/Screenshot_20260310_170940.jpg" alt="Home" width="200">

* * *

📄 Sobre este Repositório

Este é um repositório de **Showcase**. O código-fonte é mantido de forma privada para proteção da propriedade intelectual. No entanto, sinta-se à vontade para entrar em contato para discutirmos a implementação técnica das regras de negócio ou a arquitetura de persistência utilizada.
