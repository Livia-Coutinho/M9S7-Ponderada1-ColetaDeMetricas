# M9S7-Ponderada1-ColetaDeMetricas
 
#### 1. Criação do modelo ASP.NET Core
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/aa949030-f92f-43c0-8bb4-030c2d937db0)
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/dbe063f2-d7af-4c4f-b8d5-3d3361dcdc88)

#### 2. Abrir o program.cs, com a lógica principal do aplicativo
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/e73a3461-8799-4ec3-83e0-11e7ccb721c5)

#### 3. Adicionar definições de métricas e atividades no program.cs
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/e9cd2c3b-d389-4601-953a-2b35f0a45ee2)

#### 4. Criar um ponto de extremidade de API
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/265a5511-edc2-4acf-b45e-e8a5e55c3bdf)

Neste método SendGreeting, estamos:
- Iniciando uma nova atividade usando a fonte de atividade personalizada greeterActivitySource.
- Registrando uma mensagem de log usando o logger fornecido.
- Incrementando o contador personalizado countGreetings.
- Adicionando uma tag à atividade com a saudação "Hello World!".

#### 5. Abrir o .csproj
- ![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/b5ff9d66-ddd7-4b99-b90e-0068d6086a5f)

#### 6. Adicionar manualmente as referências aos pacotes no arquivo .csproj
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/cf9c8c97-5837-4c97-a308-d0762ec2402c)

#### 7. Configurar o OpenTelemetry com os provedores corretos
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/11d387c5-2385-403c-8432-a359b46f22e9)
