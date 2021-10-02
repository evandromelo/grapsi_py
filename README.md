# grapsi_py
GRÁFICO PSICROMÉTRICO em Python

Cálculo das condições psicométricas do ar úmido para altitudes até 3.000 m. 
São realizados cálculos de PONTO DE ESTADO e PROCESSOS.

--------------------------------------------------------------
PRINCIPAIS VARIÁVEIS:

      1. patm  - pressão barométrica local,  (kPa)
      2. tbs   - Temperatura do bulbo seco (°C)
      3. ur    - Umidade relativa (%)
      4. pvs   - Pressão de vapor de saturação (kPa)
      5. pv    - Pressão parcial de vapor (kPa)
      6. rm    - Razão de mistura (%)
      7. tpo   - Temperatura do ponto de orvalho (°C)
      8. tbm   - Temperatura do bulbo molhado (°C)
      9. e     - Entalpia (kJ/kg)
     10. ve    - Volume específico (m3/kg)
     11. q     - Vazão de ar  (m3/hora)
-----------------------------------------

 Cuidado: Não há validação dos dados de entrada
 
 ----------------------------------------------------------  
 PONTO DE ESTADO - Devem ser fornecidas duas variáveis: 
 
                  1. tbs e ur    
                  2. tbs e tbm   
                  3. tbs e tpo   
----------------------------------------------------------  
PROCESSOS CALCULADOS PELO PROGRAMA:

               1. aquecimento/resfriamento  
               2. umificação adiabática:dado temperatura final
               3. umificação adiabática:dado umidade relativa final
               4. umificação adiabática:dado razão de mistura final
               5. mistura de dois fluxos de ar
