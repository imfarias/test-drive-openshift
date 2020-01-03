# Lab 2.0 - Preparação  

## Lab 2.0 - Objetivos

* Preparar o ambiente local para os próximos exercícios

## Tarefas

### 2.0.1 - Ambiente OpenShift
Para conseguirmos executar os próximos exercícios precisamos de um ambiente com o OpenShift instalado e disponível. Atualmente temos algumas opções disponíveis:

#### OpenShift 3.x

* [**OpenShift Origin (OKD)**](https://www.openshift.org/minishift/): _Projeto upstream do openshift, para instalação de cluster Openshift via Ansible \(sem suporte\)._
* [**Red Hat Container Development Kit \(CDK\)**](https://developers.redhat.com/products/cdk/overview/): _Equivalente ao anterior mas para execução local de versão básica do Openshift para desenvolvimento._
* [**oc cluster up**](https://github.com/openshift/origin/blob/master/docs/cluster_up_down.md): _Sobe um ambiente openshift utilizando apenas containers \(para desenvolvimento\)._

#### OpenShift 4.x

* [**Code Ready Containers**](https://developers.redhat.com/products/codeready-containers/overview): _Versão slim do Openshift 4 para execução local, normalmente utilizada para desenvolvimento._

Consulte o instrutor sobre qual opção usar!

### 2.0.2 - Instalar cliente do OpenShift e Git
Além do acesso ao ambiente, precisamos também instalar alguns componentes adicionais. Basicamente o cliente de linha de comando do OpenShift e do Git:

```text
yum install centos-release-openshift-origin37
yum install origin-clients git
```

Caso você queira instalar o cliente do OpenShift na sua máquina real, ao invés de virtual, você pode obter os pacote em:

* [**https://www.openshift.org/download.html**](https://www.openshift.org/download.html)

### 2.0.3 - Criar conta no GitHub
Caso o instrutor esteja usando um ambiente compartilhado do Openshift no Google Cloud, crie uma conta no GitHub para poder executar os passos necessários no exercícios.

Para criar sua conta, basta acessar:

[https://github.com/join](https://github.com/join)


# Objetivo dos próximos labs

* Colocar em produção um container construído anteriormente.
* Aprender sobre operação básica do ambiente.
* Criar aplicações de forma transparente, sem manipular nenhuma instrução de container
* Expor serviços internos e externos
