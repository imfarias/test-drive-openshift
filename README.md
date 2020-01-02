# Introdução

## O que é isso?

Esse material é usado para capacitação e transferência de conhecimento de clientes e parceiros da Red Hat Brasil em **OpenShift**, aplicável tanto ao [**Red Hat OpenShift Container Platform**](https://www.openshift.com/container-platform/index.html) \(enterprise\) quanto ao [**Openshift OKD**](https://www.okd.io/) \(community\).

## Por que dessa forma?

Inspirados na cultura open-source, acreditamos que, ao disponibilizar o material de forma aberta, podemos **evoluir o workshop de forma colaborativa e alinhado com as necessidades dos nossos clientes, parceiros e a comunidade**.

Este trabalho está licenciado sob a [**Licença Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional Creative Commons \(CC BY-NC-SA 4.0\)**](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.pt_BR).

## Como usar?

**Não existe uma maneira certa ou errada de usar o conteúdo deste material.** Você poderia segur como um roteiro independente, usando a sua máquina particular como ambiente de experimentações, ou você pode se reunir com colegas e compartilhar a experiência.

**Se você tiver interesse de participar de um workshop com o time Red Hat Brasil, entre em contato com o seu time de contas/parceiro!**

Para conseguir aproveitar o material, nossa recomendação é:

* _Reserve entre **4-8 horas** para discussão dos assuntos e execução das atividades._
* _Acesso à **Internet é indispensável**._
* _Caso opte por usar uma VM local recomendamos que os participantes utilizem **um PC capaz de rodar máquinas virtuais**:_
  * _**Processador dual-core de 2GHz**_
  * _**8GB de memória RAM**_
  * _**40GB de disco livre**_
  * _**Virtualizador \(QEMU/KVM, Oracle VirtualBox, VMware Workstation\)**_

## Por onde começar?

Esse material é dividido em 2 partes:

* [**Parte 1 - Linux Containers:**](parte-1-containers/) _Material dedicado à discussão introdutória sobre a tecnologia de containers Linux._
* [**Parte 2 - OpenShift**](parte-2-openshift/)**:** _Material dedicado à discussão sobre o OpenShift na perspectiva de desenvolvimento e também infraestrutura._

## Posso contribuir?

**Aceitamos contribuições de todas as formas!** Você pode fazer uso da funcionalidade de "Issues" direto do repositório fonte no [**Github**](https://github.com/redhat-sa-brazil/workshop-openshift). Uma outra alternativa é através das funcionalidades de colaboração do próprio [**GitBook**](https://redhat-sa-brazil.gitbooks.io/workshop-openshift). Fique a vontade de usar qualquer um dos dois!


## Observação

**Para o S2I com o Quarkus** funcionar importar o template template-openjdk11-rhel8-s2i.yaml para o namespace **openshift**. Após isso importar também a secret para a service account default em cada projeto para fazer pulling da imagem do **registry.redhat.io**.

