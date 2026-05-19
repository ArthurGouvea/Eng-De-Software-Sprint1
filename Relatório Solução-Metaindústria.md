#### Relatório Solução-Metaindústria

#### 

#### 1\. Personas

* Operador de Campo: Trabalha nas máquinas; precisa de segurança sem que o sistema atrapalhe sua produtividade.



* Supervisor de Segurança (SESMT): Recebe os alertas de risco e utiliza os registros para aplicar treinamentos preventivos.



* Analista de Dados/IA: Monitora a precisão das detecções para ajustar o modelo de visão computacional.



#### 2\. Requisitos Funcionais (RF)

O que o sistema deve fazer:



* RF-01: O sistema deve capturar imagens em tempo real das câmeras instaladas nas máquinas.



* RF-02: A IA deve detectar a ausência de EPIs obrigatórios (capacete, luvas, óculos) e atitudes de risco.



* RF-03: O sistema deve registrar automaticamente a infração no banco de dados (ID do usuário, tipo de infração, data e hora).



* RF-04: O sistema deve emitir um alerta visual/sonoro imediato na estação de trabalho em caso de risco iminente.



* RF-05: O sistema deve gerar relatórios mensais de conformidade para instrução dos funcionários.



#### 3\. Requisitos Não Funcionais (RNF)

Como o sistema deve ser:



* RNF-01 (Desempenho): O tempo de processamento da IA para detectar um risco não deve ultrapassar 500ms (tempo real).



* RNF-02 (Confiabilidade): O banco de dados deve ter backup diário automático para evitar perda de registros de segurança.



* RNF-03 (Segurança): Os dados sensíveis dos funcionários devem ser criptografados, respeitando a LGPD.



* RNF-04 (Disponibilidade): O monitoramento deve operar 24/7 enquanto as máquinas estiverem ligadas.



#### 4\. Restrições do Sistema

O que limita o projeto:



Res-01: O sistema deve ser compatível apenas com câmeras IP de alta definição (mínimo 1080p).



Res-02: A linguagem de desenvolvimento do motor de IA deve ser Python.



Res-03: O sistema deve funcionar obrigatoriamente em rede local (on-premise) por questões de segurança industrial da SPI.

