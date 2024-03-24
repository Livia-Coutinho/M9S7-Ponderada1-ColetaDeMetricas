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

#### 8. Executar o projeto usando o comando dotnet run
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/e5d71638-0f2d-44f5-b512-6d26d89bc5bc)
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/c1ca2e4b-6e1b-40f5-b72a-8e325cfd00cf)

#### 9. Correção de erros
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/b1549a5b-3339-4920-9834-cf426341f3a7)

#### 10. Tentar novamente rodar o dotnet run
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/6e917758-9c30-4117-8735-29e5a8ab1e72)

#### 11. Acessar a API
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/90c88298-6ada-4a42-973b-44c36660d024)
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/32c5e057-c5cf-43d1-a492-876aa03295fc)

#### 12. /metrics (acessar as métricas)
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/d22d3d65-33ef-451b-baa4-e70e4edb4289)

#### 13. Instalando o Prometheus
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/b7122507-4ac5-4bd2-90a9-46bc423e0997)
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/ab966f9f-f7d1-45e4-aa1d-04eb4da003ce)
</br> Extração: </br>
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/7573d93f-e805-461d-a7d1-75e19b5f8605)

#### !!! Não consegui subir o prometheus
![image](https://github.com/Livia-Coutinho/M9S7-Ponderada1-ColetaDeMetricas/assets/99189965/d0e8d4b6-0378-47a8-93e3-c09913eb82e8)


