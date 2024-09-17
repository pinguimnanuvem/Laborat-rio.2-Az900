Introdução

Este relatório descreve a experiência de aprendizagem sobre a criação de uma máquina virtual (VM) no Microsoft Azure, realizada durante um laboratório prático. O objetivo foi entender o processo passo a passo de criar, configurar e gerenciar uma VM na nuvem, utilizando as funcionalidades básicas do portal Azure. Este conhecimento é essencial para quem busca uma introdução à computação em nuvem e deseja aprender a gerenciar infraestruturas virtuais de maneira eficiente.

1. Acesso e Preparação

O primeiro passo foi criar uma conta no Azure. A criação da conta foi simples e incluída o completo de informações pessoais e uma verificação de identidade via cartão de crédito. Após a conclusão, foi possível acessar o Portal do Azure , uma interface principal para gerenciar todos os recursos na nuvem. Nesse ponto, pude explorar o portal, que é bastante intuitivo, com diversos serviços organizados por categorias como computação, armazenamento e redes.

2. Criação da Máquina Virtual

O processo de criação da máquina virtual foi iniciado na seção "Máquinas Virtuais" do Portal Azure. O botão "Criar" apresentou uma série de opções de configuração:

Escolha da Assinatura e Grupo de Recursos : Escolha a assinatura gratuita, fornecida como parte do período de testes, e crie um novo grupo de recursos para manter a organização e controle dos recursos relacionados à máquina virtual.

Configuração da VM : Durante a configuração, houve a escolha do sistema operacional (optei pelo Windows Server 2019), o tamanho da VM, que foi definido como uma opção básica com 1 vCPU e 2 GB de RAM, ideal para experimentos e testes. Além disso, foi possível escolher o tipo de disco (HDD ou SSD). Optei por SSD para melhor desempenho.

Configuração de Acesso : Configurei o acesso com um nome de usuário e senha, garantindo que a máquina possa ser acessada via protocolo de área de trabalho remoto (RDP) posteriormente.

Configuração de Rede : A interface de rede foi configurada automaticamente, sendo possível definir um endereço IP público para acesso externo e definir regras de firewall, permitindo o tráfego para a porta 3389 (RDP).

3. Implementação e Gerenciamento

Após a configuração, iniciei o processo de criação da máquina virtual, o que levou alguns minutos para ser concluído. Durante o processo de criação, pude visualizar o progresso no portal. Uma vez criada, a VM ficou disponível com um endereço IP público, permitindo seu acesso externo.

Utilizei o Remote Desktop Protocol (RDP) para me conectar à VM e, dentro dela, tive a experiência de gerenciar o ambiente como se estivesse em um servidor físico. Instalei alguns softwares básicos, configurei o firewall e explorei as funcionalidades do sistema operacional.

4. Desafios e Soluções

Durante o processo, um dos desafios encontrados foi a configuração correta das regras de firewall para permitir o acesso via RDP. Inicialmente, não havia habilitada a porta 3389 no firewall do Azure, resultando em tentativas de falhas de conexão. Após revisar as configurações de rede e ajustar as regras, o acesso foi restaurado com sucesso.

Outro desafio foi a familiaridade com as diversas opções de tamanhos de máquinas virtuais e sistemas operacionais disponíveis no Azure. O portal oferece uma vasta gama de escolhas, e entende as implicações de cada configuração em termos de custo e desempenho devido a algum estudo anterior.

5. Conclusão

Aprender a criar uma máquina virtual no Azure foi uma experiência valiosa e enriquecedora. O processo de configuração é relativamente simples, mas oferece uma gama de opções que permite flexibilidade para diferentes casos de uso, desde testes e desenvolvimento até produção. O Azure oferece uma infraestrutura robusta e acessível, tornando a criação e o gerenciamento de recursos na nuvem uma tarefa ágil.

Este laboratório apresentou uma boa introdução à computação em nuvem, mostrando como o Azure pode ser uma ferramenta poderosa para criar e gerenciar máquinas virtuais. A experiência me deixou mais confiante em usar o Azure para futuros projetos de infraestrutura e desenvolvimento.



