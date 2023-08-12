## Resumao: Modelos de computacao em nuvem como (IaaS, Paas, Saas) e Modelos de implatacao.

### Modelos de computacao em nuvem:

* IaaS: Infraestrutura como serviço, focado em recursos basicos de computacao, rede e armazenamento. Oferece alto nivel de gerenciamento de infraestrutura do provedor de nuvem. Quando se trata de Iaas foca sempre no topico de flexibilidade e controle de gerenciamento sobre recursos de ti. 

  * Exemplo de IaaS: EC2

* PaaS: Plataforma como um serviço te permite nao mais gerenciar a infraestrutura(Nem hardware nem OS), permite que o foco seja totalmente concentrado no gerenciamento e implantacao de aplicacoes. Quando se trata de IaaS foca sempre que voce nao precisa mais se preocupar em mensurar em adquirir recursos, nem  fazer planejamento de capacidade.

  *  Exemplo de PasS: RDS, lambda, App Runner


* SaaS: Software como um serviço, um produto pronto para ser usado para executar sua carga de trabalho. Quando se trata de Saas, sempre lembrar que eh um servico direcionado ao uso pelo usuario final, voce so precisa pensar em como usar esse software em especifico.

  * Exemplo de SaaS: AWS Single Sign-On (AWS SSO)

### Modelos de implantacao Cloud, Hibridada, Onpremises.

* Nuvem: Uma implementacao totalmente feita na nuvem e todos os aspectos da aplicacao sao executados nela. 

    * OBS Oque a AWS quer ouvir: 
    As aplicações baseadas na nuvem podem se beneficiar de fragmentos secundários da infraestrutura ou podem utilizar serviços de nível superior que reduzem as necessidades de gerenciamento, arquitetura e escalabilidade da infraestrutura principal.


* Híbrida: Uma implementacao que permite conectar recursos de um datacenter on-prem local a recursos na nuvem. Exemplo, se tu tem um datacenter local e quer aumentar alguma dependencia local com servicos na nuvem. Isso e possivel com a implementacao hibrida.

* On-premises: Implementacao em datacenter local usando  ferramentas de gerenciamento ou virtualizacao. Mas a implementacao eh feita totalmente em um datacenter local.

Doc oficial:Material: [AWS Tipos de computação em nuvem](https://aws.amazon.com/pt/types-of-cloud-computing/)
