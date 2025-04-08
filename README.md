# resumolab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

1. SLA (Service Level Agreement - Acordo de Nível de Serviço)

SLA é um acordo formal entre um provedor de serviço e o cliente, no qual são estabelecidos os níveis de serviço esperados em relação a performance, disponibilidade, resposta, entre outros parâmetros. Em TI, os SLAs são essenciais para garantir que os serviços fornecidos atendam a certos padrões de qualidade. Por exemplo, um SLA pode definir que um serviço de hospedagem na nuvem deve ter 99,9% de disponibilidade durante o mês. Isso significa que o tempo de inatividade permitido seria de apenas 43 minutos por mês.

Esse tipo de contrato pode incluir:

Tempo de Resposta: Quanto tempo o suporte leva para responder a um incidente.

Disponibilidade: Percentual de tempo que um serviço deve estar disponível, como em serviços de nuvem.

Desempenho: Especificações de desempenho, como tempo de resposta para acessar determinado recurso.

2. Máquina Virtual (VM)

Uma máquina virtual (VM) é um ambiente de execução emulado dentro de um sistema físico. Em vez de rodar diretamente no hardware, a máquina virtual é criada em um software, como o Hypervisor, que é responsável por gerenciar a execução das VMs. Isso permite que múltiplos sistemas operacionais rodem simultaneamente na mesma máquina física. Cada VM pode ter seu próprio sistema operacional, como Windows, Linux, etc., sem interferir nos outros.

Vantagens das VMs:

Isolamento: Se uma VM falhar ou for comprometida, ela não afeta as outras.

Flexibilidade: Podemos criar, excluir e clonar VMs facilmente, o que é ótimo para testes e desenvolvimento.

Eficiência de recursos: É possível utilizar melhor os recursos de hardware, já que várias VMs podem rodar simultaneamente na mesma máquina física.

3. Disponibilidade em Zonas

Disponibilidade em zonas está relacionada à distribuição de serviços em diferentes locais físicos. Por exemplo, na nuvem, uma "zona de disponibilidade" é um centro de dados isolado em uma região específica. Grandes provedores de nuvem, como AWS, Google Cloud e Azure, dividem suas infraestruturas em várias zonas de disponibilidade para garantir que, se uma falha ocorrer em uma zona (como um problema no hardware ou uma interrupção de rede), o serviço ainda possa continuar em outra zona próxima.

A principal vantagem disso é garantir alta disponibilidade. Se você distribuir seus recursos entre múltiplas zonas de disponibilidade, as chances de uma falha afetar todo o sistema diminuem, pois as zonas são isoladas fisicamente e geralmente têm fontes de energia independentes, conexões de rede separadas e outros recursos que asseguram a continuidade dos serviços.

Em resumo:

SLA garante que o serviço oferecido atenda a padrões acordados.

Máquina Virtual permite criar ambientes isolados e eficientes para executar múltiplos sistemas operacionais na mesma máquina física.

Disponibilidade em Zonas distribui recursos em diferentes locais físicos para garantir que um serviço continue disponível, mesmo que uma zona falhe.
